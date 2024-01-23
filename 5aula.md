
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
              **ou**
```
.post{
    border-with: 3px;
    border-color: #505050;
    border-style: solid;
}
```              
