<div align="center">
     <h1> <p> Tags de HTML <p> </h1>
       <h4>  este documento tem o intuito de lembrar o porque das tags </h4>
	 <h3> lembrando: algumas tag <b> abrem <> </b> e precisam de <b> fechamento < / > </b> </h3> 
<hr>
       <p> 
		 <h2> acesso rápido </h2>     
	  <h3>  
	     <a href="#NivelDeInicio"> nível de inicio </a> |
	      <a href="#alinhartexto"> Alinhar Texto </a> |
		  <a  href="#imagens"> Imagem (img) </a> |
		  <a href="#Tabela"> Tabelas (tables) </a> |
		  <a href="#Summario"> Summario  </a> |
		  <a href="#criarLink"> Criar um link (a href) </a> |
		  <a href="#formularios"> Formulário (form) </a> 
	    </h3>
      </p> 
</div>
<hr>		 


<a name="NivelDeInicio">

<br>
<div align="center">
	<h2> Nível de Inicio </h2>	
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

## Pular ou quebrar uma linha

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

## altura e largura da imagem (height - width)

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

## Comando ALT
caso o navegador não consiga exibir a imagem, o atributo ALT permite vincular um texto explicativo a ela

Este atibuto é considerado de acessibilidade, já que é importantíssimo para deficientes visuais, uma vez que os programas desenvolvidos para eles leem as imagens.

Quando o usuário coloca o mouse sobre a imagem, o texto alternativo também é exibido, como você pode observar na imagem!

