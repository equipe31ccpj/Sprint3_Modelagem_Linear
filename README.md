# Trabalho de Análise de Dados: Estatística e Machine Learning

Este repositório contém o projeto de análise estatística descritiva, cálculo de probabilidades e modelagem preditiva desenvolvido em Python. O estudo analisa os padrões de recarga de veículos elétricos e o consumo de energia associado.

##  Integrantes
* [Maria Eduarda Rocha Benjamim] - RM: [570554]
* [Pedro Henrique Neves] - RM: [571382]
* [Akin Alexandre Mendes Martins] - RM: [572553]

## Estrutura do Repositório
* `charging_ev_and_grid_optimization_dataset (4).csv`: Base de dados contendo os registros de recargas e consumo energético.
* `Sprint3_Modelagem_Linear.ipynb`: Notebook com todo o desenvolvimento do código em Python, análises e visualizações gráficas.

## Conteúdo do Projeto
O projeto foi estruturado em quatro etapas principais de acordo com as diretrizes solicitadas:

1. **Probabilidade acima da Mediana:** Cálculo da mediana da variável de consumo de energia e análise da probabilidade teórica utilizando a Distribuição Normal.
2. **Probabilidade no Intervalo (Média ± 2s):** Determinação dos limites de variação (média e desvio-padrão) e cálculo da probabilidade teórica de ocorrência dentro deste intervalo.
3. **Modelagem com Regressão Linear:** Implementação de um modelo preditivo para analisar a relação entre a duração da recarga (`charging_duration`) e a energia consumida (`energy_consumed_kWh`), incluindo a geração da reta ajustada e interpretação dos coeficientes.
4. **Análise Geral:** Reflexão integrando os conceitos de Estatística Descritiva às técnicas de Aprendizado de Máquina Supervisionado.

## Tecnologias Utilizadas
* Python 3
* Pandas & NumPy (Manipulação de dados)
* Matplotlib & Seaborn (Visualização de gráficos)
* Scikit-Learn & SciPy (Modelagem preditiva e funções estatísticas)

