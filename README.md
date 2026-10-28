# ALGORITMOS-DE-ORDENA-O
Organizador de Preços de Supermercado
1. Objetivo

Desenvolver uma aplicação em linguagem C que organize os preços de produtos de um supermercado utilizando os algoritmos de ordenação Bubble Sort e Quick Sort.

O projeto foi desenvolvido como atividade acadêmica para demonstrar o funcionamento e comparar duas técnicas de ordenação.

2. Situação-problema

Em um supermercado, organizar os preços dos produtos facilita a comparação de valores e ajuda os consumidores a identificar os produtos mais baratos.

A aplicação resolve esse problema armazenando dez produtos e exibindo seus preços em ordem crescente.

3. Funcionalidades
Exibir os produtos antes da ordenação.
Ordenar os produtos utilizando Bubble Sort.
Ordenar os produtos utilizando Quick Sort.
Comparar os resultados dos dois algoritmos.
Exibir os nomes dos produtos e seus respectivos preços.
4. Tecnologias utilizadas
Linguagem C.
Compilador GCC.
Biblioteca padrão da linguagem C.
5. Algoritmos de ordenação
Bubble Sort

O Bubble Sort percorre a lista comparando elementos vizinhos. Quando dois elementos estão fora de ordem, suas posições são trocadas.

O processo se repete até que a lista esteja ordenada. Sua complexidade média e de pior caso é O(n²).

Quick Sort

O Quick Sort utiliza a estratégia de divisão e conquista. O algoritmo escolhe um pivô, particiona a lista em grupos de elementos menores ou iguais e maiores que o pivô e ordena esses grupos recursivamente.

Sua complexidade média é O(n log n), enquanto o pior caso é O(n²).

6. Estrutura do projeto
text
organizador-precos/
├── main.c
└── README.md

7. Como executar

É necessário ter um compilador C, como o GCC, instalado no computador.

Compile o programa com o comando:

bash
gcc main.c -o organizador -std=c11 -Wall -Wextra


No Linux ou macOS, execute:

bash
./organizador


No Windows, execute:

bash
organizador.exe


Também é possível testar o código em um compilador online, como o OnlineGDB.

8. Utilização

Ao iniciar o programa, será apresentado um menu com as seguintes opções:

Exibir os produtos originais.
Ordenar com Bubble Sort.
Ordenar com Quick Sort.
Comparar os dois algoritmos.
Encerrar o programa.

Escolha a opção desejada digitando o número correspondente.

9. Conclusão

O desenvolvimento deste projeto permitiu aplicar os conceitos de ordenação de dados utilizando a linguagem C.

O Bubble Sort demonstrou uma estratégia simples baseada em comparações entre elementos vizinhos. O Quick Sort apresentou uma abordagem baseada em divisão e conquista.

Os dois algoritmos produziram a mesma ordenação crescente para o conjunto de produtos, demonstrando como diferentes técnicas podem resolver o mesmo problema computacional.

10. Autor

Projeto acadêmico desenvolvido para a atividade de Algoritmos de Ordenação.
