# Minicurso Git-Github Eus
Repositório criado no curso Git-GitHub 29/05/26

## Comando em Promt

1. git config --global user.name "Nome"

2. git config --global user.email "email"

3. git clone "link do repositório" //Trazer o repositório do Github para a máquina local

4. cd "Nome do repositório" //

5. code . //Traz todo o código

6. git config --global --list

7. git config --global credential.helper store

## Conceitos Básicos

git status

git add . //Manda os arquivos para o Stage

git commit -m "As Alteracoes que fiz" //Enviando o código e descrevendo as alterações

git push origin "nome-da-branch" //Termina de enviar o código local para o GitHub (Remoto)

Git Pull

##Branches

git branch //Verificar as Branches existêntes

git checkout -b 'develop' //Cria uma nova Branch (Ramificação)

git checkout "nome-da-brach" //Mudar para a Branch escolhida

git merge "nome-da-brach" //Atualizar a branch atual

git fetch //Traz todas as Branch do GitHub para a Máquina Local