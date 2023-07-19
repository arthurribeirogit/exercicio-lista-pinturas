Esse projeto é para mostra uma lista de obras de famosos pintores

Foi projetado para praticar o uso do flexbox de forma responsiva, tanto desktop quanto mobile

Linguagens utilizadas:

* HTML
* CSS

Não tive tanta dificuldade para realiza-lo, porem alguns pontos são importantes destacar para estudo.
1- O uso do position relative de uma div para e o uso do position absolute para que um elemento esteja acima da camada do relative (usado para escrever o nome da obra e artista)

Para o resposivo tive a dificuldade de entender o porquê de estar dando uma margem entre as imagens sendo que ao colocar margin:0 ele também não tirava essa margem...

Ao consultar um monitor ele disse que o tamanho da altura e largura da imagem que influenciava... então para isso foi nescessário utilizar u height: 100% e um width: auto; para que ele se adequasse e tirasse essa margem, pois do jeito que estava ele estava apenas mantendo as dimensões para não causar um distorce na imagem.