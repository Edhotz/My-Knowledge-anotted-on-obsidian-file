### Matrizes  Unidimensionais

``` bash
tipo nome_var[tamanho]
```

##### Matrizes devem ser explicitamente declaradas para que o compilador possa alocar espaço para elas na memoria

``` C
double balance[100];
char p[10];
```

### Gerando um ponteiro para uma matriz

##### Ponteiros podem ser gerados apenas especificando o nome de uma matriz, sem nenhum índice

``` C
int sample[10];
```

##### O seguinte fragmento atribui a p o endereço do primeiro elemento de sample

``` C
int *p;
int sample[10];
p = sample
```

### Passando Matrizes unidimensionais para funções
##### Em **C** não se pode passar uma matriz inteira como argumento para uma função. Porem pode-se passar um ponteiro para uma matriz para uma função especificando o nome da matriz sem um índice.


``` C
void main() {
int i[10];

func1(i); 
}
```