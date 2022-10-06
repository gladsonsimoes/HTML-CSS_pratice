<div align="center">
     <h1> <p> Tags de HTML <p> </h1>
       <h4>  este documento tem o intuito de lembrar o porque das tags </h4>
	 <h3> lembrando: algumas tag <b> abrem <> </b> e precisam de <b> fechamento < / > </b> </h3> 
<hr>
       <p> 
		 <h2> acesso rápido </h2>     
	  <h3>  
	     <a href="#NivelDeInicio"> nível de inicio </a> -
	      <a href="#alinhartexto"> Alinhar Texto </a> -
		  <a  href="#imagens"> Imagem </a>	  
	    </h3>
      </p> 
</div>
<hr>		 


<a name="NivelDeInicio">

<br>
<div align="center">
	<h2> Nível de Inicio </h3>	
</div>
		 
Sintaxe de Comentários 
~~~html
<!-- -->
~~~
	
### Tags Iniciais:
	
~~~html
<!DOCTYPE html> <!-- identificar o tipo de arquivo html , verificar a versão do html-->
   
<html> </html> <!-- abrir e fechar um documento html -->

<head> </head> <!-- Abrir e fechar cabeçalho  -->

<title></title> <!-- titulo para o cabeçalho -->

<body></body> <!-- area do corpo (conteudo) -->
~~~

A forma correta de implementar para iniciar não são dessas formas então <a href="https://github.com/gladsonsimoes/Tags-HTML/blob/main/modelobasico.html"> veja o modelo inicial </a>	
</a>


## Paragrafo 
~~~html
<p></p>
~~~

## Pular uma linha

~~~html
</br>
~~~	


## Negrito
~~~htm 
<b>
~~~
##  Italico 
~~~htm 
<i>
~~~

## Underline (texto marcado) 
~~~htm 
<u>
~~~

## Como Criar um HyperLink
~~~htm
<a href=""><button>Button para direcionar o link</button></a>

<!-- 
 O <a href""></a> serve para colocar o link ,
 <button></button> é para direcionar o link do a href 
-->
~~~
	
<a name="alinhartexto">

## alinhamento de texto:

Usando o Align:

Alinhamento de paragrafo:
	
<b> alinhar o texto para esquerda </b>
~~~html
<p align="left"></p> <!-- texto para esquerda (por padrão o texto fica na esquerda) -->
~~~	
<b> alinhar o texto para o centro </b>	
~~~html	
<p align="center"></p> <!-- centralizar texto -->
~~~~	
<b> alinhar o texto para a direita </b>		
~~~html
<p align="right"></p> <!-- texto direita -->
~~~	
<b> texto justificado </b>	
~~~html
<p align="justify"></p> <!-- texto justificado -->	
~~~~

Sem align no HTML:
	
~~~html
<left></left> <!-- texto para a esquerda -->

<right></right> <!-- texto para a direita -->

<center><center/> <!-- texto centralizado -->

<justify></justify> <!-- texto justificado -->
~~~
	
</a>
	
## altura e largura (height - width)

aumentar a largura:
~~~html

width="50%"

width="50px"
~~~
aumentou a altura:
~~~html

height="50%"

height="50px"

~~~


## Fonte (mais comuns):
~~~htm
<FONT FACE=""> </FONT>

<FONT FACE="Arial"> </FONT>
<FONT FACE="Calibri"> </FONT>
<FONT FACE="Comics Sans MS"> </FONT>
<FONT FACE="Verdana"> </FONT>
~~~

## Tamanho da Fonte 1 ao 7
~~~htm
<FONT SIZE="1"> texto de tamanho 1 <FONT>
~~~

## Cor da Fonte 
~~~htm
<FONT COLOR="blue"> texto de cor azul <FONT>
<FONT COLOR="#00000"><FONT>
~~~

## linha horizontal (horizontal ruling)
~~~htm
<hr>
~~~

## Subtitulo (heading) 1 ao 6
~~~htm
<h1>
~~~

## Pré-formatado (Preformatted) 
### para deixar o usuario visualizar a pagina web com os espaços e linhas em branco que você definiu no HTML:
~~~htm
<PRE></PRE>
~~~

