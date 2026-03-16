# Análise de Dados de Acidentes de Trânsito – Brasil 2024

## Aluno
Paloma A. Santos – Curso: Ciência de Dados

## Objetivo
Explorar dados reais de acidentes de trânsito no Brasil, aplicando manipulação de dados, visualização e análise probabilística utilizando R.

## Conjunto de Dados
Arquivo: `datatran2024.csv`  
Contém informações sobre:
- Estado (UF)
- Condição climática
- Fase do dia
- Tipo de acidente
- Número de veículos e pessoas envolvidas

## Tecnologias Utilizadas
- **R** (linguagem de programação)
- **dplyr** (manipulação de dados)
- **ggplot2** (visualização)
- **Google Colab / RStudio** (ambiente de execução)

## Principais Insights
- **Estado com mais acidentes:** SP  
- **Período do dia com mais acidentes:** Pleno dia  
- **Tipos mais frequentes de acidentes:** Colisão traseira, colisão lateral, saída de pista  
- **Influência do clima:** Condições meteorológicas têm relação com o tipo de acidente (teste qui-quadrado, p < 0,05)  
- **Média de veículos envolvidos:** ~2 veículos por acidente  
- **Correlação veículos x feridos:** muito fraca (0,061), outros fatores influenciam mais

## Visualizações

### Acidentes por fase do dia
![Acidentes por fase do dia](outputs/graficos/fase_dia.png)

### Tipos de acidentes registrados
![Tipos de acidentes](outputs/graficos/tipos_acidente.png)

## Como rodar o projeto
1. Baixar todos os arquivos do repositório.  
2. Abrir `Analise_Acidentes.ipynb` no Google Colab ou RStudio.  
3. Instalar pacotes: `dplyr`, `ggplot2`.  
4. Executar o notebook/script para reproduzir gráficos e resultados.

## Referências
- [Projeto Integrado Ciência de Dados – Anderson Salata](https://github.com/AndersonSalata/projeto-integrado-ciencia-dedados)
