![](Layout/FundoGithub.png)

Esse é um projeto de Business Intelligence.

Os conjuntos de dados utilizados estão disponíveis no repositório "Bases".

# Entendimento do Negócio

A Master Eletronics é uma empresa americana que comercializa produtos eletrônicos de forma online para todo o mundo. Apesar de sua rápida expansão, atualmente a empresa não conta com uma equipe especializada em análise de dados. 

Visando mudar esse cenário e se tornar uma empresa data driven, fomos contratados para desenvolver um dashboard que retrate de forma descritiva o desempenho das vendas nos últimos anos. O dashboard deverá conter informações referentes as marcas e produtos mais vendidos, assim como uma análise temporal que demonstre de forma visual o comparativo anual de vendas. 

# Entendimento dos Dados

Os dados disponibilizados pela Master Eletronics são referentes ao anos de 2017, 2018 e início de 2019. Os arquivos foram extraídos de diversas fontes e por isso, estão em diferentes formatos como CSV, Excel e JSON. 

• Vendas: tabela com informações históricas das vendas entre 01/01/2017 a 16/03/2019. <br>
• Meta 2017: contém as metas de vendas a serem alcançadas para cada continente e categoria de produto no ano de 2017. <br>
• Meta 2018 e 2019: contém as metas de vendas a serem alcançadas para cada continente e categoria de produto nos anos de 2018 e 2019. <br>
• Clientes: tabela com informações cadastrais dos clientes. <br>
• Localizacao: tabela com informações sobre as localidades de vendas (cidades, países e continentes). <br>
• Produtos: tabela com a descrição das marcas e produtos. <br>
• Subcategoria: informações complementares dos produtos vendidos pela empresa. <br>



Durante a fase de limpeza e transformação dos dados, várias tarefas foram aplicadas utilizando o Power Query em conjunto com as linguagens DAX e M. Além dessa etapa ser fundamental para tratar possíveis inconsistências nos dados, ela também nos permitiu criar uma modelagem eficiênte através do modelo Star Schema. 

![](Modelagem/ModelagemStarSchema.png)
