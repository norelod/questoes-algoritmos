# questoes-algoritmos

Como saber se estou pronto para a seleção de programador de algoritmos?

Só aplique se você não encontrar dificuldades nas questões a seguir:

## Duas somas

Dado um array de inteiros ```nums``` e um inteiro ```target```, retorne os índices dos dois números de modo que a soma deles seja ```target```.

Você pode assumir que
- cada entrada tenha exatamente uma única solução
- não pode usar o mesmo elemento duas vezes.

Você pode retornar a resposta em qualquer ordem.

Questão original do [LeetCode](https://leetcode.com/problems/two-sum/).

## Mesclar duas listas classificadas

São fornecidos os cabeçalhos de duas listas encadeadas classificadas ```list1``` e ```list2```.

Mescle as duas listas em uma lista ordenada . A lista deve ser feita juntando os nós das duas primeiras listas.

Retorna o cabeçalho da lista vinculada mesclada. 

Exemplo:

![image](https://github.com/user-attachments/assets/7f15f390-6aa4-4ff2-8650-7a354d13a31b)

**Entrada**: ```lista1 = [1,2,4], lista2 = [1,3,4]```

**Saída**: ```[1,1,2,3,4,4]```

Questão original do [LeetCode](https://leetcode.com/problems/merge-two-sorted-lists/).

## Contando Bits

Dado um inteiro ```n```, retorne um array ```ans``` de comprimento ```n + 1``` tal que para cada ```i ( 0 <= i <= n)``` , ```ans[i]``` é o número de ```1```'s na representação binária de ```i```.

**Exemplo 1**

Entrada: ```n = 2```
 Saída: ```[0,1,1]```
 
 Explicação:
```
0 --> 0
1 --> 1
2 --> 10
```

**Exemplo 2**

Entrada: ```n = 5```
 Saída: ```[0,1,1,2,1,2]```
 
 Explicação:
 ```
0 --> 0
 1 --> 1
 2 --> 10
 3 --> 11
 4 --> 100
 5 --> 101
```

Restrições:
```0 <= n <= 10000```

Questão original do [LeetCode](https://leetcode.com/problems/counting-bits/).
