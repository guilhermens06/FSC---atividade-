# PROJETO CIRCUITOS | Fundamentos de Sistemas Computacionais
PUCRS<br>
Guilherme Niemxeski Santos - 25101197 <br>
Prof. Anderson Domingues <br>
Link do Circuito:
https://circuitverse.org/users/326699/projects/aula-8-circuitos
---

# Circuitos Implementados:

---
1. Demultiplexador (1-para-2)
---

O Demultiplexador (Demux) atua como um roteador de dados. Ele recebe uma única linha de entrada e a direciona para uma das duas linhas de saída, com base no estado de um pino de seleção.

* Função: Roteia um sinal de entrada para uma de N saídas.
* Operação: Se o pino seletor for 0, a entrada é enviada para a primeira saída. Se for 1, é enviada para a segunda.

---
2. Comparador de 6 bits
---

Este circuito lógico compara dois números binários de 6 bits (A e B) e determina se eles são idênticos.

* Função: Verificação de igualdade entre duas palavras binárias.
* Operação: A comparação é feita bit a bit usando portas XOR. O resultado de todas as comparações é então processado por uma porta NOR para produzir uma única saída: 1 se A == B, e 0 caso contrário.

---
3. Somador de 6 bits
---

Um circuito aritmético projetado para executar a adição de dois números binários de 6 bits. A arquitetura utilizada é a de Ripple-Carry Adder.

* Função: Calcular a soma S = A + B.
* Operação: O circuito é composto por seis somadores completos de 1 bit interligados em cascata. O "vai-um" (carry-out) de cada estágio é propagado para o estágio seguinte (carry-in), da direita para a esquerda.

---
4. ULA (Unidade Lógica e Aritmética) de 6 bits
---

A ULA é um componente digital versátil que forma a base de um processador. Ela é capaz de executar diversas operações lógicas e aritméticas.

* Função: Realizar um conjunto de operações pré-definidas (como Adição, Subtração, AND, OR) sobre duas entradas de 6 bits.
* Operação: Um sinal de controle de operação seleciona a função a ser executada. A lógica interna da ULA configura o fluxo de dados através de somadores e portas lógicas para produzir o resultado da operação escolhida.
