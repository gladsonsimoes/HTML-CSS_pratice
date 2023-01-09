<div align="center">
   <h1> TAGS CSS </h1>
<p> caso não saiba como usar o CSS, veja as tres formas de usar <a href="comoAdicionarCSS.md"> clique aqui e veja </a> </p> </div>

### Comentário no CSS: 
~~~css
/* */
~~~

## Seletores

Os seletores são a declaração que o CSS utiliza para identificar os elementos do HTML. Por meio dos seletores, podemos aplicar a formatação em quase qualquer parte de uma página web.

A estrutura para regras do CSS é:

~~~css
seletor {propriedade: valor;}
~~~

<hr>

### Seletor Universal
representa todos os elementos
~~~css
*{margin: 0; padding: 0;}
~~~

### Seletor Class:

#### class no html:

~~~html
<p class='nome da classe'>Seu texto </p> //podemos adicionar a mesma class em vários elementos!
~~~

#### class no css:
Na folha de estilo, a propriedade class vem precedida por um ponto (.).

~~~css
.nomedaclasse { 
   propriedade: valor;
}
~~~

<hr>

### Seletor ID
Uma coisa muito importante que devemos saber sobre o ID é que ele deve ser único em cada elemento , exemplo:

#### id no html:

~~~html
<p id="nome"> Gladson </p>
~~~

#### id no CSS:
~~~css
#nomeDoID {
     propriedade: valor;
}
~~~



## Position 

O CSS possui uma propriedade chamada position

A propriedade position precisa de um ponto inicial para calcular a coordenada e posicionar o elemento na tela.

Além disso, a propriedade position possui três valores possíveis. Clique nos valores para conhecê-los.

| Fixed | Relative | Absolute |
|--- |--- |--- |
| O valor fixed fixa o elemento nas coordenadas que atribuirmos. Mesmo com a rolagem da tela, o elemento permanece FIXO na posição definida.| O ponto inicial para o cálculo de elementos com position definida como relative é o canto superior esquerdo do próprio elemento. | Diferente do relative, o valor absolute tem como ponto inicial o elemento em que ele está inserido – seu pai. |






<hr>
<br><br>Links para estudos+

https://backefront.com.br/barra-rolagem-div/
