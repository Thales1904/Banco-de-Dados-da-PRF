# Análise de Dados da Polícia Rodoviária Federal (PRF) — 2018 a 2019

## Sobre o projeto

Este projeto tem como objetivo realizar a limpeza, a organização e a análise de duas bases de dados da Polícia Rodoviária Federal (PRF), referentes aos anos de 2018 e 2019: **acidentes de trânsito e infrações de trânsito (multas)**.

O trabalho envolve o tratamento dos dados, a concatenação de tabelas, a codificação e a decodificação de variáveis com base nos dicionários oficiais da PRF e a exportação dos conjuntos de dados finais para utilização em análises posteriores.

## Etapas do projeto

- **Concatenação das tabelas:** integração dos conjuntos de dados utilizando `MultiIndex` do Pandas para organizar e combinar as informações.
- **Limpeza e tratamento dos dados:** identificação e correção de inconsistências, organização das colunas e preparação das bases para análise.
- **Tratamento das variáveis:** codificação e decodificação de variáveis com base nos dicionários de dados da PRF, facilitando a interpretação dos registros.
- **Exportação dos resultados:** geração de dois arquivos finais, correspondentes às bases de acidentes e infrações, armazenados na pasta `Tabelas finais`.

## Estrutura do repositório

- `Acidentes/`: arquivos relacionados aos dados de acidentes de trânsito.
- `Infrações.2018-2019/`: arquivos relacionados aos dados de infrações de trânsito (multas).
- `Dicionarios/`: dicionários de dados utilizados para interpretar e tratar as variáveis das bases.
- `Tabelas finais/`: arquivos finais após as etapas de limpeza, tratamento e concatenação.
- `Projeto1`: arquivo principal com o desenvolvimento do projeto.

## Tecnologias utilizadas

- **Python:** linguagem utilizada no processamento e na análise dos dados.
- **Pandas:** manipulação de DataFrames, limpeza, concatenação e tratamento de variáveis.
- **Jupyter Notebook:** desenvolvimento e documentação das etapas do projeto.

## Resultados

Ao final do projeto, foram geradas duas bases de dados tratadas: uma referente aos acidentes de trânsito e outra às infrações de trânsito registradas pela PRF entre 2018 e 2019.

Essas bases estão organizadas para facilitar consultas, análises exploratórias e investigações sobre os registros de trânsito do período.

## Fonte dos dados

Os dados e os dicionários utilizados são provenientes da Polícia Rodoviária Federal (PRF).

Portal oficial de dados abertos: https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos

## Autor

**Thales Trajano**

GitHub: [@Thales1904](https://github.com/Thales1904)
