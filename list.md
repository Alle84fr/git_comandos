# GitHub, Git e seus comanos
[Significados ](#Significados:) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Comandos](#Comandos)

## <span style="color: green;">Significados:</span>

[O que é o Git](#Git:) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[O que é o GitHub](#GitHub:) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[O que é o Commit](#Commit:) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[O que é o Branch](#Branch:) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[O que é o Origin](#Origin:)

#### 🍀 Git:

Sistema de controle de versão do código = <i>versionamento.</i>

Registra mudanças realizadas no código e as mantém organizadas.

Sistema distribuído = código possui histórico completo que pode ser - compartilhado, usado e modificado por outros desenvolvedores 

#### 🍀 GitHub:

<i>Plataforma online</i>, para salvar os repositório (remoto), públicos ou privados.

#### 🌿 Commit:

<i>Promessa de envio</i> de uma nova versão do projeto.

Registra um ponto onde houve mudanças

#### 🌵 Branch:

A branch <i>Main/master é o braço, ou a linha principal do projeto</i>. Ela recebe as outras linhas/branches do projeto.

A branch que vai para produção

Geralmente, para não ter problemas nos projetos, os desenvolvedores utilizam outra branch para criar e testar os códigos e só depois juntam (merge) à branch principal

#### 🌱 Origin:

Nome, <i>apelido dado para o url do git</i>

Ao invés de ter de sempre digitar todo url, usa-se a palavra origin no lugar do endereço URL

## Comandos:

[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[](#) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

#### 🌴 Global e Remoto:

GLOBAL - irá modificar todos os repositório.
A modificação será do momento da configuração e seguirá para os diante.

REMOTO = irá modificar apenas o repositório em questão, não sendo aplicado a outros repositórios

- Configuração de <b>e-mail</b>

``` git config --global user.email "e-mail" ```

ex: git config --global user.email "alle@ gmail.com"

``` git config user.email "e-mail" ```

ex: git config user.email "alle@ gmail.com"

- Configuração do <b>usuário</b>

``` git config --global user.name "nome" ```

ex: git config --global user.name "Alle"

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; git config user.name "Alle"

- <b>Verificar</b> usuário e e-mail

```git config user.name```

```git config user.email```
