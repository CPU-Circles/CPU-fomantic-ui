Fomantic UI 사용 기본
==========================
  
1. HTML의 기초틀을 먼저 만듭니다.
==============================
  
```html
<html>
  <head>
      <meta charset="utf-8" />
      <title>제목</title>
  </head>
  <body>
      <h1>Hello, World!</h1>
  </body>
</html>
```
2. Fomantic-UI의 Cdn 을 불러옵니다.
===================================
  
Cdn은 https://fomantic-ui.com/introduction/getting-started.html#using-a-cdn-provider 에 있습니다.
3. Fomantic-UI의 cdn을 head에 적용합니다.
==========================================
  
```html
<html>
  <head>
    <meta charset="utf-8" />
    <title>test</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>   
    <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/fomantic-ui/2.8.5/semantic.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/fomantic-ui/2.8.5/semantic.min.js"></script>
  </head>
  <body>
    <h1>Hello, World!</h1>
  </body>
</html>
```
4. Fomantic-UI의 템플릿중 하나를 불러와봅시다.
=============================================
  
저는 기본 버튼을 불러오겠습니다.  
https://fomantic-ui.com/elements/button.html#button 의 버튼을 이용해봅시다.  
  
Button 옆에 <> 가 보이실텐데요  
클릭할시 코드가 출력됩니다.  
해당 코드를 소스에 적용해봅시다.  
  
```html
<html>
  <head>
    <meta charset="utf-8" />
    <title>test</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/fomantic-ui/2.8.5/semantic.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/fomantic-ui/2.8.5/semantic.min.js"></script>
  </head>
  <body>
    <button class="ui button">Follow</button>
  </body>
</html>
```
