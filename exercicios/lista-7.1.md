# SQL - DML

## Lista de Exercícios 7

Escreva as instruções DDL da SQL para declarar o esquema de banco de dados relacional a seguir.

`empregado (id, cpf, nome, endereco, sexo, salario, supervisor_id, departamento_id)`

`departamento (id, nome, gerente_id) `

`departamento_localizacao (departamento_id, localizacao)`

`projeto (id, nome, localizacao, departamento_id)`

`alocacao (projeto_id, empregado_id, numHoras)`

`empregado_dependente (empregado_id, nome, sexo, data_nascimento, parentesco)`

Importe este arquivo de dump no seu servidor MySQL: [empresa-dump.sql](https://drive.google.com/file/d/0B0y5EoTTrjktamVrZm5uVDVIdUE/view?usp=sharing&resourcekey=0-sPYtZMOVUdMpZF-EdEKoeg). 
No PHPMyAdmin, basta copiar todo o conteúdo do arquivo, colar no editor de SQL e executar.


Utilizando linguagem SQL, execute as seguintes operações no banco acima:

1. Insira uma tupla em cada tabela.
1. Faça com que os projetos localizados em Santa Luzia - PB passem a ser controlados pelo departamento de código 3.
1. Remova os dependentes com grau de parentesco “FILHO” do sexo masculino que têm mais de 21 anos.

Utilizando linguagem SQL, execute as seguintes consultas no banco acima:

1. Obtenha o nome e o endereço de todos os empregados do departamento de 'Rock'.
1. Para cada projeto localizado em ‘Picos - PI’, liste o código do projeto, o código do departamento que controla o projeto e o nome, endereço e salário do gerente deste departamento.
1. Liste os nomes dos empregados que não têm dependentes.
1. Liste o nome e o número de horas alocadas de todos os empregados que trabalham em projetos do departamento de Blues
1. Liste o nome de todos os empregados que possuem pai e filho como dependentes
1. Liste o nome dos gerentes dos departamentos localizados no Rio de Janeiro - PB e em Piracuruca - PI e os seus respectivos dependentes
1. Liste o nome dos empregados cujos supervisores são também gerentes de departamento.
1. Liste o nome de projetos cuja localização é diferente da localização do departamento que o controla.
