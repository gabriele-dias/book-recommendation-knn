# 📚 Sistema de Recomendação de Livros: Inteligência Artificial com KNN

Este repositório contém um sistema de recomendação de livros desenvolvido em **Python**. O projeto utiliza algoritmos de **Aprendizado Não Supervisionado** para identificar padrões de leitura e sugerir obras com base na similaridade entre usuários e títulos.

---

## 🚀 O que este projeto faz?
O sistema analisa uma base histórica de avaliações de leitores e, ao receber o título de um livro, o "robô" identifica quais outros livros possuem o perfil mais próximo. O diferencial deste projeto é a saída visual: além dos nomes, o sistema renderiza uma galeria com as capas dos livros recomendados.

---

## 🧠 O Coração do Projeto: O que é o KNN?
O **KNN (K-Nearest Neighbors)**, ou Vizinhos Mais Próximos, é um algoritmo de Machine Learning que funciona por **proximidade geográfica numérico**. 

1. **Vetorização**: O robô transforma cada livro em um ponto em um gráfico multidimensional.
2. **Cálculo de Distância**: Quando você escolhe um livro, o robô calcula a **Similaridade de Cosseno** para medir a distância entre esse ponto e todos os outros.
3. **Recomendação**: Ele seleciona os $K$ vizinhos que estão mais perto (os mais similares) e os apresenta como sugestão.

---

## 🛠️ Explicando o Código (Passo a Passo)
O projeto foi dividido em notebooks para facilitar a organização:
* **EDA (Análise Exploratória)**: Onde os dados brutos são limpos e filtrados para remover usuários com poucas avaliações, garantindo que o modelo não seja "poluído" por dados irrelevantes.
* **Modelagem (KNN)**: Aqui os dados são convertidos em uma **Matriz Esparsa (CSR)**. Isso é vital para que o computador não trave ao processar arquivos grandes (como o de 314MB utilizado aqui).
* **Visualização**: Implementação do **Plotly** e **Pillow** para buscar URLs de imagens e criar a galeria de recomendações.

---

## 📊 Onde obter os dados?
Para reproduzir este projeto, utilize o dataset **Book-Crossing**, disponível no Kaggle:
👉 [Link para o Dataset no Kaggle](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)
*(Nota: Devido ao limite de tamanho do GitHub, as bases de dados originais .csv não estão inclusas neste repositório)*

---

## 💼 Quem usa essa tecnologia?
Sistemas de recomendação são o motor de lucro das maiores empresas de tecnologia do mundo:
* **Amazon**: "Quem comprou este item também comprou...".
* **Netflix/Spotify**: Para sugerir o próximo filme ou música com base no seu histórico.
* **Instagram/TikTok**: Para decidir qual post aparecerá no seu "Explorar".

---

## 📈 Aprendizados para o Futuro
Este projeto consolidou competências essenciais para uma carreira em Dados:
* **Gestão de Hardware**: Aprendi a otimizar a memória RAM usando matrizes matemáticas em vez de carregar tabelas brutas.
* **Autonomia Profissional**: Adaptei um projeto acadêmico da **Udemy** para uma ferramenta de mercado (**VS Code**).
* **Storytelling com Dados**: Transformei cálculos complexos em uma galeria visual compreensível para qualquer usuário.

---
 Machine Learning, KNN, Python, Ciência de Dados, Sistemas de Recomendação, Matrizes Esparsas, VS Code.
