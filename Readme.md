como fazer um README.md bacanudo para aquele projeto que você tanto se orgulha. Chega de colocar uns textinhos sem jeito.
Falaremos um pouco sobre markdown e focaremos em formatação, imagens, GIFs, links, listas, quotes, tasklists e código, tudo isso no nosso amigão, o README.md.

Ok, é bacana sabermos que o README.md tendo a extensão .md é um arquivo markdown, e o que é isso? Uma linguagem de marcação, assim como HTML e serve basicamente para estilizarmos texto na web. Falando no HTML algumas tags também funcionam, veremos adiante.

Sintaxe com seu equivalente em HTML (caso haja):

Header (equivalente aos <h1><h2><h3>)
![header](https://user-images.githubusercontent.com/101885085/204771167-9e64cefd-a998-40e0-ba00-c035f4102ada.jpg)

Ênfase (equivalente ao negrito <b>, itálico <i> e riscado <strike>)
![enfase](https://user-images.githubusercontent.com/101885085/204771071-ec31a10f-25a8-4271-8a2f-61effda55605.jpg)

Lista Ordenada (equivalente ao <ol>)
![lista ordenada](https://user-images.githubusercontent.com/101885085/204771212-d10cd920-03f3-4851-995c-70509a918a18.jpg)

Lista Não Ordenada (equivalente ao <ul>)
![lista não ordenada](https://user-images.githubusercontent.com/101885085/204771210-7f15a3b7-c259-4b5a-b7df-706610e8e77f.jpg)

Links (equivalente ao <a>)
![links](https://user-images.githubusercontent.com/101885085/204771208-cf96d4f1-d133-4408-b5aa-263f547b195a.jpg)

Quotes (equivalente ao <blockquote>)
![quotes](https://user-images.githubusercontent.com/101885085/204771213-2a99e06e-264e-49ed-b0bd-63764be1e1db.jpg)

Tasklists
![task](https://user-images.githubusercontent.com/101885085/204771219-1024c011-e4ac-4b5f-b7a7-69a265dc49c9.jpg)

Código
![codigo](https://user-images.githubusercontent.com/101885085/204770910-1c7072df-0f4d-4505-85ad-3411ab73218f.jpg)

Tabelas
![tabelas](https://user-images.githubusercontent.com/101885085/204771215-e9860e67-a643-41c0-8b13-7c030752dd1f.jpg)
  
  
  
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
