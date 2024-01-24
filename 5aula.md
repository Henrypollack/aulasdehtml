
# DIO | 5ª Aula CSS HTML.

## Estilizando elementos.
#### Padding e Margin
```
.post {
    1# padding: 15px 10px;
    2# padding: 15px 10px 5px 0;
    3# padding-top: 15px;
       padding-right: 10px;
       padding-bottom: 5px;
       padding-letf: 0;
}
```
- No primeiro exemplo de `padding` o valor de `15px` esta se referindo a parte superior e inferior, e o de `10px `ao lados esquerda e dereita.
- No 2º exemplo temos 3 lados com valor e o ultimo e quarto lado sem valor. Começando por cima, direita,baixo,esquerda.
- No 3º exemplo usamos propriedade especifica pra cada lado.
---
#### Background
```
.post {
    background-color: green;
    background-image: url("bg.png");
    background-position: top

}
```
- Podemos personalizar estilar na verdade o elemento mudando a cor, a imagem do fundo o poscionamento da imagem.
- Pra mudar a cor podemos usa tanto o nome em inglez como o valor hexadecimal ou somente usando a palavra `background: cor que voce deseja`.
---
#### Border
```
.post {
    border: 3px solid blue;
    boder-top: 2px dotted green;
    border-right: 4px dashed pink;    
}
```
- Podemos estilizar as bordas tbm mudando a largura usando os pixel a cor da borda ou o estilo dela se e uma borda solidaou pontilhada etc.
Na 1ª linha a borda tem `3px`de largura ela e solida e azul, na 2ª linha temos uma borda que esta direciona pra parte supeiror em pontos na cor verde, e na direita temos a tracejada na cor rosa.
- Temos como estilar cada lado da borda usando os comandos abaixo:
```
.post{
    border-top: 2px dotted green;
    border-right: 4px dashed pink;
    border-bottom: 1px solid purple;
    border-left: 4px dotted cyan;
}
```
- Você também pode usar
```
.post {
    border 3px solid #505050;
}
```
**ou essa opção**

```
.post{
    border-with: 3px;
    border-color: #505050;
    border-style: solid;
}
```     
- Ultima propriedade e o `border-radius `.
```
border-radius: 10px;
border-radius: 50%
border-radius: 10% 20%
border-radius: 10% 20% 15% 22%
```       
- Permite arredondar os cantos de um elemento, colocando apenas um valor alteramos todos os cantos do elemento. Uma *dica* e que se o elemento for quadrado e colocarmos o `border-radius: 50%`ele fica redondo.
---
### Estilizando Textos
```
#title {
    font-family: Verdana;
}
.post_title {
    font-family: Verdana,Arial;
}
```
- O `font-family` faz alterações por fontes que estejam na internet ou instalados na nossa maquina. No primeiro exemplo estamos usando uma fonte somene, no segundo estamos usando duas fontes diferentes por que caso 1 nao funciona a 2 funciona como um backup.
```
#title {
    font-size: 30px;
}
.post_title {
    font-size: 18px;
}
```
- O `font-size` é usado para aumentar ou diminuir a fonte de tamanho, pra isso basta mudar a quantiade de pixels que voce deseja.
```
#title {
    font-style: normal;
}
.subtitle {
    font-style: italic;
}
```
- O `font-style`altera a aparencia do texto pra italico ou pra normal. 
```
#title {
    font-weight: normal;
}
.subtitle {
    font-weight: bold;
}
```
- O `font-weight`altera o peso do texto, podemos usar valores numerico ao invez de `normal`e `bold`.
```
#title {
    text-transform: uppercase;
}
.subtitle {
    text-transform: lowercase;
}
.post_title{
    text-transform: capitalize;
}
```
- O `text-transform`muda o nosso texto para minusculas ou maiusculas como mostra no primeiro e segundo exemplo no terceiro podemos ver que ele deixa todas as primeiras letras da frase maiusculas.

- O `text-decoration`é muito usado pra dar destaque ao texto pois ele adciona linhas.O valor `underline` coloca uma linha abaixo das palavras, o valor `overline` adciona uma linha sobre as palavras e o `line-through` adciona uma linha sobre as palavras.
---
### Estilizando Listas
```
ul {
    list-style-type: square;
}
ol {
    list-style-type: upper-roman;
}
ul {
    list-style-type: "\1F44D";
}
```
- Exitem varios tipos de estilizar listas como o `square` que altera os pontos para quadrados,o `upper-roman`alera para algarismos romanos, o `1F44D` esse codigo altera  para um caractere especial como nesse caso um emoji de like.
```
ul {
    list-style-image: url("rocket.png");
}
```
- Nos podemos adcionar também imagens nos nossos marcadores só colocar a tag `list-style-image`e depois a url da imagem.

##Dica 

- O CSS funciona em cascata, da seguinte maneira.
```
<ul class="contact_list">
<li><a href="mailto:Henrypollack1@gmail.com">Henrypollack1@gmail.com</a></li>
<li><a href="https://dio.me/users/henrypollack1" target="_blank">DIO|Perfil</a></li>
<li><a href="https://github.com/Henrypollack" target="_blank">GitHUB</a></li>
```
- Se quisermos mudar um valor do link ou seja do `<a>` teremos que fazer algo assim no CSS.
```
.contact_list li a {
    color: blue;
}
```
- Colocamos a id da classe em seguida o elemtno `<li>`e depois o `<a>`, fazendo assim em cascata.

