# 📘 Aula: Algoritmos de Ordenação – Fundamentos e Aplicações

## 🌟 Objetivo da Aula
Ensinar os principais algoritmos de ordenação, explicando seu funcionamento, análise de complexidade, vantagens e desvantagens, aplicações práticas e sistemas reais que os utilizam.

---

## 📌 Conteúdo Programático

1. Introdução à ordenação
2. Insertion Sort
3. Selection Sort
4. Merge Sort
5. Quick Sort
6. Heap Sort
7. Priority Queue como estrutura de ordenação
8. Comparativo entre algoritmos
9. Casos de uso reais detalhados
10. Recursos visuais
11. Quiz: Qual algoritmo escolher?
12. Referências

---

## 1. 🧭 Introdução à Ordenação

A ordenação é o processo de organizar dados em uma sequência (crescente ou decrescente). Fundamental para:

- Melhorar a eficiência de buscas
- Otimizar algoritmos dependentes de ordem
- Facilitar análise e visualização

---

## 2. 📥 Insertion Sort

- **Funcionamento**: Insere cada elemento na posição correta, como se fossem cartas na mão.
- **Complexidade**:
  - Melhor caso: O(n)
  - Pior caso: O(n²)
- **Prós**: Simples, bom para listas pequenas
- **Contras**: Ineficiente para grandes volumes

**Casos de uso reais**:
- Sugestão de texto em IDEs
- TimSort (usado em Android e Python)

