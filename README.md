# PLSQL

    1. Criar uma procedure que quando for informado o código do cliente ela retorne o valor pago por ele pelas locações realizadas no período de janeiro de 2006 a dezembro de 2006. Somente devem ser retornadas informações para os clientes cadastrados, caso o cliente não exista na base de dados deve ser informado ao usuário, também deve ser informado ao usuário caso o período informado não exista locações de fitas por parte do cliente.

    2. Criar uma procedure que retorne o valor total de fitas compradas em um determinado intervalo de data. Caso o intervalo de data não exista nenhuma compra, deve ser retornada a mensagem “Neste período não foram adquiridas novas fitas para a locadora”.

    3. Criar uma procedure que permita localizar o cliente que mais efetuou locações no ano de 2007, bem como o valor total pago por estas locações.

    4. Criar uma procedure que receba os dados de um ATOR, de um FILME e efetue a inclusão do mesmo no banco de dados. Também deve ser relacionado o ator ao filme na tabela FILMES_ATOR.

    5. O Gerente Geral empresa em que você trabalha solicitou ao DBA um relatório dos vendedores que tenham comissão acima de R$1.000,00 independente do percentual de comissão que cada vendedor recebe. Esta solicitação foi necessária visto que o sistema existente atualmente não contempla este tipo de relatório gerencial, e para complicar ainda mais, o gerente disse que está indo em 10 minutos para uma reunião com o Diretor Presidente da empresa e o resultado bem sucedido da reunião vai depender de você. Após o susto, você decide implementar uma SP para resolver o problema. Dentro das possibilidades existentes para a criação da SP, implemente a solução do problema apresentado utilizando uma tabela de vendedores na qual deve conter os seguintes atributos: VENDEDORES = {vendedor, nome, comissão, total_vendas}. Alimente a tabela com as informações que julgar necessário. 
O relatório gerado deverá possuir o nome do vendedor, o total de suas vendas, o percentual de sua comissão, o valor que ele irá receber de comissão, o total geral das vendas de todos os vendedores, e o percentual de sua comissão relativa ao total geral das vendas.
