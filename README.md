# Projeto Python IA: Inteligência Artificial e Previsões 🤖

### Case: Score de Crédito dos Clientes

## 📋 Descrição do Projeto

Este projeto foi desenvolvido para ajudar um banco a definir automaticamente o **score de crédito** de seus clientes com base em suas informações. O modelo de inteligência artificial classifica o score de crédito em três categorias: **Ruim**, **Ok**, e **Bom**. Essa classificação é crucial para o banco ao avaliar o risco de concessão de crédito e tomar decisões mais informadas.

## 🎯 Objetivo

O principal objetivo é construir um modelo preditivo que possa analisar os dados dos clientes e prever o score de crédito automaticamente. A solução permitirá ao banco uma avaliação mais ágil e precisa dos clientes.

## 📂 Estrutura do Projeto

```bash
├── clientes.csv              # Dados dos clientes existentes
├── novos_clientes.csv         # Dados dos novos clientes para prever o score
├── score_analysis.ipynb       # Notebook contendo o código do projeto
└── README.md                  # Este arquivo
```

## 🛠️ Bibliotecas Utilizadas

- **Pandas**: Para manipulação e análise dos dados.
- **Scikit-learn**: Utilizada para pré-processamento dos dados, construção e avaliação dos modelos de machine learning.
- **LabelEncoder**: Para conversão de variáveis categóricas em numéricas.
- **Random Forest Classifier**: Um dos modelos utilizados para prever o score de crédito.
- **K-Nearest Neighbors (KNN)**: Outro modelo utilizado para fazer as previsões.

## 📊 Metodologia

1. **Carregamento e Limpeza dos Dados**: Os dados foram carregados de um arquivo CSV e tratados para remover valores nulos ou incorretos. Também foi necessário transformar variáveis categóricas (como profissão) em números, utilizando técnicas de pré-processamento.
   
2. **Divisão de Dados**: Os dados foram divididos em duas partes: **treinamento** e **teste**. Isso permite avaliar o desempenho do modelo em dados que ele não viu durante o treinamento.

3. **Treinamento dos Modelos**: Dois modelos foram treinados:
   - **Random Forest**: Um modelo baseado em árvores de decisão que combina múltiplas árvores para aumentar a precisão.
   - **KNN (K-Nearest Neighbors)**: Um algoritmo baseado em proximidade que classifica os dados com base nos vizinhos mais próximos.

4. **Avaliação e Previsão**: Após o treinamento, o modelo foi avaliado em uma base de dados de teste, para verificar sua precisão. Além disso, novos clientes podem ser analisados através do modelo para prever seus scores de crédito.

## 📈 Resultados e Conclusão

O modelo desenvolvido consegue classificar com precisão o **score de crédito** dos clientes com base em características como profissão, renda, histórico de pagamento, entre outros fatores. A capacidade de automatizar essa análise oferece ao banco uma vantagem significativa, permitindo decisões mais rápidas e embasadas.

## 📊 Aplicações Futuras

O modelo pode ser ampliado para incorporar mais dados, como histórico de crédito e comportamento de uso de serviços financeiros, além de ser ajustado com mais algoritmos e técnicas avançadas, como **Deep Learning**, para melhorar ainda mais a acurácia.
