# Git E GitHub

Git é um sistema de controle de versão de código, proporcionando organização, segurança 
e facilidade no trabalho em equipe. Github é uma plataforma de hospedagem desses códigos.

[Link para download do Git](https://git-scm.com/downloads) 

### Git Bash

O Git Bash é um terminal extendido para otimizar o uso do Git.

### Repositório

Pasta em que estão todos os arquivos do projeto e que está fazendo parte de um
controle de versão.

### Usando o Git Bash
Abrindo o Git Bash dentro da pasta que será o repositório, temos essas funcionalidades:

> `git init `  - A pasta passa a ser um repositório local (é criada uma pasta oculta .git);
>
> **É possível verificar a existência dessa pasta através do comando `ls -la`, o qual
> lista todos os arquivos e pastas, inclusive os ocultos ** 

> `git status `  - Este comando listará todos os os arquivos/diretórios novos 
> ou que sofreram modificações

> `git add .`  - Este comando fará todos os arquivos/diretórios irem para o estado Preparado, incluindo as alterações no próximo commit.

> `git commit -m "mensagem de commit"`  - Este comando fará todos os arquivos/diretórios que estão no estado Preparado irem para o repositório.

> `git push origin main`  - Este comando fará todos os arquivos/diretórios do repositório local irem para a hospedagem remota em nuvem.

 

### Os três estados:
Os arquivos do repositório sempre estão em um dos estados fundamentais:
#### 1. Modificado (modified): Arquivos adicionados, modificados ou removidos
Ainda não foi informado que esses arquivos farão parte do próximo commit, ou seja,
da próxima versão que será consolidada no repositório.

#### 2. Preparado (staged/index): **Após comando `git add` ser executado no arquivo **
Nesse estado o Git já foi informado que arquivo foi modificado e está pronto para ser 
commitado, é o momento de decidir se faremos o commit ou não.

#### 3. Consolidado (comitted): **Após comando `git commit` ser executado no arquivo **

**Obs: Não é possível pular estados, o fluxo deve ser seguido**
**Obs: No terceiro estado o arquivo efetivamente fará parte do repositório** 

