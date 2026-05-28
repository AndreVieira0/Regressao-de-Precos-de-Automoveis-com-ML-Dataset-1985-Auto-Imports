# Trabalho 2 - Aprendizado de Máquina

Este repositório contém o código e a documentação referentes ao Trabalho 2 de Aprendizado de Máquina para a disciplina de Ciência de Dados.

## Objetivo
Desenvolver um projeto completo de aprendizado de máquina, abordando desde a análise exploratória até o tratamento de outliers, treinamento e avaliação de modelos. A tarefa escolhida foi a **Regressão** para previsão de preços de veículos.

## Conjunto de Dados
Utilizamos o **1985 Auto Imports Dataset**, disponível no UCI Machine Learning Repository (Opção 19 da lista de Datasets sugeridos do trabalho). Este dataset contém várias características de automóveis associadas ao seu preço de mercado.
- **Fonte:** [UCI ML Repository - Automobile](https://archive.ics.uci.edu/ml/datasets/automobile)
- **Instruções para download:** Caso deseje baixar os dados brutos manualmente, acesse a página do link acima, clique em "Data Folder" e baixe o arquivo `imports-85.data`. Aqui no repositório, ele já se encontra renomeado e salvo na pasta `data/` como `imports-85.csv`.

## Estrutura do Repositório
- `data/`: Contém os dados brutos em CSV e as imagens extraídas dos gráficos.
- `notebooks/`: Contém o notebook Jupyter `trabalho2_analise_e_modelagem.ipynb` com código documentado e executável.
- `requirements.txt`: Lista as dependências necessárias (pandas, scikit-learn, etc).
- `relatorio_tecnico.md`: Arquivo Markdown fonte para geração do relatório técnico em PDF.

## Como Executar
1. Instale o Python 3.8+ (preferencialmente 3.10 ou superior).
2. Clone o repositório ou baixe os arquivos.
3. Instale as dependências executando no terminal:
   ```bash
   pip install -r requirements.txt
   ```
4. Inicie o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Acesse a pasta `notebooks/`, abra o arquivo `trabalho2_analise_e_modelagem.ipynb` e execute as células sequencialmente para replicar os modelos.

## Conclusões
O uso de Pipelines e tratamento de Outliers garantiu uma modelagem robusta, com o algoritmo Random Forest apresentando ótimo desempenho. Mais detalhes no `relatorio_tecnico`.
