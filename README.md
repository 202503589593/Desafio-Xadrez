Xadrez: Movimentação das Peças

Este projeto implementa a movimentação das peças de xadrez (Torre, Bispo, Rainha e Cavalo) em C, utilizando conceitos de recursividade e loops aninhados para simular corretamente seus movimentos.

📌 Funcionalidades Implementadas

Movimento Recursivo:

Torre (movimento horizontal)

Bispo (movimento diagonal)

Rainha (movimento diagonal)

Movimento com Loops Aninhados:

Bispo (implementação alternativa com loops)

Movimento do Cavalo:

Implementado com loops aninhados para simular o movimento em "L" (duas casas para cima e uma para a direita)

🛠️ Estrutura do Código

O código principal está no arquivo xadrez.c, e suas principais funções são:

moverTorre(int casas): Move a Torre recursivamente para a direita.

moverBispo(int casas): Move o Bispo recursivamente na diagonal superior direita.

moverRainha(int casas): Move a Rainha recursivamente na diagonal inferior esquerda.

moverBispoLoops(int casas): Move o Bispo utilizando loops aninhados.

moverCavalo(): Simula o movimento do Cavalo com loops aninhados e controle de fluxo.

🏗️ Como Executar o Código

Compilar o programa:

gcc xadrez.c -o xadrez

Executar o programa:

./xadrez

📌 Saída Esperada

O programa imprime no console os movimentos das peças, por exemplo:

Movimento da Torre:
Direita
Direita
Direita
Direita
Direita

Movimento do Bispo (recursivo):
Diagonal superior direita
Diagonal superior direita
Diagonal superior direita
Diagonal superior direita
...

Cada peça tem sua movimentação separada e exibida de forma clara.

📜 Requisitos do Projeto

Utilizar recursividade para os movimentos da Torre, Bispo e Rainha.

Utilizar loops aninhados para o movimento do Bispo.

Implementar o movimento do Cavalo com loops complexos.

Exibir a movimentação no console de forma clara e organizada.
