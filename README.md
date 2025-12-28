# TCC – Análise do Desempenho Financeiro no Agronegócio Brasileiro

Este repositório contém os scripts desenvolvidos no âmbito do Trabalho de Conclusão de Curso (TCC),
com foco na análise estatística e visualização de indicadores financeiros de empresas do agronegócio brasileiro,
a partir de dados públicos disponibilizados pela Comissão de Valores Mobiliários (CVM).

## Objetivo do projeto

O objetivo deste projeto é disponibilizar o código-fonte utilizado para a análise exploratória e inferencial
do desempenho econômico-financeiro de empresas do setor agrícola brasileiro, com base nos indicadores
Retorno sobre Ativos (ROA), Retorno sobre o Patrimônio Líquido (ROE) e Margem Líquida, considerando os
exercícios de 2023 e 2024.

## Estrutura metodológica

O projeto está organizado em duas etapas principais, conforme descrito na metodologia do TCC:

1. **Processamento e cálculo dos indicadores financeiros**
   - Script: `scripts/01_processamento_calculo_indicadores.py`
   - Responsável pela extração, tratamento e cálculo dos indicadores financeiros a partir das DFPs da CVM.

2. **Análise estatística e visualização dos dados**
   - Script: `scripts/02_analise_estatistica_visualizacao.py`
   - Contém as análises estatísticas descritivas e inferenciais, incluindo histogramas, boxplots,
     correlação de Pearson, teste t pareado e teste não paramétrico de Wilcoxon.

## Ferramentas utilizadas

- Python (pandas, matplotlib, scipy)
- Google Colab
- Power BI

## Observações

- Os dados financeiros utilizados neste estudo são públicos e provenientes da CVM.
- Os scripts foram desenvolvidos com finalidade acadêmica, visando garantir transparência e reprodutibilidade.
- O dashboard interativo foi construído no Power BI a partir dos dados processados em Python.
