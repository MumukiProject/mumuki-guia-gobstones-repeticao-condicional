Em um determinado ponto da viagem, Alex tem que escalar uma montaña. Como já dissemos antes, as paredes serão representadas com pedras azuis. As montanhas podem ter tamanhos e formas diferentes, por exemplo:

<gs-board>
  GBB/1.0
    size 3 4
    cell 1 0 Azul 1
    cell 1 1 Azul 1
    cell 2 0 Azul 1
    cell 2 1 Azul 1     
    cell 2 2 Azul 1     
    head 0 0
</gs-board>

Vamos fazer um procedimento, o qual sirva para que o viajante escale **qualquer** montanha, reconhecendo que ela sempre vai estar **ao Leste** da sua localização. O roteiro da escala faremos por etapas, e em cada uma é necessário subir até o próximo descanso; no exemplo, o primeiro descanso está na posição (1, 2).

> Execute o procedimento `EscalarAteDescanso()`, que deixe o nosso amigo no primeiro descanso que há na montanha.
