* **Listas (`list`):** Coleções ordenadas e mutáveis [2, 3]. Cada elemento é acessado por um índice numérico de base zero [3]. Suportam métodos como `.append()` (adicionar ao final) [1, 3], `.insert()` (inserir em posição específica) [1, 3] e `.pop()` / `.remove()` (remoção de elementos) [1, 3]. Podem armazenar elementos heterogêneos [3].
* **Tuplas (`tuple`):** Sequências ordenadas e imutáveis [2, 3]. Não podem ter seus elementos alterados após a criação [2, 3]. São delimitadas por parênteses e recomendadas para conjuntos de dados fixos (como dias da semana ou coordenadas) [3].
* **Dicionários (`dict`):** Estruturas de memória associativa compostas por pares de `chave: valor` [1, 4]. As chaves devem ser únicas e imutáveis [1, 4]. Métodos úteis incluem `.keys()` (chaves) [4] e `.values()` (valores) [4].
* **Conjuntos (`set`):** Coleções não ordenadas de elementos únicos [1, 2]. Eliminam duplicatas automaticamente e oferecem operações matemáticas de união e interseção [1, 2].

### 2. Glossário de Conceitos

* **Mutabilidade:** Capacidade de uma estrutura de dados ser alterada (adicionar, remover ou modificar itens) após ter sido criada em memória [3].
* **Indexação:** Forma de acessar um valor específico dentro de uma sequência usando sua posição numérica (ex: `lista`) [3].
* **KeyError:** Exceção levantada em Python ao tentar acessar uma chave que não existe dentro de um dicionário [1, 4].
* **List Comprehension:** Sintaxe concisa em Python para criar novas listas aplicadas a iteráveis existentes [1].

### 3. Prompts Reutilizáveis para Revisão

```text
1. "Explique a diferença entre usar o método .pop() e a instrução del ao remover elementos de um dicionário em Python."
2. "Crie 3 exercícios práticos envolvendo ordenação de listas e contagem de itens duplicados com conjuntos (sets)."
3. "Como posso usar list comprehensions para filtrar números pares em uma lista de inteiros?"
