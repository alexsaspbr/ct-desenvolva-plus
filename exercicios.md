## 📝 Sessão de Exercícios – Algoritmos de Ordenação (Nível Iniciante)

### **1. Qual algoritmo de ordenação é mais eficiente para listas quase ordenadas?**

<p>a) Selection Sort</p>
<p>b) Heap Sort</p>
<p>c) Insertion Sort</p>
<p>d) Quick Sort</p>

---

### **2. Qual algoritmo abaixo sempre terá a mesma complexidade no pior e melhor caso?**

<p>a) Quick Sort</p>
<p>b) Heap Sort</p>
<p>c) Insertion Sort</p>
<p>d) Selection Sort</p>

---

### **3. Qual algoritmo utiliza a estratégia “divide e conquista”?**

<p>a) Insertion Sort</p>
<p>b) Merge Sort</p>
<p>c) Heap Sort</p>
<p>d) Selection Sort</p>

---

### **4. Qual algoritmo faz o menor número de trocas, mesmo com alto custo de comparações?**

<p>a) Selection Sort</p>
<p>b) Quick Sort</p>
<p>c) Merge Sort</p>
<p>d) Heap Sort</p>

---

### **5. O algoritmo Quick Sort tem pior desempenho quando:**

<p>a) Os elementos já estão ordenados</p>
<p>b) O tamanho da lista é pequeno</p>
<p>c) Todos os elementos são iguais</p>
<p>d) Os elementos estão em ordem aleatória</p>

---

### **6. Uma Priority Queue é mais comumente implementada com qual estrutura?**

<p>a) Lista encadeada</p>
<p>b) Fila comum</p>
<p>c) Heap binário</p>
<p>d) Árvore AVL</p>

---

### **7. Qual dos seguintes algoritmos NÃO é estável?**

<p>a) Merge Sort</p>
<p>b) Insertion Sort</p>
<p>c) Selection Sort</p>
<p>d) Bubble Sort</p>

---

### **8. Qual algoritmo é mais indicado para ordenar dados que estão armazenados em disco (fora da memória RAM)?**

<p>a) Quick Sort</p>
<p>b) Selection Sort</p>
<p>c) Merge Sort</p>
<p>d) Insertion Sort</p>

---

## ✅ Gabarito e Comentários

| Questão | Resposta Correta | Comentário                                                                 |
|---------|------------------|----------------------------------------------------------------------------|
| 1       | c) Insertion Sort | Muito eficiente com listas quase ordenadas (O(n) no melhor caso)          |
| 2       | b) Heap Sort      | Sempre O(n log n), independente do estado inicial                         |
| 3       | b) Merge Sort     | Divide a lista e conquista com recursão e mesclagem                       |
| 4       | a) Selection Sort | Apenas O(n) trocas, ideal onde o custo de troca é alto                    |
| 5       | a) Já estão ordenados | Quick Sort pode cair em O(n²) nesse caso sem pivô otimizado         |
| 6       | c) Heap binário   | Priority Queues geralmente são implementadas com heaps                    |
| 7       | c) Selection Sort | Não é estável, pois pode trocar elementos iguais de lugar                 |
| 8       | c) Merge Sort     | Ideal para ordenação externa (arquivos grandes fora da memória principal) |
