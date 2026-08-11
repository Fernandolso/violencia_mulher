# Violência Contra a Mulher em Niterói (2012–2025)

Mapa interativo desenvolvido em R para visualização espacial dos casos de violência contra mulheres no município de Niterói (RJ), com foco nos registros enquadrados na **Lei Maria da Penha**.

## Objetivo

Este projeto busca apoiar análises territoriais sobre a violência contra a mulher, permitindo identificar a distribuição dos casos por bairro e destacar áreas com maior incidência.

## Dados Utilizados

### Base de Ocorrências

Foram considerados exclusivamente os registros que atendem aos seguintes critérios:

- Lei: **Lei Maria da Penha**
- Sexo da vítima: **Feminino**
- Período: **2012 a 2025**
- Localização: **Município de Niterói (RJ)**

### Base Cartográfica

Utiliza a malha geográfica dos setores censitários do IBGE agregada por bairro.

## Funcionalidades

- Mapa coroplético por bairro
- Visualização da concentração de casos
- Pop-up informativo para cada bairro
- Percentual de participação no total municipal
- Destaque visual ao passar o mouse
- Alternância entre diferentes mapas-base:
  - Cinza
  - Ruas
  - Satélite
  - Tema escuro

## Informações Exibidas

Ao clicar sobre um bairro são exibidas:

- Nome do bairro
- Total de casos registrados
- Percentual em relação ao total municipal



## Tecnologias Utilizadas

- R
- sf
- dplyr
- leaflet
- htmlwidgets

## Estrutura do Projeto

```text
violencia_contra_mulher/
│
├── index.html
└── README.md
