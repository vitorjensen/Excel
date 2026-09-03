
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
  
#### Metodologia SOM (SERVICEABLE OBTAINABLE MARKET)

- Mercado útil acessível.
- Parcela da SAM que realmente pode ser capturada.
- Faz algumas considerações: Capacidade comercial, Concorrência e Maturidade de Mercado.
- Responde: O quanto conseguimos converter em receita?

Definição de **Taxa de Penetração:**
Percentual do mercado que a empresa consegue capturar.

Isso é baseado em:
      1. Força de Venda.
      2. Posicionamento de Mercado.
      3. Benchmark competitivo.
      
A SOM pode ser pautada em alguns cenários:
      1. Conservador = 1%
      2. Realista = 3%
      3. Agressivo = 5%

