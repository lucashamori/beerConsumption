# Previsão do Consumo de Cerveja com Regressão Linear

Este projeto tem como objetivo prever o consumo médio de cerveja em São Paulo utilizando um modelo de Regressão Linear. Baseado em variáveis climáticas e comportamentais, como temperatura, chuva e finais de semana, o modelo busca identificar padrões e oferecer predições precisas para apoiar tomadas de decisões relacionadas ao consumo.

---

## Objetivo
Desenvolver um modelo preditivo que estime o consumo médio de cerveja (em litros) com base em dados históricos e variáveis explicativas.

---

## Dataset

- Fonte: [Beer Consumption São Paulo - Kaggle](https://www.kaggle.com/dongeorge/beer-consumption-sao-paulo)
- **Período**: Ano de 2015
- **Localidade**: São Paulo (região universitária)
- **Público**: Indivíduos entre 18 e 28 anos

### Metadados
- **data**: Data da coleta
- **temp_media**: Temperatura Média (°C)
- **temp_min**: Temperatura Mínima (°C)
- **temp_max**: Temperatura Máxima (°C)
- **chuva**: Precipitação (mm)
- **fds**: Final de Semana (1 = Sim; 0 = Não)
- **consumo**: Consumo de Cerveja (litros)

---

## Metodologia

### 1. Análise Exploratória dos Dados (EDA)
- Verificação de inconsistências e valores ausentes.
- Análise das distribuições e relações entre variáveis.
- Visualizações com **Seaborn** e **Matplotlib** para explorar padrões nos dados.

### 2. Engenharia de Dados
- Normalização e transformação de variáveis.
- Criação de features derivadas para melhorar a performance do modelo.

### 3. Treinamento do Modelo
- Algoritmo utilizado: Regressão Linear.
- Métricas de Avaliação: **R² Score**, **RMSE** e **MAE**.

### 4. Validação
- Divisão do dataset em dados de treino e teste.
- Ajuste de hiperparâmetros e avaliação de desempenho com dados não vistos.

---

## Resultados
- O modelo apresentou **R² = 0.75**, indicando uma forte capacidade explicativa.
- Visualizações comparando valores reais e previstos mostraram boa aderência.
- Análise revelou que a temperatura média e finais de semana têm maior impacto no consumo.

### Gráficos Incluídos
- Correlação entre variáveis.
- Erros de predição.
- Comparativo entre valores reais e previstos.

---

## Requisitos
- **Linguagem**: Python 3.8+
- **Bibliotecas**:
  - Pandas
  - Numpy
  - Matplotlib
  - Seaborn
  - Scikit-learn

---
