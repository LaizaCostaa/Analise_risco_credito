# Analise exploratoria de risco de crédito

O objetivo desse material é realizar uma análise descritiva para identificar os clientes com maior probabilidade de default(risco de crédito)

1. TRATAMENTO DOS DADOS
  - Exclusão das linhas nulas do default;
  - Substituição dos valores faltantes do limite de crédito e do número de empréstimos com inadiplência pela mediana;
  - Substituição das variáveis qualitativas (genero, perfil_facebook, signo) pela moda

***********************************************************************************

2. ANÁLISE EXPLORATÓRIA
  Passo 1 - Análise das variáveis qualitativas

  Resumo:

  Variável resposta (Default): possui classes desbalanceadas;
  Signo: As classes possuem contagens parecidas, exceto pela contagem dos 'desconhecidos', que representam 31% dos dados, logo, optei por apagar essa coluna para não perder a informação dessas linhas;
  Gênero: O desconhecido será substituído por 'masculino', já que possui uma frequência maior;
  Perfil_facebook: o desconhecido será substituído por falso.


 ---------------


  Passo 2 -Análise das variáveis quantitativas

  Resumo:

  A taxa de risco teve um pico em torno de 0.3;
  75% pediram empréstimo no valor de até 18.036,6;
  75% tem limite de crédito atpe 35125 e o valor máximo foi de 613117;
  75% tem renda até 8.500;
  75% não foram inadiplentes com empréstimos.
