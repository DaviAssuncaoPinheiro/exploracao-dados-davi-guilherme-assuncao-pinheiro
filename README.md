# exploracao-dados-davi-guilherme-assuncao-pinheiro

Este repositorio guarda o trabalho de exploracao de dados com o dataset de beneficios concedidos pelo INSS (competencia 202305). A analise foi feita em Python com pandas, numpy e matplotlib.

## O que tem no repositorio
- `exploracao_inss_beneficios_concedidos_maio_2023.ipynb`: notebook com limpeza, estatistica descritiva e visualizacoes.
- `requirements.txt`: dependencias para rodar o notebook.
- `data/D.SDA.PDA.001.CON.202305.csv`: arquivo usado na analise.

## Sobre os dados
Usado o dataset publico de Beneficios Concedidos do INSS.
- Fonte do dataset: https://dadosabertos.inss.gov.br/dataset/inss-beneficios-concedidos
- Pagina institucional: https://www.gov.br/inss/pt-br/acesso-a-informacao/dados-abertos/dados-abertos

## Como rodar
1. Instale as dependencias com `pip install -r requirements.txt`.
2. Garanta que o CSV esteja em `data/D.SDA.PDA.001.CON.202305.csv`.
3. Abra o notebook no Jupyter ou no VS Code e execute as celulas em ordem.

## Resumo do que foi analisado
O notebook mostra estatisticas descritivas (media, mediana, moda, min, max, desvio padrao, variancia, quartis e IQR), verifica tipos de dados e ausencias, e constrói graficos para entender a distribuicao dos valores e o perfil dos beneficiarios.
