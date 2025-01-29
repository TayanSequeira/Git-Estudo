# Git Study

Eu estou estudando para aprender a trabalhar com versionamento de código e repositório remotos com GitHub.

Pretendo ir até GitFlow utilizando VScode.

xD

## Fluxo de trabalho git local

01. Git checkout -b <nova-branch>
02. cria ou atualiza arquivos
03. git status
04. git add "arquivos"
05. git status
06. git commit -m "msg"
07. git checkout main
08. git merge nova-branch


## Fluxo de trabalho GitHub <> Local (projeto próprio ou empresa)
01. git clone <endereço do projeto>
02. git checkout
03. alterações de arquivos
04. git status
05. git add "arquivos"
06. git status
07. git commit -m "msg"
08. git push origin <nova-branch>
09. abrir pull request no GitHub para a main
10. Excluir <nova-branch> origin
11. git checkout main
12. git branch -D <nova-branch>


## Fluxo de trabalho GitHub <> Local (projeto open source)
01. Fork do projeto para seu próprio GitHub
02. git clone endereço do projeto>
03. git checkout
04. alterações de arquivos
05. git status
06. git add "arquivos"
07. git status
08. git commit -m "msg"
09. git push origin <nova-branch>
10. abrir pull request no GitHub da branch fork para a main do projeto original
11. Excluir <nova-branch> origin
12. git checkout main
13. git branch -D <nova-branch>