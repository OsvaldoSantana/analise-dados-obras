# Análise de Dados de Obras com Python

Projetos de análise, limpeza e tratamento de dados de execução de obras usando Python e Pandas.

## Contexto

Dados de obra chegam sujos: medições duplicadas, datas inconsistentes, formatos diferentes entre planilhas. Este repositório documenta soluções práticas para tratar e analisar esses dados.

## Projetos

### 01 — Limpeza de base de medições
- Problema: base exportada do ERP com registros duplicados e campos vazios
- Solução: identificação e remoção de duplicatas, tratamento de valores nulos, padronização de formatos
- Arquivo: `01_limpeza_medicoes.py`

### 02 — Análise de desvio de cronograma
- Problema: comparar datas previstas vs realizadas de um cronograma de obra
- Solução: cálculo de desvio em dias, classificação por criticidade, geração de resumo por fase
- Arquivo: `02_desvio_cronograma.py`

### 03 — Consolidação de dados de múltiplas obras
- Problema: dados de várias obras em planilhas separadas com formatos diferentes
- Solução: leitura, padronização e consolidação em DataFrame único
- Arquivo: `03_consolidacao_obras.py`

## Ferramentas

- Python 3.x
- Pandas
- Jupyter Notebook
- Dados simulados baseados em cenários reais

## Sobre

Engenheiro Civil aprendendo análise de dados para aplicar inteligência operacional ao planejamento de obras.

[LinkedIn](https://linkedin.com/in/osvaldo-santana-334792267)