## Listas Ordenada/Númerica

~~~html
<ol></ol> <!-- abrir e fechar a lista ordenada -->
<li></li> <!-- abrir e fechar cada item da lista  -->
~~~
## Lista Não Ordenada
~~~html
<ul></ul> <!--abrir e fechar a lista não ordenada --> 
<li></li> <!-- abrir e fechar cada item da lista  --> 
~~~
## Lista Intercalada
também é possível criar combinações de listas em uma página web. Essa combinação é chamada de lista intercalada, exemplo:
~~~htm
<OL>
	<LI>Orange
		<UL>
			<LI>Tela sensível ao toque de 13" </LI>
			<LI>3 entradas USB </LI>
		</UL>	
	<LI>Lemon
		<UL>
			<LI>Tela sensível ao toque de 15" </LI>
			<LI>2 entradas USB </LI>
		</UL>
	</OL>
~~~
## Personalizar Listas
O atributo TYPE pode especificar o tipo de marcador em uma lista não ordenada, ou tipo de número em uma lista ordenada.

Estilo do número
~~~html
<OL TYPE="estilo do número"></Ol>
<OL TYPE="A"></Ol> <!-- para exibir letras maiúsculas -->
<OL TYPE="a"></Ol> <!-- para exibir letras minúsculas -->
<OL TYPE="I"></Ol> <!-- Para exibir números romanos grandes -->
<OL TYPE="i"></Ol> <!-- Para exibir números romanos pequenos -->
~~~
Estilo do Marcador
~~~html
<UL TYPE="estilo do marcador"></UL>
<UL TYPE="DISC"></UL> <!-- para exibir um simbolo de um circulo escuro -->
<UL TYPE="CIRCLE"></UL> <!-- para exibir um circulo branco -->
<UL TYPE="SQUARE"></UL> <!-- para exibir um simbolo de um quadrado escuro-->
~~~

<a name="imagens">
	
## Adicionar Imagens

~~~html 
<img>
~~~
para colocar a imagem devemos usar o atributo SRC (source) para procurar a imagem , você colocará o nome da imagem e o formato. exemplo:
~~~html
<img SRC="logo.png">
~~~
<b>importante saber:</b> a imagem que será inserida no HTML, tem que está na mesma pasta do html que irá inserir a imagem , e também digitar o nome e o formato da imagem.

## Alinhar Imagens

Usando o Align:

~~~html
align="left" <!-- alinhar para esquerda (por padrão o texto fica na esquerda) -->
align="center" <!-- centralizar imagem -->
align="right" <!-- alinhar para direita -->

align="top" <!-- deixar o texto no topo da imagem -->
align="middle" <!-- deixar o texto no meio da imagem -->
align="bottom" <!-- deixar o texto em baixo da imagem (por padrão do html já fica neste formato) -->
~~~

## Comando ALT
caso o navegador não consiga exibir a imagem, o atributo ALT permite vincular um texto explicativo a ela

Este atibuto é considerado de acessibilidade, já que é importantíssimo para deficientes visuais, uma vez que os programas desenvolvidos para eles leem as imagens.

Quando o usuário coloca o mouse sobre a imagem, o texto alternativo também é exibido, como você pode observar na imagem!

