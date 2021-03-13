# Linguagem Java: ☕

#### O que é java? ☕

É uma linguagem criada em 1995 na Sun Microsystems, por um time liderado pelo James Gosling. Tempo depois, a Sun foi adquirida pela Oracle que hoje é a responsável pelo Java.

O java é compilado para um bytecode que é interpretado por uma máquina virtual.

#### O que é um compilador? ⌨️

É um programa que a partir de um código fonte, cria um programa semanticamente equivalente, escrito em _código objeto._ Ou seja, o compilador traduz a linguagem dos seres humanos para a linguagem das máquinas. 

Alto nível (nossa linguagem) -> Baixo nível (linguagem de máquina)

_O nome do compilador Java é o Javac._

#### O que é o bytecode? 🖥️

É o código originado da compilação de programas Java. O bytecode é o programa interpretado e executado pela Máquina Virtual Java, JVM.

#### JVM??? Mas o que é isso??? 💻

Originado de uma VM (Virtual Machine), que é um software que simula uma máquina física. Ou seja, a JVM é a máquina virtual do Java, que executa os bytecodes em linguagem de máquina para cada sistema operacional.

#### Mas qual a grande vantagem dessa JVM? 🤔

​	 	Como compilamos para a JVM, isso permite que o bytecode seja executado pela máquina virtual, e não diretamente pelo SO (como em outras linguagens). E como o software escrito em Java possui portabilidade para qualquer sistema operacional, não é necessário compilar várias vezes. Lembrando que, cada JVM deve ser construída para um sistema operacional específico.

![texto](http://www2.hawaii.edu/~takebaya/ics111/process_of_programming/2000000100000109000000BDEB75FEAC.png)

#### O que é JRE? 📚

O Java Runtime Environment (ambiente de execução do Java), é composto pela JVM, bibliotecas e APIs da linguagem Java e outros componentes para o suporte da plataforma. Representa a parte de execução do software Java.



#### O QUE a JDK? 🤪

A JDK é o Java Development Kit, que é um conjunto de utilitários que permitem criar software para a plaforma Java. Sua composição é: Compilador Java, bibliotecas da linguagem, ferramentas e a JRE. É o pacote mais completo.

#### O que é o Java SE? 🤯

O Java **Standard Edition**, é a distribuição mínima da plataforma de desenvolvimento de aplicações Java. Geralmente são aplicações OpenSouce e não são corporativas. 

Obs: Existe a OpenJDK que é a implementação de referência opensouce da plataforma Java, que é mantida pela Oracle. 

#### E o que é o Java EE? Estou me perdendo nessa chuva de letrinhas... 🤔

O Java **Enterprise Edition**, é uma extensão do Java SE que possui suporte para o desenvolvimento de sistemas corporativos. Possui diversas especificações de partes da infraestrutura de aplicações, como acesso ao banco de dados, mensageria, serviços web, e muito mais... 

#### O que é o Jakarta EE? 🐛

Com a falta de investimento da Oracle no Java, ela cedeu todo o código, implementações e especificações do Java EE para o Eclipse Foudation, mas como Java EE é uma marca registrada da Oracle, foi escolhido o nome Jakarta EE. Agora a evolução da especificações e padrés do Java será feito sob o nome Jakarta EE, com compatibilidade com o Java EE



### Criando um Hello World com o VIM: 🤗

Iniciei com um **ls** para me localizar nos meus diretórios, com o **cd** fui até minha pasta de códigos e fiz um diretório com o nome Hello a partir do comando **mkdir Hello**.

Após isso, iniciei o editor vim com o comando **vim Hello.java**, onde coloquei o seguinte código:

```java
public class Hello {
        public static void main(String[] args){
                System.out.println("Hello World"); 
        }
}

```

Para salvar e sair do vim, basta usar a tecla **Esc**, e digitar **:wq**. Verifiquei se possuo o Java instalado a partir do comando **java -version**, então pude compilar meu código com o Javac. Utilizei o comando **javac Hello.java**, para compilar, e logo após usei o **ls**. Foi possível verificar a existencia de dois arquivos, sendo o Hello.java e Hello.class.

Para executar o código utilizei o comando **java Hello**, e assim pude visualizar o que foi escrito no meu System.out.println. 

Só de curiosidade, dei um **cat Hello.java**, onde pude visualizar meu código e também usei o **cat Hello.class**, onde não entendi nada pois era o código fonte. 😅

