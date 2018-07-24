# semantix-bank
desafio proposto pela empresa semantix


Além das bibliotecas nativas do pacote anaconda (usei o jupyter notebook para criar as análises), será necessário fazer o download da biblioteca MLxtend.


Minhas respostas para o desafio estão abaixo e inseridas no código.

1) A profissão com maior tendência de contratar empréstimo é a de estudantes, pois possui a maior taxa de conversão (40%) para as ofertas entre todas profissões. A oferta mais popular entre os estudantes é a da modalidade housing. Ainda, é notável que devido ao número superior de gerentes na base, os impréstimos concedidos aos gerentes representam 25% do total de empréstimos, mas sua taxa de conversão é somente de 15%.

2) Sobre a relação entre número de contatos e o sucesso da campanha é notável que a mediana e a média são próximas a 2 ligações, isso significa que a maior parte das conversões da campanha acontecem até o segundo contato. É possível observar também que a moda é igual a 1, significando que a maior parte das conversões aconteceu na primeira ligação desta campanha. No gráfico que exemplifica os percentuais é evidenciado o percentual de sucesso da primeira ligação (48,42%).

3) A média atual das conversões de ligações por sucesso é de 2,14, sendo que 48,42% dos sucessos aconteceram na primeira ligação, 26,49% para a segunda e 11,68% para terceira ligação. Para otimizar os esforços, a proposta é de que o número máximo de ligações para o mesmo cliente deva ser de 3 contatos, pois o sucesso de até 3 ligações somados representam quase 90% das conversões. É necessário também que mais de 50% dos casos a conversão aconteça na primeira ligação, para que a média ideal de conversões por ligação seja menor que 2.

4) Todas as pessoas da campanha anterior estão na atual e receberam ao menos uma ligação na campanha anterior. É difícil estabelecer uma relação de depência comportamental dos eventos da campanha anterior e atual, mas é fato que todos os sucessos da campanha atual também receberam ligações da campanha anterior. De 1511 conversões da primeira campanha, 978 voltaram a comprar na campanha atual, uma retenção de 64%. Ainda, a média de ligações de sucesso somando campanha anterior e atual é de 3,81. Portanto, Há um relação de fidelização de mais da metade das conversões da primeira campanha e elas impactam na no aceite da campanha atual.

5) Provavelmente se o cliente não tem renda declarada ou se já tem um crédito contratado, mas não há dados para explorar essa hipótese pois não encontrei uma coluna indicando o seguro de crédito.

6) As caraterísticas mais proeminentes de um cliente que possua crédito na modalidade housing são: ser casado, não possuir crédito pessoal e não ter crédito em default. Interessante observar que é comum nesses clientes ter o status do outcome da primeira campanha como 'unknown' e a resposta da camanha atual como 'no'
