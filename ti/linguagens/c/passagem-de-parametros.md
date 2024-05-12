# Diferença entre passagem de parâmetros por valor e por referência com exemplos em linguagem C

Em C, passagem por valor significa que uma cópia do valor do argumento é passada para a função. Já na passagem por referência, o endereço de memória do argumento é passado para a função, permitindo que a função modifique o valor original da variável fora da função.

Exemplo de passagem por valor:


```
# include <stdio.h>

void increment (int num) {
    num++;
}

int main(){
    int x =  5;
    increment(x);
    printf('o valor de x após a chamada da função é: %d\n', x);
    return 0;
}
```

