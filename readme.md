# 📈 Análise de Hábitos e Desempenho Acadêmico

Este projeto consiste em uma Análise Exploratória de Dados (EDA) e Modelagem de Regressão Linear para investigar a correlação entre diversos hábitos de estudantes e sua nota final em um exame. O objetivo é identificar quais hábitos (como horas de estudo, sono, uso de redes sociais, etc.) têm o maior impacto, positivo ou negativo, no desempenho acadêmico.

## 🎯 Objetivo

* Realizar uma análise de correlação detalhada entre 7 variáveis de hábitos e a nota final.
* Visualizar o impacto de diferentes hábitos no desempenho acadêmico usando gráficos de regressão.
* Construir e avaliar um modelo de regressão linear para prever a nota final com base nos hábitos.

## 📊 Principais Descobertas e Resultados

Os resultados da análise de correlação (matriz fornecida) apontam para as seguintes relações chave:

### 1. Correlação Positiva Muito Forte
A variável **Horas de Estudo por Dia** é a que tem o maior impacto positivo na **Nota do Exame**, com um coeficiente de correlação de **0.83**.

### 2. Correlação Negativa Fraca
O tempo gasto em **Redes Sociais** e **Netflix** demonstra uma correlação negativa fraca com a Nota do Exame (ambas com $-0.17$), sugerindo que o aumento dessas atividades está levemente associado à queda do desempenho.

### 3. Fatores com Baixo Impacto Linear
Variáveis como **Percentual de Presença** ($\approx 0.09$) e **Horas de Sono** ($\approx 0.12$) apresentaram uma correlação muito fraca com a Nota Final.

## ⚙️ Tecnologias e Bibliotecas

O projeto foi desenvolvido em Python, utilizando as seguintes bibliotecas:

* **Pandas:** Para manipulação e análise de dados.
* **Seaborn:** Para visualização estatística de dados (incluindo a matriz de correlação e o `lmplot`).
* **Matplotlib:** Para customização de gráficos.
* **Scikit-learn:** Para a construção e avaliação do modelo de Regressão Linear.
