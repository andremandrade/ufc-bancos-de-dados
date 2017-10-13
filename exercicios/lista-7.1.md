# SQL - DML

## Lista 1

Escreva as instruções DDL da SQL para declarar o esquema de banco de dados relacional a seguir.

`empregado (id, cpf, nome, endereco, sexo, salario, supervisor_id, departamento_id)`

`departamento (id, nome, gerente_id) `

`departamento_localizacao (departamento_id, localizacao)`

`projeto (id, nome, localizacao, departamento_id)`

`alocacao (projeto_id, empregado_id, numHoras)`

`empregado_dependente (empregado_id, nome, sexo, data_nascimento, parentesco)`

Utilizando linguagem SQL, execute as seguintes operações no banco acima:

1. Insira uma tupla em cada tabela
1. Faça com que os projetos localizados em Brasília passem a ser controlados pelo departamento de código 25
1. Remova os dependentes com grau de parentesco “filho(a)” do sexo masculino que têm mais de 21 anos.

Utilizando linguagem SQL, execute as seguintes consultas no banco acima:

1. Obtenha o nome e o endereço de todos os empregados do departamento de Pesquisa.
1. Para cada projeto localizado em ‘Natal’, liste o código do projeto, o código do departamento que controla o projeto e o nome, endereço e salário do gerente deste departamento.
1. Liste os nomes dos empregados que não têm dependentes.
1. Liste o nome e o número de horas alocadas de todos os empregados que trabalham em projetos do departamento de Recursos Humanos
1. Liste o nome de todos os empregados que possuem pai e mãe como dependentes
1. Liste o nome dos gerentes dos departamentos localizados no Rio de Janeiro e em Sao Paulo e os seus respectivos dependentes
1. Liste o nome dos empregados cujos supervisores são também gerentes de departamento.
1. Liste o nome de projetos cuja localização é diferente da localização do departamento que o controla.
