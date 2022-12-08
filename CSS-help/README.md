<div align="center">
  
  # TAGS CSS
  
  </div>

Comentar no CSS: 
~~~css
/* */
~~~


## Inline – diretamente no HTML
~~~html
<p style="color: red; font-size: 30px"> Texto aqui </p>
~~~

## Incorporado – por meio da tag style, no topo da página, dentro da tag head

~~~html
<style></style>
~~~

## Linkado ou externo – por meio da tag <link>, de modo a vincular o HTML a uma folha de estilos externa. 

tag e atributo do html para relacionar com arquivo de css , coloque a pasta e o arquivo css ("como no exemplo abaixo")

~~~HTML
<link rel="stylesheet" href="css/estilo.css">
~~~
ou desse outro modo:
~~~html
<link rel="stylesheet" type="text/css"  href="estilo.css">
~~~

## Seletores

Os seletores são a declaração que o CSS utiliza para identificar os elementos do HTML. Por meio dos seletores, podemos aplicar a formatação em quase qualquer parte de uma página web.

A estrutura para regras do CSS é:

seletor {propriedade: valor;}

### class:

#### class no html:
~~~html
<p class='nome da classe'>Seu texto </p>
~~~
Também podemos adicionar a mesma class em vários elementos:
~~~html
<p class='primeira da classe'>Primeiro parágrafo</p>
<p class='primeira da classe'>Segundo parágrafo</p>
<p class='primeira da classe'>Terceiro parágrafo</p>
~~~

### class no css:
Na folha de estilo, a propriedade class vem precedida por um ponto (.).

~~~css
.nomedaclasse { 
   propriedade: valor;
}
~~~

Uma coisa muito importante que devemos saber sobre o ID é que ele deve ser único nos elementos


## header

![Captura de Tela (18)](https://user-images.githubusercontent.com/99969693/206040803-dbbf88c6-d451-4d6d-955f-b9b911bdb0ca.png)




<br><br>Links para estudos+

https://backefront.com.br/barra-rolagem-div/
