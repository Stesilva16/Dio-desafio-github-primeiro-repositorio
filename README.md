# Desafio de projeto sobre Git/Github da DIO
Repertorio criado para o Desafio de Projeto sobre Git/Github

## Links Utéis

[Sintaxe Basica Markdow](https://www.markdownguide.org/)

## O que é o Git:

É um sistema de versionamento de código comumente utilizado para projetos de desenvolvimento de software. Isso significa que ele trabalha como um intermediador entre um repositório local e um remoto (como por exemplo o GitHub), onde você pode controlar e administrar as alterações e atualizações do seu código. Lembrando que Git e GitHub não são a mesma coisa !!
#### Em resumo:
##### Fica mais fácil de compreender o que é o Git quando analisamos o fluxo de trabalho do Git.
## Alguns comandos do Git:
- git init: inicializa um repositório local git
- git status: verifica o estado dos seus arquivos
- git add <nomeDoArquivo>: envia seu arquivo especificado para o Stage
- git add - -all: envia todos os arquivos para o Stage
- git commit -m “tituloDoCommit: envia o que está no Stage para o HEAD
- git remote add origin urlDoRepositorio: adiciona e indica a URL do repositório remoto em que os arquivos serão mantidos
- git push origin master: envia os arquivos para o repositório remoto que você especificou através da URL do comando acima
- git checkout -b <nomeDaBranch>: cria uma nova branch
- git checkout <nomeDaBranch>: alterna para a branch especificada
### Lembrando que o Git abrange 3 camadas. O chamado “Working Directory”, que é onde você está codificando seu projeto, o “Index”, também chamado de “Stage”, que é uma camada onde você adiciona suas modificações de forma não permanente, ou seja, nesta camada você pode resetar as alterações que você incluiu no Stage/Index ou então partir para a próxima camada, a chamada de “HEAD”, quando você confirma suas alterações fazendo um “commit”. Porém essa ultima camada ainda não é o seu repositório remoto para o qual você deseja incrementar suas modificações. Para que o seu código chegue até o repositório remoto é necessario um comando muito simples chamado git push. 

## O Que é o Git Bash:
Git Bash é o aplicativo para ambientes do Microsoft Windows que oferece a camada de emulação para a experiência de linha de comando Git.
Bash é acrônico para "Bourne Again Shell". Shells são aplicativos terminais usados como interface em sistemas operacionais por meio de comandos gravados.

[Base de ideias](https://medium.com/@andradegabriela20/o-que-%C3%A9-git-git-bash-e-comandos-b%C3%A1sicos-94a53de6d376)

