# Percursos em Árvores

Os percursos em árvores são métodos para percorrer e visitar todos os nós de uma árvore em uma ordem específica.

Existem três principais formas de percurso em árvores:

1. **Pré-ordem (preorder):** Neste método, o nó raiz é visitado primeiro, seguido pela visita dos nós filhos da esquerda para a direita recursivamente. É útil para criar uma cópia da árvore ou para imprimir a expressão em notação polonesa (prefixa).

2. **Em ordem (inorder):** Neste método, os nós filhos da esquerda são visitados primeiro, seguidos pela visita do próprio nó raiz, e então os nós filhos da direita são visitados. É comumente utilizado para visitar os nós de uma árvore de busca binária em ordem crescente.

3. **Pós-ordem (postorder):** Neste método, os nós filhos da esquerda são visitados primeiro, seguidos pelos nós filhos da direita, e então o próprio nó raiz pe visitado por último. É útil para liberar a memória associada aos nós da árvore.

Esses percursos são implementados de forma recursiva ou iterativa e são fundamentais para muitos algoritmos que operam em árvores, como busca, inserção, remoção e balanceamento. Cada método de percurso tem suas aplicações específicas, dependendo do problema a ser resolvido.
