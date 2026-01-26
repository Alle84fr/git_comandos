# GitHub, Git e seus comanos
[Significados ](#Significados) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Comandos](#Comandos)

## Significados:

[O que é o Git](#-git) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[O que é o GitHub](#-gitHub) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[O que é o Commit](#-commit) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[O que é o Branch](#-branch) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[O que é o Origin](#-origin)


#### 🍀 Git:

Sistema de controle de versão do código = <i>versionamento.</i>

Registra mudanças realizadas no código e as mantém organizadas.

Sistema distribuído = código possui histórico completo que pode ser - compartilhado, usado e modificado por outros desenvolvedores 

#### 🪼 GitHub 🐱:

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

[Repositório](#-repositório) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[URL Repositório](#-url) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Git init](#-git-init) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Git clone](#-git-clone) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Git status](#-git-status) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Git add](#-git-add) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Git commit](#-git-commit) 

[Git push](#-git-push) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Git  pull](#-git-pull) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Git branch](#-git-branch) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fork](#-fork) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Git merge](#-git-merge) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [⬆︎ voltar](#Significados)


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

#### 🌱 Repositório:

╰┈➤ Iniciando:

- Página profile

![Pag Profile com mensagem create new](/img/01.png)
![Lista de ações, criar respotories](/img/02.png)

Página profile (principal), lado direito superior, clicar no símbolo de +

Aparecerá uma lista de ações, clicar em <b>new repository</b>
<br>
- Página Dashboard

![Pag Dashboar com botão verde](/img/03.png)

Página dashboard, lado esquerdo, botão verde, no lado direito do texto top repositories

- Todas páginas - menu navegação

![lista de pag do github](/img/04.png)
![Pag repositories com botão verde new](/img/05.png)

Clicar na foto (sua foto, logo, etc), redonda, lado direito

Clicar em Repositories

Clicar no botão verde new

╰┈➤ Criando:

1° Repository name = nome que quer dar no repositório, ele será usado no url

2° Description = opcional
&nbsp;&nbsp;&nbsp;&nbsp; Breve descrição do projeto

3° Configutation = se será: público, todos podem ter acesso
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; particular, só vc ou quem tiver permissão pode ter acesso

4° ADD README - README.md é capa do projeto, nele estão o que é o projeto, tecnologias usadas, estrutura do projeto, autores e outras informações

&nbsp;&nbsp;&nbsp;&nbsp;Por costume eu add REDME.md depois, deixo off

5° ADD GITIGNORE - Gitignore é uma pasta com conteúdos que deverão ser ignorados na hora de commitar e dar push, já tive de usar, mas, geralmente deixo No.gitignore

6° ADD LINCENSE - diria que é como outros pode usar, divulgar o conteúdo, se tem permissão de atuar no projeto.

&nbsp;&nbsp;&nbsp;&nbsp;Esta parte não tenho muitos conhecimentos, mas, quando coloco eu ponho MIT License - pessoa pode usar mas deve informar que é seu

&nbsp;&nbsp;&nbsp;&nbsp;O mais adequado é estudar cada uma delas e ver qual se adequa ao tipo de projeto.

7° CREATE REPOSITORY 

[⬆︎ voltar](#comandos)
<br>

#### 💐 URL:

![Pag do repositório criado](/img/06.png)

Ao criar repositório irá abrir a página do mesmo

Dentro do retângulo azul - Quick setup ... - o HTTPS estará na cor cinza (selecionado) e um pouco mais ao lado, o url (https://Github.....)

Este URL será usado para:

<b>Inciar </b>um repositório local(seu computador), se estiver vazio no remoto (no github).

<b>Clonar </b>um repositório local, se estiver com algo já adiconado no remoto.

<b>Enviar </b>o link para que outra pessoa o encontre ou possa fazer fork, ou outras ações

[⬆︎ voltar](#comandos)
<br>

#### 🪾 Git init:

Iniciar no seu computador (local) o projeto criado no github (repositório) que, neste caso,
<b><i>DEVEE ESTAR VAZIO</i></b>

Deve criar uma pasta,s e for usar comandos no terminal é mkdir nome_pasta (eu coloco o mesmo do repositório criado), cd . nome_pasta, para entrar na pasta, code . (este só para vscode) que é entrar na pasta

No terminal:

- inicia o git no computador
```
git init
```
- Criar seu projeto, seus files e folders, quando quiser mandar algo
<br>
- No decorrer das explicações direi um pouco mais sobre formas de adiconar, esta não é a única
```
git add .
```
- No decorrer das explicações direi um pouco mais sobre commit
```
git commit -m "texto"
```
- Conectando o repositório local(seu computador) ao remoto(github).
Traduzo o comando como :
"conecte o git remoto "nome" url

```
git remote add origin url
```
ex: git remote add origin https://github.com/Alle84fr/nome_repositorio.git

[⬆︎ voltar](#comandos)
<br>

#### 🪺 Git clone:

O respositório <b> já deve ter algum conteúdo</b>, seja uma descrição, README, um file

Não crio pasta antes, apenas clono e entro

O comando dará um pull e trará todo conteúdo da nuvem (remoto) para o local

```
git clone url
```

ex: git clone https://github.com/Alle84fr/nome_repositorio.git

[⬆︎ voltar](#comandos)
<br>

#### 🪻 Git status:

- informa:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Nome da branch ativa, que está atuando no momento
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Changes to comitted = mudanças já adicionadas que poderão ser commitadas, já estão no staged(local de espera)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Changes not Staged for commit - arquivos que o git já rastreou, ex, já foi adicionado anteriormente, mas tiveram modificações que não foram adicionadas
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Untracked files - arquivos novos ainda não rastreados, não adicionados anteriormente

```
git status
```

[⬆︎ voltar](#comandos)
<br>

#### 🌲 Git add:

Marcando, adicionando o arquivo a área chamada de staging area, local onde os arquivos ficam esperando para ver se serão, ou não commitados

- adicionando apenas um arquivo

Se por . depois do add e apertar TAB ou inicio do nome do file, irá aparecer as opções existentes no projeto, seleciona com ENTER

```
git add nome_file.extensão
ou
git add nome_folder/nome_file.extensão
```

ex: git add README.md
ex: git add .\text\texto.js

- mais de um arquivo, observe que há um espeço entre os nomes

```
git add nome_file.extensão nome_file.extensã
```

ex: git add aula1.py aula2.py README.md

- todos de uma única vez

Este comando pega todos os arquivos criados e modificados, sem risco de esquecer algum

```
git add .
```

[⬆︎ voltar](#comandos)
<br>

#### 🌹 Git commit:

Deixar tudo pronto para envio ao repositório remoto
Se abrir uma aspa, escrever uma linha e der enter, irá criar nova linhas, só será considerado fim do comentário do commit, quando a segunda aspas for posta
Curiosidade -m é atalho para mensagem ou nomear, neste caso, mensagem

```
git commit -m "texto"
ou
git commit -m "texto1
texto2
texto3" 
```

- Verbos para commitar
&nbsp;&nbsp;➡︎ <b>add</b> = quando foi adicionado novos arquivos, funcionalidades, branches .....
&nbsp;&nbsp;➡︎ <b>fix</b> = quando se corrigiu u bug
&nbsp;&nbsp;➡︎ <b>update</b> = atualização, porém sem correção de bugs
&nbsp;&nbsp;➡︎ <b>enhance</b> = atualização, porém sem correção de bugs
&nbsp;&nbsp;➡︎ <b>remove</b> = removeu, deletou algo
&nbsp;&nbsp;➡︎ <b>rename</b> = renomeou algo como, variável, função, file, folder ....
&nbsp;&nbsp;➡︎ <b>refactor</b> = melhoria do código, sem corrigir erros
&nbsp;&nbsp;➡︎ <b>move</b> = moveu arquivo, código para outro lugar
&nbsp;&nbsp;➡︎ <b>revert</b> = desfez alteração
&nbsp;&nbsp;➡︎ <b>merge = </b> = mesclou as merges

- verificar histórico de commits, mostra a hash SHA-1 completo (40 caracteres)

O short hash pega os 7 primeiros n°s do hash SHA completo

PARA SAIR DEVE DIGITAR &nbsp;&nbsp;&nbsp;<b><i>q</i></b>

informa:

hash SHA , se este for o último commit feito terá (HEAD -> branch, orignal/main)

autor <e-mail>

data

mensagem do commit

```
git log
```

- para verificar histórico de commits, mas de forma compacta (short hash)

Este não precisa teclar q para sair, sai direto

informará:

short hash mensagem do commit

se for o último commit feito será short hash (HEAD -> branch , origin/main) mensagem commit

```
git log --oneline
```
- remover último commit (o head)

Desfaz commit e remove alterações do staged

As alterações permanecerão no diretório

```
git reset Head~1
```

- remover commit permanentemente

```
git reset --hard HEAD~1
```

DEPOIS DE ALTERAR DEVE DAR UM DESTES COMANDO

<i>Para atualizar o repositório remoto</i>

```
git push origin nome_branch -f
ou
git push origin nome_branch --force
ou
git push --all --force
```

- excluir commit específico, não sendo o último

Poder ver qual hash

```
git log 
ou 
git log --oneline
```

Abrirá editor de texto

```
git rebase -i hash_do_commit
```
Aparecerá os commites mais ou menos assim:

pick 5c6c04a Adiciona nova feature de login

pick a2b3c4d Corrige bug de cadastro

Troque pick por drop ou deleta a linha

drop e1f2g3h Commits para teste

pick 4d5e6f7 Mais correções

pick 8a9b0c1 Atualiza arquivo de configuração

tecle:

w - salvar

ws - salvar e sair

q - desistir

DEPOIS DEVE DAR

```
gir push --all --force 
ou 
git push origin nome_branch -f
```

[⬆︎ voltar](#comandos)
<br>

#### 🌻 Git push:

Enviar modificações do repositório local para remoto

- enviar uma branch específica

```
git push origin nome_branch
```

ex: git branch origin main
ex: git branch origin alle

- envinando todas branches local

```
git branch --all
ou
git branch -a
```

[⬆︎ voltar](#comandos)
<br>

#### 🌷 Git pull:

Trazer conteúdo da remota para local

- uma única branch

```
git pull origin nome_branch
```

- trazer todas (pode dar conflito)

```
git pull --all
```

- trazer trodas infromações, SEM MESCLAR

```
git fetch --all
```

[⬆︎ voltar](#comandos)
<br>

#### 🌼 Git branch:

Curiosidade o -a é de all, todas
- Saber todas as branches, local e remota

```
git branch -a
```

- Mudar nome da branch

```
git branch -m novo_nome_branch
```
ex: a branch se chamava main e se tornará master
 git branch -m master

- Criar branch sem entrar direto na nova branch

```
git branch nome_nova_branch
```
ex: estou na branch main e quero criar outra branch e continuar na main
git branch alle

- Mudar de branch

```
git checkout nome_branch
```
ex: estava na branch main e mudei para alle
git checkout alle

- ciar uma branch e no mesmo comando ir para a nova branch

 -b de branch, comando que faz mudar a branch "automaticamente"

```
git checkout -d nome_branch
```
ex: ao dar enter, irá criar a branch alle, sairá da branch main e entrará na alle
git checkout -b alle

- enviar as branches para repositório remoto

 -u é atalho para o comando --set-upstream, conecta branch local à remota

 Depois de usar o -u não precisa mais informar o remoto e a branch

```
git push origin -u nome_nova_branch
```
ex:antes
git push origin nome_nova_branch
git pull origin nome_nova_branch
depois:
git push
git pull

- copiar branch original (que será copiada) em outra branch destino (que receberá a cópia)

ATENÇÃO - SOBRESCEVE TODOS OS ARQUIVOS ATUAIS

reset - desfaz alterações no histórico de commits

 --hard remove as alterações do diretório, staging e do commit

Quero deixar a branch alle exatamente igual a branch lua

1° estar na branch de destino, que receberá a cópia, para isso pode usar comando de mudar de branch

2°comando

```
git reset --hard nome_branch_original
```

ex: Já está dentro da branch lua
git --hard alle

- copiar branch mantendo historio, se tiver arquivos diferentes irá manter-nos, já os que tiverem iguais, irá sobrescrever

Merge mescla as alterações

 --stategy-option para o git resolver o conflito de merge

 theirs branch original sobrescreve a branch destino

1° já estar na branch destino

```
git merge branch_original --stategy-option theirs
```
- deletar branch local

```
git branch -d nome_da_sua_branch
```
- deletar branch remoto no terminal

```
git push origin :nome_da_sua_branch
```
[⬆︎ voltar](#comandos)
<br>

#### 🌳 fork:

Copiar todo um repositório de outra pessoa no seu github
Todas modificações que fizer neste fork não serão passados para o original
Se quiser atualizar, conforme o original, deve dar comando

1° Ir no repertório que deseja copiar

2° Selecionar Fork

3° create a new fork

4° clonar no seu computador

![Pag repositório para afzer fork](/img/07.png)

[⬆︎ voltar](#comandos)
<br>

#### 🌳 Git merge:

Clicar em:

&nbsp;&nbsp;&nbsp;&nbsp; - pull request
&nbsp;&nbsp;&nbsp;&nbsp; - new pull request
&nbsp;&nbsp;&nbsp;&nbsp; - base = main
&nbsp;&nbsp;&nbsp;&nbsp; - compare = branch a ser enviada para main
&nbsp;&nbsp;&nbsp;&nbsp; - create pull request
&nbsp;&nbsp;&nbsp;&nbsp; - Se não tiver conflito, merge pull request
&nbsp;&nbsp;&nbsp;&nbsp; - confirm merge
<br>
[⬆︎ voltar](#comandos)
