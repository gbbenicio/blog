# Alocação Sequencial
É o armazenamento de dados de forma sequencial na memória do computador. Isto quer dizer que as posições da memória ocupadas serão contíguas.

Na alocação sequencial o programa precisa informar **previamente todo o tamanho da memória** que será necessário.

A alocação sequencial é representada por **arrays** ou **vetores**.

# Vetor (Array)

Vetor ou array é uma estrutra de dados que armazena uma coleção de elementos do **mesmo tipo**, onde cada elemento é acessado através de um **índice numérico**.

Implementação em Linguagem C:

Abaixo o código para um vetor(array):

```sh
int vetor[10];
```
Informa ao compilador que deverão ser reservadas posições de memória suficientes para armazenar 10 elementos do tipo inteiro.

Atenção: Posição de memória ≠ Tamanho  
O número de posições necessárias depende do tamanho do tipo de dado e da palavra da memória.

Código:

```sh
int main()
{
    int vetor[10];
    int a = 50;
    vetor[3] = a;
    return 0;
}
```
Visualização da execução do código:

![Visualização do código em C](alocacao-sequencial-em-c.png)

1. Foi criado um vetor(array) com 10 posições para elementos do tipo inteiro e o valor 50 foi armazenado na 4ª posição, elemento com índice 3.  
2. A variável `a` do tipo inteiro recebeu, por operação de atribuição, o valor 50. 