![Insertion Sort](https://upload.wikimedia.org/wikipedia/commons/0/0f/Insertion-sort-example-300px.gif)

---

## 3. 🔽 Selection Sort

- **Funcionamento**: Seleciona o menor elemento e coloca na primeira posição.
- **Complexidade**: Sempre O(n²)
- **Prós**: Poucas trocas
- **Contras**: Ineficiente mesmo em melhores casos

**Casos de uso reais**:
- Dispositivos com EEPROM
- Ensino de algoritmos

![Selection Sort](https://upload.wikimedia.org/wikipedia/commons/9/94/Selection-Sort-Animation.gif)

---

## 4. 🔀 Merge Sort

- **Funcionamento**: Divide a lista em partes menores, ordena e mescla.
- **Complexidade**: O(n log n) em todos os casos
- **Prós**: Estável, eficiente em grandes dados
- **Contras**: Usa memória adicional

**Casos de uso reais**:
- Hadoop, Spark
- PostgreSQL (JOIN, ORDER BY)
- Java (`Collections.sort()`)

![Merge Sort](https://upload.wikimedia.org/wikipedia/commons/c/cc/Merge-sort-example-300px.gif)

---

## 5. ⚡ Quick Sort

- **Funcionamento**: Escolhe um pivô, divide menores/maiores, aplica recursivamente
- **Complexidade**:
  - Média: O(n log n)
  - Pior: O(n²)
- **Prós**: Muito rápido na prática
- **Contras**: Não é estável

**Casos de uso reais**:
- Python (`sort`)
- `qsort()` da linguagem C
- Backends de APIs ordenando resultados

![Quick Sort](https://upload.wikimedia.org/wikipedia/commons/6/6a/Sorting_quicksort_anim.gif)

---

## 6. ⛰️ Heap Sort

- **Funcionamento**: Constrói heap (árvore binária) e extrai ordenado
- **Complexidade**: Sempre O(n log n)
- **Prós**: Uso constante de memória
- **Contras**: Não é estável

**Casos de uso reais**:
- BI Tools (PowerBI, Tableau)
- Equipamentos embarcados
- Sistemas críticos

![Heap Sort](https://upload.wikimedia.org/wikipedia/commons/4/4d/Heapsort-example.gif)

---

## 7. 🧺 Priority Queue

- **Funcionamento**: Inserção e remoção baseada em prioridade (usualmente com heap)
- **Operações**:
  - Inserção: O(log n)
  - Remoção: O(log n)

**Casos de uso reais**:
- Sistemas operacionais (agendamento de processos)
- Algoritmos de IA (A* em jogos)
- Redes (QoS em roteadores)

---

## 8. ⚖️ Comparativo Geral

| Algoritmo       | Média       | Estável | In-place | Melhor caso | Pior caso |
|----------------|-------------|---------|----------|--------------|------------|
| Insertion Sort | O(n²)       | Sim     | Sim      | O(n)         | O(n²)      |
| Selection Sort | O(n²)       | Não     | Sim      | O(n²)        | O(n²)      |
| Merge Sort     | O(n log n)  | Sim     | Não      | O(n log n)   | O(n log n) |
| Quick Sort     | O(n log n)  | Não     | Sim      | O(n log n)   | O(n²)      |
| Heap Sort      | O(n log n)  | Não     | Sim      | O(n log n)   | O(n log n) |

---

## 9. 🔄 Casos de Uso Combinados

| Sistema / Tecnologia         | Algoritmo(s) Aplicado(s)            | Justificativa Técnica                                                                 |
|-----------------------------|-------------------------------------|----------------------------------------------------------------------------------------|
| Android Runtime (ART)       | TimSort (Insertion + Merge Sort)    | Ótimo desempenho com dados parcialmente ordenados                                     |
| PostgreSQL / MySQL          | Merge Sort, Heap, Priority Queue    | Join, Sort, agendamento de planos de execução                                         |
| Google Maps / Waze          | Priority Queue                      | Caminho mais curto com A*                                                             |
| Spark / Hadoop              | Merge Sort                          | Ordenação de arquivos grandes (em disco)                                              |
| Jogos de estratégia (RTS)   | Priority Queue                      | Execução de ações em tempo real com base em prioridade                                |
| PowerBI / Tableau           | Heap Sort, Merge Sort               | Ordenação de dados de dashboards com muitos registros                                 |

---

## 10. 📺 Recursos Visuais

- [Visualgo.net](https://visualgo.net/en/sorting) – Animações interativas de algoritmos
- GIFs utilizados são de domínio público via Wikipedia Commons

---

## 11. 🎯 Quiz: Qual Algoritmo Usar?

1. Dados quase ordenados? → **Insertion Sort**
2. Muitos registros em disco? → **Merge Sort**
3. Alta performance com pouca memória? → **Quick Sort**
4. Lista pequena com escrita cara? → **Selection Sort**
5. Precisa extrair elementos por prioridade? → **Priority Queue**
6. Ambientes embarcados previsíveis? → **Heap Sort**

---

## 12. 🔗 Referências

### Livros
- *Introduction to Algorithms* – Cormen, Leiserson, Rivest, Stein (CLRS)
- *Estruturas de Dados e Algoritmos em Java* – Robert Lafore

### Artigos e Sites
- [GeeksforGeeks](https://www.geeksforgeeks.org/sorting-algorithms/)
- [Khan Academy](https://pt.khanacademy.org/computing/computer-science/algorithms)
- [Wikipedia: Sorting Algorithms](https://en.wikipedia.org/wiki/Sorting_algorithm)
- [Oracle Docs - Java Sorting](https://docs.oracle.com/javase/8/docs/api/java/util/Collections.html)

### Videos

- [Insertion Sort](https://www.youtube.com/watch?v=7GUwzd_h3pI&list=PLldrzuO43P_zNudi9VTp3RDPDBRbaWW6b&index=4)
- [Selection Sort](https://www.youtube.com/watch?v=pDY2rGdsYAE&list=PLldrzuO43P_zNudi9VTp3RDPDBRbaWW6b&index=5)
- [Merge Sort](https://www.youtube.com/watch?v=BnsYGiYYdnQ&list=PLldrzuO43P_zNudi9VTp3RDPDBRbaWW6b&index=7)
- [Quick Sort](https://www.youtube.com/watch?v=WP7KDljG6IM&list=PLldrzuO43P_zNudi9VTp3RDPDBRbaWW6b&index=6)
- [Heap Sort](https://www.youtube.com/watch?v=bXwCZj1xipY)
- [Heap & Priority Queue](https://www.youtube.com/watch?v=HqPJF2L5h9U&t=2820s)