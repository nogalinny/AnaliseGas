Análise de Preços da Gasolina no Brasil – 2º Semestre de 2025
Objetivo

Este projeto tem como objetivo analisar o comportamento dos preços da gasolina no Brasil durante o segundo semestre de 2025, utilizando dados públicos da ANP.

A análise busca:

Identificar padrões de preço ao longo do tempo
Comparar diferenças regionais e estaduais
Avaliar desigualdade dentro dos mercados locais
Investigar fatores que influenciam o preço final ao consumidor
Tecnologias Utilizadas
Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook
Tratamento de Dados

Foram aplicadas etapas de limpeza e padronização:

Normalização de colunas
Conversão de tipos (datas e valores)
Remoção de valores nulos
Filtro de amostragem (mínimo de 100 postos por dia)
Exclusão de outliers extremos (> R$ 8,50)
Análises Realizadas
1. Evolução Temporal (Média vs Mediana)

A comparação entre média e mediana mostrou forte convergência ao longo do período.

Insight:
A proximidade entre média e mediana indica um mercado homogêneo, sem grandes distorções causadas por valores extremos.

📌 Os preços oscilaram em uma faixa estreita (R$ 6,25 a R$ 6,45), sugerindo estabilidade no período.

2. Ranking de Estados

A análise por mediana revelou forte desigualdade regional:

Estado mais caro: Acre (AC)
Estado mais barato: Piauí (PI)
Diferença total: R$ 1,66

Insight:
O Brasil não possui um único mercado de combustíveis, mas sim 27 mercados distintos, influenciados principalmente por fatores logísticos.

3. Dispersão de Preços (Boxplot)

A análise de variabilidade mostrou diferenças internas relevantes:

Estados como SP e AM apresentam alta dispersão
Outros estados possuem preços mais uniformes

Insight:
Mercados com maior dispersão indicam menor uniformidade de preços, impactando diretamente o consumidor.

4. Ceará vs Brasil

Comparando o Ceará com o restante do país:

O estado apresentou preços R$ 0,10 acima da média nacional

Insight:
A diferença observada sugere impacto de fatores regionais, como logística de distribuição e dependência de abastecimento externo.

5. Capital vs Interior

Foi criada uma variável para diferenciar capitais e cidades do interior.

Resultado:
Cidades do interior apresentam preços consistentemente mais altos.

Insight:
A distância dos centros de distribuição impacta diretamente o preço final.

6. Análise por Região

Ranking de preços por região:

Norte (mais caro)
Centro-Oeste
Sul
Nordeste
Sudeste (mais barato)

Insight:
Regiões mais isoladas apresentam maiores custos, reforçando o impacto logístico.

7. Índice de Dispersão (Desvio Padrão)

Estados com maior variação de preços:

Pará (PA)
Mato Grosso do Sul (MS)
Amazonas (AM)

Insight:
Maior desvio padrão indica mercados mais desiguais, onde consumidores pagam preços muito diferentes dentro do mesmo estado.

Conclusões
O mercado de combustíveis apresentou alta estabilidade no período analisado
A desigualdade regional é significativa (diferença de até R$ 1,66)
O ICMS, atualmente padronizado, tem menor influência na variação entre estados
A logística é o principal fator explicativo dos preços
Cidades do interior tendem a apresentar preços mais elevados
A concorrência local influencia a dispersão de preços
