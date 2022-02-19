# Template para artigos LaTeX

Esse projeto é apenas um scaffolding rápido para criar um projeto de documento .tex, já adicionando figuras e biblioteca de citações ao documento. Além desse projeto, você vai precisar instalar uma distribuição LaTeX, eu pessoalmente uso o [TeX Live](https://www.tug.org/texlive/) mas você pode escolher qualquer outra.

Você pode editar utilizando o próprio editor que vem com o TeX Live, mas vou deixar mais uma dica, edição utilizando o editor [Visual Studio Code](https://code.visualstudio.com) e a extensão [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) que adiciona preview, compilação automática ao salvar, autocomplete e syntax highlight.

## Figuras

O diretório padrão de imagens está setado como `/figures`, caso você deseje alterar isso precisa mudar também a referência para ele no documento, logo nas primeiras linhas do `article.tex`

## Biblioteca de citações

Foi utilizado o BibTeX, sendo que o arquivo linkado é o `biblio.bib`, caso queira adicionar outros arquivos também será necessário alterar a referência para eles no final do arquivo `article.tex`. Se quiser entender melhor como o BibTeX funciona pode dar uma olhada [nessa página](https://www.overleaf.com/learn/latex/Bibliography_management_with_bibtex). 