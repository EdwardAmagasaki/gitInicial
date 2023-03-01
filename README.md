
# Git e Github - Controle de Versão de Software
Wiki: GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git.

Linguagem de marcação para os arquivos readme.md do Github:
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

Após criação do repositório ainda vazio:

* Trocar o endereçorepositório, pelo endereço correto do novo repositório.

Ex:
echo "# endereçorepositório" >> README.md

git init
git add README.md
git commit -m "primeiro commit"
git branch -M main
git remote add origin endereçorepositório.git
git push -u origin main

…push an existing repository
git remote add origin endereçorepositório.git
git branch -M main
git push -u origin main

…import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

+++
Clona o repositório remoto
git clone endereçorepositório.git

Mostrar o Status
git status

Linha do tempo
git reset --hard CÓDIGOAQUI ( git reflog mostra os códigos )


+++ Dicas para desenvolvimento git nos arquivos:

maisDicas.md
github-desktop-3-1-2.exe
github-git-cheat-sheet.pdf
leiame.md
samcollett_git.pdf