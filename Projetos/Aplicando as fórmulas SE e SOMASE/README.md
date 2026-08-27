### Explorando a fórmula SE e SOMASE
Baseado na tabela de dados, o objetivo será realizar o cálculo das variáveis **Perfil Elegível**, **Público Elegível** e **Estimativa de Mercado**, a fim de simular a decisão para o lançamento de um novo produto.

- **Cálculo do Perfil Elegível:**

    Utilização da fórmula **=SE(E())** para teste lógico entre as variáveis de "Faixa Etária" e "Escolaridade". Retorna **True**, se as duas condições forem atendidas.

- **Público Elegível:**

    Utilização da fórmula **=SOMASE(intervarlo1 ;"1"; intervalo2)** para realizar a soma total da variável "População", que corresponderam ao Perfil Elegível.

- **Estimativa de Mercado:**

    É a multiplicação entre total do **Público Elegível** e o valor do **Ticket Médio** fornecido.
