
# Análise dos Suicídios no Brasil


## Objetivo

Essa análise tem como principal objetivo encontrar os fatores de risco para suicídio no Brasil e prever a evolução desses dados para os próximos anos.

## A Base de Dados

Nessa análise será usada a base de dados de mortalidade da **OMS** Mortality, ICD-10. Ela é organizada pelo código dos países como variáveis categóricas e está em formato **long**. Com os dados dos países, outras variáveis categóricas são o tipo de morte e o gênero. Com isso, o número de mortes é separado por faixas-etárias padronizadas pela **OMS**.

## Fonte dos Dados

Os dados foram obtidos do site internacional da OMS [https://www.who.int/healthinfo/statistics/mortality_rawdata/en/](https://www.who.int/healthinfo/statistics/mortality_rawdata/en/)
Onde eles podem ser baixado em formato "puro", como dois arquivos com mais de 10Mb para serem tratados. Eles vem como arquivos CSV que, após terem as causas da morte e países desejados selecionados, serão unidos e transformados em um único arquivo. Agilizando o tratamento dos dados.

## Dicionário de Dados

O dicionário de dados também está no link [https://www.who.int/healthinfo/statistics/mortality_rawdata/en/](https://www.who.int/healthinfo/statistics/mortality_rawdata/en/)
Apesar do dicionário conter as informações sobre todas as bases de dados, nessa sessão só serão exibidas as tabelas e linhas utilizadas.


## Perguntas em Potencial 

 - Existe uma diferença significativa entre as taxas de suicídio entre os gêneros?
 - Quais são as categorias com maior chance de cometerem suicídios?
 - Utilizando um modelo de regressão linear, as categorias em mais risco estão com o número de suicídios aumentando ou diminuindo?
