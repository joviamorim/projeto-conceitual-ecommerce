# projeto-conceitual-ecommerce

## **Resumo do desafio**
O diagrama desse desafio foi construido durante as aulas, e apenas algumas tabelas foram adicionadas durante o desafio, sendo elas:
* PJ
* PF
* Pagamento
* Entrega

### **Descrição das tabelas:**
* **PJ e PF:** São as tabelas de pessoa física(PF) e pessoa jurídica(PJ). Ambas as tabelas são especializações de cliente, em que o tipo de pessoa influenciará em qual delas será utilizada, já que é uma restrição do projeto a utilização de apenas uma das tabelas. A cardinalidade dessas tabelas será (1,1).
* **Pagamento:** A tabela pagamento herdará as informações da tabela cliente. A cardinalidade será de (1,n), pois um cliente pode ter mais de uma forma de pagamento.
* **Entrega:** Essa tabela será responsável pelas informações de entrega de um pedido. A tabela Entrega herdará todos os dados da tabela Pedido. Um pedido pode ser feito, mas não obrigatoriamente ser entregue, já que o pedido pode ser cancelado antes de sair para entrega. Dessa forma, a tabela Entrega será dependente da tabela Pedido.
####[Confira o Diagrama](diagramaECommerce.png)