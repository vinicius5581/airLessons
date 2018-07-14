# Big-O notation

## Analize simplificada da eficiência de algoritimos
Big-O notation nos da uma noçāo de quanto tempo um algoritimo leva para rodar.
Big-O notation nos permite analizar a complexidade de algoritimos baseado no tamanho does seus inputs, N.
Big-O notation nāo leva em consideraçao a máquina onde o algoritimo vai rodar e sim a quantidade de passos leavados na computaçao do algoritmo.
Big-O notation nos permite analizar o tempo e espaco. 

Um algoritmo pode ser analizado de algumas maneiras diferentes:
- worst-case (pior cenário)
- best-case (melhor cenário)
- average-case (cenário mediano)

Big-O notation geralmente analiza o pior cenário.

## Algumas regras
- Ignore constantes
`5n -> O(n)`
- Ordem de prioridades (ignore os termos com menores ordens)
`O(1) < O(logn) < O(n) < O(nlogn) < O(n^2) < O(2^n) < O(n!)`


### Constant time
x = 5 + (15 * 20);
y = 15-2;
print x + y;
