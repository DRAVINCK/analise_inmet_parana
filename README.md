# 🌦️ Projeto de Análise Climática Exploratória: Estado do Paraná

## 🎯 Visão Geral do Projeto

Este projeto consiste em uma *Análise Exploratória de Dados (EDA)* detalhada sobre as condições climáticas históricas do Paraná, Brasil. O objetivo principal é extrair e visualizar padrões temporais e sazonais de variáveis críticas como *temperatura* e *precipitação*.

A análise se concentra em quatro áreas-chave:
1. Variação anual das temperaturas extremas (mínima, média e máxima).
2. Ciclos sazonais de temperatura e chuva (médias mensais).
3. Comportamento de longo prazo da temperatura média.
4. Investigação da *correlação* e tendências entre *precipitação* e *umidade* ao longo dos anos.

---

## 🛠️ Tecnologias e Dependências

O projeto é construído em *Python* e utiliza as bibliotecas padrão da Ciência de Dados para manipulação e visualização de dados.

| Biblioteca | Função Principal |
| :--- | :--- |
| *pandas* | Leitura, limpeza e manipulação estruturada dos dados (DataFrames). |
| *matplotlib* | Criação dos gráficos estáticos e personalização das visualizações. |
| *seaborn* | Utilizado para a criação de linhas de regressão e tendências no gráfico de correlação. |
| *numpy* | Suporte a operações numéricas de alto desempenho. |

---

## 🚀 Guia de Execução

Para replicar esta análise, siga os passos abaixo:

### 1. Requisitos de Ambiente

Certifique-se de que o *Python 3* está instalado em sua máquina.

### 2. Instalação das Bibliotecas

Instale todas as dependências do projeto através do terminal com o seguinte comando:

```bash
pip install pandas matplotlib numpy seaborn   
```

## 📊 Visualizações e Resultados

Os gráficos gerados revelam informações valiosas sobre o clima da região analisada.

### 1. 🌡️ Temperaturas Média, Mínima e Máxima por Ano (°C)
Este gráfico de linha mostra a evolução da temperatura ao longo de todos os anos disponíveis na base, permitindo identificar tendências de longo prazo ou anomalias.

![Gráfico de Temperatura Média, Mínima e Máxima por Ano](imagem5.jpg)

### 2. ☀️ Ciclo Sazonal da Temperatura Média Mensal (°C)
Aqui, é possível ver o padrão sazonal de temperatura, destacando os meses mais quentes (Verão) e mais frios (Inverno) ao calcular a média de todos os anos para cada mês.

![Gráfico de Temperatura Média por Mês](imagem2.jpg)

### 3. 🌧️ Volume Médio de Chuva por Mês (mm)
Um gráfico de barras essencial para o planejamento hídrico e agrícola, exibindo o volume médio de precipitação por mês e identificando o período de maior e menor incidência de chuvas.

![Gráfico de Volume Médio de Chuva por Mês](imagem3.jpg)

### 4. 📈 Série Temporal da Temperatura Média Diária (°C)
Uma visão de alta granularidade da temperatura média registrada ao longo de toda a série histórica, útil para observar a variação e volatilidade diária.

![Gráfico de Temperatura Média Total da Base](imagem4.jpg)

### 5. 📉 Correlação: Evolução Anual da Precipitação vs. Umidade
Este gráfico de duplo eixo compara a tendência da precipitação média anual com a umidade média anual, oferecendo um insight visual sobre a relação entre estas duas variáveis.

![Gráfico de Correlação Anual](imagem1.jpg)
