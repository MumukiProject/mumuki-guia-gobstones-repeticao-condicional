Te deixamos o código da solução anterior, o único que precisará mudar é a **pergunta**.

``` gobstones
procedure IrAoExtremo(direcao) {
  while (podeMover(direcao)) {
    Mover(direcao)
  }
}
```
