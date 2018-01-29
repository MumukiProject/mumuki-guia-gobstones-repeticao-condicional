Uma vez mais chegou o momento de procurar alimento, mas dessa vez Alex encontrou um campo cheio de plantas... algumas comestíveis e outras não.

Este campo vamos representar com uma fila de um tabuleiro Gobstones, que vai estar cheia de ambos tipos de plantas. Sua tarefa será criar um procedimento `RecolherPlantasNaFila()` que:

* **percorra** a fila completa, a qual obviamente não sabemos quão comprida é, começando desde a origem e **em direção ao Leste**;
* em cada porção (célula), recolha a planta comestível **se é que existe alguma**;
* deixe no mesmo lugar as plantas não comestíveis.

Facilitamos a função `haPlantaComestivel()` e o procedimento `RecolherPlanta()` para que os use.