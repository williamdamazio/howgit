# Atividades no GitHub (online)

1 - Vá para o github: https://github.com/William-Damazio/

- Crie um novo projeto no repositório com o nome `Basico-Git-e-GitHub`

2 - Crie uma pasta no computador local

- Nomear a pasta para `Basico-Git-e-GitHub`

- Abra a pasta com o programa `Git Bash Here`

# Projeto inicial do Git

## Comandos

- `git --version`

*Exibe versão para confirmar se a instalação está correta.* 

- `git config --global user.email "williamsdamazio@gmail.com"`

ou

- `git config --global user.name "Your Name"`

*Acessar GitHub pelo email cadastrado. (Encontrado em Settings da conta)*

## Após abrir a pasta com o Git

- `git init`

*Iniciar git no repositorio main (ramificação principal).*

- `git branch -M "main"`

*Mudar o nome da Branch (ramificação, ramo).*

- `git add nome_arquivo.ext`

*Colocar os arquivos em fila para serem despachados(Commit).*

- `git status`

*Passar informação do estado do Git.*

- `git commit -m "Primeiro Commit"`

*Exportar os arquivos e acrescentar uma mensagem relacionada aos despachos.*

- `git remote add origin "https://github.com/willsbq/ProjetoGit.git"`

*Preparar para adicionar o arquivo com apelido "origin" no projeto criado no GitHub.*

- `git push -u origin main`

*Enviar origin para main*

- `clear`

*Limpar o Bash.*

## RESUMO

…or create a new repository on the command line

echo "# Basico-Git-e-GitHub" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin 
https://github.com/William-Damazio/Basico-Git-e-GitHub.git

git push -u origin main




…or push an existing repository from the command line

git remote add origin 
https://github.com/William-Damazio/Basico-Git-e-GitHub.git

git branch -M main

git push -u origin main