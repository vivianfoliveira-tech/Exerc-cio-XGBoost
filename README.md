# Previsao de Compra de Veiculos com XGBoost

Este projeto utiliza Machine Learning para prever se um cliente tem probabilidade de comprar um carro, com base em características simples como idade, salario anual e gênero. A ideia é transformar dados demográficos em inteligência acionável para equipes comerciais.

A base utilizada com 1.000 clientes e aplicação do XGBoost como modelo de classificação. O pipeline incluiu limpeza de dados, encoding de variáveis categóricas, análise de correlação, treinamento do modelo com hyperparametros ajustados e avaliação completa com matriz de confusão e classification report.

A análise revelou que a idade é o fator mais determinante na decisão de compra, seguida pelo salario anual, enquanto o genero tem influência quase irrelevante. O ranking de feature importance do XGBoost confirmou exatamente a mesma ordem observada na correlação linear, mas com o modelo capturando relações não-lineares que a correlação simples não detecta.

**Tecnologias:** Python, XGBoost, Pandas, Scikit-learn, Seaborn, Matplotlib.