[Screenshot_17](https://user-images.githubusercontent.com/99969693/192383951-43159a01-f493-4290-af00-5735562d0c93.png)
~~~html
<img ALT="Texto explicativo">
~~~
	
</a>
<hr>		
		
## criar links no hipertexto

### tag anchor 
~~~html
<a>
~~~
a tag ANCHOR <a></a> (âncora) é utilizada para criar links no hypertexto. a sintaxe desta tag é exibida abaixo:
~~~html
<a href="URL"></a> 
~~~
href é um atributo usado para especificar a URL do documento linkado ou interligado

URL é o endereço da página ou documento a ser linkado (ou seja o link)

### texto com link
~~~html
<a href="URL"> texto para direcionar o link </a>
~~~
para deixar um texto como um link , na parte acima tem escrito <b> texto para direcionar o link </b> é neste campo que você irá escrever o 
texto. E assim direcionando a link que está no href

### direncionar o email
~~~html
<a href="mailto:emailexemple@exemple.com"> texto para direcionar o link para o email escrito </a>	
~~~
### criar links de seção
~~~html
	<a href="#nomedasecao"> texto explicativo ou nome da Seção </a> <!-- para direcionar a seção-->
	<a name="nomedasecao"></a> <!-- para criar uma seção -->
~~~
exemplo:
~~~html
	<HTML>
     <HEAD>
     <TITLE>Link para seção</TITLE>
     </HEAD>
<BODY>
     <P><FONT FACE="Calibri" SIZE="3">Inserindo <I>links</I> criando seções.</P>
     <P> Neste exemplo você verá que, quando o texto for muito grande, você poderá criar <I>links</I> que levem o usuário diretamente ao ponto desejado.</P>
     <A href = "#Capítulo I">O que é HTML?</A><BR>
     <A href = "#Capítulo II">Principais comandos</A>
     <BR>
     <BR>
     <A name = "Capítulo I">
     <H2>O que é HTML?</H2>
     <P>HTML é uma das linguagens de marcação mais conhecidas e utiliza um formato simples de código, que pode ser gerado sem a ajuda de aplicativos especiais.</P>
     <P>Para criar um documento HTML, tudo o que você precisa é de um editor de texto ASCII como o NotePad (Bloco de Notas), por exemplo. Se você precisar verificar a formatação do documento durante a criação, pode usar qualquer navegador, pois todos eles são capazes de interpretar o código.</P>
     </A>
     <A name = "Capítulo II">
     <H3>Principais comandos</H3>
     <P>Os comandos são inseridos no código entre os sinais de menor que "<" e maior que ">" e são chamados de <I>tags</I>.</P>
     </A>
     </FONT>
</BODY>
</HTML>
~~~	
	     
### imagem com link
~~~html
<a href=""><img src=""></a>	     
~~~	     
### cor do link
~~~html
<body link="cor" vlink="#cor" alink="cor">
~~~
LINK = especifica a cor do link não acessado
VLINK = após o link ser acessado especifica a cor do link 
ALINK = especifica a cor que o link deverá apresentar quando o mouse estiver sobre ele.
	     
### Seleção de item:
exemplo:
~~~html
<select>
    <option>Serra</option>
    <option>Vitória</option>
    <option>Cariacica</option>
    <option>Vila Velha</option>
</select>
~~~

## criar uma tabela
comando para criar uma tabela:	
~~~html
<table>
~~~
comando para criar linha:
~~~html
<tr>	
~~~
comando para criar células:
~~~html
<td>	
~~~	

## borda de tabela
~~~html
<table border="n de pixels">
~~~
colorir borda:
~~~html
<table bordercolor="cor">
~~~
cor de fundo:
~~~html
<table bgcolor="cor">
~~~
para colorir uma parte da tabela é só usar bgcolor no tr ou no td 
	
## colocar imagem de fundo numa tabela	
~~~html
<table background="imagem.png">
~~~	
	
![image](https://user-images.githubusercontent.com/99969693/193047878-262dc33e-6a36-4153-a78f-1317275623b0.png)
![image](https://user-images.githubusercontent.com/99969693/193048536-a75cc1da-b975-49f3-afa8-54398f323ce3.png)
		
----
# Tags que não necessitam de fechamento:
## Quebra de linha no mesmo paragrafo (break)
~~~html
</br>
~~~
	
## definir o caractere brasileiro	
~~~html
<meta charset="utf-8" />
~~~
	
## para digitar	
~~~html
<input type="text" /> <!-- escrever um texto -->
<input type="number" /> <!-- definir um número -->
<input type="password" /> <!-- escrever senha -->
<input type="button" />	 <!-- colocar botão -->
<input type="radio"/> <!-- caixa de seleção redonda -->
<input type="radio" name="selectone"/> <!-- o atributo name é para deixar a mesma seleção do mesmo atributo , (não deixar multipla escolha do mesmo name) -->
<input type="checkbox"/> <!-- -->
<input type="submit"/> <!-- -->
~~~

