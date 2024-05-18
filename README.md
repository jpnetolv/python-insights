# Análise de Cancelamentos com Python e Pandas

Este script em Python utiliza a biblioteca Pandas para análise de uma base de dados de cancelamentos. O objetivo é realizar diversas etapas, desde a importação dos dados até a visualização dos resultados em gráficos.

## Funcionalidades

O script realiza as seguintes etapas:

1. **Passo 1 - Importar Base de Dados:**
   - Carrega os dados de cancelamentos a partir de um arquivo CSV.

2. **Passo 2 - Visualizar a Base de Dados:**
   - Remove a coluna "CustomerID" da base de dados.
   - Exibe a tabela resultante.

3. **Passo 3 - Corrigir os Problemas da Base de Dados:**
   - Realiza uma análise da estrutura da tabela para identificar possíveis erros.
   - Remove linhas que contenham valores vazios.
   - Exibe a informação da tabela após a limpeza.

4. **Passo 4 - Análise Inicial dos Cancelamentos:**
   - Conta o número de pessoas que cancelaram e que não cancelaram.
   - Calcula o percentual de cancelamentos.

5. **Passo 5 - Análise Final dos Cancelamentos por Meio de Gráficos:**
   - Utiliza a biblioteca Plotly Express para criar gráficos de histograma, mostrando como as diferentes colunas da base de dados impactam nos cancelamentos.

## Pré-Requisitos

- Python 3.x instalado.
- Instalação das bibliotecas Pandas e Plotly via pip: `pip install pandas plotly`.

## Como Usar

1. Clone o repositório ou baixe o arquivo do script e o arquivo CSV.
2. Certifique-se de que o arquivo CSV está na mesma pasta que o script ou especifique o caminho correto no código.
3. Execute o script Python.

## Aviso

- Este script foi criado para fins educacionais e de demonstração.
- Certifique-se de entender o código antes de executá-lo em seus próprios dados.
- Esteja ciente de que a análise e as conclusões dependem da qualidade e relevância dos dados fornecidos.