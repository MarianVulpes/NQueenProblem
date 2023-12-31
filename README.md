# N Queen Problem
Algoritmo que acha todas as soluções para o problema das N rainhas, podendo N ser qualquer valor que apresente resultado. Embora o problema tenha sido apresentado a mim num contexto de algoritmos genéticos, onde me aprofundei nele através do mesmo contexto, este script usa o Backtracking.

# O que é o Problema das N Rainhas?
"Este problema consiste em posicionar um número N de rainhas em um tabuleiro de xadrez de tamanho N*N de forma que nenhuma delas colida com a outra, considerando as regras de movimentação do jogo." - Citação do meu TCC "A Utilização de Algoritmos Genéticos na Otimização de Problemas"

# O que é e como funciona o Backtracking?
Backtracking é um refinamento do algoritmo de busca por força bruta, que também pode ser descrito por enumeração exaustiva, no qual boa parte das soluções podem ser eliminadas sem serem explicitamente examinadas. De maneira simples, backtracking é uma estratégia recursiva de tentativa e erro, explorando diferentes caminhos para encontrar uma solução para um determinado problema. 
![image](https://github.com/MarianVulpes/NQueenProblem/assets/82874011/de771e4f-5f79-4925-8b1f-1148950aed1c)
<br>
Imagem retirada de: https://www.simplilearn.com/tutorials/data-structure-tutorial/backtracking-algorithm

# Referência do código
Utilizei este guia passo a passo como referência:: https://medium.com/cracking-the-coding-interview-in-ruby-python-and/8-12-the-8-queens-problem-with-solutions-ruby-javascript-and-python-409cea33b5b3
O problema com ele é que apenas apresenta as primeiras soluções encontradas por meio do backtracking. Por isso, fiz melhorias para que agora busque todas as soluções possíveis.
