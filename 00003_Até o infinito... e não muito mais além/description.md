Tudo muito bonito isso do `while`, mas o que acontece se a pergunta **sempre é verdadeira**? Vejamos um exemplo:

``` gobstones
procedure AteOInfinito() {
  while (podeMover(Leste)) {
    Colocar(Vermelho)
  }
}
```

> Quando terminará esse procedimento? Analise: escreva o código no editor e observe o que faz.
