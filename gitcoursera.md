
## Comandos Básicos Git 
 - Inicializa um repositório git 
`git init`

### check your Git repository's status 
- Checa o status do repositório:
`git status` 

### add files to the staging area of your Git repository
- Adiciona arquivos para o staging area:
`git add .` 

### Commiting to the Git repository 
- Fazendo isso você cria um commit no seu repositório
`git commit -m "first commit"` 

### Checking the log of Git commits
- Checa o log do repositório
`git log --oneline` 

### Checking out a file from an earlier commit
- Checa o arquivo de um commit anterior
`git checkout <second commit's number> index.html</li>` 

### Resetting the Git repository
- discarta o efeito do commit anterior e volta para o estado anterior
`git reset HEAD index.html`

###  trocar de branch em que você está trabalhando
`git checkout -- index.html`
