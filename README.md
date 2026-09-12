
# Análise Financeira ClearBank

Este projeto em Python desenvolvido em um notebook Jupyter/Colab tem como objetivo principal processar um arquivo CSV de transações financeiras (`transacoes.csv`), validá-las, gerar um relatório financeiro mensal detalhado, identificar transações suspeitas e apresentar os resultados de forma clara e organizada.

## Funcionalidades Principais:

*   **Leitura e Validação de Transações:** Lê transações de um arquivo CSV, validando cada linha para garantir a integridade dos dados (tipos corretos, valores positivos, IDs válidos, etc.).
*   **Relatório Financeiro Mensal:** Calcula métricas financeiras por mês, incluindo quantidade de transações, total de crédito, total de débito, saldo, média, maior e menor valor transacionado.
*   **Identificação de Transações Suspeitas:** Sinaliza transações que excedem um limite predefinido (`LIMITE_SUSPEITO`).
*   **Exportação de Dados:** Salva o relatório financeiro consolidado em formato JSON (`relatorio.json`).
*   **Exibição no Terminal:** Apresenta um resumo formatado do relatório diretamente no terminal.
*   **Análise com Pandas (Opcional):** Demonstra a capacidade de realizar a mesma análise de forma eficiente usando a biblioteca `pandas`, com comparação de resultados.
*   **Visualização de Dados com Matplotlib (Opcional):** Gera um gráfico visual das transações de crédito e débito mensais, salvo como `grafico.png`.

## Como Executar o Projeto:

1.  **Abrir o Notebook:** Faça o download do arquivo `.ipynb` e abra-o em um ambiente Jupyter (Jupyter Notebook, JupyterLab) ou no Google Colab.
2.  **Executar as Células:** Execute todas as células do notebook em ordem, da primeira à última. No Google Colab, você pode usar `Ambiente de execução > Executar tudo`.
3.  **Verificar as Saídas:** Observe a saída no terminal, que exibirá o relatório financeiro, e verifique os arquivos gerados.

## Saídas Geradas:

Ao final da execução do notebook, os seguintes artefatos serão criados:

*   **`transacoes.csv`**: O arquivo de entrada simulado que contém os dados das transações.
*   **`relatorio.json`**: Um arquivo JSON contendo o resumo financeiro mensal e a lista de transações suspeitas.
*   **`grafico.png`**: Uma imagem contendo um gráfico de barras empilhadas que visualiza o crédito e débito mensal.

## Requisitos Técnicos:

*   **Python 3.x**
*   **Bibliotecas:**
    *   `csv` (nativo do Python)
    *   `datetime` (nativo do Python)
    *   `json` (nativo do Python)
    *   `pandas` (para análise opcional)
    *   `matplotlib` (para visualização opcional)

**Observação:** O ambiente do Google Colab já oferece todas as bibliotecas necessárias.
