# JUnitVanilla
Este é um pequeno projeto sobre JUnit Vanilla utilizando Java 17 como linguagem e JUnit 5 como framework para realização dos teste automatizados.

# Especificações da classe utilizada

![image](https://user-images.githubusercontent.com/100853329/174077682-cda83100-6cf2-485b-9785-8c161876b81b.png)

No caso acima, a ideia é que um financiamento tenha três dados:
- totalAmount: valor total de dinheiro financiado.
- income: renda mensal do cliente que está financiando.
- months: número de meses do financiamento.

E dois metodos: 
- entry: entrada do financiamento, igual a 20% do valor total.
- quota: prestação mensal do financiamento (sem juros).

# Teste realizados
## Construtor
- Deve criar o objeto com os dados corretos quando os dados forem válidos
- Deve lançar IllegalArgumentException quando os dados não forem válidos
## setTotalAmount
- Deve atualizar o valor quando os dados forem válidos
- Deve lançar IllegalArgumentException quando os dados não forem válidos
## setIncome
- Deve atualizar o valor quando os dados forem válidos
- Deve lançar IllegalArgumentException quando os dados não forem válidos
## setMonths
- Deve atualizar o valor quando os dados forem válidos
- Deve lançar IllegalArgumentException quando os dados não forem válidos
## entry
- Deve calcular corretamente o valor da entrada
## quota
- Deve calcular corretamente o valor da prestação

Abaixo imagem com todos os 10 testes funcionando:

![image](https://user-images.githubusercontent.com/100853329/174100001-c601b070-0a73-49fd-9e9a-aca79244088b.png)


