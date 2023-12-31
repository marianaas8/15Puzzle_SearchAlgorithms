# README
## 15 Puzzle Solver

**1º passo:** Criar um ficheiro de texto denominado de "input.txt" que contenha duas linhas com as configurações inicial e final respetivamente como o exemplo seguinte:

```plaintext
1 2 3 4 5 6 8 12 13 9 0 7 14 11 10 15
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 0
```
**2º passo:** Colocar no terminal o seguinte comando "python Principal.py ESTRATÉGIA input.txt" onde no local ESTRATÉGIA você coloca o método de busca que deseja utilizar sendo as opções as seguintes:
- BFS
- DFS 12 (12 indica a profundidade máxima)
- IDFS 12 (12 indica a profundidade máxima)
- A*-misplaced
- A*-Manhattan
- Greedy-misplaced
- Greedy-Manhattan

**Observações:**
Após seguir as referidas instruções aparecerá no seu ecrã dois tabuleiros indicativos dos estados contidos no seu input. Poderá também observar se é possível chegar à configuração standard ("1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 0"). De seguida aparecerá o nome da pesquisa selecionada assim como o tempo de execução, os nós gerados e armazenados, a percentagem do CPU e de memória RAM utilizados. Finalmente conseguirá visualizar as trocas efetuadas, ou seja, 'Cima' indica que o espaço em branco foi trocado com a peça acima, assim como os estados dos tabuleiros que levaram à configuração desejada.
