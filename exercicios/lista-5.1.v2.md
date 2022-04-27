# Álgebra Relacional

## Lista 1 - Versão 2 (Relax)

Considere o modelo a seguir e escreve as consultas descritas abaixo utilizando as operações da álgebra relacional.

`Empregado (matr, nomeE, endereço, sexo, salario, supervisor, depto)`

`Departamento (codDepto, nomeD, matrGerente)`

`DepLocalizações (codDepto, localizacao)`

`Alocação (matrEmp, codProj, numHoras)`

`Projetos (codProj, nome, localização, deptoControla)`

`Dependentes (matrEmp, nomeDep, sexo, dataNasc, parentesco)`

1. Obtenha o nome e o endereço de todos os empregados do departamento de 'Rock'.
1. Para cada projeto localizado em ‘Picos - PI’, liste o código do projeto, o código do departamento que controla o projeto e o nome, endereço e salário do gerente deste departamento.
1. Encontre os nomes dos empregados que trabalham em todos os projetos do departamento 3.
1. Liste os nomes dos empregados que não têm dependentes.
1. Liste o nome e o número de horas alocadas de todos os empregados que trabalham em projetos do departamento de 'Blues'
1. Liste o nome de todos os empregados que possuem pai e mãe como dependentes.
1. Liste o nome dos gerentes dos departamentos localizados no Rio de Janeiro e em Sao Paulo e os seus respectivos dependentes
1. Liste o nome dos empregados cujos supervisores são também gerentes de departamento
1. Liste o nome dos projetos que possuem empregados com dependentes acima de 50 anos
1. Liste o nome de projetos cuja localização é diferente de todas as localizações do departamento que o controla.
