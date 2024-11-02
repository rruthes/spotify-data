
# Guia Técnico da Análise das Músicas mais ouvidas no Spotify




- Autor: [@rruthes](https://www.github.com/rruthes)
- Data: 10/10/2024
- Projeto: Análise das Músicas mais ouvidas do Spotify


## Sumário

**1.** Objetivo do Projeto

**2.** Descrição dos Dados

**3.** Metodologia
- 3.1 Limpeza e Pré-processamento
- 3.2 Análise exploratória de Dados (EDA)
- 3.3 Visualizações

**4.** Ferramentas e bibliotecas utilizadas

**5.** Considerações e limitações

**6.** Conclusões


## 1. Objetivo do Projeto
Esse projeto foi desenvolvido por mim como uma forma de estudo das tecnologias que envolvem a análise exploratória de dados em Python. Para tanto, busquei juntar duas das minhas maiores paixões: a música e a computação. Busquei, então, traçar correlações e conclusões acerca das músicas que contam com o maior número de streams no Spotify.

## 2. Descrição dos Dados
O dataset utilizado é uma lista das músicas mais tocadas no Spotify, coletada de uma tabela de dados do site [Kaggle](#https://www.kaggle.com/).

**Nome da música**

**Artista**

**Gênero**

**Popularidade**

**Características Musicais: Duração, energia, dançabilidade, BPM, entre outros.**

**Data de Lançamento**

## 3. Metodologia
### 3.1 Limpeza e Pré-processamento
- **Remoção de Duplicatas**: Eliminação de músicas duplicadas para evitar enviesamento.
- **Tratamento de Valores Nulos**: Valores ausentes em colunas essenciais foram preenchidos com a média ou mediana.

### 3.2 Análise Exploratória dos Dados (EDA)

- **Distribuição por valência**: Visualização das músicas mais populares por porcentagem de valência.
- **Popularidade por ano de lançamento**: Relação entre os anos de lançamento das músicas com a quantidade de streams.
- **Popularidade por mês de lançamento**: Relação entre as épocas do ano com o lançamento de músicas populares.

### 3.3 Visualizações

- **Histograma e gráfico de setores** para a análise da distribuição de características.
- **Gráfico de dispersão** para analisar a correlação entre diferentes características.

## 4. Ferramentas e bibliotecas utilizadas
- **Pandas**: Manipulação e limpeza de dados.
- **Seaborn e Matplotlib**: Visualizações e gráficos.
- **Plotly**: Visualizações interativas.

## 5. Consideração e limitações
- Os dados podem não estar 100% atualizados, dado a data de publicação do dataset utilizado.
- As playlists podem afetar diretamente a popularidade de uma música, o que pode introduzir um viés nos dados.

## 6. Conclusões
- Músicas lançadas em Janeiro tendem a ter uma maior chance de se tornarem populares.
- O BPM das músicas não está relacionado com a dançabilidade delas.
- Não existe correlação clara entre a valência das músicas e a quantidade de streams, ou seja, tanto músicas mais triste como músicas mais felizes podem atingir um grande número de streams.


