Exemplo Básico em C

Primeiro programa

Este exemplo apresenta um programa simples escrito em C que exibe uma mensagem na tela.

#include <stdio.h>

int main() {
    printf("Ola, mundo!\n");

    return 0;
}

Explicação

Biblioteca

#include <stdio.h>

Essa linha inclui a biblioteca padrão de entrada e saída do C.

Ela disponibiliza funções como "printf()".

Função principal

int main() {

A função "main()" é o ponto de entrada do programa.

É a partir dela que a execução do programa começa.

Exibição da mensagem

printf("Ola, mundo!\n");

A função "printf()" apresenta uma mensagem na tela.

O "\n" indica uma quebra de linha.

Encerramento

return 0;

Indica que a função "main()" terminou sua execução normalmente.

Resultado esperado

Ao executar o programa, o resultado será:

Ola, mundo!

Segundo exemplo

Podemos utilizar uma variável para armazenar uma informação e depois apresentar seu valor.

#include <stdio.h>

int main() {
    int idade = 25;

    printf("Idade: %d\n", idade);

    return 0;
}

Resultado:

Idade: 25

Exercício

Modifique o primeiro programa para apresentar três informações diferentes.

Por exemplo:

Nome: Daniel
Curso: Analise e Desenvolvimento de Sistemas
Linguagem: C

Depois altere novamente o programa para utilizar uma variável para armazenar a informação do nome.