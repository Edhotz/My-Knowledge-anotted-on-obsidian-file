
#### Uma string pode ser definida como uma matriz de caracteres que são terminadas por um carácter nulo \0

##### Deve-se declarar Strings com um índice a mais para passar o carácter nulo por exemplo: 

``` C
char str[11]
```

##### Isso reserva um espaço para o nulo no final da string

#### Funções de manipulação de strings:
- strpy(s1, s2) - copia s2 em s1
- strcat(s1, s2) - Concatena s2 ao final de s1
- strlen(s1) - Retorna o tamanho de s1
- strcmp(s1, s2) - Retorna 0 se s1 > s2
- strchr(s1, ch) - Retorna um ponteiro para a primeira ocorrência de ch em s1
- strstr(s1, s2) Retorna um ponteiro para a primeira ocorrência de s2 em s1


