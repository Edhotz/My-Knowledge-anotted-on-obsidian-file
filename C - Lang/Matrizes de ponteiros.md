
### Ponteiros podem ser organizados em matrizes como qualquer outro tipo de dado. A declaração de uma matriz de ponteiros int,  de tamanho 10: 

``` c
int x*[10];
```

#### Para atribuir o endereço de uma variável inteira, chamada var, ao terceiro elemento da matriz de ponteiros, deve-se escrever

``` c
x[2] = &var;
```

#### Para encontrar este valor de var, escreve-se
``` c
*x[2];
```

#### Se for necessário passar uma matriz de ponteiros para uma função, pode ser usado o mesmo método que e utilizado para passar o outras matrizes.

``` c
void display_array(int *q[]) 
{
 int t;
 for(t = 0; t < 10; t++) {
	 printf("%d", *q[t]);
 }
}
```



