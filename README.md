![](Layout/FundoGithub.png)

Esse é um projeto de Business Intelligence.

Os conjuntos de dados utilizados estão disponíveis no repositório "Bases".

# Entendimento do Negócio

A Master Eletronics é uma empresa americana que comercializa produtos eletrônicos de forma online para todo o mundo. Apesar de sua rápida expansão, atualmente a empresa não conta com uma equipe especializada em análise de dados. 

Visando mudar esse cenário e se tornar uma empresa data driven, fomos contratados para desenvolver um dashboard que retrate de forma descritiva o desempenho das vendas nos últimos anos. O dashboard deverá conter informações referentes as marcas e produtos mais vendidos, assim como uma análise temporal que demonstre de forma visual o comparativo anual de vendas. 

# Entendimento dos Dados

Os dados disponibilizados pela Master Eletronics se referem as vendas realizadas pela empresa nos anos de 2017, 2018 e início de 2019. Os arquivos foram extraídos de diversas fontes e por isso, estão em diferentes formatos como CSV, Excel e JSON. 

Durante a fase de limpeza e transformação dos dados, várias tarefas foram aplicadas utilizando o Power Query em conjunto com as linguagens DAX e M. Além dessa etapa ser fundamental para tratar possíveis inconsistências nos dados, ela também nos permitiu criar uma modelagem eficiênte através do modelo Star Schema. 

![](Modelagem/ModeloStarSchema.png)
