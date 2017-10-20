# SQL - Consultas Avançadas

## Lista 1

![modelo-banco](https://raw.githubusercontent.com/andremeirelesa/ufc-bancos-de-dados/master/images/bd-algebra-relacional-modelo02.png)

1. Consulte o nome dos clientes que possuem transações maiores que todas as transações de "Joao Silva" (Dica: use ALL)
1. Consulte os nomes dos clientes que não possuem nenhuma conta (Dica: use EXISTS) 
1. Consulte o nome dos clientes cadastrados nas mesmas agências onde a cliente "Ana Maria" está cadastrada. (Dica: Use EXISTS e EXCEPT)
1. Consulte o RG dos clientes cadastrados nas agências de número 1, 2 ou 3 (Dica: use conjunto como constante)
1. Consulte o número das agências que possuem pelo menos uma conta que não tem transação.
1. Consulte o RG dos clientes com saldo maior que que o saldo do cliente de maior saldo das agências de Crateús.
1. Consulte do nome do cliente, o número das contas, o saldo, os valores das transações e as datas das transações de todos os clientes das agências de Sobral. Use JOIN.
1. Consulte os nome dos funcionários que trabalham em agência que possuem algum cliente com o mesmo nome daquele funcionário.
1. Consulte o RG, o nome, e o número da contas de TODOS os clientes. Caso o cliente não possua conta, o número da conta deve apresentar o valor NULL.
1. Consulte a soma e a média dos valores das transações do cliente "Jose Vieira"
1. Consulte a quantidade de contas que o cliente "José Vieira" possui na agência 340
1. Consulte o número das agências que possuem mais de 100 clientes cadastrados (Dica: use COUNT na consulta interna)
1. Consulte o número da conta e a quantidade de transações para cada conta (Dica: use GROUP BY)
1. Consulte o número, a cidade, a média, o menor salário, o maior salário e a soma dos salários de cada agência.
1. Consulte a quantidade de contas que não possuem transação.
1. Consulte o número e a cidade das agências com média salarial maior que a média salarial da agência da cidade de Sobral.
1. Consulte o número da agência, a cidade, e a quantidade de contas para todas as agências com mais 50 contas (Dica: use GROUP BY e HAVING)
1. Consulte o número das contas e a quantidade de transações com valor acima de 20.000 das contas com mais 150 transações (Dica: precisa de consulta interna)
