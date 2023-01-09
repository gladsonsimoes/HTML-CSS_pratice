para usar o css temos que definir ele no html e tres forma veja:

### Inline – diretamente no HTML
~~~html
<p style="color: red; font-size: 30px"> Texto aqui </p>
~~~

### Incorporado – por meio da tag style, no topo da página, dentro da tag head
~~~html
<style></style>
~~~

### Linkado ou externo – por meio da tag <link>, de modo a vincular o HTML a uma folha de estilos externa. 

~~~html
<link rel="stylesheet" type="text/css" href="estilo.css"> 
~~~

exemplo:

~~~~html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Titulo do Site</title>
    
     <!--  CSS link -->
    <link rel="stylesheet" type="text/css" href="css/normalize.css">
    <!-- CSS Incorporado -->
    <style>
        h1 {
        color: black;
        }
    </style>
    
</head>
<body>
    <h1>Subtitulo</h1>
    <!-- CSS inline -->
    <p style="color: red; font-size: 30px"> Texto aqui </p>
</body>
</html>
