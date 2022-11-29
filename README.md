# Tutorial-git-github

## Objetivos

O objetivo desse repositório é ensinar os primeiros passos, desde a configuração até o uso diário, do git, com apoio da plataforma [GitHub](https://github.com).


# O que é o Git e GitHub?

## Git

É um software de código aberto para controle de versões de arquivos, apesar de ser voltado à área de desenvolvimento de software, ele pode ser utilizado para quaisquer tipos de arquivos, por exemplo, versionamento de documentos e trabalhos de conclusão de curso.<br>

<img src="./images/Git-Logo.png" alt="logo do git" width="150"/>

O [Git](https://git-scm.com) foi publicado originalmente em abril de 2005 e foi desenvolvido pelo mesmo desenvolvedor do linux, [Linus Torvalds](https://github.com/torvalds), atualmente é o sistema de versionamento mais utilizado por uma ampla gama de profissionais na área.

> Esse sistema possui uma série de diferenciais quando comparado a outros softwares de versionamento, caso queira saber mais, [veja aqui](https://www.atlassian.com/br/git/tutorials/what-is-git).

## GitHub

É uma plataforma de hospedagem de código fonte, amplamente utilizada por milhares de usuários diariamente, tanto para projetos pessoais ou faculdade, qunato para uso profissional e código aberto.

<img src="./images/github-icon.png" alt="logo do GitHub MONA!" width="150"/>

A empresa foi fundada em 2008, sendo posteriormente adiquirida pela Microsoft, tendo crescido tanto que em julho de 2022 tinha cerca de 83 milhões de usuários na plataforma.

# Primeiros Passos

## Conta no GitHub

Antes de tudo, já crie sua conta no [GitHub](https://github.com), ela é gratuita, mas vale a pena linkar seu email da sua instituição de ensino, você pode ganhar diversos benefícios, entre eles o GitHub PRO, que te permite ter ilimitados repositoriórios privados (sem o PRO só se pode ter 1 por conta).

---

## Instalação do Git

O Git pode ser instalado em todos os principais sistemas operacionais da atualidade, sendo presente nativamente no Mac e kernel Linux.

Antes de se instalar, verifique se o seu sistema já não possui o git instalado, para isso, abra o terminal e digite o comando:

```
$ git version
```

caso tenha o git instalado, ele vai imprimir na tela a versão instalada no seu computador no seguite formato:

```
> git version 2.35.1.windows.2
```

Caso o Git não esteja instalado, ele mostrará o erro que o comando "git" não é conhecido. Logo, o mesmo deve ser instalado [clicando aqui](https://git-scm.com/downloads).

## Configuração do ambiente

Com o git instalado, agora deve-se configurar o usuario e e-mail para poder utilizar o mesmo.

### Definição do usuário:

Abra o terminal e digite o seguinte comando:

``` C++
$ git config --global user.name "Seu usuario" 
// substitua pelo seu nome de usuário
```

Para confirmar se o usuario foi cadastrado corretamente, execute o seginte comando, que deve retornar o seu usuário criado:

```
$ git config --global user.name

> Seu usuario
```

### Definição do Email

Abra o terminal e digite o seguinte comando:

``` C++
$ git config --global user.email "seu.email@exemplo.com" 
// substitua pelo seu email
```

Para confirmar se o email foi cadastrado corretamente, execute o seginte comando, que deve retornar o seu email cadastrado

```
$ git config --global user.email

> seu.email@exemplo.com
```