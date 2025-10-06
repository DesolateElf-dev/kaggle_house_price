# Kaggle House Price Prediction

Este projeto tem como objetivo aprender a utilizar machine learning para previsão de preços de casas, utilizando o conjunto de dados disponível no Kaggle.

## Objetivo
Criar um modelo de machine learning que possa prever o preço de casas com base em características como tamanho, localização, número de quartos, etc.

## Conjunto de Dados
O projeto utilizará o conjunto de dados de preços de casas disponível no Kaggle ("House Prices: Advanced Regression Techniques").

## Estrutura do Projeto
- `notebooks/`: Jupyter notebooks para análise e modelagem
  - `house_price_prediction.ipynb`: Notebook principal para análise e modelagem
- `data/`: Dados utilizados no projeto (será criado após download dos dados do Kaggle)
- `src/`: Código fonte do projeto
- `models/`: Modelos treinados

## Requisitos
- Python 3.7+
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Como Executar

1. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```
   ou instale individualmente:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

2. **Baixe os dados do Kaggle:**
   - Acesse a competição "House Prices: Advanced Regression Techniques" no Kaggle
   - Faça o download dos arquivos `train.csv` e `test.csv`
   - Coloque-os na pasta `data/`

3. **Execute o Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   ou
   ```bash
   python -m jupyter notebook
   ```

4. **Abra e execute o notebook:**
   - Navegue até `notebooks/house_price_prediction.ipynb`
   - Execute as células em ordem para realizar a análise e treinar o modelo

## Metodologia

O projeto segue a seguinte abordagem:
1. Análise exploratória de dados (EDA)
2. Pré-processamento dos dados
3. Treinamento de modelo de regressão linear
4. Avaliação do modelo
5. Otimização e melhorias

## Resultados Esperados

O modelo desenvolvido deverá ser capaz de prever preços de casas com um erro quadrático médio (MSE) relativamente baixo e um coeficiente de determinação (R²) próximo de 1.
