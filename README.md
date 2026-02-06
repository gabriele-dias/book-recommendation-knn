# 📚 Sistema de Recomendação de Livros: Inteligência Artificial com KNN

Este projeto desenvolve um motor de recomendação inteligente baseado em **Aprendizado Não Supervisionado**. O sistema analisa o comportamento de milhares de leitores para sugerir novos títulos de forma personalizada, utilizando o algoritmo KNN.

---

## 🎓 Origem e Diferencial Técnico (Udemy + VS Code)
Este projeto foi inicialmente baseado no curso de Machine Learning da **Udemy**. No entanto, realizei adaptações fundamentais para elevar o nível técnico da solução:
* **Migração de IDE**: O código foi adaptado do Google Colab para execução local no **VS Code**, exigindo a gestão de ambientes virtuais (`.venv`) e dependências.
* **Otimização para Big Data**: Implementei o uso de **Matrizes Esparsas (CSR)** para processar datasets volumosos, solucionando erros de memória comuns em execuções locais.

---

## 🧠 Como o "Robô" Funciona?
O **KNN (K-Nearest Neighbors)** funciona através da **Similaridade de Cosseno**:
1. Cada livro é transformado em um vetor numérico em um espaço multidimensional.
2. O algoritmo calcula a "distância" matemática entre o livro escolhido e os demais na base.
3. Os vizinhos com a menor distância são selecionados e apresentados como recomendação.

---

## 🛠️ Tecnologias Utilizadas
* **Manipulação de Dados**: `Pandas` e `Numpy`.
* **Visualização**: `Matplotlib`, `Seaborn` e `Plotly` (Galeria Interativa).
* **Processamento**: `Scipy` (Matrizes Esparsas).
* **Machine Learning**: `Sklearn` (Algoritmo KNN).

---

## 📊 Base de Dados (Kaggle)
Devido ao tamanho dos arquivos (acima de 25 MB), o dataset completo e os arquivos processados estão disponíveis no meu perfil do Kaggle:
👉 **[Clique aqui para acessar os Dados no Kaggle](https://www.kaggle.com/datasets/gabrielem41/sistema-de-recomendao-de-livros-com-knn)**

---

## 💼 Aplicações no Mercado
Sistemas de recomendação são essenciais para a personalização e retenção de usuários em gigantes como **Amazon**, **Netflix** e **Spotify**.

---

##
