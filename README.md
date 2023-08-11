# Dsa - Conjunto_Paises_Setores

O propósito desta planilha é realizar uma análise aprofundada dos índices de países da Data Science Academy, a fim de identificar os setores de maior presença em diferentes regiões.

Nessa investigação, empregamos uma abordagem simples que envolve a agregação dos códigos de setores para calcular totais específicos para cada país. 
Utilizamos painéis interativos para apresentar os resultados de forma clara, mostrando tanto as cifras absolutas por país quanto por setor.

A colaboração generosa da empresa resultou no fornecimento de um conjunto de dados destinado à exploração. Através dessa exploração, esperamos extrair percepções cruciais, 
discernir padrões, identificar tendências e revelar inter-relações entre os diversos elementos presentes nos dados. A configuração adotada é a seguinte:

Arquivo Clientes do Txt: 

```bash

  Codigo_Cliente
```
depois foi mudado para: 

```bash

 Id,
 Codigo_Pais_Cliente,
 Sigla_Pais_Cliente

```

Arquivo de Países do Txt: 

```bash

  Codigo
  Pais

```

Arquivo de Setores do Txt: 

```bash

  Codigo
  Setor
```

## Passos para a realização das análises da Conjunto_Paises_Setores. 

```bash

  1 - Importação de Bibliotecas para a Planilha
  2 - Fazendo a Leitura dos Arquivos: Cliente, Países e Setores
  3 - Manipulação de dados para a criação das colunas: Sigla_Pais_Cliente, Codigo_Pais_Cliente
  4 - Retirada da Coluna Código_Cliente
  5 - Mudança de Posições do Csv dos Clientes
  6 - Conexão para o Banco de dados da DSA Conjunto_Países
  7 - Seleção de Consulta dos Dados
  8 - Carregamento dos Dados Conjunto_Países no Power 
  9 - Criação dos Dashboards para as abas: Setores e Países

```

* Nome das Tabelas para o banco de dados do tipos sanguíneos

```bash

    1 - Tabela Clientes
    2 - Tabela Países
    3 - Tabela Setores 
```

# Análise dos dados da Conjunto_Paises_Setores

. No Power BI 

```bash

  1 - Clientes por Setor
  2 - Média de Segmento de Setores
  3 - Total de Códigos
  4 - Média de Segmento de Setores
  5 - Clientes por Paisés
  6 - Total de Clientes por Países
  7 - Total e Variação de Clientes
  8 - Média e Variação de Clientes
  9 - Máxima e Meta Mínima de Clientes
  10 - Mediana de Clientes em Desvio Padrão

```

## Tecnologias Utilizadas  

** O projeto foi desenvolvido com as seguintes tecnologia ** 

- [anaconda](https://www.anaconda.com/) 

- [jupyter notebook](https://jupyter.org/)

- [Python](https://www.python.org/)

- [Power BI](https://powerbi.microsoft.com/pt-br/)

- [Sqlite3](https://www.sqlite.org/index.html)

# Visualização do Projeto em Python e Power BI 

 1. Power BI

 ```bash

  ## 1 - Clique no arquivo Conjunto_Paises.pbix 
  ## 2 - Vai aparecer um link chamado View raw, aperte nele e abra o projeto no Power BI Desktop

  Obs: O Power BI só vai funcionar somente na versões Windows 7, 8, 8.1, 10 ou 11

```

 2. Python
    
```bash

  ## 1 - Clique no arquivo SSA.ipynb e no outro chamado Conjunto_Paises.ipynb
  ## 2 - Já vai aparecer pronto o formato da Ide Python - Jupyter Notebook para a visualização do código 

```
