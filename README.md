<h1> Desafio: Aprenda na Pr�tica Programa��o Orientada a Objetos</h1>

<p align="center"> Objetos
📜 <a href="https://academiapme-my.sharepoint.com/:p:/g/personal/camila_cavalcante_dio_me/EaXyYOjBaFpZjkxhexMo5EcBKMEEAI5t5aHlsTjnBQJlUw?e=nxdB6C"> SLIDES APRESENTADO NO PROJETO </a> Objetos
Objetos
📜 </P>
<p> Sejam bem-vindos ao desafio: <strong>APRENDENDO NA PR�TICA O PARADIGMA DE ORIENTA��O A OBJETOS.</strong><br>Desafio este que tive a honra de co-criar com a plataforma de cursos online <strong><a href="https://web.digitalinnovation.one/">DIGITAL INNOVATION ONE</a></strong>  e disponibilizado de forma gratuita para a comunidade dos desenvolvedores Java.<br>
    ? O objetivo principal � colocar em pr�tica umas das principais ferramentas da OO: <strong>ABSTRA��O, ENCAPSULAMENTO, HERAN�A E POLIMORFISMO,</strong> atrav�s de um projeto Java. </p>



<h2>? Pr�-Requisitos</h2>

<p>
? Conhecer a sintaxe da Java<br>
? Java JDK 11<br>
? IDE para desenvolvimento Java (usarei IntelliJ)<br>
? Git<br>
? Conta no GitHub.<br>
</p>


<h2> ? Passo-a-Passo</h2>

<p>
<strong>	1.</strong> Vamos ABSTRAIR o DOM�NIO Bootcamp e MODELAR seus ATRIBUTOS E M�TODOS <br>
<strong>	2.</strong> Criaremos as CLASSES: Bootcamp, Cursos, Mentorias e Devs e vamos relaciona-las <br>
<strong>	3.</strong> As CLASSES Curso, Mentoria e Devs tamb�m ser�o MODELADOS, ou seja, criaremos seus ATRIBUTOS E M�TODOS <br> 
<strong>	4.</strong> Para que o c�digo fique mais leg�vel e de f�cil manuten��o, iremos utilizar de algumas das ferramentas que o PARADIGMA DE ORIENTA��O A OBJETOS (POO) nos oferece: ABSTRA��O, ENCAPSULAMENTO, HERAN�A E POLIMORFISMO <br>
<strong>	5.</strong> E para representar CLASSES que foram criadas e relacionadas, iremos transforma-las em OBJETOS<br>
</p>

----

<h2> ? Paradigma de Programa��o Orientado a Objetos (POO) </h2>

<p>
A vis�o de Orienta��o a Objetos (OO) � aquela de um mundo de objetos que interagem.<br>
Este paradigma � um modelo de an�lise, projeto e programa��o baseado na aproxima��o entre o mundo real e o mundo virtual, atrav�s da cria��o e intera��o entre classes, atributos, m�todos, objetos, entre outros.<br>
S�o 4 os pilares principais do POO: ABSTRA��O, ENCAPSULAMENTO, HERAN�A E POLIMORFISMO. 
</p>


<h3>? ABSTRA��O:</h3>

<p>
Habilidade de concentrar-se nos aspectos essenciais de um dom�nio, ignorando caracter�sticas menos importantes ou acidentais. Nesse contexto, objetos s�o abstra��es de entidades existentes no dom�nio em quest�o.</p>

<h3>? ENCAPSULAMENTO:</h3>

<p> Encapsular significa esconder a implementa��o dos objetos. O encapsulamento favorece principalmente dois aspectos de um sistema: a manuten��o e a evolu��o.</p>

<h3>? HERAN�A:</h3>

<p>Permite que voc� defina uma classe filha que reutiliza (herda), estende ou modifica o comportamento de uma classe pai. A classe cujos membros s�o herdados � chamada de classe base. A classe que herda os membros da classe base � chamada de classe derivada.</p>

<h3>? POLIMORFISMO:</h3>

<p>Capacidade de um objeto poder ser referenciado de v�rias formas. Cuidado, polimorfismo n�o quer dizer que o objeto fica se transformando, muito pelo contr�rio, um objeto nasce de um tipo e morre daquele tipo, o que pode mudar � a maneira como nos referimos a ele. A capacidade de tratar objetos criados a partir das classes espec�ficas como objetos de uma classe gen�rica � chamada de polimorfismo.</p>
<br>
<h2 align="center"> ?? CONCEITOS FUNDAMENTAIS POO ?? </h2>
<p>
<h3>? DOM�NIO:</h3> 
Dom�nio da aplica��o, tamb�m conhecida como camada de neg�cio ou de objetos de neg�cio, � aquela onde est�o localizadas as classes que fazem parte do dom�nio do problema, ou seja, classes correspondentes a objetos que fazem parte da descri��o do problema.

<h3>? CLASSE: </h3> 
Um elemento do c�digo que tem a fun��o de representar objetos do mundo real. Dentro dela � comum declararmos atributos e m�todos, que representam, respectivamente, as caracter�sticas e comportamentos desse objeto.

