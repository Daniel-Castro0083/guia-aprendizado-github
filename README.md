Introdução à Lógica de Programação em C para Iniciantes

Sobre o projeto

Este guia apresenta uma introdução prática ao Git e ao GitHub para organização de projetos.

O material foi organizado de forma progressiva, começando pelos conceitos fundamentais e avançando para exercícios práticos.

Além do aprendizado de programação, este projeto utiliza Git e GitHub para demonstrar organização, versionamento, colaboração e controle das alterações realizadas durante o desenvolvimento.

---

Objetivo

O objetivo deste guia é ajudar iniciantes a compreender os principais conceitos da lógica de programação e desenvolver seus primeiros programas utilizando a linguagem C.

Ao final do guia, o estudante deverá ser capaz de:

- Compreender o que é lógica de programação;
- Identificar os principais elementos de um programa em C;
- Utilizar variáveis e tipos de dados;
- Receber dados do usuário;
- Exibir informações na tela;
- Utilizar estruturas condicionais;
- Utilizar estruturas de repetição;
- Desenvolver pequenos programas em C;
- Resolver problemas simples utilizando lógica de programação.

---

Público-alvo

Este material é destinado principalmente a:

- Pessoas que nunca programaram em C;
- Pessoas que desejam desenvolver sua lógica de programação.

Pré-requisitos

Não é necessário possuir conhecimento prévio em programação.

É recomendado apenas ter familiaridade básica com computadores e disposição para praticar.

---

Conteúdo do guia

1. Introdução

Apresentação dos conceitos de programação, lógica de programação e linguagem C.

"Acessar Introdução" (docs/01-introducao.md)

2. Conceitos fundamentais

Estudo dos principais elementos utilizados nos primeiros programas em C:

- Variáveis;
- Tipos de dados;
- Entrada e saída de dados;
- Operadores;
- Estruturas condicionais;
- Estruturas de repetição.

"Acessar Conceitos" (docs/02-conceitos.md)

3. Exercícios

Atividades práticas para testar os conhecimentos adquiridos ao longo do guia.

"Acessar Exercícios" (docs/03-exercicios.md)

4. Referências

Materiais utilizados como apoio durante a elaboração do guia.

"Acessar Referências" (docs/04-referencias.md)

---

Seu primeiro programa em C

Um dos primeiros programas tradicionalmente utilizados para começar a aprender uma linguagem de programação é o famoso "Olá, mundo!".

#include <stdio.h>

int main() {
    printf("Olá, mundo!");
    return 0;
}

O que esse programa faz?

O programa utiliza a função "printf()" para exibir a mensagem:

Olá, mundo!

O comando "return 0" indica que o programa foi encerrado normalmente.

---

Dicas para aprender programação

Aprender programação exige prática. Algumas recomendações importantes são:

1. Estude os conceitos antes de tentar decorar comandos.
2. Escreva os códigos manualmente.
3. Execute os programas e observe os resultados.
4. Quando ocorrer um erro, tente entender a mensagem apresentada.
5. Faça pequenas alterações nos exemplos para observar o que acontece.
6. Resolva exercícios regularmente.
7. Evite apenas copiar códigos prontos.

---

gDesafio final

Depois de estudar o conteúdo deste guia, tente desenvolver um programa em C que:

1. Receba três notas de um estudante;
2. Calcule a média;
3. Mostre a média na tela;
4. Informe se o estudante foi:
   - Aprovado, caso a média seja maior ou igual a 7;
   - Em recuperação, caso a média esteja entre 5 e 6,9;
   - Reprovado, caso a média seja menor que 5.

Esse desafio reúne diversos conceitos apresentados neste guia.

---

Estrutura do projeto

guia-aprendizado-github/
├── README.md
├── LICENSE
├── aprendizados.md
├── conflito-resolvido.md
├── docs/
│   ├── 01-introducao.md
│   ├── 02-conceitos.md
│   ├── 03-exercicios.md
│   └── 04-referencias.md
└── exemplos/
    └── exemplo-basico.md

---

Git e GitHub

Durante o desenvolvimento deste projeto, foram utilizados conceitos de Git e GitHub, incluindo:

- Criação de repositório;
- Commits;
- Branches;
- Versionamento;
- Pull Requests;
- Merge;
- Resolução de conflitos;
- Organização do histórico de alterações.

O objetivo é demonstrar não apenas o conteúdo produzido, mas também o processo utilizado para desenvolver, revisar e organizar o projeto.

---

Materiais adicionais

- "Aprendizados do projeto" (aprendizados.md)
- "Registro de conflito resolvido" (conflito-resolvido.md)
- "Referências utilizadas" (docs/04-referencias.md)

---

Considerações finais

Este guia foi desenvolvido como um projeto acadêmico com o objetivo de unir aprendizado de programação e práticas de versionamento de código.

A proposta é mostrar que aprender programação não significa apenas escrever código, mas também saber organizar, documentar, testar e acompanhar a evolução de um projeto.

---

Projeto acadêmico — Guia de Aprendizagem Interativo em Markdown usando Git e GitHub