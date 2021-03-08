# Redes: 🔗

 ### Fundamentos de redes: são dispositivos interligados para trocarem informações e compartilharem recursos, como por exemplo: impressoras, celulares.



## Tipos de redes:


>
> ### Rede wan:
> ```c
> 	É uma rede geograficamente distribuída ligando países, continentes...(cobertura mundial).
> ```

> ### Rede man: 
> ```c#
> 	É uma rede metropolitana que liga vários lugares.
> ```
> 
> ###  Rede lan:
> ```c
>	É uma rede local que liga um único prédio ou "campo."
>```

****



# Protocolos:

### "Linguagem usada pelos dispositivos de uma rede de modo que eles consigam se entender." (Torres, 2004)

## Tipos de protocolos: 


>> ### IP (protocolo de internet)
> ```c
> 	São números que identificam seu computador em uma rede.
> ```

> ### ICMP (internet control message protocol)
> ```c
> 	Tem por objetivo prover mensagens de controle na comunicação entre "nós".
> ```
> 
> ###  DNS (domain name sever)
> ```c
>	Identifica endereços de IP para manter uma tabela com os endereços dos caminhos de rede. (protocolo de aplicação)
>```

****



# Mas como os protocolos se comunicam?


>```c
>A 'interface de rede' é um software e/ou um hardware que faz a comunicação em um rede de computadores.
>    
>Existe também a 'interface de rede loopback', que é um tipo especial de interface pois permite fazer conexões contigo mesmo,
>permindo testar programas de rede sem interferir em sua rede. Por exemplo, é possível criar um servidor web, subir um site...
>```



# Comandos de redes: 🥅

- **ifconfig** = visualizar a interface de rede, como exemplo: dados da rede local e física (IP, netmask, broadcast)
- **hostname** = traz informações sobre o _host_.
  - **hostname -I** = traz o IP do computador
  - **hostname -i** = traz o endereço de _loopback_.
- **whoami** = mostra o nome do usuário que está na rede
- **ping www.google.com.br** = verifica se o host está ativo
  - **ping www.google.com.br -w 4** = para limitar os pacotes de dados
- **dig www.google.com.br** = informações sobre o DNS (caminho de rede)
  - **dig www.google.com.br short ** = mostrar o ip do site mencionado
- **traceroute** = traça a rota da rede local até outro host
  - **traceroute www.google.com.br** = mostra a quantidade de dispositivos queque passa até chegar ao site do google.
- **whois www.google.com.br** = traz informações sobre IP, país, proprietário, servidor DNV, contato...
- **finger** = informações do usuário que está logado no host



****





> ### Glossário:
>
> Host = pode ser uma aplicação web, um computador, um servidor...
>
> Loopback = roteamento de sinais eletrônicos, fluxo de dados(itens digitais que retornam para suas origens sem processamento ou modificação).
>
> 