<h3>? ATRIBUTO: </h3>
Atributos s�o, basicamente, a estrutura de dados que vai representar a classe. Os atributos tamb�m s�o conhecidos como VARI�VEL DE CLASSE, e podem ser divididos em dois tipos b�sicos: atributos de inst�ncia e de classe. 

<h3>? VARI�VEL: </h3>
Uma ?regi�o de mem�ria (do computador) previamente identificada cuja finalidade � armazenar os dados ou informa��es de um programa por um determinado espa�o de tempo?.

<h3>? M�TODO: </h3>
Os m�todos representam os estados e a��es dos objetos e classes.

<h3>? OBJETO: </h3>
Em POO, objeto � um "molde" de uma determinada classe, que passa a existir a partir de uma inst�ncia da classe. A classe define o comportamento do objeto, usando atributos (propriedades) e m�todos (a��es).
Objeto em ci�ncia da computa��o, � uma refer�ncia a um local da mem�ria que possui um valor. Um objeto pode ser uma vari�vel, fun��o, ou estrutura de dados. 

<h3>? INST�NCIA: </h3>
Uma inst�ncia de uma classe � um novo objeto criado dessa classe, com o operador new. Instanciar uma classe � criar um novo objeto do mesmo tipo dessa classe. Uma classe somente poder� ser utilizada ap�s ser instanciada.

</p>
    
------------
<br>

<h2> ? Linguagem de Programa��o vs Paradigma de Linguagem de Programa��o</h2>

<p>
<h3> ? LINGUAGEM DE PROGRAMA��O:</h3> 
� uma linguagem formal que, atrav�s de uma s�rie de instru��es, permite que um programador escreva um conjunto de ordens, a��es consecutivas, dados e algoritmos para criar programas que controlam o comportamento f�sico e l�gico de uma m�quina.<br>
Seguem alguns exemplos de como as linguagens de programa��o podem ser classificadas:<br>
<br>
? N�vel de abstra��o:<br>
Baixo N�vel: Assembly<br>
M�dio N�vel: C, C++, D, Objective C, etc.<br>
Alto N�vel: Java, C#, PHP, Javascript, etc.<br>
Alt�ssimo N�vel: Python, Ruby, Elixir, etc.<br>
<br>
? Paradigma de programa��o:<br>
Programa��o Estruturada: C, Pascal, Ada, etc.<br>
Programa��o Orientada a Objetos: Java, C#, C++, Objective C, D, etc.<br>
Programa��o Funcional: Lisp, Scheme, Erlang, Elixir, etc.<br>
<br>
? Linguagens classificadas pela arquitetura da aplica��o:<br>
Desktop: C, C++, Object Pascal, Java, etc.<br>
Web: PHP, Ruby, Javascript, Java, etc.<br>
<br>
? Tipo de execu��o:<br>
Linguagens compiladas: C, C++, Pascal, D, GO, etc.<br>
Linguagens Interpretadas: Python, Ruby, PHP, Javascript, etc.<br>
Linguagens Hibridas: Java, Erlang, Elixir, etc.<br>


<h3> ? PARADIGMA DE LINGUAGEM DE PROGRAMA��O</h3> 

� um conjunto de caracter�sticas que podem ser utilizados para categorizar determinado grupo de linguagens. Um paradigma pode oferecer t�cnicas apropriadas para uma aplica��o espec�fica.<br>
<br>
<strong>PARADIGMAS PRINCIPAIS e SEUS SUBPARADIGMAS</strong><br>

? <strong>1. Paradigma Imperativo</strong><br>
Neste paradigma, o programa descreve o processamento necess�rio para solucionar o problema. Assim, o paradigma imperativo � caracterizado por execu��o sequencial de instru��es, pelo uso de vari�veis que representam posi��es de mem�ria e pelo uso de instru��es de atribui��o que alteram os valores dessas vari�veis.<br>
Vejamos alguns Subparadigmas do Paradigma Imperativo e exemplos linguagens de programa��o que adotam esses subparadigmas.<br>
<br>
?  1.1 Paradigma estruturado:  ALGOL 58 e ALGOL 60 <br>
?  1.2 Paradigma concorrente: Java e Ada<br>
?  1.3 Paradigma Orientado a Objetos: Smalltalk e Java<br>
<br>
? <strong>2. Paradigma Declarativo</strong><br>
Este paradigma � o modelo no qual os resultados s�o descritos, mas os passos para chegar aos resultados n�o s�o estabelecidos.<br>
Vejamos alguns Subparadigmas do Paradigma Declarativo e exemplos linguagens de programa��o que adotam esses subparadigmas:<br>
<br>
? 2.1 Paradigma Funcional: Lisp e Haskell<br>
? 2.2 Paradigma L�gico: Prolog<br>
</p>

<h2> ? Contribuindo </h2>

<p>
Este reposit�rio foi criado para fins de estudo, ent�o contribua com ele.<br>
Se te ajudei de alguma forma, ficarei feliz em saber. E caso voc� conhe�a algu�m que se identidique com o conte�do, n�o deixe de compatilhar.<br>
<br>
Se poss�vel:<br>
??  Star o projeto<br>
? Encontrar e relatar issues<br>
</p>



------------

Disponibilizado com ? por [cami-la](https://www.linkedin.com/in/cami-la/ "cami-la").
Muito Obrigado Tutora Camila e DIO!