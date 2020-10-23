# Emmet exercises  
Repositório para guardar atividades sobre a sintaxe do plugin emmet. Não encontrei muito material para praticar, então espero colaborar com o aprendizado de outras pessoas através desse compilado de exercícios.

01) Qual a sintaxe emmet para criar elementos filhos? Dê um exemplo.

02) Qual a sintaxe emmet para criar elementos primos, ou seja, equivalentes em grau na hierarquia? Dê um exemplo.

03) Qual a função da sintaxe ^? Dê um exemplo utilizando-a.

04) Cite qual a sintaxe emmet para criar blocos / grupos. Exemplifique.

05) Escreva a expressão que corresponda a estrutura HTML abaixo:
```html
<div>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
</div>
```
06) Escreva a expressão que corresponda a estrutura HTML abaixo:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>

</body>
</html>
```
07) Escreva a expressão abreviada que produza o elemento a seguir:
```html
<input type="radio" name="" id=""/>
```
08) Escreva a expressão abreviada que produza o elemento a seguir: 
```html
<button type="reset"></button>
```
09) Escreva a expressão abreviada que produza o elemento a seguir:
```html
<input type="email" name="" id=""/>
```
10) Escreva a expressão abreviada que produza o seguinte elemento: 
```html
<select name="" id="">
    <option value=""></option>
</select>
```
11) Explique usando palavras e não código qual seria o resultado da expressão a seguir:
```html
table>tr*3>td*5
```
12) Escreva a estrutura HTML gerada pela expressão abaixo:
```html
p>div{inner}*2
```
13) Escreva a expressão que corresponda a estrutura HTML abaixo:
```html
<div id="hello">Hi everybody!
  <span>lol</span>
  <span>lol</span>
  <span>lol</span>
</div>
```
14) Escreva uma expressão emmet que crie uma lista não ordenada contendo 8 imagens com a classe .pic-[1-8]. A fonte de cada imagem deve ser uma pasta chamada img localizada dentro do diretório principal. Cada imagem foi nomeada como photo-[1-8].

15) Escreva uma expressão emmet que crie uma nav com a classe .menu contendo uma imagem com classe .logo. Além da imagem, inclua uma lista não ordenada com 5 items.
Cada li deve possuir a classe .menu__item[1-5]. Dentro de cada item, inclua um link com a classe .menu__link e o atributo href com valor "#".

16) Escreva uma expressão que corresponda a estrutura HTML a seguir:
```html
<div class="container">
  <h1 class="title">
  <a href="#">Link 1</a>
  <img id="pic" src="./img/photo.png" alt="description">
</div>
```
17) Qual a expressão para criar uma tag <link> com atributo src contendo o valor "favicon"?

18) Escreva a expressão que reproduza a estrutura HTML abaixo:
```html
<div class="box"></div>
<div>
    <p><strong>Hello</strong> <em>world</em></p>
    <blockquote></blockquote>
</div>
```
19) Escreva a expressão que reproduza o seguinte HTML:
```html
<meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0" />
```
20) Escreva a estrutura HTML que será gerada a partir expressão abaixo:
```html
ul>li.item$@-*5
```
21) Escreva a expressão abreviada que reproduza o seguinte HTML:
```html
<input type="password" name="" id=""/>
```
22) Determine a expressão emmet que corresponda o HTML a seguir:
```html
<h1 class="title1">headline 1</h1>
<h2 class="title2">headline 2</h2>
<h3 class="title3">headline 3</h3>
<h4 class="title4">headline 4</h4>
<h5 class="title5">headline 5</h5>
<h6 class="title6">headline 6</h6>
```
23) Qual a expressão emmet *implícita* para a seguinte estrutura:
```html
<ol>
  <li class="item"></li>
  <li class="item"></li>
  <li class="item"></li>
  <li class="item"></li>
</ol>
```
24) Escreva a expressão emmet que corresponda ao HTML abaixo:
```html
<div id="page">
  <div class="logo"></div>
    <ul id="navigation">
      <li><a href="">Item 1</a></li>
      <li><a href="">Item 2</a></li>
      <li><a href="">Item 3</a></li>
      <li><a href="">Item 4</a></li>
      <li><a href="">Item 5</a></li>
    </ul>
  </div>
</div>
```
25) Defina a expressão emmet para gerar a estrutura HTML a seguir:
```html
<div class="container hero">
  <h1 class="main-title" data-weight="600">Title</h1>
</div>
```
26) Escreva a expressão shorthand da sintaxe emmet para o HTML abaixo:
```html
<button type="reset"></button>
```
27) Qual será o HTML gerado pela seguinte expressão:
```html
div+div>p>span+em^^bq
```
28) Escreva a estrutura HTML produzida pela expressão abaixo:
```html
(div>dl>(dt+dd)*3)+footer>p
```
