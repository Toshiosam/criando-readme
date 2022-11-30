como fazer um README.md bacanudo para aquele projeto que você tanto se orgulha. Chega de colocar uns textinhos sem jeito.
Falaremos um pouco sobre markdown e focaremos em formatação, imagens, GIFs, links, listas, quotes, tasklists e código, tudo isso no nosso amigão, o README.md.

Ok, é bacana sabermos que o README.md tendo a extensão .md é um arquivo markdown, e o que é isso? Uma linguagem de marcação, assim como HTML e serve basicamente para estilizarmos texto na web. Falando no HTML algumas tags também funcionam, veremos adiante.

Sintaxe com seu equivalente em HTML (caso haja):

Header (equivalente aos <h1><h2><h3>)

Ênfase (equivalente ao negrito <b>, itálico <i> e riscado <strike>)

Lista Ordenada (equivalente ao <ol>)

Lista Não Ordenada (equivalente ao <ul>)

Links (equivalente ao <a>)

Quotes (equivalente ao <blockquote>)

Tasklists

Código


Tabelas

  
  
  
Em markdown temos que basicamente desenhar a tabela, porém existe um gerador de tabelas que facilita a nossa vida: gerador
Basta copiar o que o gerador criar e colar no README.md.

Em HTML usamos a nossa conhecida <table>:


Imagens e Gifs

Ensinarei duas maneiras, a maneira “espertinha” (e que eu não recomendo tanto) e a maneira mais “correta”. Faça como achar melhor.

Primeiro a maneira “espertinha”. Vamos em New Issue e jogamos a imagem lá, o GitHub hospeda e já converte em um link certinho, basta copiarmos e jogarmos no README.md, se liga só:


E agora uma maneira mais controlada. Tendo a imagem que queremos em um diretório do nosso repositório, basta usar a seguinte sintaxe:

Em markdown: ![](caminho até a imagem)

Em HTML: <img src=”caminho até a imagem”>
Com a tag HTML também podemos usar os atributos height e width para alterar o tamanho :D

Ambas as maneiras funcionam com links externos, vamos a alguns exemplos de sintaxe:


# criando-redme
