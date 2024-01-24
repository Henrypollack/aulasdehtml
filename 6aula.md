# DIO | 6ª Aula CSS HTML.
##### Introdução ao CSS
---
### Dimensão e alinhamento.
- Para trabalhar com isso nos vamos usar as propriedades abaixo, podemos tanto colocar em `px`ou em `%`. Em porcentagem o elementos a imagem ou texto nao ultrapassa o tamanho em px que ele esta dentro.

|Codigo|Propriedade|
|------|-----------|
|Width|Largura.|
|Height|Altura.|
|Max-Width|Largura Maxima.|
|Max Height|Altura Maxima.|
|Margin|Espaçamento.|
|Text align|Alinhamento|

---
#### Width & Height
- Respresentam largura e altura no CSS. No exemplo abaixo vemos que a largura foi defenida pro maximo do corpo e altura pra um tamanho especifico.
```
.image {
    width: 100%;
    height: 350px
}
```
#### Max-Width & Max Height
- Se referem a alura maxima e a largura maxima que esses elementos podem ter. Usando ele quando temos diferentes tamanhos de tela no caso uma tela menor que `900px`o conteudo se ajusta a este tamanho menor mas nao ultrapassa o valor defenido.
```
.body {
    max-width: 900px;
    max-Height: 900px
}
```
#### Margin
- Usamos para alinhar e colocar Espaçamento entre elementos. A `margin` também tem uma propriedade chamada `auto`que ajusta automaticament as margens pro conteudo ficar no centro.
```
.body {
    margin: auto;
}
.body {
    margin: 15px;
}
.body {
    margin: 15%;
}
.body {
    margin: 15px 0 10px 0;
}
```
#### Text align
- Server pra alinhar textos pode ser no centro usando o `center`ou esquerda e direita usando `right`e `left` ou justificar o texto com o valor `justify`.
```
.body {
    text-align: center;
}
.body {
    text-align: right;
}
.body {
    text-align: left;
}
.body {
    text-align: justify;
}
```
