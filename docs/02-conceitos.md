2. Conceitos Fundamentais de C

Neste capítulo serão apresentados alguns dos principais conceitos utilizados nos primeiros programas em C.

Variáveis

Uma variável é um espaço reservado na memória para armazenar um valor que pode ser utilizado durante a execução do programa.

Em C, uma variável possui um tipo, um nome e um valor.

Exemplo:

int idade = 25;

Nesse exemplo:

- "int" define o tipo da variável;
- "idade" é o nome da variável;
- "25" é o valor armazenado.

O valor de uma variável pode ser alterado durante a execução do programa.

int idade = 25;

idade = 26;

Depois da segunda instrução, a variável "idade" passa a armazenar o valor "26".

Tipos de dados

Os tipos de dados indicam que tipo de informação uma variável pode armazenar.

Alguns tipos básicos utilizados em C são:

Tipo| Utilização| Exemplo
"int"| Números inteiros| "10"
"float"| Números decimais| "7.5"
"double"| Números decimais com maior precisão| "15.75"
"char"| Um único caractere| "'A'"

Exemplos:

int idade = 25;
float altura = 1.75;
double salario = 2500.50;
char inicial = 'D';

Saída de dados

A função "printf()" é utilizada para apresentar informações na tela.

Exemplo:

#include <stdio.h>

int main() {
    printf("Meu primeiro programa em C!");
    return 0;
}

Também podemos utilizar variáveis dentro do "printf()".

#include <stdio.h>

int main() {
    int idade = 25;

    printf("Minha idade e: %d", idade);

    return 0;
}

O "%d" é utilizado para exibir um valor do tipo "int".

Alguns especificadores comuns são:

Especificador| Tipo
"%d"| "int"
"%f"| "float"
"%lf"| "double"
"%c"| "char"

Entrada de dados

Para receber informações digitadas pelo usuário, podemos utilizar a função "scanf()".

Exemplo:

#include <stdio.h>

int main() {
    int idade;

    printf("Digite sua idade: ");
    scanf("%d", &idade);

    printf("Sua idade e: %d", idade);

    return 0;
}

Nesse exemplo, o programa solicita uma idade, armazena o valor na variável "idade" e depois apresenta o resultado.

O símbolo "&" utilizado antes da variável indica o endereço de memória onde o valor recebido será armazenado.

Operadores aritméticos

Os operadores aritméticos permitem realizar operações matemáticas.

Operador| Operação
"+"| Adição
"-"| Subtração
"*"| Multiplicação
"/"| Divisão
"%"| Resto da divisão

Exemplo:

int a = 10;
int b = 3;

int soma = a + b;
int subtracao = a - b;
int multiplicacao = a * b;
int divisao = a / b;
int resto = a % b;

Quando trabalhamos com números inteiros, a divisão entre dois valores inteiros resulta em um valor inteiro.

Por exemplo:

int resultado = 10 / 3;

Nesse caso, "resultado" será "3".

Estruturas condicionais

As estruturas condicionais permitem que o programa tome decisões.

A principal estrutura condicional é o "if".

Exemplo:

#include <stdio.h>

int main() {
    int idade;

    printf("Digite sua idade: ");
    scanf("%d", &idade);

    if (idade >= 18) {
        printf("Maior de idade.");
    }

    return 0;
}

Nesse exemplo, a mensagem somente será exibida se a condição "idade >= 18" for verdadeira.

Também podemos utilizar "else" para definir o que acontece quando a condição for falsa.

if (idade >= 18) {
    printf("Maior de idade.");
} else {
    printf("Menor de idade.");
}

Operadores relacionais

Os operadores relacionais são utilizados para comparar valores.

Operador| Significado
"=="| Igual a
"!="| Diferente de
">"| Maior que
"<"| Menor que
">="| Maior ou igual a
"<="| Menor ou igual a

Exemplo:

if (nota >= 7) {
    printf("Aprovado.");
}

Operadores lógicos

Os operadores lógicos permitem combinar diferentes condições.

Operador| Significado
"&&"| E
`| 
"!"| NÃO

Exemplo:

if (idade >= 18 && idade <= 60) {
    printf("Condicao atendida.");
}

Nesse caso, as duas condições precisam ser verdadeiras.

Estrutura switch

O "switch" pode ser utilizado quando precisamos verificar diferentes possibilidades de um mesmo valor.

Exemplo:

#include <stdio.h>

int main() {
    int opcao;

    printf("Digite uma opcao: ");
    scanf("%d", &opcao);

    switch (opcao) {
        case 1:
            printf("Opcao 1 selecionada.");
            break;

        case 2:
            printf("Opcao 2 selecionada.");
            break;

        default:
            printf("Opcao invalida.");
    }

    return 0;
}

O "break" encerra a execução daquele caso.

O "default" é executado quando nenhum dos casos anteriores corresponde ao valor informado.

Estrutura de repetição while

O "while" permite repetir um bloco de código enquanto uma condição for verdadeira.

Exemplo:

int contador = 1;

while (contador <= 5) {
    printf("%d\n", contador);
    contador++;
}

Nesse exemplo, os números de 1 a 5 serão apresentados.

Estrutura de repetição for

O "for" também pode ser utilizado para repetir um bloco de código.

Exemplo:

for (int contador = 1; contador <= 5; contador++) {
    printf("%d\n", contador);
}

A estrutura possui três partes principais:

inicialização; condição; atualização

No exemplo:

- "int contador = 1" inicializa a variável;
- "contador <= 5" define a condição;
- "contador++" aumenta o contador a cada repetição.

Diferença entre while e for

As duas estruturas podem realizar tarefas semelhantes, mas geralmente:

- "for" é utilizado quando sabemos ou conseguimos definir claramente a quantidade de repetições;
- "while" é útil quando a repetição depende de uma condição que pode permanecer verdadeira por uma quantidade desconhecida de vezes.

Exemplo integrando os conceitos

O programa abaixo utiliza entrada de dados, variável, cálculo e estrutura condicional:

#include <stdio.h>

int main() {
    float nota1;
    float nota2;
    float media;

    printf("Digite a primeira nota: ");
    scanf("%f", &nota1);

    printf("Digite a segunda nota: ");
    scanf("%f", &nota2);

    media = (nota1 + nota2) / 2;

    printf("Media: %.2f\n", media);

    if (media >= 7) {
        printf("Aprovado.");
    } else if (media >= 5) {
        printf("Em recuperacao.");
    } else {
        printf("Reprovado.");
    }

    return 0;
}

Esse exemplo reúne vários conceitos apresentados neste capítulo.

Exercícios de fixação

1. Crie um programa que armazene sua idade em uma variável e apresente o valor na tela.

2. Crie um programa que receba dois números inteiros e apresente a soma dos valores.

3. Crie um programa que receba um número e informe se ele é positivo, negativo ou igual a zero.

4. Crie um programa que receba uma idade e informe se a pessoa é maior ou menor de idade.

5. Crie um programa que receba um número de 1 a 7 e utilize "switch" para informar um dia da semana.

6. Crie um programa que utilize "while" para apresentar os números de 1 a 10.

7. Crie um programa que utilize "for" para apresentar os números pares de 0 a 20.

8. Crie um programa que receba cinco números e calcule a soma deles.

9. Crie um programa que receba três notas, calcule a média e informe se o estudante foi aprovado, está em recuperação ou foi reprovado.

10. Modifique o programa anterior para informar também a média calculada.

---

Próximo capítulo: "Exercícios" (03-exercicios.md)