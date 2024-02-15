# Previsão de Renda com Regressão Linear

Este projeto visa desenvolver um modelo de regressão para prever a `renda` com base em várias características preditivas. Utilizamos um conjunto de dados contendo informações como tempo de emprego, nível educacional, e outras variáveis socioeconômicas.

## Descrição do Projeto

O objetivo do projeto é explorar diferentes técnicas de pré-processamento de dados, seleção de variáveis e modelagem para construir um modelo robusto que possa prever com precisão a `renda`. 

### Etapas do Projeto

1. **Pré-processamento de Dados**
   - Limpeza de dados, incluindo a remoção de variáveis irrelevantes e o tratamento de valores ausentes.

2. **Análise Exploratória de Dados (EDA)**
   - Investigação das relações entre variáveis usando gráficos e estatísticas descritivas.
   - Aplicação de transformações, como a logaritma, para normalizar as distribuições e facilitar análises lineares.

3. **Seleção de Variáveis**
   - **Transformação Polinomial**: Criamos termos polinomiais para `tempo_emprego` para capturar relações não lineares com `renda`.
   - **Eliminação Recursiva de Atributos (RFE)**: Utilizamos RFE com um modelo de regressão linear para selecionar as 10 variáveis mais importantes.

4. **Modelagem e Avaliação**
   - Ajuste de modelos de regressão linear, incluindo um modelo stepwise e um modelo com variáveis selecionadas pelo RFE.
   - Avaliação da performance dos modelos na base de testes, com foco no coeficiente de determinação (\(R^2\)).

### Resultados Principais

O modelo que utilizou a abordagem stepwise apresentou a melhor performance, com um \(R^2\) de 0.35305621494306305 na base de testes. Isso indica que, apesar da complexidade dos dados, o modelo foi capaz de capturar uma proporção significativa da variabilidade na `renda`.

## Conclusão

Este projeto destaca a importância de técnicas meticulosas de seleção de variáveis e a potencialidade de modelos simplificados na previsão eficaz de variáveis alvo complexas. A abordagem stepwise, em particular, mostrou-se valiosa pela sua capacidade de selecionar variáveis significativas e melhorar a performance do modelo.

