
### Aplicando o cálculo das fórmulas de TAM, SAM e SOM utilizando o Excel

#### Metodologia TAM (Mercado Total Endereçável)

- Calcula a estimativa do **mercado total potencial** para um produto/serviço
- Utilizado para formular planejamentos estratégicos e priorização de mercados.
Responde: Qual o tamanho máximo da oportunidade?

      TAM = Número de clientes potenciais x Ticket médio anual

- Fórmula de cálculo para TAM no Excel:
  
      =SOMASE(Total!B:B;"5 a 9 anos";Total!C:C )  + SOMASE(Total!B:B;"10 a 14 anos";Total!C:C)

#### Metodologia SAM (Mercado Útil Acessível)

- Nem toda TAM é "acessível".
- Representa o mercado que se consegue atender com o produto atual.
- Traz a visão macro para mais perto da realidade.
- Responde: Onde consigo atuar com eficiência?

      SAM = Número de clientes atendível x Ticket médio anual

- Fórmula de cálculo para SAM no Excel:

      =SOMASE(Total!A:A;'Premissas e Cálculos'!A20;Total!C:C)
  
