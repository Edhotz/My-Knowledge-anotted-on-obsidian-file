
#### Ponteiros e matrizes estão intimamente relacionados. O nome de uma  matriz sem um índice e um ponteiro para o primeiro elemento da matriz. Por exemplo considere a matriz.

``` C
char p[10]
```

##### As seguintes sentenças são iguais:

``` C
	p 
	&p[0]
```

##### Colocando de outra forma,

``` C
p == &p[0];
```

##### E avaliado como verdadeiro porque o endereço do primeiro elemento e o mesmo que o da matriz.


``` C
int *p, i[10];
p = i;
p[5] = 100;
*(p + 5) = 100;
```


##### Processo este que também pode ser aplicado a matrizes de duas ou mais dimensões.

##### Assumindo que *a* e uma matriz de inteiros 10 por 10 , estas duas sentenças são equivalentes:

``` C
a 
&a[0][0];
```


#### *Nota*
### a[j]""[k] é equivalente a *(a+(j*comprimento das linhas)+k)

