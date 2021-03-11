# Comandos de usuário: 

- **sudo adduser** _nome_ = adicionar um usuário
- **su** _nome_  = entrar no usuário
- **passwd** _nome_ = mudar a senha do usuário
- **laslog** = informações de login de todos usuários do sistema
- **last** = exibe  uma lista de entrada e saída do sistema
- **id** = exibe todos os identificadores do usuário 
- **cat /etc/passwd** = visão de todos os usuários
- **userdel -r** _nome_ = remover o usuário e pasta pessoal





# Grupos:

Os grupos permitem organizar os usuários e definir as permissões de acesso a arquivos e diretórios de forma mais fácil.

- **cat /etc/group** = ver todos os grupos do sistema
- **groups** = exibir todos os grupos de um usuário
- **sudo addgroup** = criar um grupo
- **add user** _nomeUsuário_ _nomeGrupo_ = adicionar o usuário ao grupo
- **gpasswd -d** _nomeUsuário_ _nomeGrupo_ = remover usuário do grupo
- **groupdel** _nomeGrupo_ = excluir um grupo
- **cat /etc/group/grep** _nomeGrupo_ = para retornar um grupo 4



# Permissões:

r - read

w - white

x - execution 



- **ls -lh** = verificar permissões em um diretório
- **chmod** _nºoctal_ _exemplo.txt_ = mudar a permissão de um arquivo ou comando
  - Modo octal:
    - 1º dígito representa o dono do ficheiro/diretório (u);
    - 2º dígito representa o grupo (g);
    - 3º dígito representa os outros (o);
    - As permissões são especificas para cada grupo. 

| User (Ower) | Group | Other |
| :-------------: | :------------------------: | :------------------: |
| R      W      X | R      W      X            |   R      W      X    |
| 4      2      1 | 4      2      1 | 4      2      1 |

