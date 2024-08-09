# exercicio01

a) echo 01 > arquivo.txt

b) git add arquivo.txt
git status

c) git commit -m "git add example - arquivo.txt"

d) echo 02 > arquivo.txt

e) git diff arquivo.txt

f) git add arquivo.txt
git status

g) git diff --staged arquivo.txt

h) echo 03 > arquivo.txt

i) git diff arquivo.txt

j) git restore --staged arquivo.txt
git status

k) git commit -m "Atualização do conteúdo para 02"
git log --oneline

l) echo "*.txt" > .gitignore
git add .gitignore
git commit -m "Adicionar .gitignore para ignorar arquivos .txt"

m) echo "conteúdo qualquer" > novo.txt
git status