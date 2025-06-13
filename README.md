# Code Review 
realizado pelo aluno João Vitor Bertan

Repositório:
```
https://github.com/dede-ugolini/algoritimos-universidade/tree/main
```

## Algoritmos de ordenação

### Pontos positivos
- Modularização do código.
- Informações sobre a execução (tempo e iterações).
- Uso da constante N para tamanho do array, facilita a manutenção e legibilidade

### Possíveis melhorias
- Váriável size não tem seu valor alterado durante a execução do programa e possui o mesmo valor e finalidade da constante N.
```
#define N 1000
```
```
int size = sizeof(arr) / sizeof(arr[0]);
```

- Váriaveis globais que estão sendo usadas para fazer a ordenação em mais de uma função é uma má prática e podem se tornar um problema conforme a aplicação cresce.
```
int i, j, tmp;
```
