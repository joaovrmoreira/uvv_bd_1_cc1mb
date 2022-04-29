# PSet-1
### Este é o primeiro pset proposto pelo professor, no qual temos que desenvolver um projeto que está nos capítulos 5 e 6 do livro texto de referência da disciplina, que é o sistema de banco de dados dos autores Elmasri e Navathe.

**Aluno:** João Vitor Rocha Moreira

**Professor:** Abrantes Araujo Silva Filho

**Foram utilizados alguns sistemas de gerenciamneto de banco de dados (SGBD), como:** 
* PostgreSQL
* MySQL/MariaDB

**Para realizar este trabalho, foram disponibilizados algumas ferramentas, tais como:**

* SQL Power Architect: comecei fazendo o projeto lógico do Pset. Depois de pronto, eu pude extrair os scripts do MariaDB/MySQL e PostgreSQL.
* Oracle VM VirtualBox: a principal ferramenta disponibilizada, uma vez que ela já vem configurada com alguns dos principais SGBD do mundo e com o SQL Power Architect.
* DBeaver: local em que usamos os SGBD do PostgreSQL e do MariaDB. Também será o local em que vou usar os scripts salvos do power architect. A partir do script do power architect, tenho que passar todos os comandos de insert que estão no Pset.

**Mudanças nos scripts e tabelas que foram necessárias:**

Precisei diminuir os comentários no power architect, porque cabiam no máximo 60 characteres. Aumentei o número de characteres do endereço na tabela funcionário para 50, pois com 30 o meu deu erro falando que não dava para inserir todo o endereço. Alterei também os dados de alguns cpf_supervisor da tabela funcionário de acordo com o numero_departamento e o cpf_gerente da tabela departamento que estavam dando erro por estar diferente do cpf do número do departamento.

##### Resultado do PSet:
* Aprendi a utilizar o Github e Markdown
* Consegui Implementar projetos lógicos utilizando os SGBD relacionais PostgreSQL e o MariaBD/MySQL
* Aprendi a criar os scripts no MariaDB e no PostgreSQL
* Além de conhecer as dificuldades de utilizar os bancos de dados e superá-las lendo a documentação dos bancos de dados 
