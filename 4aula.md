# DIO| 4ª Aula de HTML & CSS
Conceitos Básicos de CSS3

### Box model
- Toda pagina da web e divida em divisões, ou caixas que sao chamadas de `"Box model"`
- Que são dividas em:
```
margin-¬
       |
       border¬
              |
              padding¬
                      |
                      content
```

#### Margin 
- As magens são espaçamentos entre os elementos.

#### Border
- As bordas elas circulam o "padding" e o conteudo, entao nos conseguimos mudar a aparencia dela, como largura e cor e formato.

#### Padding
- O padding é o espaçamento entre a borda e o conteudo.

#### Content
- O content e o conteudo que seu blog representa
um texto uma imagem ou um video.

### Border
- Tem até `3 valores`, como largura a cor e o estilo, a cor pode ser atribuida pelo nome ou pelo codigo hexadecimal dela, as quantiade de pixel pode ser vairas e os estilos existem mais de um. Temos essas variações:
**solid:** _mostra uma borda simples e reta._

**dotted:** _são bolinhas com um pequeno espaçamento entre elas._

**dashed:** _forma uma linha tracejada._ 
```
.{
    border: 3px black solid;
    border: 5px white dotted;
    border: 4px #fcfcfc dashed;
}
```
- No 1º exemplo vemos a cor preta e a borda solida, no 2º vemos a cor branca e a borda com bolinhas e no 3º cor branca também com a borda em tracejado.
- Existem algumas propriedades especifica  para cada aspecto da borda.
---

|Aspecto| Modificação|
|-------|------------|
|_border-width_|Para largura da borda.|
|_border-color_|Para cor.|
|_border-style_|Para estilo.|
|_border-radius_|Pra arrendonar os cantos|

---
- Nessa ultima propriedade a `border-redius`, colocando apenas um valor mudamos todos os cantos do elemento, mas seguimos a mesma ordem do `padding` e `margin` 1º Topo, 2º Direita,3º Inferior, 4º Esquerda.
Exemplos:
```
.{
    border-width: 12px;
    border-color: blue;
    border-style: dotted;
    border-radius: 12px 0 12px 0;
    border-radius: 12px;
}
```
---
### Estilizando Textos
Podemosa mudar cor e tamanho de algums fontes,agora vamos ver melhor isso.
#### Font-family
- Com o `font-family` podemos alterar a fonte do texto com fontes da internet ou que esta instala no pc, porem vamos focar nas web safe fonts pois são aceitas na maior parte dos sistemas.
#### Font-Size
- O `font-size `nos ajuda a mudar o tamanho do texto.
#### Font-Style
- Usamos o `font-style `para tornar um texto em _italico_ ou deixa em negrito.
