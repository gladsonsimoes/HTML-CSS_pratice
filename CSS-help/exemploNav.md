~~~css
nav{position: absolute; right: 30px; bottom: 0px;} /* Usaremos, novamente, uma tag como seletor. Nesse caso, será atag <nav> juntamente com a técnica do aninhamento para definiras propriedades dos itens da lista <ul>/<li> e dos links <a>. */
nav ul li{float: left; color: #fff; width: auto; margin: 0.8cm; font-size: 1.5em; font-family : 'verdana'; list-style:none; } /* O float corresponde à flutuação de um elemento. Essa propriedade trabalha muito bem com o position relative e éindispensável para o desenvolvimento sem tabelas - tableless. No caso do nav, usamos o float left nas linhas para forçaros itens <li> de nossa lista <ul> a flutuar para esquerda. Com isso, as opções do nav permanecem em uma mesma linha */
nav ul li a {text-decoration: none;color: #bbb; }
nav ul li a:hover{color:#b13030}
~~~

