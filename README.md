# Banco-de-dados-.I
Para transformar a tabela em anexo na Primeira Forma Normal (1FN), precisamos remover a repetição de dados, identificar as chaves primárias e criar tabelas separadas para cada entidade.

A tabela em anexo possui as seguintes colunas:

ID	Nome	Email	Telefone
1	João	joao@email.com	(11) 1234-5678
2	Maria	maria@email.com	(21) 9876-5432
3	Pedro	pedro@email.com	(31) 4567-8901
4	Ana	ana@email.com	(41) 2345-6789
Para normalizá-la na 1FN, podemos identificar as seguintes entidades:

Pessoa:

ID	Nome
1	João
2	Maria
3	Pedro
4	Ana
Contato:

ID	Email	Telefone
1	joao@email.com	(11) 1234-5678
2	maria@email.com	(21) 9876-5432
3	pedro@email.com	(31) 4567-8901
4	ana@email.com	(41) 2345-6789
Na 1FN, cada tabela possui sua própria chave primária. A tabela "Pessoa" possui o atributo "ID" como chave primária, enquanto a tabela "Contato" também possui o atributo "ID" como chave primária. Agora, cada dado está atomicamente representado em tabelas separadas, evitando a repetição de dados e garantindo que cada tabela esteja na 1FN.

