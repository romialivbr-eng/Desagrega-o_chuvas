# Desagregação temporal de chuvas

Este repositório contém uma metodologia para desagregar a precipitação diária em intervalos subdiários utilizando modelos de aprendizado profundo.

São avaliadas diferentes configurações de entrada e resoluções temporais, com o objetivo de reproduzir a distribuição da chuva e as precipitações máximas acumuladas.

## Principais etapas

* Preparação e organização dos dados de precipitação;
* Treinamento dos modelos RNN e GRU;
* Geração das séries simuladas para o período de teste;
* Cálculo das máximas anuais para diferentes durações;
* Avaliação dos resultados por métricas de erro e viés.

## Notebooks finais

* `04_geracao_series_teste.ipynb`: gera as séries subdiárias simuladas;
* `05_maximos_anuais_acumulados.ipynb`: calcula as precipitações máximas acumuladas;
* `06_metricas_maximos_anuais.ipynb`: compara os resultados observados e simulados.

## Tecnologias

Python, Jupyter Notebook e bibliotecas para análise de dados e aprendizado profundo.

**Autor:** Aldo Romero Miranda
