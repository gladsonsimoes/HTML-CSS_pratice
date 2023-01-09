~~~css
nav{position: absolute; right: 30px; bottom: 0px;} /* Usaremos, novamente, uma tag como seletor. Nesse caso, será atag <nav> juntamente com a técnica do aninhamento para definiras propriedades dos itens da lista <ul>/<li> e dos links <a>. */
nav ul li{float: left; color: #fff; width: auto; margin: 0.8cm; font-size: 1.5em; font-family : 'verdana'; list-style:none; } /* O float corresponde à flutuação de um elemento. Essa propriedade trabalha muito bem com o position relative e éindispensável para o desenvolvimento sem tabelas - tableless. No caso do nav, usamos o float left nas linhas para forçaros itens <li> de nossa lista <ul> a flutuar para esquerda. Com isso, as opções do nav permanecem em uma mesma linha */
/* Já conhecemos a propriedade margin. Nesse caso, vamos utilizar essa propriedade para separar um item do outro */
/* Também aumentamos a letra do menu por meio dapropriedade font-size, com a unidade de medida em. Dessemodo, a font (letra) irá se adequar ao tamanho da tela. */
nav ul li a {text-decoration: none;color: #bbb; }
nav ul li a:hover{color:#b13030} /* Outro ponto importante é que utilizamos o :hover para atribuir uma cor diferente quando o usuário passar o mouse sobre o menu */
~~~