[Screenshot_17](https://user-images.githubusercontent.com/99969693/192383951-43159a01-f493-4290-af00-5735562d0c93.png)
~~~html
<img ALT="Texto explicativo">
~~~

## Imagem de Fundo de uma tabela
~~~htm
<table background="imagem.png">	
~~~	
	
</a>
		
		
		
<hr>		

<a name="criarLink">	
	
## criar link e hipertexto

### tag anchor 
~~~html
<a>
~~~
a tag ANCHOR <a></a> (âncora) é utilizada para criar links no hypertexto. a sintaxe desta tag é exibida abaixo:
~~~html
<a href="URL"></a> <!-- href é um atributo usado para especificar a URL do documento linkado ou interligado -->
~~~

### Atributo target	
#### o atributo target é utilizado como o exemplo abaixo:
~~~html
<a href="" target="_blank"></a>
~~~	
tipos de atributos target:
~~~html
target="_blank" <!-- _blank: abre a página em uma nova janela/aba -->
target="_self" <!--  _self: abre a página na mesma janela; -->
target="_parent" <!-- _parent: abre a página na mesma janela do link -->
target="_top" <!--  _top: cancela todos os demais frames e abre a nova página no mesmo navegador. -->
~~~

Questões de segurança envolvendo o target="_blank"
Eu recomendo fortemente que você sempre adicione rel="noreferrer noopener" ao elemento de âncora sempre que você usar o atributo target (por questões de segurança): <a href="https://www.freecodecamp.org/portuguese/news/como-usar-o-html-para-abrir-um-link-em-uma-nova-aba/#:~:text=%C3%89%20f%C3%A1cil%20usar%20o%20HTML,voc%C3%AA%20quer%20fazer%20a%20liga%C3%A7%C3%A3o" target="_blank" rel="noopener noreferrer"> Veja mais sobre </a>
~~~html
<a href="" target="_blank" rel="noopener noreferrer"></a>	
~~~	
	
### texto com link
~~~html
<a href=""> texto para direcionar o link </a> 
~~~
para deixar um texto como um link , na parte acima tem escrito <b> texto para direcionar o link </b> é neste campo que você irá escrever o 
texto. E assim direcionando a link que está no href

### direncionar o email
~~~html
<a href="mailto:emailexemple@exemple.com"> texto para direcionar o link para o email escrito </a>	
~~~
</a>	
	
<a name="Summario">	
	
### Sumario - criar links de seção
	
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
	     
</a>
	     
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

<a name="Tabela">
<DIV align="center">

# TABELAS

</DIV>
	
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

### atributos da tag TD

#### ALIGN
além de alinhar a tabela em relação à página web, o atributo ALIGN alinha horizontalmente os dados uma célula. Seu valor pode ser especificado como: LEFT , RIGHT E CENTER.
~~~HTML
<td align="alinhamento"></td>	
~~~
	
#### VALIGN 
para alinhar os dados de uma célula verticamente, este atributo é util quando a altura das células foi aumentada os atributos para o valign são:
TOP = alinha os dados com a parte superior da célula
BOTTOM = alinha os dados com a parte inferior
CENTER = alinha os dados centralizado
~~~HTML
<td valign="alinhamento"></td>
~~~
	
#### COLSPAN
O atributo COLSPAN é utilizado para mesclar uma célula em mais de uma coluna. Este atributo é muito utilizado quando a tabela possui um título ou conteúdo que, sem ele, ficaria alinhado apenas na primeira célula. O valor para este atributo deve ser especificado em números.
~~~HTML
<td colspan="número"></td>
~~~

#### ROWSPAN
O atributo ROWSPAN é utilizado para mesclar uma célula em mais de uma coluna. Este atributo é muito utilizado quando a tabela possui dados classificados por tipo, categoria etc. Sem ele, o texto ficaria alinhado apenas na primeira célula.
O valor para este atributo deve ser especificado em números.
~~~HTML
<td rowspan="número"></td>
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
	
## Espaço entre borda da tabela e as células	
~~~html
<table cellspacing="valor">	
~~~	

## Espaço entre os dados e a borda de uma célula 
~~~html
<table cellpadding="valor">
~~~
sempre em pixels!
<hr>
</a>

<br>
<br>

<hr>

<h1 align="center"> avançado </h1>
	
## definir o caractere brasileiro	
~~~html
<meta charset="utf-8" />
~~~


<a name="formularios">

<div align="center">

# Formulário:

</div>

Para que você possa criar um formulário em HTML, utilize a tag FORM.
a sintaxe fica assim:
~~~html
<form atributos>
  (conteúdo do formulário)
</form>  
~~~

### atributos: 

#### ACTION
O primeiro atributo utilizado com a tag <form> é o action.
Ele especifica a URL do script que processará os dados do formulário.
~~~html
<form action="URL"></form>
~~~

[exemplos](https://github.com/gladsonsimoes/HTML-CSS_pratice/blob/main/HTML-help/exemplesFormAction.md/)

#### METHOD
O atributo METHOD especifica a maneira de envio dos dados do formulário para o servidor web, para que sejam processados.

Existem dois métodos que podem ser utilizados: POST e GET

##### Method POST
Se o valor do atributo METHOD for definido como POST, o navegador enviará diretamente o fluxo de dados para o [script CGI](https://github.com/gladsonsimoes/HTML-CSS_pratice/blob/main/HTML-help/scriptCGI.md/) no servidor web. <br>
é mais utilizado, porque permite a transmissão de uma maior quantidade de dados ao servidor web.

~~~html
<form action="" method="post">
~~~

##### Method GET
Por outro lado, se o atributo METHOD for definido como GET, o fluxo de dados será anexado à URL especificada no atributo ACTION  e enviado  ao servidor como uma única URL.

O valor GET é utilizado  para respostas únicas, como uma string de texto.
~~~html
<form action="" method="get">
~~~
Caso você tenha de utilizar um sript, verifique qual o melhor método para que as informações sejam enviadas a ele.
<br>
</a>	

## Objetos do formulário

### Tag INPUT e seus atributos
alguns atributos da tag INPUT

#### TYPE
Especifica o tipo de controle a ser criado. Se nada por especificado, o padão é "text".	
##### exemplos do type:	
	
~~~html
<input type="image" /> <!-- Criar um botão de enviar baseado em uma imagem especifica, cuja URL deve ser fornecida  -->
<input type="button" /> <!-- Cria um botão para ser pressionado. O atributo deve ter o nome do botão. -->
<input type="radio" /> <!-- Cria um botão de escolha única -->
<input type="file" /> <!-- Criar um controle para seleção de arquivo. O valor do atributo deve ser configurado como o nome do arquivo -->
<input type="submit" /> <!-- Criar um botão de enviar -->
<input type="text" /> <!-- Cria um campo de texto de uma linha -->
<input type="checkbox" /> <!-- cria caixa de seleção -->
<input type="reset"/> <!-- Cria um botão dde reset, que limpa todos os campos. -->
<input type="password" /> <!-- Cria um campo de texto sem exibir o que está sendo digitado -->
<input type="hidden"/> <!-- Cria controle oculto --> 

<input type="text" /> <!-- escrever um texto -->
<input type="number" /> <!-- definir um número -->
<input type="password" /> <!-- escrever senha -->
<input type="button" />	 <!-- colocar botão -->
<input type="radio"/> <!-- caixa de seleção redonda -->
<input type="radio" name="selectone"/> <!-- o atributo name é para deixar a mesma seleção do mesmo atributo , (não deixar multipla escolha do mesmo name) -->
<input type="checkbox"/> <!-- -->
<input type="submit"/> <!-- -->
~~~

#### VALUE 
Especifica o valor inicial do controle. É opcional, com exceção de quando o TYPE é "radio" ou "checkbox". Por padrão as caixas de texto ficam vazias, se colocar o atributo value irá preencher o vazio da caixa de texto.


#### NAME
Nomeia cada campo do formulário para que o script possa manipular os dados.

#### MAXLENGHT
Quando o valor de TYPE for "text" ou "password", eles estabelecem o número máximo de caracteres do campo. O valor padão é ilimitado.

#### SRC
Quando o valor de TYPE for "image", este atributo especifica a localização da imagem usada para decorar o botão de enviar.

#### CHECKED
Quando o valor de TYPE for "image", este atributo especifica a localização da imagem usada para decorar o botão de enviar.

#### SIZE 
Especifica o tamanho inicial do controle. A largura é dada em pixels, com exceção de quando o valor for "text" ou "password". Nestes casos, o valor refere-se ao número de caracteres.

#### Exemplo de um campo de texto
~~~html
<input type="text" name="Nome" SIZE="20" maxlenght="50">
~~~
Type : valor que especifica o tipo de entrada como texto. <br>
Name: Nome da variável que armazena os dados <br>
Size: Tamanho do campo, em número de caracteres. <br>
maxlenght: Número máximo de caracteres que podem ser inseridos pelo usuário. <br>


#### Exemplo de botões de escolha única

~~~html
<input 	type="radio" name="variável">
~~~
para exibir uma das opções selecionadas como padrão, usamos o atributo CHECKED na tag <input>

~~~html
<input type="radio" name="variavel" checked>valor
~~~

### Botões de múltipla escolha
	
~~~html	
<input type="checkbox" name="variavel">valor	
~~~
para escolha única usamo o checked igual do botão radio!
	
	
### Inserindo uma área de texto
	
~~~html
	<p>Descrição <textarea name="nome" rows="numero" cols="numero" name="variavel"> </textarea></p>
~~~
Os atributos ROWS que especifica o número de linhas (altura) , e COLS que especifica o número de colunas (largura) da área de texto.	
	
### Botões de enviar e limpar (SUBMIT e RESET)	
	
~~~html
<INPUT TYPE="submit" VALUE="Enviar">
~~~	
Em um formulário, o botão SUBMIT envia ao servidor web a informação digitada pelo usuário para ser processada pelo script CGI correspondente.
	
~~~html
<INPUT TYPE="reset" VALUE="Limpar">
~~~		  
O botão RESET limpa as entradas que foram feitas em um formulário, ou seja, apaga as informações inseridas em todos os campos.

### Inserindo Campo Oculto
	
Por exemplo, no formulário de pedidos on-line, podemos 	






	
