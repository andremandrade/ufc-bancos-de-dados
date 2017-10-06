# SQL - DDL

## Lista 1

Escreva as instruções DDL da SQL para declarar o esquema de banco de dados relacional a seguir.

`empregado (id, cpf, nome, endereco, sexo, salario, supervisor_id, departamento_id)`

`departamento (id, nome, gerente_id) `

`departamento_localizacao (departamento_id, localizacao)`

`projeto (id, nome, localizacao, departamento_id)`

`alocacao (projeto_id, empregado_id, numHoras)`

`empregado_dependente (empregado_id, nome, sexo, data_nascimento, parentesco)`

*REGRAS DE NEGÓCIO:*
1. O empregado pode ficar eventualmente sem supervisor ou não estar lotado em nenhum departamento.
1. O CPF do empregado deve ser único.
1. O departamento pode ficar eventualmente sem gerente.
1. A localização só deve existir se estiver associada a algum departamento, por isso, caso um departamento seja apagado, suas localizações também devem ser apagadas.
1. O projeto sempre precisa está associado a um departamento, por isso, um departamento só pode ser apagado se não tiver nenhum projeto associado a ele.
1. Quando um empregado é apagado, suas alocações em projetos também devem ser apagadas.
1. Um projeto só pode ser apagado quando não houver mais empregados alocados nele.
1. Quando um empregado é apagado, seus dependentes também devem ser apagados.
