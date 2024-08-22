# Análise Previsão de Churn

## Descrição do Projeto
Este projeto tem como objetivo desenvolver um modelo que possa prever se um cliente vai deixar um banco fictício em breve. 
São analisados dados sobre o comportamento passado dos clientes e rescisões de contratos com o banco.

## Ferramentas e Bibliotecas Utilizadas
- Python: Linguagem principal utilizada para a análise.
- Pandas: Biblioteca para manipulação e análise de dados.
- Sklearn: Biblioteca para construção de modelo de machine learning.
- Matplotlib.pyplot: Biblioteca para construção de gráficos

## Tabela
O conunto de dados possui os seguintes campos:

- RowNumber — índice das strings de dados
- CustomerId — identificador exclusivo do cliente
- Surname — sobrenome
- CreditScore — pontuação de crédito
- Geography — país de residência
- Gender — gênero
- Age — idade
- Tenure — período de maturação para o depósito fixo de um cliente (anos)
- Balance — saldo da conta
- NumOfProducts — número de produtos bancários usados pelo cliente
- HasCrCard — cliente possui cartão de crédito (1 - sim; 0 - não)
- IsActiveMember — cliente ativo (1 - sim; 0 - não)
- EstimatedSalary — salário estimado
- Exited — o cliente saiu (1 - sim; 0 - não)

## Metodologia
**Análise Exploratória de Dados**
- Importar as bibliotecas necessárias
- Carregar e visualizar os dados

**Pré-processamento**
- Identificar e tratar valores ausentes ou duplicados

**Preparação do conjunto para o modelo**
- Identificação das festures e target do modelo
- Divisão dos conjuntos em treino, teste e validação
- Ajustando o equilíbrio de classes 

**Construindo e testando modelos**
- Regressão Logística
  - Treino
  - Teste
  - Validação
  - Aplicação do modelo com e sem o equilíbrio de classes
  - Métricas de avaliação
  
## Resultados
Treinamos o nosso modelo onde o mesmo apresentou bons resultados das métricas que utilizamos para verficiar sua qualidade, como valor F1, e AUC-ROC. 
O modelo não apresenta o valor máximo em ambas as métricas, mas seu resultado é aceitável para poder colocar ele em uso. 
Também é possível perceber pela Curva ROC que ele apresenta resultados melhores que o modelo aleatório.

## Aprendizados
- Análise de dados: interpretação e extração de insights valiosos a partir de grandes volumes de dados.
- Preparação do conjunto para aplicações em Machine Learning: separação do conjunto original em teste e treino, além da seleção das features e target do modelo.
- Equilíbrio de classes: ajuste das features do modelo para reduzir o viés de uma classe.
- Aplicação de modelos de Machine Learning: aplicação, seleção de hiperparâmetros, teste e avalição do modelo.
- Documentação de projetos: elaboração de documentação clara e detalhada para garantir que o projeto seja compreensível e replicável.
- Utilização de bibliotecas e ferramentas: aplicação prática de diversas bibliotecas e ferramentas do ecossistema Python.
- Tomada de decisões baseadas em dados: uso de insights derivados da análise de dados para orientar decisões estratégicas.
