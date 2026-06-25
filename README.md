# Projeto: Grafos com Matriz de Adjacência

Trabalho prático de Estrutura de Dados focado na representação e análise topológica de grafos em C.

## 📌 Introdução
O presente trabalho apresenta o desenvolvimento de um programa em linguagem C para a representação e manipulação de grafos não direcionados. Para estruturar os dados, optou-se pela utilização de uma **Matriz de Adjacência**, que permite armazenar e consultar de forma eficiente as conexões entre os vértices. O sistema possui um menu interativo que oferece funcionalidades fundamentais da teoria dos grafos.

## ⚙️ Metodologia
O projeto foi desenvolvido utilizando as bibliotecas padrão de entrada e saída (`stdio.h` e `stdlib.h`). A estrutura de **Matriz de Adjacência** foi implementada através de um vetor bidimensional alocado estaticamente. O desenvolvimento foi estruturado de forma modular, dividindo as operações principais em funções específicas (`limparGrafo`, `modificaAresta`, `imprimirMatriz`, etc.) para facilitar a manutenção. A interação com o usuário ocorre por meio de uma interface de terminal contínua.

## 🚀 Como testar o código
Ao executar o programa, siga estes passos para testar as funcionalidades:
1. Digite a quantidade de vértices (ex: `3`).
2. Escolha a opção **3** para ver a matriz zerada.
3. Escolha a opção **2** e adicione uma aresta entre o vértice `0` e o vértice `1` (com valor `1`).
4. Escolha a opção **4** ou **5** para ver os graus e a lista de adjacências atualizados!

## ✅ Conclusão
O desenvolvimento deste projeto permitiu consolidar na prática os conceitos teóricos sobre grafos e suas representações computacionais. A escolha da matriz de adjacência demonstrou ser uma solução simples e direta para o armazenamento de grafos não direcionados.

---
*Nota sobre o uso de IA: Durante a elaboração deste relatório, o modelo de inteligência artificial Gemini foi utilizado como ferramenta de apoio à redação e formatação dos textos estruturais.*S