git init  //criar repositório 

git config --global user.name "usuario" // definir nome

git config --global user.email "usuario@usuario"// definir email

git add . //adiciona todos os arquivos

git status //para ver as mudanças

git log // para ver as alterações no repositório

git commit -m "mensagem" // para subir uma commit

git remote add origin 'seu repositorio online' // conectar repositório online

git remote -v // para visualizar repositorio

git push -u origin master //para autenticar o seu usuario no git

git push origin master // para subir commits no repositorio online //
//git push indica que estamos subindo uma commit para o remote, origin indica que estamos falando dos arquivos locais da máquina, e o terceiro campo é o local onde estamos subindo a commit, no caso master

git pull // para a atualizar seus arquivos locais com os arquivos do repositório online

git checkout -b 'nome da branch' // para criar uma branch no repositório// o valor '-b' indica que estamos criando uma branch nova que não existe ainda

git checkout 'nome da branch' // se move entre as branchs

git merge 'nome da branch 1' 'nome da branch 2' // une as branchs

git tag // usado para cria uma tag

git tag -a 1.0 -m "mensagem"

git push origin --tags // para subir as tags no remote
