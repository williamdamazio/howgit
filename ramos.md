## Conceitos de Branch (ramificação)

- `git checkout -b "auxiliar"`

*Primeiro crie a Branch e depois faça as edições.*

*Checkout sai da branch Main e vai para a **auxiliar***

*Crie o(este) arquivo **ramos.md** no CodeStudio e seu conteúdo.*

- `git add .`

- `git commit -m "adicionando arquivo ramos.md ao branch auxiliar"`

*Adicionando ou Atualizando o arquivo ramos.md ao Branch auxiliar*

- `git push origin auxiliar`

*Envia para o projeto no GitHub na branch (ramificação) que estamos trabalhando agora: auxiliar*

## Juntar ramificações

- `git checkout main`

*Use git checkout main para ir para a branch (ramificação) main, que é a ramificação que deverá ser usada e irá receber a ramificação auxiliar.*

- `git merge auxiliar`

*Juntar (**Merge**) a ramificação auxiliar à main (que está em uso).*

- `git push origin main`

*Envia para o projeto no GitHub na branch (ramificação) main. Com isso, o arquivo **ramos.md** irá aparecer na ramificação main.*
