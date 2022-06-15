# PSet-3
### Este é o terceiro pset proposto pelo professor, no qual temos que desenvolver um projeto de Queries SQL hierárquicas (recursivas).

**Aluno:** João Vitor Rocha Moreira

**Professor:** Abrantes Araujo Silva Filho

**Foram utilizados alguns sistemas de gerenciamneto de banco de dados (SGBD), como:** 
* PostgreSQL

**Para realizar este trabalho foi necessário:**

* Rodar o script do arquivo "pset3.sql" no banco de dados "UVV" que foi criado no PostgreSQL no pset 1
* Aprender a fazer a query recursiva com os sites: https://blog.sqlauthority.com/2012/04/24/sql-server-introduction-to-hierarchical-query-using-a-recursive-cte-a-primer e https://www.sqlservertutorial.net/sql-server-basics/sql-server-recursive-cte.

**Modelo utilizado para a criação das querys recursivas:**

WITH MyCTE

AS ( SELECT EmpID, FirstName, LastName, ManagerID

FROM Employee

WHERE ManagerID IS NULL

UNION ALL

SELECT EmpID, FirstName, LastName, ManagerID

FROM Employee

INNER JOIN MyCTE ON Employee.ManagerID = MyCTE.EmpID

WHERE Employee.ManagerID IS NOT NULL )

SELECT *

FROM MyCTE

##### Resultado do PSet:
* Aprendi a utilizar o Github e Markdown
* Consegui Implementar projetos lógicos utilizando os SGBD relacionais PostgreSQL
* Aprendi a gerar diversos relatórios SQL a partir dos dados inserdos no banco de dados do primeiro PSet
* Aprendi a rodar scripts prontos no PostgreSQL
* Além de conhecer as dificuldades de criar querys recursivas


