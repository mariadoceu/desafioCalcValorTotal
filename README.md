Desafio — Cálculo de Pedido com Desconto e Frete
Este projeto é parte de um estudo com Java e Spring Boot, focado em consolidar conceitos de componentes e injeção de dependência. 
O desafio consiste em calcular o valor total de um pedido

Tecnologias utilizadas
- Java 17+
- Spring Boot
- Maven
- IntelliJ IDEA / VS Code

- Order: representa os dados do pedido (código, valor básico, desconto).
- OrderService: contém a lógica de cálculo do valor total com desconto e frete.

Regras de negócio
- Aplicar o desconto percentual sobre o valor básico do pedido.
- Calcular o frete com base no valor original do pedido:
- Abaixo de R$ 100,00 → R$ 22,00
- De R$ 100,00 até R$ 200,00 (exclusive) → R$ 12,00
- R$ 200,00 ou mais → Frete grátis
