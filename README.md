# Pratica1_PDS1

Exercício 1: Código do nome

Escreva um programa para imprimir o seu primeiro nome em código ASC. Se o seu nome for “Ana”, o seu programa deve imprimir “65 110 97”.

Exercício 2: Troca de valores

Considere o programa abaixo:

    #include <stdio.h>
    void main(){
      float a = 3.14159, b = 2.71828;
      printf(“\nPI = %f”, b);
      printf(“\nEULER = %f”, a);
    }

Note que o programador trocou as variáveis que deveriam ser exibidas em cada printf. Assim, altere o programa acima de forma a corrigir o erro do programador. O problema é que o programador proibiu que você altere o que ele escreveu e também que digite os valores das constantes novamente. Então, faça isso (1) sem alterar nenhuma linha que o programador escreveu e (2) sem escrever novamente as constantes 3.14159 e 2.71828. Dica: troque os valores armazenados em cada variável.

Exercício 3: Conta Poupança

Uma conta poupança foi aberta com um depósito de R$789,54, com rendimentos de 0.56% de juros ao mês. No segundo mês, R$303,20 reais foram depositados nessa conta poupança. No terceiro mês, R$58,25 reais foram retirados da conta. Implemente um programa que imprime quanto haverá nessa conta no quarto mês.

Resposta: A conta terá R$1050,91 no quarto mês.

Exercício 4: IMC

Brutus e Olívia foram ao médico, que disse a eles que ambos estão fora do peso ideal. Ambos discordaram veementemente da afirmação do médico. Para provar que estava certo, o médico mostrou o Índice de Massa Corporal (IMC) de ambos, considerando que Brutus tem 1,84m e pesa 122kg e que Olívia tem 1,76m e pesa 45kg. Implemente um programa para mostrar o IMC de Brutus e Olívia e qual é a quantidade mínima de quilos que Brutus e Olívia devem perder ou ganhar para atingirem um peso saudável segundo a classificação do IMC. Use a seguinte fórmula para cálculo do IMC:                    
                   IMC = pesoaltura  altura

A tabela abaixo descreve a classificação para as faixas de IMC.


IMC

Classificação

    < 16 - Magreza grave
    16 a < 17 - Magreza moderada
    17 a < 18.5 - Magreza leve
    18.5 a < 25 - Saudável
    25 a < 30 - Sobrepeso
    30 a < 35 - Obesidade grau I
    35 a < 40 - Obesidade grau II (severa)
    ≥ 40 - Obesidade grau III (mórbida)

Resposta: O IMC do Brutus é 36,03 e o IMC da Olívia é 14,53. Brutus precisa perder, no mínimo, (aproximadamente) 37 quilos e Olívia precisa ganhar, no mínimo, (aproximadamente) 12 quilos.

Desafio para os fortes

Dígito verificador ou algarismo de controle é um mecanismo de autenticação utilizado para verificar a validade e a autenticidade de um valor numérico, evitando dessa forma fraudes ou erros de transmissão ou digitação. Consiste em um ou mais algarismos acrescentados ao valor original e calculados a partir deste através de um determinado algoritmo. Números de documentos de identificação, de matrícula, cartões de crédito e quaisquer outros códigos numéricos que necessitem de maior segurança utilizam dígitos verificadores. Esse trabalho consiste em calcular o dígito verificador do CPF. Seu programa deve receber um cpf sem o dígito verificador do usuário e imprimir o CPF com o dígito verificador. Você pode usar o seu CPF e de parentes e colegas para testar o programa. A seguir, as regras para o cálculo do dígito verificador são definidas através de um exemplo. É utilizado como exemplo o número: 123456789.
Calcule a soma dos produtos dos nove dígitos utilizando peso 2 para unidade, peso 3 para dezena, peso 4 para centena e assim sucessivamente.  Exemplo: 9*2+8*3+7*4+6*5+5*6+4*7+3*8+2*9+1*10 = 210.

A dezena do número verificador é 0 caso o resto da divisão por 11 da soma dos produtos seja 0 ou 1; caso contrário a dezena corresponde  a subtrair de 11 o resto da divisão por 11 da soma dos produtos. 

Calcule a soma dos produtos dos dez dígitos, onde o dígito menos significativo passa a ser a dezena dos dígitos verificadores, utilizando os seguintes pesos: 2, 3, 4, 5, 6, 7, 8, 9, 10, 11; 

A unidade do número verificador é 0 caso o resto da divisão da soma dos produtos seja 0 ou 1; caso contrário a unidade corresponde a 11 menos o resto da divisão por 11 da soma dos produtos. Exemplo: resto da divisão de 255 por 11 é 2 então a unidade do número verificador é 11-2=9
Dica: para resolver esse problema, você precisa aprender três conceitos que ainda não foram ensinados em sala de aula: leitura de dados a partir do teclado, resto da divisão entre dois números, e processamento condicional. Para o primeiro conceito, procure saber como funciona a função scanf, que é da biblioteca stdio.h. Para o segundo conceito, procure saber como funciona o operador %, ou mod. Por fim, e mais difícil que os conceitos anteriores, procure saber como funciona o comando if e else da linguagem C. O aprendizado de uma linguagem depende muito da sua iniciativa de correr atrás das soluções. Esse exercício é uma forma de incentivar a autodidática. 

