#### Para criar uma matriz de strings, usa-se uma matriz bidimensional de caracteres. O tamanho do índice esquerdo indica o numero de strings e o tamanho do índice direito indica o comprimento máximo de cada string 

``` C
char str_arr[40][80];
```

#### Text Editor

``` C
#include <stdio.h>

#define MAX 100
#define LEN 80

char text[MAX][LEN];

/* SIMPLE TEXT EDITOR */

void main()
{
  register int t, i, j;

  printf("Digite uma linha vazia para sair \n");
  for(t = 0; t < MAX; t++) {
    printf("%d: \n", t);
    scanf("%s", text[t]);

    if(!*text[t]) {
      break;
    }
  }

  for(i = 0; i < t; i++) {
    for(j = 0; text[i][j]; i++) {
      putchar(text[i][j]);
    }

    putchar('\n');
  }
}
```

