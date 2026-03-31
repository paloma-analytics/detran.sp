# Análise de Dados de Acidentes de Trânsito – DETRAN 2024

## Descrição do Projeto
Este projeto tem como objetivo analisar um conjunto de dados de acidentes de trânsito no Brasil utilizando a linguagem **R**. A análise explora padrões de acidentes, fatores que influenciam sua ocorrência e aplica conceitos estatísticos como probabilidade, teste qui-quadrado e correlação.

O projeto permite visualizar insights importantes sobre segurança no trânsito.

---

## Tecnologias Utilizadas
- **R** – Linguagem de programação para análise de dados.  
- **RStudio / Google Colab** – Ambientes para rodar o notebook.  
- **Pacotes R:**  
  - `dplyr` → Manipulação e agregação de dados.  
  - `ggplot2` → Visualização de dados (gráficos).  

---

## Conjunto de Dados
O dataset utilizado é `datatran2024.csv` e contém informações como:  
- Estado (`uf`)  
- Fase do dia (`fase_dia`)  
- Tipo de acidente (`tipo_acidente`)  
- Condição meteorológica (`condicao_metereologica`)  
- Número de veículos envolvidos (`veiculos`)  
- Número de feridos (`feridos`)  

---

## Principais Insights

### 1. Acidentes por Estado
- Estados com maior número de acidentes tendem a ser os mais populosos e com maior circulação de veículos.  

### 2. Fase do Dia
![Acidentes por fase do dia](outputs/graficos/fase_dia.png)  
- A maior quantidade de acidentes ocorre durante o período diurno.  
- Períodos de amanhecer e anoitecer apresentam menor número de ocorrências.  

### 3. Tipos de Acidentes
![Tipos de acidentes registrados](outputs/graficos/tipos_acidente.png)  
- Colisões traseiras, laterais e saídas de pista são os tipos mais comuns.  
- Esses acidentes podem estar relacionados à atenção do motorista, condições da via e fluxo de veículos.  

### 4. Teste Qui-Quadrado
- Foi realizada a análise da relação entre condições meteorológicas e tipos de acidente.  
- Resultado: **p < 0,05**, indicando que há relação estatística entre clima e tipo de acidente.  

### 5. Intervalo de Confiança
- Média de veículos envolvidos: ~1,99 veículos por acidente.  
- Intervalo de confiança de 95%: 1,986 – 2,004 veículos.  

### 6. Correlação
- Correlação entre número de veículos e pessoas feridas: 0,061 (muito fraca).  
- Sugere que outros fatores influenciam mais a gravidade dos acidentes.  

---

