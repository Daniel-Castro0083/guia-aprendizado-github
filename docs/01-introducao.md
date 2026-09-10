1. Introdução à Lógica de Programação em C

O que é programação?

Programação é o processo de criar instruções que um computador consegue executar para realizar determinada tarefa.

Essas instruções são escritas utilizando uma linguagem de programação, como C, Python, Java e JavaScript.

Um programa pode, por exemplo:

- Realizar cálculos;
- Armazenar informações;
- Receber dados do usuário;
- Tomar decisões;
- Repetir determinadas tarefas;
- Automatizar atividades.

O que é lógica de programação?

A lógica de programação é a capacidade de organizar uma sequência de passos para resolver um problema.

Antes de escrever código, é importante entender qual problema precisa ser resolvido e quais passos são necessários para chegar à solução.

Exemplo

Imagine que precisamos calcular a média de duas notas.

Podemos organizar a solução da seguinte maneira:

1. Receber a primeira nota;
2. Receber a segunda nota;
3. Somar as duas notas;
4. Dividir o resultado por 2;
5. Mostrar a média.

Essa sequência de passos representa uma lógica para resolver o problema.

O que é a linguagem C?

C é uma linguagem de programação criada na década de 1970 e que possui grande importância na história da computação.

Ela é utilizada em diferentes áreas, incluindo:

- Sistemas operacionais;
- Sistemas embarcados;
- Softwares de baixo nível;
- Desenvolvimento de aplicações;
- Ensino de lógica e fundamentos de programação.

Aprender C também pode ajudar o estudante a compreender conceitos fundamentais sobre como os programas funcionam.

Como funciona um programa?

De maneira simplificada, podemos pensar em um programa como uma sequência:

Entrada → Processamento → Saída

Entrada

São os dados fornecidos ao programa.

Exemplo:

Digite sua idade: 25

Processamento

É o momento em que o programa utiliza os dados para realizar alguma operação.

Exemplo:

idade + 1

Saída

É o resultado apresentado pelo programa.

Exemplo:

Sua idade no próximo ano será: 26

Primeiro programa em C

Um dos primeiros programas utilizados para aprender uma linguagem de programação é o tradicional "Olá, mundo!".

#include <stdio.h>

int main() {
    printf("Olá, mundo!");
    return 0;
}

Entendendo o código

"#include <stdio.h>"

Inclui a biblioteca padrão de entrada e saída do C.

Ela permite utilizar funções como "printf()".

"int main()"

É a função principal do programa.

A execução começa a partir dela.

"printf()"

É utilizada para exibir uma mensagem na tela.

Neste exemplo:

printf("Olá, mundo!");

o programa apresenta:

Olá, mundo!

"return 0"

Indica que a função "main" terminou sua execução normalmente.

Por que aprender lógica antes de avançar?

Aprender programação não significa apenas memorizar comandos.

O mais importante é desenvolver a capacidade de:

- Analisar problemas;
- Dividir problemas em etapas;
- Identificar informações necessárias;
- Criar uma sequência de soluções;
- Testar diferentes possibilidades;
- Corrigir erros.

Essas habilidades podem ser utilizadas independentemente da linguagem de programação escolhida.

Atividade de fixação

Antes de avançar para o próximo capítulo, tente responder:

1. O que é programação?
2. O que significa lógica de programação?
3. Para que serve uma linguagem de programação?
4. Qual é a função da "main()" em um programa C?
5. Para que serve a função "printf()"?
6. Qual é a diferença entre entrada, processamento e saída?

Desafio

Imagine que você precisa criar um programa que calcule a idade de uma pessoa no próximo ano.

Escreva, com suas próprias palavras, quais seriam os passos necessários para resolver esse problema antes de escrever o código.

---

Próximo capítulo: "Conceitos Fundamentais" (02-conceitos.md)