# TCC – Análise do Desempenho Financeiro no Agronegócio Brasileiro

Este repositório reúne os scripts desenvolvidos no âmbito do Trabalho de Conclusão de Curso (TCC),
com foco na análise estatística e na visualização de indicadores financeiros de empresas do agronegócio brasileiro,
a partir de dados públicos disponibilizados pela Comissão de Valores Mobiliários (CVM).

O objetivo do repositório é garantir transparência metodológica e reprodutibilidade às análises realizadas,
complementando os procedimentos descritos no trabalho acadêmico.

## Objetivo do estudo

Disponibilizar o código-fonte utilizado na análise exploratória e inferencial do desempenho
econômico-financeiro de empresas do setor agrícola brasileiro, com base nos indicadores
Retorno sobre Ativos (ROA), Retorno sobre o Patrimônio Líquido (ROE) e Margem Líquida,
considerando os exercícios de 2023 e 2024.

## Estrutura metodológica

O projeto está organizado em duas etapas principais, em conformidade com a metodologia descrita no TCC:

1. **Processamento e cálculo dos indicadores financeiros**
   - Script: `scripts/01_processamento_calculo_indicadores.py`
   - Responsável pela extração, tratamento, padronização e cálculo dos indicadores financeiros
     a partir das Demonstrações Financeiras Padronizadas (DFPs) da CVM.

2. **Análise estatística e visualização dos dados**
   - Script: `scripts/02_analise_estatistica_visualizacao.py`
   - Contém as análises estatísticas descritivas e inferenciais, incluindo histogramas,
     boxplots, correlação de Pearson, teste *t* de Student pareado e teste não paramétrico de Wilcoxon,
     bem como as visualizações gráficas utilizadas no estudo.

Essa estrutura reflete diretamente as etapas metodológicas adotadas no trabalho acadêmico.

## Ferramentas utilizadas

O desenvolvimento do estudo contou com o uso integrado de ferramentas de ciência de dados,
estatística e visualização, conforme descrito a seguir:

- **Python**  
  Linguagem utilizada para o processamento, tratamento e análise dos dados financeiros,
  permitindo a automatização das etapas metodológicas e a reprodução dos resultados.

  - **pandas**: utilizada para leitura, manipulação, limpeza e estruturação dos dados,
    bem como para o cálculo dos indicadores financeiros ROA, ROE e Margem Líquida.
  - **matplotlib**: empregada na construção das visualizações gráficas, incluindo histogramas
    e boxplots, com o objetivo de analisar a distribuição dos dados e identificar padrões e outliers.
  - **scipy.stats**: utilizada na aplicação dos testes estatísticos, incluindo o teste de normalidade
    de Shapiro-Wilk, o teste *t* de Student pareado, o teste não paramétrico de Wilcoxon e a correlação
    de Pearson.

- **Google Colab**  
  Ambiente utilizado para o desenvolvimento e execução dos scripts em Python, possibilitando
  a organização do fluxo de processamento e análise dos dados de forma acessível e reprodutível.

- **Power BI**  
  Ferramenta empregada para a construção do dashboard interativo, permitindo a visualização dinâmica
  dos indicadores financeiros, a comparação entre empresas e exercícios financeiros, bem como a
  exploração das relações entre as variáveis analisadas.

## Observações

- Os dados financeiros utilizados neste estudo são públicos e provenientes da Comissão de Valores Mobiliários (CVM).
- Os scripts foram desenvolvidos exclusivamente para fins acadêmicos.
- O repositório não substitui o conteúdo do TCC, mas fornece suporte à reprodutibilidade
  e à transparência do fluxo metodológico adotado.
- O dashboard interativo foi construído no Power BI a partir dos dados processados em Python
  e encontra-se descrito na pasta `dashboard/`.
