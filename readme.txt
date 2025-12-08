informa de tem arquivo que foi modificado, quais arquivos estão selecionados para ser enviados e se tem algum commits que seria a descrição do que foi feito.
git status

adiciona apenas o arquivo informado 
git add [ARQUIVO]

adiciona todos os arquivos que foram modificados 
git add .

git commit -m ["DESCRIÇÃO"]

git push origin [BRASH]

copiar os arquivos que estão no site git e colar no local onde está selecionado
já cria uma pasta com o nome do repositorio
git clone [URL]


git config --global user.name ["NAME"]
git config --global user.email ["YOU@EMAIL.COM"]

cria uma nova ramificação
git checkout -b nova-feature

Resetar Staging
git reset

sincronizar todas as branches remotas com o repositório local
git fetch


----------------
Criando uma Nova Branch

cria uma brash e vai para essa brash
git checkout -b alternativa_a

informa a branch que está no momento
git branch

vai para a branch informada
git checkout [MAIN]

os arquivos da branch na qual está será substituída pelos arquivos da branch informada
git merge alternativa_a


-------------------------------------------------------------------
Criando um Novo Repositório Local

Crie um novo repositório no GitHub

Inicialize o repositório
git init

Adiciona todas as alterações para serem commitadas.
git add .

Realiza um commit com a mensagem especificada.
git commit -m ["DESCRIÇÃO"]

Verifica o status atual do repositório.
git status

Exibe o histórico de commits.
git log

adicione o repositório remoto
git remote add origin [URL]

Envie suas alterações para o GitHub
git push -u origin main


-------------------------------------------------------------------

pegando um Repositório no Git

esteja na pasta onde você quer importar que fique o arquivo que será importado do git
cd /caminho/para/pasta

git clone [URL]



-------------------------------------------------------------------

----------------
Atualizar Branch Local

precisa está na mesma branch para fazer a atualização do remoto para o local
git pull origin main


----------------
Mesclar Branch Remota no Local

vá para a branch que será alterada
git checkout [branch]

depois escolha a branch que será mesclada na branch atual "onde você está"
git pull origin [branch]








