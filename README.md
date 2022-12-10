<h1 align="center"> dio-orange-tech-00-intro-git-e-github </h1>
<h2 align="center">Repositório do 1º projeto do BootCamp Orange Tech sobre Git e GitHub</h2>


# Sumário

- [O que é Git e GitHub ?](#o-que-é-git-e-github)
  - [Git](#git)
  - [GitHub](#github)
- [Comandos básicos no terminal](#comandos-básicos-no-terminal)
  - [Windows](#windows)
  - [Linux](#linux)
- [Git "por baixo dos panos"](#git-"por-baixo-dos-panos")
  - [Fundamentos](#fundamentos)
  - [Objetos internos do Git](#objetos-internos-do-git)
  - [Chave SSH e Token](#chave-ssh-e-token)
- [Ciclo de vida dos arquivos no Git](#ciclo-de-vida-dos-arquivos-no-git)
- [Resolvendo conflitos](#resolvendo-conflitos)


# O que é Git e GitHub ?
  Pela frequência do uso dos dois termos de maneira conjunta, é comum que cause certa confusão em pessoas que estão tendo seu primeiro contanto com eles, levando a acreditar que ambos termos tratam-se da mesma coisa. Mas, não são! Vou explicar o porquê nos tópicos abaixo. 👇

## Git
  Criado em 2005, por Linus Torvalds e sua equipe, trata-se de um **sistema de versionamento distribuído**, o qual permite que cada linha de código modificada ou nova, seja versionada e salva corretamente, desta maneira podemos transitar facilmente pelas versões mais antigas do nosso código ou realizar novas implementações de maneira segura.

## GitHub
  Desenvolvido pela Microsoft, o github é uma plataforma que permite a hospedagem do nosso código em um ambiente de maneira remota, trazendo benefícios como:
  - Armazenamento em nuvem
  - Facilitação do trabalho em equipe
  - Melhorio do seu código (por meio de feedback de outras pessoas desenvolvedoras a respeito dele).

# Comandos básicos no terminal
  Comandos básicos para trabalhar com o terminal, Linux & Windows:

## Windows:
  - `dir` >> Traz uma lista de diretórios contidos na pasta em que estamos situados.
  - `cd` >> Caminha até determinado arquivo | cd ~> "change directory".
    - `cd ./` >> caminha para um diretório interno.
    - `cd ../` >> Volta um diretório.
  - `cls` >> Limpa o terminal | cls -> "clear screen".
  - `mkdir` >> Cria uma pasta nova | mkdir -> "make directory".
  - `echo hello > hello.txt` >> Insere o conteúdo hello dentro de um novo arquivo "hello.txt".
  - `del diretorio_exemplo` >> Deleta todos arquivo dentro de um diretório.
  - `rmdir diretorio_exemplo /S /Q` >> Deleta um diretório juntamente com todos seus arquivos.
    - "/S" >> Deleta a árvore de arquivos do diretório.
    - "/Q" >> Não pede por confirmação ao deletar a árvore de um diretório.
## Linux:
  - `ls` >> Traz uma lista de diretórios contidos na pasta em que estamos situados.
  - `cd` >> Caminha até determinado arquivo | cd ~> change directory
    - `cd ./` >> Caminha para um diretório interno
    - `cd ../` >> Volta um diretório
  - `clear` >> Limpa o terminal.
  - `mkdir` >> Cria uma pasta nova | mkdir -> "make directory". 
  - `echo hello > hello.txt` >> Insere o conteúdo hello dentro de um novo arquivo "hello.txt".
  - `rm -rf diretorio_exemplo` >> Deleta um diretório juntamente com todos seus arquivos de maneira recursiva e forçada.




# Git "por baixo dos panos"
## Fundamentos
## Objetos internos do Git
## Chave SSH e Token
# Ciclo de vida dos arquivos no Git
# Resolvendo conflitos

