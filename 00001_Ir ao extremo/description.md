Vamos começar com um dos problemas que colocamos recentemente: escrever um procedimento que mova a garra até um extremo do tabuleiro. Este procedimento deveria funcionar de tal forma que se eu faço `IrAoExtremo(Leste)`, a garra se posiciona _"o mais ao Leste"_ possível, conservando a fila em que está (e da mesma maneira para quaisquer outras direções).

Provavelmente sua primeira idéia seja tentar algo com `MoverN` mas, como já dissemos, isso não serve; não tem como saber quantas vezes serão necessárias que se mova: poderiam ser 3, 12 ou nenhuma.

O que sim sabemos é que existe uma função `podeMover(direcao)` que nos indica se a garra pode se mover em uma certa direção. Com isso e um pouco de imaginação, poderíamos pensar em uma forma de repetição que faça o seguinte:

1. Pergunte se a garra pode se mover na direção desejada.
2. Mova a garra na direção desejada.
3. Volte ao passo 1, até que já não possa se mover.

Bem, exatamente essa é a forma de resolver, e (dessa vez) vai de presente: :gift:

``` gobstones
procedure IrAoExtremo(direcao) {
  while (podeMover(direcao)) {
    Mover(direcao)
  }
}
```

> Escreva nossa versão de `IrAoExtremo` no editor e envie.