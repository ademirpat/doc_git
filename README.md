# Documentaçao git
## 💻 Relação de comandos básicos

> ##   ⚙️ Comandos e sua funções


> ### ▶️ Comando inicial:


+ ele inicia o arquivo "/.git" para controlar a pasta.
````
git init
````


> ### 🧑‍💻 Configuração do usuário do git:

+ altera o nome de usuário
````
 git config --global user.name "<*seu_nome*>
````

+ altera o e-mail de usuário
````
git config --global user.email "<*seu_email*>"
```` 

> ### 🚀 Comandos básicos:
+ responsável por validar os arquivos modificados dentro do projeto.
  
````
git status:
````
 
>  🔴 *Em vermelho ele mostra os arquivos modificados.*
>
>  🟢 *Em verde mostra os arquivos que foram adicionados pelo "git add".*


+ responsável por adiciona o arquivo modificado em uma área segura.
````
git add:
````

+ Ele é responsável por criar uma nova versão do projeto com as referências do criador.
````git commit -m "<*texto_da_modificação*>":````

+ **git log:** validar os meus comentários e modificações.

+ **git checkout -b <*nome_da_branch*>:** Cria uma nova branch ou ramo

+ **git checkout <*nome_da_branch*>:** Muda de branch/ramo

+ **git merge <*nome_da_branch*>:** Ele adicona a branch atual o conteúdo de outra branch.

+ **git clone <*url*>:** Baixa o projeto do repositório.

+ **git push:** Ele envia a alteração para o repositório.

+ **git pull:** Ele puxa as alterações do repositório.

> ## ⚠️ *Possíveis erros:*
+ **403:** apagando as gerenciais, gerenciamento de credenciais.
