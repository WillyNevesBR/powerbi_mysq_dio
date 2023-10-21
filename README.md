# powerbi_mysq_dio

Descrição do desafio módulo 3 – Processamento de Dados Simplificado com Power BI
1.	Criação de uma instância na Azure para MySQL
2.	Criar o Banco de dados com base disponível no github
3.	Integração do Power BI com MySQL no Azure 
4.	Verificar problemas na base a fim de realizar a transformação dos dados

Diretrizes para transformação dos dados
1.	Foi verificado todos os cabeçalhos e alguns modificados para o PT-BR.
2.	Valores monetários alterados para Decimal Fixo.
3.	Nulos alterados.
4.	Alterado null para dno 1.
5.	Departamentos verificados.
6.	Alterado as lacunas.
7.	Hora sem alterações.
8.	Separado colunas de endereço, mesclado entre endereço número e cidade, Removendos os dados nulos.
9.	Mescla entre employer e departamento com remoção de data de inicio e criação.
10.	Colunas dnum e project removidas.
11.	Criada nova tabela para junção Colaborador/Gerente.
12.	Nome e sobrenome mesclado em um coluna.
13.	Criação de nova tabela com junção de departamento e local.
14.	A função mesclar utiliza apenas uma coluna comum para relacionar tabelas, se fosse utilizar o atribuir iria adicionar as linhas da tabela abaixo da outra.
15.	Tabela criada com dados de contagem de gerentes.
16.	Colunas foram removidas, já que não teriam utilidade.
