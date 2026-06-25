# Projeto: Grafos com Matriz de Adjacencia

Trabalho pratico de Estrutura de Dados focado na representacao e analise topologica de grafos em C.

##  Introducao
O presente trabalho apresenta o desenvolvimento de um programa em linguagem C para a representacao e manipulacao de grafos nao direcionados. Para estruturar os dados, optou-se pela utilizacao de uma **Matriz de Adjacencia**, que permite armazenar e consultar de forma eficiente as conexoes entre os vertices. O sistema possui um menu interativo que oferece funcionalidades fundamentais da teoria dos grafos.

##  Metodologia
O projeto foi desenvolvido utilizando as bibliotecas padrao de entrada e saida (`stdio.h` e `stdlib.h`). A estrutura de **Matriz de Adjacencia** foi implementada atraves de um vetor bidimensional alocado estaticamente. O desenvolvimento foi estruturado de forma modular, dividindo as operacoes principais em funcoes especificas (`limparGrafo`, `modificaAresta`, `imprimirMatriz`, etc.) para facilitar a manutencao. A interacao com o usuario ocorre por meio de uma interface de terminal continua.

##  Como testar o codigo
Ao executar o programa, siga estes passos para testar as funcionalidades:
1. Digite a quantidade de vertices (ex: `3`).
2. Escolha a opcao **3** para ver a matriz zerada.
3. Escolha a opcao **2** e adicione uma aresta entre o vertice `0` e o vertice `1` (com valor `1`).
4. Escolha a opcao **4** ou **5** para ver os graus e a lista de adjacencias atualizados!

##  Conclusao
O desenvolvimento deste projeto permitiu consolidar na pratica os conceitos teoricos sobre grafos e suas representacoes computacionais. A escolha da matriz de adjacencia demonstrou ser uma solucao simples e direta para o armazenamento de grafos nao direcionados.