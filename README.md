# Homework-interface-dependency-injection-services
Exercício proposto para trabalhar com interface e injeção de dependência para entender mais a fundo!

Exercicio de altacomplexidade - Exercicio proposto: 

Uma empresa deseja automatizar o processamento de seus contratos. O processamento de um contrato consiste em gerar as parcelas a serem pagas para aquele contrato, com base no
número de meses desejado.
A empresa utiliza um serviço de pagamento online para realizar o pagamento das parcelas. Os serviços de pagamento online tipicamente cobram um juro mensal, bem como uma taxa
por pagamento. Por enquanto, o serviço contratado pela empresa é o do Paypal, que aplica juros simples de 1% a cada parcela, mais uma taxa de pagamento de 2%.
Fazer um programa para ler os dados de um contrato (número do contrato, data do contrato, e valor total do contrato). Em seguida, o programa deve ler o número de meses para
parcelamento do contrato, e daí gerar os registros de parcelas a serem pagas (data e valor), sendo a primeira parcela a ser paga um mês após a data do contrato, a segunda parcela dois
meses após o contrato e assim por diante. Mostrar os dados das parcelas na tela. 

Veja exemplo na próxima página.

![image](https://user-images.githubusercontent.com/50780211/108566398-217f4c00-72e5-11eb-9b19-9f27725fccb6.png)


UML:

Entities: 

![image](https://user-images.githubusercontent.com/50780211/108566446-322fc200-72e5-11eb-914c-e19e73663a29.png)


Services:

![image](https://user-images.githubusercontent.com/50780211/108566488-45db2880-72e5-11eb-9e9a-0582d6076bfe.png)


