# **Predição Sobre Demandas para Produtos de Supermercados**

## **Descrição do Projeto**

O projeto **SmartRetail** visa o desenvolvimento de um algoritmo fundamentado em Machine Learning que prevê a demanda por produtos em supermercados. Por meio do dataset Retail Rocket Recommender System, meu modelo interpreta padrões históricos de vendas e aspectos como promoções, sazonalidade e dias da semana, visando otimizar o planejamento de estoques e logística. 

## **Motivação**

Supermercados enfrentam desafios constantes com o gerenciamento de estoques. O objetivo deste projeto é reduzir desperdícios, evitar a falta de produtos e melhorar a eficiência no planejamento logístico.

## **Tecnologias Utilizadas**  
- Linguagem: Python  
- Bibliotecas:  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Matplotlib / Seaborn  
  - Jupyter Notebook  

## **Algoritmos Implementados**  
1. **Regressão Linear**: Para analisar relações entre fatores contínuos e demanda.  
2. **Random Forest**: Para capturar padrões complexos e não lineares.  

## **Dataset**  
O dataset utilizado é o **[Retail Rocket Recommender System Dataset](https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset)**, disponível no Kaggle.  

## **Como Utilizar**  
1. Clone este repositório:  
   ```bash
   - git clone https://github.com/seu-usuario/smartretail.git
   cd smartretail
   ```

2. Instale o Poetry utilizando o pipx (recomendado):
    - O pipx é uma ferramenta para instalar e rodar aplicativos Python isoladamente. Caso não tenha o pipx instalado, use o seguinte comando:

   ```bash
   pip install pipx
   pipx ensurepath
   ```

    - Em seguida, instale o Poetry:
    ```bash
    pipx install poetry
    ```

3. Configure o ambiente do projeto com o Poetry:  
   - Inicialize o ambiente virtual:  
     ```bash
     poetry shell
     ```  
   - Instale as dependências listadas no arquivo `pyproject.toml`:  
     ```bash
     poetry install
     ```

4. Execute o Jupyter Notebook:  
   Com o ambiente virtual ativado, rode o seguinte comando para iniciar o notebook:  
   ```bash
   jupyter notebook
   ```
   
5. Abra o arquivo principal **AnaliseDeConversao.ipynb** no Jupyter e execute as células para carregar o dataset, treinar os modelos e visualizar os resultados.

Para ter visualizar o relatorio completo que explica o motivo e a logica por tras do Algoritmo gerado, basta entrar em 