#### Matrizes dimensionais são armazenadas em uma matriz linha-coluna, onde o primeiro índice indica a linha e o segundo, a coluna. Isso significa que o índice mais a direita varia mais rapidamente do que o mais a esquerda quando acessamos os elementos da matriz na ordem em que eles estão realmente armazenados na memoria.

![[c-multimensionalimages.png]]


#### No caso de uma matriz bidimensional, a seguinte formula fornece o numero de bytes de memoria para armazena-la: 

``` bash
bytes = tamanho do 1*indice * tamanho do 2*indice  * sizeof(tipo base)
```

Quando usada como argumento para uma funcao, apenas o primeiro elemento e realmente passado porem uma funcao que recebe ujma matriz bidimensional como parametro deve definir pelo menis o comprimento da segunda dimensao.
Por exemplo uma matriz com dimensoes 10,10 seria declarada desta forma:


``` C
void func1(int x[][10]) {
.
.
.
}
```


