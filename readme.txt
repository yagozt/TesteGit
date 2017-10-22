Tutorial git

git config --user.name ""

git config --user.email ""

git init //iniciar git

git add *.txt

git status

git add commit -m ""

git diff - git diff -staged //diferenciar arquivo da staging area do workstation

git log //logs de commit

git log --pretty=oneline

git checkout -- "readme.txt" // remover diferenças da workstation

git rm "" //remover arquivos

git checkout "Ambiente" //mudar para ambiente
git checkout -b "NomeBranch" // criar branch e mudar pra ele.

git merge "NomeBranch"

git branch //listar branchs
-git branch -d "NomeBranch" //deletar Branch

git clone "endereço"

git remote //lista servidor

git push origin master //manda alterações para o servidor

//Sabendo que a outra máquina fez alterações no servidor, tem que pegar as alterações.
git pull origin master //pega as alterações dos servidor e joga no seu branch "master"
//Quando faz isso, automaticamente faz as alterações no seu branch, para evitar isso
git fetch origin "branch"