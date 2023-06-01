# Desigualdade de renda

## Project
[GIT](https://github.com/Gabriel-MR/desigualdade-de-renda)

## Resources
[Wid World](https://wid.world/data/)

## Setup

[Google Colab](https://github.com/Gabriel-MR/desigualdade-de-renda/blob/main/projeto_semestral_1_ciencia_de_dados.ipynb)

### Importando bibliotecas
Utilizamos as libs pandas, numpy para tratamento e matplotlib para visualização dos dados
Foi utilizado também a lib sklearn.linear_model para criar um possível predição para os dados.

### Extraindo os dados
Foi utilizado a base de dados da Wid World

### Preparação dos dados
Os dados Foram padronizado, mantendo a métrica e nomenclatura e transformados dropando valores Nan removendo outliers

### Visualização de dados
Os gráficos foram gerados via matplotlib com o modo artist layer


## Objetivo
O objetivo primário deste projeto é analisar os indicadores de desigualdade de renda em diferentes países - Brasil, EUA e China - e observar como esses indicadores têm se comportado desde o ano 2000. Além disso, examinar o impacto da pandemia de Covid-19 nos mesmos indicadores.

Para alcançar esses objetivos, iremos considerar cinco indicadores específicos: o Pall, o P0p50, o P50p90, o P90p100 e o P99p100. Esses indicadores são amplamente utilizados para medir a desigualdade de renda em diferentes faixas de renda.

Ao analisar esses indicadores ao longo do tempo, poderemos identificar tendências e padrões relacionados à desigualdade de renda nos países selecionados. Além disso, a inclusão da análise do período da pandemia de Covid-19 permitirá entender como a crise afetou a distribuição de renda desses países.

Como objetivo secundário temos o uso de machine learning para prever o comportamento para a próxima geração (25 anos) para o indicador p0p50.

### Pall
Indica o grau de concentração de renda nas mãos dos mais ricos.

### P90p100
Indica a parcela da renda que está concentrada nos estratos superiores da população.

### P99p100
Indica o grau de concentração extrema de renda nas mãos de uma pequena parcela da população.

### P0p50
Indica a fatia da renda que é destinada aos 50% mais pobres.

### P50p90
Indica a distribuição de renda entre a classe média.

## Conclusões
Inseridas no próprio Google Colab em três sessões:
- Conclusão Geral
- Conclusão Covid-19
- Conclusão Machine Learning
