### Um ponteiro e uma variável que armazena um endereço de memoria

##### tipo * nome

### Operadores de Ponteiros
#### & Operador unário que retorna o endereço da memoria do seu operando

``` c
m = &count;
```

#### * Operador unário que retorna o valor da variável localizada no endereço

``` c
q = *m;
```


### Aritmética de ponteiros

#### Existem apenas duas operações aritméticas que podem ser usadas com ponteiros: adição e subtração. Para entender o que ocorre na aritmética de ponteiros, consideremos p1 um ponteiro para um inteiro com o valor atual 2000. Assuma,também, que os inteiros são de 2 bytes

``` c
p1++
p1--
```

#### A aritmética de ponteiros não esta limitada apenas ao incremento e ao decremento, também se pode somar e subtrair inteiros de ponteiros

``` c
p1 = p1 + 12;
```

#### Isso faz com que *p1*  aponte para o 12 elemento do ponteiro.

*Nota*
o índice de Arrays começam em 0


![[aritmeticaponteiros.png]]

### Comparação de ponteiros
#### E Possível comparar ponteiros em uma expressa relacional

``` C
if(p < q){
	printf("p Aponta para uma memoria mais baixa que q \n");
}
```
#### Geralmente são usadas quando dois ponteiros apontam para um objeto em comum.


[[Ponteiros de funções]]