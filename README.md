# Dormindo como uma Pedra

## Resumo do Projeto

Este projeto, intitulado **"Dormindo como uma Pedra"**, tem como objetivo desenvolver um modelo preditivo utilizando técnicas de aprendizado profundo para analisar e prever a qualidade do sono. A proposta baseia-se na utilização de dados comportamentais e fisiológicos, extraídos do dataset [Health and Sleep Statistics](https://www.kaggle.com/datasets/hanaksoy/health-and-sleep-statistics), para identificar padrões que influenciam o descanso e fornecer recomendações práticas que contribuam para a melhoria da saúde e qualidade de vida dos indivíduos.

## Estrutura do Projeto

O projeto se estrutura em diversas etapas:

- **Coleta e Pré-processamento dos Dados:** Tratamento de valores ausentes, codificação de variáveis categóricas, normalização e divisão do dataset em conjuntos de treinamento, validação e teste.
- **Análise Exploratória (EDA):** Visualizações e correlações para identificar relações entre as variáveis.
- **Modelagem:** Implementação e treinamento de modelos preditivos, com foco no GBM (usando CatBoost) e na rede MLP, seguidos do ajuste de hiperparâmetros e validação cruzada.
- **Avaliação e Interpretação dos Resultados:** Utilização de métricas como RMSE e R² para mensurar o desempenho dos modelos e identificação dos fatores mais influentes na qualidade do sono.

## Estrutura de Diretórios

- `data/`: Contém o dataset utilizado no projeto.
  - `Health_Sleep_Statistics.csv`: Arquivo CSV com os dados de saúde e sono.
- `Notebook/`: Contém os notebooks Jupyter utilizados no projeto.
  - `Sleep_Project.ipynb`: Notebook principal do projeto.
  - `catboost_info/`: Diretório com informações do treinamento do modelo CatBoost.
    - `catboost_training.json`: Arquivo JSON com informações do treinamento.
    - `learn_error.tsv`: Arquivo TSV com os erros de aprendizado.
    - `test_error.tsv`: Arquivo TSV com os erros de teste.
    - `time_left.tsv`: Arquivo TSV com o tempo restante.
    - `learn/`: Diretório com eventos de aprendizado.
      - `events.out.tfevents`: Arquivo de eventos de aprendizado.
    - `test/`: Diretório com eventos de teste.
      - `events.out.tfevents`: Arquivo de eventos de teste.
    - `tmp/`: Diretório temporário.
- `Presentation/`: Contém a apresentação do projeto.
  - `Apresentação.pdf`: Arquivo PDF com a apresentação do projeto.
  - `Relatório do Projeto.pdf`: Arquivo PDF com o relatório do projeto.

## Objetivos do Projeto

- Desenvolver um modelo preditivo para analisar e prever a qualidade do sono.
- Identificar padrões que influenciam a qualidade do sono.
- Fornecer recomendações práticas para melhorar a saúde e a qualidade de vida dos indivíduos.

## Requisitos

Para instalar as dependências necessárias para executar o projeto, utilize o arquivo `requirements.txt`. Você pode instalar todas as dependências com o seguinte comando:

```sh
pip install -r "Dormindo como uma Pedra/requirements.txt"
```

## Colaboradores

| [<img src="https://avatars.githubusercontent.com/u/129231720?v=4" width=115><br><sub>Henrique César Higino Holanda Cordeiro</sub>](https://github.com/SapoSopa) | [<img src="https://avatars.githubusercontent.com/u/68339043?v=4" width=115><br><sub>Rafael Moura</sub>](https://github.com/Rafael-N-Moura) |
| :---: | :---: |