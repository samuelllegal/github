# GitHub

<br><br>
## Fazendo conexão do computador local para o servidor do git 
**lembrando que precisa ter o diretoria no github já criado**
~~~MARKDOWN
cd [/caminho/para/pasta]
~~~
~~~MARKDOWN
git init
~~~
~~~MARKDOWN
git remote add origin [URL]
~~~
----------------------------------------------------------------
<br><br>
## Fazendo conexão do servidor do git para o computador local

~~~MARKDOWN
cd [/caminho/para/pasta]
~~~
~~~MARKDOWN
git clone [URL]
~~~
----------------------------------------------------------------
<br><br>

git add .
git commit -m ["DESCRIÇÃO"]
git status

git push -u origin main

>informa de tem arquivo que foi modificado, quais arquivos estão selecionados para ser enviados e se tem algum commits que seria a descrição do que foi feito.
  ~~~MARKDOWN
  git status
  ~~~

adiciona apenas o arquivo informado 
~~~MARKDOWN
git add [ARQUIVO]
~~~
adiciona todos os arquivos que foram modificados
~~~MARKDOWN
git add .
~~~
~~~MARKDOWN
git commit -m ["DESCRIÇÃO"]
~~~
~~~MARKDOWN
git push origin [BRASH]
~~~
copiar os arquivos que estão no site git e colar no local onde está selecionado
já cria uma pasta com o nome do repositorio
~~~MARKDOWN
git clone [URL]
~~~
~~~MARKDOWN
git config --global user.name ["NAME"]
~~~
~~~MARKDOWN
git config --global user.email ["YOU@EMAIL.COM"]
~~~
cria uma nova ramificação
~~~MARKDOWN
git checkout -b nova-feature
~~~
Resetar Staging
~~~MARKDOWN
git reset
~~~
sincronizar todas as branches remotas com o repositório local
~~~MARKDOWN
git fetch
~~~

----------------
## Criando uma Nova Branch

cria uma brash e vai para essa brash
~~~MARKDOWN
git checkout -b alternativa_a
~~~
informa a branch que está no momento
~~~MARKDOWN
git branch
~~~
vai para a branch informada
~~~MARKDOWN
git checkout [MAIN]
~~~
os arquivos da branch na qual está será substituída pelos arquivos da branch informada
~~~MARKDOWN
git merge alternativa_a
~~~

-------------------------------------------------------------------
## Criando um Novo Repositório Local

Crie um novo repositório no GitHub

Inicialize o repositório
~~~MARKDOWN
git init
~~~
Adiciona todas as alterações para serem commitadas.
~~~MARKDOWN
git add .
~~~
Realiza um commit com a mensagem especificada.
~~~MARKDOWN
git commit -m ["DESCRIÇÃO"]
~~~
Verifica o status atual do repositório.
~~~MARKDOWN
git status
~~~
Exibe o histórico de commits.
~~~MARKDOWN
git log
~~~
adicione o repositório remoto
~~~MARKDOWN
git remote add origin [URL]
~~~
Envie suas alterações para o GitHub
~~~MARKDOWN
git push -u origin main
~~~

-------------------------------------------------------------------

## pegando um Repositório no Git

esteja na pasta onde você quer importar que fique o arquivo que será importado do git
~~~MARKDOWN
cd /caminho/para/pasta
~~~
~~~MARKDOWN
git clone [URL]
~~~


-------------------------------------------------------------------

----------------
## Atualizar Branch Local

precisa está na mesma branch para fazer a atualização do remoto para o local
~~~MARKDOWN
git pull origin main
~~~

----------------
Mesclar Branch Remota no Local

vá para a branch que será alterada
~~~MARKDOWN
git checkout [branch]
~~~
depois escolha a branch que será mesclada na branch atual "onde você está"
~~~MARKDOWN
git pull origin [branch]
~~~






