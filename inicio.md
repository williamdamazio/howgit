# Atividades no GitHub (online)

1 - Vá para o github: https://github.com/williamdamazio/

- Crie um novo projeto no repositório com o nome `howgit`

2 - Crie uma pasta no computador local

- Nomear a pasta para `HowGit`

- Abra a pasta com o programa `Git Bash Here`

# Projeto inicial do Git

## Comandos

- `git --version`

*Exibe versão para confirmar se a instalação está correta.* 

- `git config --global user.name "williamdamazio"`

*Definir nome de usuário*

- `git config --global user.name`

*Verificar se o nome de usuário está correto*

- `git remote -v`

*Ver o nome dos repositórios que estam em uso*

- `git config --global user.email "williamsdamazio@gmail.com"`

ou

- `git config --global user.name "Your Name"`

*Acessar GitHub pelo email cadastrado. (Encontrado em Settings da conta)*

- `git remote add origin https://github.com/williamdamazio/howgit.git`

*Preparar para adicionar o arquivo com apelido "origin" no projeto criado no GitHub.*

- `git remote rm origin`

*Remove a url remota do repositório se ela já existir (Somente se der erro, para depois, adicionar novamente com o comando anterior).*


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

- `git remote add origin https://github.com/williamdamazio/howgit.git`

*Preparar para adicionar o arquivo com apelido "origin" no projeto criado no GitHub.*

- `git push -u origin main`

*Enviar origin para main*

*->**IMPORTANTE:** Caso o Git retorne erro de permissão, pesquise no Windows por **Gerenciador de Credenciais** e no link do Github mude o nome de usuário(williamdamazio) e a senha. *

- `clear`

*Limpar o Bash.*

## Atualizando um arquivo alterado

- `git add .`

*Subir todas as alterações feitas nos arquivos (**obs**. Caso tenha criado outro arquivo, ele será incluído na branch em uso)*

- `git commit -m "Adicionado Informações sobre o Gerenciador de Credenciais do Windows."`

*adiciona todos os arquivos.*

- `git push origin main`

*push eleva ao nosso respositório do Github (**sem o -u** se já se encontra no arquivo certo) no ramo principal, "main".*

## RESUMO

…or create a new repository on the command line

echo "# Basico-Git-e-GitHub" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin 
https://github.com/williamdamazio/howgit.git

git push -u origin main




…or push an existing repository from the command line

git remote add origin 
https://github.com/williamdamazio/howgit.git

git branch -M main

git push -u origin main
