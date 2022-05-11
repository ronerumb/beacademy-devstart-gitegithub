
# Comandos Git 

## Instalação 👾
Acesse o link https://git-scm.com/downloads e realize o Download de acordo com o sistema operacional utilizado

## Comandos de configuração  🤖

git config --global user.name = 'Nome aqui' - Configura o nome do utilizador do Git   
git config --global user.email - Configura o email de cadastro do Git


## Comandos de inicialização  🦾

git init - Inicializa o repositorio  
git add nomearquivo.html - Esse comando permite adicionar um arquivo especifico para ser enviado ao git no Commit  
git add . - Adiciona todos os arquivos para ser enviado ao git no Commit  
git rm --cached nomearquivo.html - Remove o arquivo especifico do envio no commit  
git commit -m "Escreva uma mensagem"- Envia os arquivos que foram adicionados pelos comandos "git add" para o repositorio no Git  


## Comandos de ramificações 👨‍👦‍👦

git branch - Lista todas as ramificações existentes no repositorio  
git branch nomedabranch - Cria uma nova branch  
git checkout nomebranch - Navega até a Branch  
git checkout -b nomebranch - Cria a Branch e já navega até ela  
git branch -d nomebranch - Exclui a Branch  
git merge  nomedabranch - Mescla a branch especificada com a brand master   
