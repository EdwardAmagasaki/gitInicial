
# Git e Github - Versionamento do Software

*Wiki:* GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git.

## Requisitos:

1. Conta de acesso cadastrada no Github.

Além de texto poderemos utilizar a linguagem de marcação Markdown para os arquivos, como por exemplo o README.md que abre na visualização do repositório.

## Implementação

Após a criação do repositório ainda vazio:

1. Trocar o endereçorepositório, pelo endereço correto do seu novo repositório.

Ex:
echo "# endereçorepositório" >> README.md

```
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
```

* Código acima apresentado na inicialização do repositório no Github*.

## Alguns Comandos utilizados:

Clona o repositório remoto:
```
git clone endereçorepositório.git
```
Mostrar o Status:
```
git status
```
Linha do tempo:
```
git reset --hard CÓDIGOAQUI ( git reflog mostra os códigos )
```

Para o arquivo README.md , que é um arquivo criado com a linguagem de marcação Markdown:

[Algumas dicas do Github em: ](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Github Markdown Cehat Sheet")

No link do Github acima, você encontrará vários códigos como o que utilizamos para apresentar o link acima.

Logo abaixo, o código que utilizamos:

```
[Algumas dicas do Github em: ](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Github Markdown Cheet Sheet")
```
E para podermos exibir o código acima sem renderizar, utilizamos as marcações com três "```"
O código aqui... "```" crases. 

Na pasta dicas livre se encontram mais resumos de comandos que podem ser úteis.