Vejamos outro exemplo de **loop infinito** (assim se chama isso dos `while` que **não terminam**).

``` gobstones
procedure PraFrenteEPraTras() {
  while (podeMover(Norte)) {
    Mover(Norte)
    Colocar(Verde)
    Mover(Sul)
  }
}
```

> Escreva o código no editor e observe como (não) funciona.
 
