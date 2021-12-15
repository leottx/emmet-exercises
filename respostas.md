**1. Qual a sintaxe emmet para criar elementos filhos? Dê um exemplo.**

Resposta:

O aninhamento de elementos é feito pelo operador >

```text
div>p
```

Resultado:

```html
<div>
  <p></p>
</div>
```

**2. Qual a sintaxe emmet para criar elementos primos, ou seja, equivalentes em grau na hierarquia? Dê um exemplo.**

Resposta:

Elementos primos são definidos pelo operador +

```text
a+span
```

Resultado:

```html
<a href=""></a>
<span></span>
```

**3. Qual a função da sintaxe ^? Dê um exemplo utilizando-a.**

Resposta:

O operador ^ eleva o elemento a direita em um grau na hierarquia atual.

```text
div>div>a>span^a
```

Resultado:

```html
<div>
  <div>
    <a href="">
      <span></span>
    </a>
    <a href=""></a>
  </div>
</div>
```

**4. Cite qual a sintaxe emmet para criar blocos / grupos. Exemplifique.**

Resposta:

Blocos/grupos são criados ao envolver um ou mais elementos entre parênteses.

```text
div>ul>(li>a+button)
```

Resultado:

```html
<div>
  <ul>
    <li>
      <a href=""></a>
      <button></button>
    </li>
  </ul>
</div>
```

**5. Escreva a expressão que corresponda a estrutura HTML abaixo:**

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

Resposta:

```text
div>ul>li*6
```

**6. Escreva a expressão que corresponda a estrutura HTML abaixo:**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

Resposta:

```text
!
```

**7. Escreva a expressão abreviada que produza o elemento a seguir:**

```html
<input type="radio" name="" id="" />
```

Resposta:

```text
input:r
```

**8. Escreva a expressão abreviada que produza o elemento a seguir:**

```html
<button type="reset"></button>
```

Resposta:

```text
input:reset
```

**9. Escreva a expressão abreviada que produza o elemento a seguir:**

```html
<input type="email" name="" id="" />
```

Resposta:

```text
input:email
```

**10. Escreva a expressão abreviada que produza o seguinte elemento:**

```html
<select name="" id="">
  <option value=""></option>
</select>
```

Resposta:

```text
select>opt
```

**11. Explique usando palavras e não código qual seria o resultado da expressão a seguir:**

```html
table>tr*3>td*5
```

Resposta:

Será criado uma tabela com 3 linhas e 5 células cada.

**12. Escreva a estrutura HTML gerada pela expressão abaixo:**

```html
p>div{inner}*2
```

Resposta:

```html
<p>
  <div>inner</div>
  <div>inner</div>
</p>
```

**13. Escreva a expressão que corresponda a estrutura HTML abaixo:**

```html
<div id="hello">
  Hi everybody!
  <span>lol</span>
  <span>lol</span>
  <span>lol</span>
</div>
```

Resposta:

```html
#hello{Hi everybody!}>span{lol}*3
```

**14. Escreva uma expressão emmet que crie uma lista não ordenada contendo 8 imagens com a classe .pic-[1-8]. A fonte de cada imagem deve ser uma pasta chamada img localizada dentro do diretório principal. Cada imagem foi nomeada como photo-[1-8]**.

**15. Escreva uma expressão emmet que crie uma nav com a classe .menu contendo uma imagem com classe .logo. Além da imagem, inclua uma lista não ordenada com 5 items. Cada `<li>` deve possuir a classe .menu-item[1-5]. Dentro de cada item, inclua um link com a classe .menu-link e o atributo href com valor "#".**

**16. Escreva uma expressão que corresponda a estrutura HTML a seguir:**

```html
<div class="container">
  <h1 class="title">
  <a href="#">Link 1</a>
  <img id="pic" src="./img/photo.png" alt="description">
</div>
```

**17. Qual a expressão para criar uma tag `<link>` com atributo src contendo o valor "favicon"?**

**18. Escreva a expressão que reproduza a estrutura HTML abaixo:**

```html
<div class="box"></div>
<div>
  <p><strong>Hello</strong> <em>world</em></p>
  <blockquote></blockquote>
</div>
```

**19. Escreva a expressão que reproduza o seguinte HTML:**

```html
<meta
  name="viewport"
  content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0"
/>
```

**20. Escreva a estrutura HTML que será gerada a partir expressão abaixo:**

```html
ul>li.item$@-*5
```

**21. Escreva a expressão abreviada que reproduza o seguinte HTML:**

```html
<input type="password" name="" id="" />
```

**22. Determine a expressão emmet que corresponda o HTML a seguir:**

```html
<h1 class="title1">headline 1</h1>
<h2 class="title2">headline 2</h2>
<h3 class="title3">headline 3</h3>
<h4 class="title4">headline 4</h4>
<h5 class="title5">headline 5</h5>
<h6 class="title6">headline 6</h6>
```

**23. Qual a expressão emmet _implícita_ para a seguinte estrutura:**

```html
<ol>
  <li class="item"></li>
  <li class="item"></li>
  <li class="item"></li>
  <li class="item"></li>
</ol>
```

**24. Escreva a expressão emmet que corresponda ao HTML abaixo:**

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

**25. Defina a expressão emmet para gerar a estrutura HTML a seguir:**

```html
<div class="container hero">
  <h1 class="main-title" data-weight="600">Title</h1>
</div>
```

**26. Escreva a expressão shorthand da sintaxe emmet para o HTML abaixo:**

```html
<button type="reset"></button>
```

**27. Qual será o HTML gerado pela seguinte expressão:**

```html
div+div>p>span+em^^bq
```

**28. Escreva a estrutura HTML produzida pela expressão abaixo:**

```html
(div>dl>(dt+dd)*3)+footer>p
```
