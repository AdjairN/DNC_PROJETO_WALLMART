Projeto referente a especialização em ciências de dados pela DNC.

Introdução:
Wallmart, Inc., é uma multinacional estadunidense de lojas de departamento.
A companhia foi fundada por Sam Walton em 1962, incorporada em 31 de outubro de 1969 e feita capital aberto na New York Stock Exchange, em 1972.
No ano de 2021, obteve um um lucro de $13.51 Bilhões.
Sendo uma das principais lojas de varejo do mundo, os dados contemplam as vendas semanais de 45 lojas espalhadas pelos Estados Unidos.
O Walmart realiza vários eventos promocionais de descontos ao longo do ano. Essas remarcações precedem feriados importantes, os quatro maiores de todos, que são o Super Bowl, o Dia do Trabalho, o Dia de Ação de Graças e o Natal. As semanas que incluem esses feriados têm um peso maior.

 A questão do negócio:
A empresa Walmart deseja fazer um investimento em uma das lojas localizadas nos Estados Unidos a fim de expandir seu tamanho.
Foram avaliados os dados de 45 lojas, com as seguintes informações, a partir do arquivo Walmart.csv:

● Semana de Venda;
● Venda Naquela Semana;
● Flag se é ou não semana com feriado (1 - Holiday Week 0 - Non-HolidayWeek);
● Temperatura do dia em °F;
● Preço do combustível na região da loja;
● Índice de preços ao consumidor e
● Taxa de desemprego.

Entendimento do negócio/;
Através dos dados disponibilizados, foram analisados gráficos e DataFrames (Tabelas) para ser possível determinar:

● As Lojas com maiores médias de Vendas Semanais;
● Preço médio de venda semanal por loja;
● A loja com maior venda acumulada (soma de vendas de todo o período) e em quantas semanas do ano ela ultrapassou a média do período;
● Vendas máximas, mínimas e médias de todas as lojas ao longo do tempo;
● Comparativo dos preços de combustível na região da loja;
● Comparativo de taxa de desemprego;
● Índice de temperatura: para avaliar em quais lojas a temperatura média tem a possibilidade de nevar;
● Médias por loja e visualização e ordenação decrescente pelas maiores médias de venda

Com essa análise foi possível visualizar dentre as que mais vendem, o que elas têm em comum e principalmente se, dentre estes que mais vendem, tem algum que se destaca por ter índices diferentes.

Coleta de dados:
Descrição dos dados:
Feriados
Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12
Labour Day: 10-Sep-10, 09-Sep-11, 07-Sep-12
Thanksgiving:26-Nov-10, 25-Nov-11, 23-Nov-1
Christmas:31-Dec-10, 30-Dec-11, 28-Dec-12

Variáveis:
Store: Número da Loja
Date:Semana de Venda
Weekly_Sales:Venda Naquela Semana
Holiday_Flag:Flag se é ou não semana com feriado (1 - Holiday Week 0 - Non-Holiday Week)
Temperature:Temperatura do dia em °F
Fuel_Price:Preço do combustível na região da loja
CPI:Índice de preços ao consumidor
Unemployment:Taxa de desemprego
