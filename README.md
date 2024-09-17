# 🏞️ Análise de Dados de Poluição da Água

## 📄 Visão Geral do Projeto

Este projeto foi desenvolvido como parte de um estudo de ciência de dados focado na análise dos níveis de poluição da água em diferentes regiões e países ao redor do mundo. O objetivo principal foi identificar padrões, tendências e possíveis causas da poluição da água, ajudando a formular hipóteses e estratégias para mitigação do problema.

Este projeto me permitiu aprimorar minhas habilidades em Análise Exploratória de Dados (EDA) e Testes de Hipóteses, além de aplicar técnicas de visualização de dados.

## 📊 Descrição dos Dados

O conjunto de dados utilizado contém as seguintes variáveis:

* City: Nome da cidade onde os dados foram coletados.
* Region: Região do país onde os dados foram coletados.
* Country: Nome do país.
* WaterPollution: Nível de poluição da água, em uma escala de 0 (sem poluição) a 100 (extremamente poluída).

### Informações adicionais:

* O dataset contém 3.963 linhas e 4 colunas.
* A coluna Region possui 425 valores nulos.
* A distribuição dos dados é desigual, com 51% das observações concentradas em apenas 10 países.

## 🔍 Análise Exploratória de Dados (EDA)

1. Tratamento de Dados Faltantes:

* Remoção da coluna AirQuality, que não era relevante para o estudo de poluição hídrica.
* Identificação de valores nulos na coluna Region.
  
2. Distribuição das Observações por País:

* 51% dos dados pertencem a apenas 10 países.
* Essa concentração de dados possibilitou análises mais detalhadas nesses países, mas também gerou vieses ao comparar com países com menos observações.

3. Análise Comparativa entre Países:

* A Índia apresentou níveis elevados de poluição da água (média acima de 60), enquanto o Reino Unido teve os menores índices de poluição entre os 10 países analisados.

4. Análises Regionais:

* Realizadas análises específicas para países como Brasil e Estados Unidos, explorando a disparidade regional dos dados e a representatividade das observações.

## 📐 Testes de Hipóteses

1. Poluição da Água e Desenvolvimento Socioeconômico:

* Hipótese testada: Existe uma diferença significativa nos níveis de poluição da água entre países desenvolvidos e emergentes.
* Teste t de Student aplicado para comparar a média de poluição da água entre os países do hemisfério norte e sul. O resultado levou à rejeição da hipótese nula, indicando que há uma diferença significativa.

2. Desigualdade na Distribuição das Observações:

* Hipótese testada: A distribuição das observações entre os estados brasileiros é significativamente desigual.
* Teste de Kruskal-Wallis foi utilizado, e a análise demonstrou que a hipótese nula deveria ser rejeitada.

## 🧑‍🏫 Conclusão

Este estudo revelou que os níveis de poluição da água variam consideravelmente entre diferentes países e regiões, com fatores como desenvolvimento socioeconômico, políticas ambientais e práticas culturais desempenhando papéis importantes. Essas descobertas podem contribuir para a formulação de políticas públicas e estratégias de mitigação ambiental.

## 🛠️ Tecnologias Utilizadas

* Python para análise de dados e visualizações
* Bibliotecas: pandas, matplotlib, seaborn, scipy

## Documentação

Estou deixando disponivel tanto o caderno no jupyter notebook quanto o pdf com a dcoumentação do trabalho aqui no repositório, sinta a vontade para utilizar 😁

## ✍️ Autor

Mateus Iago Sousa Conceição
Estudante de Engenharia de Software - FIAP
Aspirante a Cientista de Dados

---

# 🏞️ Water Pollution Data Analysis

## 📄 Project Overview
This project was developed as part of a data science study focused on analyzing water pollution levels across different regions and countries worldwide. The primary goal was to identify patterns, trends, and potential causes of water pollution, aiding in the formulation of hypotheses and mitigation strategies.

This project allowed me to improve my skills in Exploratory Data Analysis (EDA) and Hypothesis Testing, as well as applying data visualization techniques.

## 📊 Dataset Description
The dataset includes the following variables:

* City: Name of the city where data was collected.
* Region: The region within the country.
* Country: Country name.
* WaterPollution: Water pollution level on a scale from 0 (no pollution) to 100 (extremely polluted).

### Additional Information:
* The dataset contains 3,963 rows and 4 columns.
* The Region column has 425 missing values.
* Data is unevenly distributed, with 51% of observations concentrated in only 10 countries.

## 🔍 Exploratory Data Analysis (EDA)

1. Handling Missing Data:

* Removed the AirQuality column as it was irrelevant to the water pollution study.
* Identified missing values in the Region column.

2. Data Distribution by Country:

* 51% of the data belongs to just 10 countries.
* This concentration allowed for more detailed analysis in these countries but introduced biases when comparing with countries with fewer observations.

3.Country Comparison Analysis:

* India showed high levels of water pollution (average above 60), while the United Kingdom had the lowest pollution levels among the top 10 countries analyzed.

4. Regional Analyses:

* Specific analyses were performed for countries like Brazil and the United States, examining regional data disparities and the representativeness of the observations.

## 📐 Hypothesis Testing

1. Water Pollution and Socioeconomic Development:

* Hypothesis: There is a significant difference in water pollution levels between developed and emerging countries.
* Student's t-test was applied to compare the average water pollution levels between countries in the northern and southern hemispheres. The results led to the rejection of the null hypothesis, indicating a significant difference.

2. Inequality in Observation Distribution:

* Hypothesis: The distribution of observations between Brazilian states is significantly unequal.
* Kruskal-Wallis Test was applied, and the analysis showed enough evidence to reject the null hypothesis, confirming the inequality in distribution.

## 🧑‍🏫 Conclusion

This study revealed considerable variations in water pollution levels across different countries and regions. Factors such as socioeconomic development, environmental policies, and cultural practices play crucial roles. These insights can contribute to the formulation of public policies and environmental mitigation strategies.

## 🛠️ Technologies Used

* Python for data analysis and visualizations
* Libraries: pandas, matplotlib, seaborn, scipy

## ✍️ Author

Mateus Iago Sousa Conceição
Software Engineering Student - FIAP
Aspiring Data Scientist
