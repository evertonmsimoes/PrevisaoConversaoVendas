# **Predição de Conversão de Vendas em Varejo Online**

## **Descrição do Projeto**

Este projeto aplica técnicas de aprendizado de máquina visando prever conversões de vendas em um ambiente de varejo online com base no conjunto de dados do Sistema de Recomendação Retail Rocket. Ao invés de prever a demanda geral do mercado por bens, o foco aqui é identificar quais usuários têm mais probabilidade de realizar uma compra após visitar o site. Os modelos analisam comportamentos que indicam intenção de compra, como visualizações de produtos, cliques e adições ao carrinho, a fim de estimar a taxa de conversão. O projeto aborda os desequilíbrios de classes que são oferecidos para desafios neste caso, onde a taxa de usuários que compram o produto é baixa.

## **Motivação**

Compreender e prever o comportamento do cliente no competitivo mercado de compras online é fundamental para melhorar os negócios e as vendas. O projeto visa criar um modelo preditivo que ajude a identificar potenciais compradores, permitindo que planos e necessidades individuais aumentem as taxas de conversão.

## **Tecnologias Utilizadas**  
- Linguagem: Python  
- Bibliotecas:  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Matplotlib / Seaborn  
  - Jupyter Notebook  

## **Algoritmos Implementados**  
1. **Regressão Linear**: Utilizada como modelo de baseline para comparação.  
2. **Random Forest**: Empregado para capturar relações não lineares e melhorar a performance preditiva, especialmente na classe minoritária ("Convertido"). 

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