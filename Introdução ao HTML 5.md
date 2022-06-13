# Introdução ao HTML 5

## 	Estrutura básica 

- Elemento HTML  
  - Tag de abertura 
  - Conteudo do elemento
  - Tag de fechamento 

- <!DOCTYPE html>
      <html>
          <head>
              <meta charset="utf-8">
              <title>Marina Guerreiro</title>
          </head>
          <body>
              <header>
                  <h1>
                      Marina Guerreiro
                  </h1>
              </header>
              <section>
                  <h2>
                      Posts
                  </h2>
                  <article>
                  	<h3>
                      Post #1
                      </h3>
                  </article>
              </section>
              <footer></footer>
          </body>
  </html>

## Semântica ##

- < section > = Seção genérica de conteúdo, como uma lista de arquivos;
- < header > = Cabeçalho da página ou parte da página;
- < article > = Conteúdo relevante dentro da sua página;
- < aside > = Conteúdo relacionado ao principal da página, como uma biografia ou links relacionados, geralmente é uma barra lateral;
- < footer > = Rodapé da página, pode ser tanto rodapé de um article quanto de um aside;
- < h1 > - < h6 > = Tamanho de um titulo dentro do site; (Só pode ter um h1 por página)

## Textos e links em HTML ##

- <  h1 > Título da página < / h1>

- < h2 >  Título da seção < / h2 >

- < h3 > Título de artigo </ h3>

- < p > Conteúdo do artigo </ p> (Parágrafo: texto, imagem, vídeo e vários conteúdos)

  

  ### Tags de Links ###

  -  < a > Link < /a>
  - < a href="linkedin.com"> Linkedin </a> (Hiperlink)
  - < a href="mailto:ninaguerreiro1@gmail.com"> E-mail< /a>
  -  < a target="_blank"> Link< /a> (Abre o link em outra página)

### Tag IMG ###

- < img>
- < img src="img/avatar.jpg">
- < img alt="Foto de Nina Guerreiro"> (descrição da imagem quando ela não carrega)
- [Comprimir dados das fotos](https://tinypng.com/)

### Listas ###

- Servem para agrupar coleções de itens
- < ul> ( a ordem dos elementos não importa)
  - Item 1
  - Item2

- < ol> (A ordem dos itens é importante) (Pontos viram números para indicar a ordem dos itens)
  - Item 1
  - Item 3

- < li> item