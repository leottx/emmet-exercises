# Emmet exercises  
Repositório para guardar atividades sobre a sintaxe do plugin emmet. Não encontrei muito material para praticar, então espero colaborar com o aprendizado de outras pessoas através desse compilado de exercícios.

1) Escreva a expressão que corresponda a estrutura HTML abaixo:
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
2) Escreva a expressão que corresponda a estrutura HTML abaixo:
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
3) Explique usando palavras e não código qual seria o resultado da expressão a seguir:
```
table>tr*3>td*5
```
4) Escreva a estrutura HTML gerada pela expressão abaixo:
```
p>div{inner}*2
```
5) Escreva a expressão que corresponda a estrutura HTML abaixo:
```html
<div id="hello">Hi everybody!
  <span>lol</span>
  <span>lol</span>
  <span>lol</span>
</div>
```
6) Escreva uma expressão emmet que crie uma lista não ordenada contendo 8 imagens com a classe .pic-[1-8]. A fonte de cada imagem deve ser uma pasta chamada img localizada dentro do diretório principal. Cada imagem foi nomeada como photo-[1-8].

7) Escreva uma expressão emmet que crie uma nav com a classe .menu contendo uma imagem com classe .logo. Além da imagem, inclua uma lista não ordenada com 5 items.
Cada li deve possuir a classe .menu__item[1-5]. Dentro de cada item, inclua um link com a classe .menu__link e o atributo href com valor "#".

8) Escreva uma expressão que corresponda a estrutura HTML a seguir:
```html
<div class="container">
  <h1 class="title">
  <a href="#">Link 1</a>
  <img id="pic" src="./img/photo.png" alt="description">
</div>
