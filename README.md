# Curso de Git CI&T

![Murilo](https://i.imgur.com/XLn2CAt.png)



![Murilo](https://i.imgur.com/lvDLMoH.png)

git diff (mostra a alteração)


git ckeckout <nome do arquivo> (volta o estado atual da banch)
  
  
git reset --hard  (apaga tudo que está no status ou exclui o arquivo)

### Listar Commit

git log --pretty=oneline (Você controla completamente o que o log mostra. Eu gosto do formato de linha única)

git log

### Git Log 

git log --pretty=oneline --max-count=2

git log --pretty=oneline --since='5 minutes ago'

git log --pretty=oneline --until='5 minutes ago'

git log --pretty=oneline --author=<your name>
  
git log --pretty=oneline --all

git log --all --pretty=format:"%h %cd %s (%an)" --since='7 days ago' ( Apenas as modificações que eu fiz ) 

git log --pretty=format:"%h %ad | %s%d [%an]" --graph --date=short ( Apenas as modificações que eu fiz [formato adequado])

### Criar Branch 

git branch 


git branch feature/jira-333 (criação da branch)

### Git Checkout

Git checkut master


git checkout -b feature/jira-333


git  checkout index.html

### Git Stash

Salvar o estado da Branch e voltar para o estado inicial

git stash


git stash list


git stash pop


git stash apply

### Git  rebase -i

Deixar sua Branch direrente com o da master, manter organizado

git rebase -i origin/develop


git rebase -i origin/master


git rebase -1 HEAD~3 (AGRUPANDO COMMIT)

### git tag

marcar commit especifico, para poder voltar a uma tag especifica.

git tag v1.0.0 origin/master


git push --tags

### git fetch 

Faz downloads de todas a Branch cridas para saber as alterações

git fetch origin
git fetch --all (ver as breach novas )

### Git Pull

Vai atualizar sua Branch e vai enserir na sua master 

git pull
git fetch + git merge

### Git Push
Envia seus commit e objetos de uma branch 

git psuh origin master

## git diff   

mostram as alterações que foram feitas

git diff 

### 

