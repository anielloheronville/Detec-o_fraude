Dashboard de Detecção de Fraudes com Machine Learning e Streamlit

📖 Descrição do Projeto

Este projeto implementa uma solução de ponta a ponta (end-to-end) para a detecção de fraudes em transações de cartão de crédito. O objetivo é ir além da simples análise de dados, construindo um pipeline completo que inclui:

Limpeza e preparação de dados.

Treinamento e otimização de modelos de Machine Learning.

Criação de um dashboard web interativo para análise e previsões em tempo real.

O projeto utiliza um dataset anonimizado contendo transações financeiras e aplica técnicas avançadas para identificar padrões e prever com alta precisão quais transações são provavelmente fraudulentas.

✨ Principais Funcionalidades

Limpeza de Dados Robusta: Scripts para tratar dados mal formatados, garantindo a qualidade e integridade das informações para o modelo.

Treinamento de Modelos: Implementação e comparação entre RandomForest e LightGBM, um poderoso algoritmo de Gradient Boosting.

Otimização de Hiperparâmetros: Uso do RandomizedSearchCV para encontrar a melhor configuração para o modelo, maximizando sua performance.

Dashboard Interativo com Streamlit: Uma aplicação web com três seções principais:

Visão Geral: Métricas chave sobre o conjunto de dados.

Análise Exploratória: Gráficos interativos para explorar a distribuição dos dados.

Previsão de Fraude: Uma ferramenta para inserir dados de uma nova transação e receber uma previsão de fraude em tempo real, junto com a probabilidade.

Deploy do Modelo: O modelo treinado e o scaler são salvos em arquivos (.joblib e .pkl), simulando um ambiente de produção onde podem ser carregados e utilizados pela aplicação.

🚀 Demo do Dashboard

(Dica: Tire um print da sua aplicação rodando e substitua o link abaixo pela imagem)

🛠️ Tecnologias Utilizadas
Linguagem: Python 3.9+

Bibliotecas de Dados e ML: Pandas, Scikit-learn, LightGBM, Joblib, Pickle

Dashboard e Visualização: Streamlit, Plotly Express, Seaborn
