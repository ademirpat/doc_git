# Documentaçao git
## 💻 Relação de comandos básicos

> ## Comandos e sua funções


> ###  Comando inicial:


+ ele inicia o arquivo "/.git" para controlar a pasta.
````
git init
````


> ###  Configuração do usuário do git:

+ altera o nome de usuário
````
 git config --global user.name "<*seu_nome*>
````


+ altera o e-mail de usuário
````
git config --global user.email "<*seu_email*>"
```` 

> ### Comandos básicos:
> 
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
````
git commit -m "<*texto_da_modificação*>":
````

+ validar os meus comentários e modificações.
````
git log:
```` 

+ Cria uma nova branch ou ramo
````
git checkout -b <*nome_da_branch*>
```` 

+ Muda de branch/ramo
````
git checkout <*nome_da_branch*>
```` 

+ Ele adicona a branch atual o conteúdo de outra branch.
````
git merge <*nome_da_branch*>
```` 

+ Baixa o projeto do repositório.
````
git clone <*url*>
```` 

+ Ele envia a alteração para o repositório.
````
git push
```` 

+ Ele puxa as alterações do repositório.
````
git pull
````

> ## ⚠️ *Possíveis erros:*

+ **403:** apagando as gerenciais, gerenciamento de credenciais.
