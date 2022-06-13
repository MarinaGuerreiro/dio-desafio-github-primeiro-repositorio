# INTRODUÇÃO AO CSS #

### O que são seletores? ###

- Seletores: a, p, h1, h3 {

  ​			color: blue;

  ​			font-size: 14px;               (Declarações)

  }

## ID X Classe  ##

- < header id="header" class="header">< /header> 
-  < header class="header">< /header>
- CSS uma **CLASSE** é definida por um ponto (.header) e um **ID** é definido por um # (#header)
- **ID** só pode ser usado uma vez na página.



## Box Model ##

- Margin: Espaçamento entre elementos.
- Border: Circundam o padding e o conteúdo (podemos alterar largura e cor)
- Padding: Espaçamento entre a borda e conteúdo.
- Content: O que o bloco representa (imagens, textos, etc.)

## Estilizando elementos ##

### Paddin e Margin ###

- Colocando um valor para a parte superior e inferior

- .post { 

  ​		padding 15px 10px 5px 0;

  } // superior, direito, abaixo, esquerda.

- .post {

  ​        padding-top: 15px;

  ​        padding-right: 10px;

  ​        padding-bottom: 5px;

  ​        padding: left: 0; }

  // Usado quando nós temos um padding ou margin com 3 lados iguais e um só diferente.

- **Background**

  . post {

  background-color: green;

  background-image: url("bn.png");

  background-position: top;

  } 

  //**mozila developer networl MDN para estudar** [MDN](https://developer.mozilla.org/pt-BR/)

- **Border**
  - Largura: pixels, centímetros, milímetros...
  - Cor: blue, #0000fff...
  - Estilo: sólida, pontilhada, tracejada...

- .post{

  border: 3px solid blue;

  border-top: 2px dotted green;

  border-right 4px dashed pink;

  }

- **Border-radius**

​	border-radius: 10px;

​	border-radius: 50%;

​	border-radius: 10% 20%

​	border-radius: 10% 20% 15% 22%;

## Estilizando textos ##

- **Font-family**: Altera a fonte do nosso texto 

​	#title {

​		font-family: Verdana;

}

​	.post_title {

​		font-family: Verdana, Arial;  //caso a primeira fonte não funcione, a segunda entra como um backup

}

- **Font-size** (tamanho da fonte)

​	#title {

​		font-size: 30px;

}

​	.post_title{

​		font-size:18px;

}

- **Font-style** (altera a aparência do texto)

​	#title {

​		font-style: normal;

}

​	.subtitle{

​		font-style: italic;

}

- **Font-weight** (altera o peso do texto)

​	#title {

​		font-weight: normal;

}

​	.subtitle {

​		font-weight: bold;

}

- **Text-transform** (Altera o texto entre maiúsculas e minúsculas)

​	#title {

​		text-trasnform: uppercase; (Tudo maiúscula)

}

​	.subtitle {

​		text-transform: lowercase; (Tudo minúscula)

}

​	.post_title {

​		text-tansform: capitalize; (Primeiras letras de cada palavra em maiúscula)

}

- **Text-decoration** (Dá destaque ao texto colocando linhas) 

  #title{

  ​	text-decoration: underline; (Abaixo do texto)

  }

  .subtitle{

  ​	text-decoration: overline; (Acima do texto)

  }

​	.post_title {

​		text-decoration: line-through; (Corta a palavra)

}

## Estilizando Linhas ##

- **List-style-type**

  ​	ul{

  ​		list-style-type: square;

  }

  ​	ol{

  ​		list-style-type: upper-roman;

  }

  ​	ul{

  ​		list-style-type: "\1f44D";

  }

  ​	ul{

  ​		list-style-image: url("rocket.png");

  }

## Propriedades de dimensão e alinhamento

- Width: Ajustar largura

- Height: Ajustar altura

  

- Max-width: Largura máxima que ele pode ter (deixa o design mais responsivo ao tamanho de tela, pois se ajusta)

- Max-heigth: altura máxima que o elemento pode ter

- Margin: espaçamento entre elementos;

- Text-align: alinhar textos.