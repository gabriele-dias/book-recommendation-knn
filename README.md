# Sistema-de-recomenda-o-com-dados-de-livros
Sistema de recomendação usando Python e o algoritmo KNN. O projeto trata dados reais, utiliza Matrizes Esparsas para otimização de memória e entrega uma galeria visual via Plotly.  ✅ EDA &amp; Limpeza ✅ Sklearn (Similaridade de Cosseno) ✅ Visualização Dinâmica de Capas  #DataScience #Python #ML
📚 Machine Learning: Sistema de Recomendação de Livros
Este projeto consiste no desenvolvimento de um sistema de recomendação inteligente utilizando técnicas de Aprendizado Não Supervisionado. O objetivo é criar um motor que sugira novos títulos para usuários com base em seus gostos literários, simulando a experiência de grandes plataformas como a Amazon.

🚀 Tecnologias Utilizadas
Para este desafio, utilizei o ecossistema de Ciência de Dados do Python:

Manipulação e Tratamento: Pandas e Numpy.

Visualização: Matplotlib, Seaborn e Plotly.

Processamento Científico: Scipy (uso de Matrizes Esparsas/CSR).

Machine Learning: Sklearn (Algoritmo KNN - K-Nearest Neighbors).

Manipulação de Imagens: Requests e Pillow.

🧠 Desafios Técnicos e Soluções
Gestão de Memória: O processamento de grandes bases de dados (como o dataset de 314MB utilizado) foi otimizado através de Matrizes Esparsas, evitando erros de estouro de memória RAM.

Ambiente de Desenvolvimento: O projeto foi adaptado do Google Colab para ser executado localmente no VS Code, demonstrando controle total sobre o ambiente e dependências.

Interface Visual: Além do modelo matemático, implementei uma galeria dinâmica que busca as capas dos livros via URL para uma apresentação intuitiva dos resultados.

📋 Etapas do Projeto
EDA (Análise Exploratória): Cruzamento de bases de dados de livros, usuários e avaliações.

Modelagem: Implementação do KNN com métrica de Similaridade de Cosseno.

Validação: Cálculos manuais para entendimento da vizinhança do algoritmo.

Relatório Visual: Galeria interativa com as recomendações finais.

👩‍💻 Como utilizar
Clone o repositório.

Instale as dependências listadas nos notebooks.

Execute o arquivo Machine_learning.ipynb para ver o modelo em ação.
