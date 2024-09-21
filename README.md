# Modelando um Dasboard de E-commerce com Power BI Utilizando Fórmulas DAX

Criação das novas tabelas (D_Produtos, D_Produtos_Detalhes, D_Descontos, D_Detalhes, F_Vendas) a partir de tabela origem financials. A partir da duplicidade da tabela origem Financials fiz a criação das colunas ID_ product e Índice.
A construção de ID_product foi feita no Power query através do adicionar coluna Condicional colocando o nome da coluna para cada produto e uma numeração para cada um deles, logo foram retirados os valores duplicados.

A construção da tabela ID_product foi feita no Power query através da criação do índice. 

Para fazer a criação da tabela D_Produtos, foi criada por agrupamento das informações da power query.

Logo de criar cada una das novas tabelas, foram retiradas as colunas que não tinham sentido ficar dentro das novas tabelas.

A tabela D_Calendário, foi criada por DAX com, para isso foram criadas hierarquias (ano, trimestre, messes, dias), para poder fazer a agrupação com a tabela F_Vendas (fato)
	
Logo se verificaron las agrupaciones e foram exclusas, e foram feitas novamente de forma manual, para conseguir ter o modelo final do star schema.


# Objetivo

### Entregar relatório. Repositório criado para o Desafio do Projeto.

# Ferramentas

### Power BI
