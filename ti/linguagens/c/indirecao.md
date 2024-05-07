# Indireção

Em linguagem C, a indireção é o processo de acessar o valor de uma variável usando um ponteiro que aponta para ela. Em outras palavras, indireção ocorre quando você utiliza um ponteiro para ler ou modificar o valor de uma variável. O operador de indireção em C é o operador de desreferenciamento (`*`).

Aqui está um exemplo para ilustrar a indireção em C:

```c
int x = 10; // Uma variável de tipo inteiro
int *ptr = &x; // Um ponteiro para 'x'

/* Acesso indireto ao valor de 'x' usando o ponteiro 'ptr' */
int valor = *ptr; // valor agora é igual a 10

/* Modificando o valor de 'x' usando o ponteiro 'ptr' */
*ptr = 20; // Agora 'x' é igual a 20
```

No exemplo, `int *ptr = &x;` cria um ponteiro `ptr` que aponta para a variável `x`. Em seguida, `int valor = *ptr;` acessa o valor de `x` usando o ponteiro `ptr` e o armazena na variável `valor`. Por fim, `*ptr = 20;` modifica o valor de `x` para 20, usando o ponteiro `ptr`.

Portanto, indireção é o acesso ou modificação do valor de uma variável através de um ponteiro que aponta para ela.