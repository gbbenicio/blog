# Alocação de Memória

A alocação de memória é um processo fundamental na programação de computadores, responsável por reservar e gerenciar espaço de memória do sistema para armazenar dados e instruções. É crucial para o bom funcionamento dos programas, otimizando o uso de recursos e evitando conflitos de memória.

## Tipos de Alocação

- **Estática**
  - Tamanho fixo predefinido em tempo de compilação.
  - Eficiente em termos de espaço, mas menos flexível.
  - Exemplos: variáveis globais, arrays.
 
- **Dinâmica**
  - Tamanho variável definido em tempo de execução.
  - Mais flexível, mas pode levar à fragmentação de memória.
  - Exemplos: malloc, calloc, new(C++)
 
## Gerenciamento de Memória

- **Alocadores de Memória**
  - Responsáveis por reservar e liberar memória dinamicamente.
  - Implementam diferentes algoritmos para otimizar o uso da memória.
  - Exemplos: malloc, calloc, realloc, free (C), new, delete (C++).
 
- **Coleta de Lixo**
  - Automatiza a liberação de memória em linguagens como Java e Python.
  - Libera memória que não está mais sendo utilizada pelo programa.
 
## Problemas Comuns

- **Fragmentação de Memória**
  - Ocorre quando a memória é dividida em pequenos blocos não contíguos.
  - Pode reduzir a eficiência do uso da memória.
 
- **Vazamentos de memória**
  - Ocorrem quando a memória alocada dinamicamente não é liberada quando não é mais necessária.
  - Pode levar ao esgotamento da memória e à falha do programa. 
