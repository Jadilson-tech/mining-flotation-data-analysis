# Análise de Dados - Processo de Flotação de Minério
Visão Geral

Este projeto tem como objetivo a análise de dados reais de um processo de flotação na indústria de mineração. O foco principal é compreender como variáveis operacionais influenciam a qualidade do produto final, especialmente a concentração de sílica (% Silica Concentrate) no minério de ferro.

 Objetivo

Identificar e analisar os principais fatores que impactam a concentração de sílica no processo de flotação, contribuindo para uma melhor compreensão da eficiência operacional e do comportamento do sistema.

 Dataset

O dataset utilizado neste projeto foi obtido a partir da plataforma Kaggle.

Devido ao seu grande volume de dados, o arquivo não foi incluído neste repositório.
Para reprodução da análise, acesse o link abaixo:

👉 [https://www.kaggle.com/datasets/edumagalhaes/quality-prediction-in-a-mining-process]

O conjunto de dados contém variáveis reais de processo, incluindo:

Air Flow (fluxo de ar)
Ore Pulp pH
Density (densidade da polpa)
Reagent Flow (Starch, Amina)
Indicadores de qualidade do minério
 Tecnologias Utilizadas
Python
Pandas
Matplotlib
Seaborn

 Etapas do Projeto
1. Data Loading
Importação de dataset em formato CSV
Tratamento de inconsistências com on_bad_lines='skip'
2. Data Cleaning
Conversão de formato decimal (vírgula → ponto)
Ajuste de tipos de dados (numéricos e datetime)
3. Exploratory Data Analysis (EDA)
Análise estatística descritiva
Distribuição das variáveis
Análise temporal
Correlação entre variáveis
4. Data Visualization
Histogramas
Heatmap de correlação
Scatter plots para análise de relações entre variáveis
 Principais Insights
Forte correlação negativa (-0.80) entre % Iron Concentrate e % Silica Concentrate, indicando aumento da pureza do minério.
Variáveis operacionais como Air Flow e pH apresentam influência moderada no processo.
Concentração de dados em faixas específicas sugere padrões operacionais estáveis.

 Conclusão

A análise demonstrou que o processo de flotação apresenta comportamento consistente com os princípios industriais, onde o aumento do teor de ferro está diretamente associado à redução de impurezas como a sílica.

Também foi possível observar que variáveis operacionais influenciam o resultado final, porém de forma integrada, reforçando a complexidade do processo e a necessidade de controle conjunto das condições operacionais.

Durante minha experiência na indústria, tive contato direto com o processo de flotação, incluindo a operação de tanques e a adição de reagentes, como amido (starch), utilizados na separação mineral. Essa vivência prática contribuiu para uma melhor interpretação dos dados analisados, permitindo conectar teoria e prática de forma mais consistente.

Dessa forma, este projeto demonstra não apenas habilidades técnicas em análise de dados, mas também a capacidade de compreender e interpretar processos industriais reais.

 Autor

Jadilson José Tavares
