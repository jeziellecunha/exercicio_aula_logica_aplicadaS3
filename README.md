## Workshop Back end - Reprograma

#### Exercício Lógica aplicada - Loop, Escopo e Função

**Professora: Simara Conceição**

**Aluna: Jezielle Cunha**



​	Com a resolução do exercício , trabalhamos o conteúdo exposto durante a aula  de Lógica aplicada do dia 22 de maio de 2021. Com isso, o aprendizado sobre estrutura de repetição, funções e comandos especiais (break/continue), além da ferramenta debug do VScode foi reforçado.

Abaixo como foi solucionada cada questão:	

**1 -**  _Crie um algoritmo que imprime no console de 10 a 60, iterando a cada 5, exceto para os numeros 35 e 45 que irão ser substituidos pela palavra "PULOU"._

No quesito 1 foi utilizada a estrutura de repetição While para contar de 10 a 60 incrementando de 5 em 5, dentro dela, foi colocado um If para que na condição de 35 ou 45 a instrução seja pulada (continue) e seja impresso no console "Pulou"!.

**2 -** _Crie um algoritmo que converte dias em horas, quando recebe um número de dias._

Para realizar essa tarefa, foi criada a função converterDiaEmHoras, onde a constante horas recebe o parâmetro dias e multiplica por 24, calculando quantas horas tem aquela quantidade de dias.

**3 -** _Crie uma função que recebe 2 parâmetros e retorna o resultado da divisão entre eles. Além disso, se o resto dessa divisão for zero deverá imprimir no console o valor e dizer que ele é par._

A função dividir recebe dois parâmetros correspondentes aos valores que devem ser divididos. Após a divisão, para saber se o resultado é par foi colocado dentro de um If a verificação se o resultado dividido por 2 é igual a zero, nessa condição o valor é par e isso é impresso em console.

**4 -** _Utilize a estrutura de repetição for para imprimir no console conforme instruções abaixo:_
    _a) números de 1 a 100_  
    _b) quando chegar no número 50 interrompa a instrução e pare o loop_
    _c) quando chegar no número 50 pule a instrução_

Para atender o quesito 4 foi feito uma iteração do tipo For onde começa por 1, termina em 100 e o incremento acontecia de um em um. Depois um If , na condição de i igual 50, implementa um Break. Para pular o numeral 50, foi colocado um If,onde no momento que i for igual a 50 o comando Continue irá pular esse numeral e prosseguir com a contagem.

**5 -** _Vamos criar uma calculadora com as 4 operações matemáticas básicas?_

_a) Deverá ser possível escolher uma operação aritimética em forma de string: 'soma', 'multiplicacao', 'divisao' e 'subtracao'_
_b) Deverá ser possível passar 2 números para a operação escolhida_
_c) Deverá retornar o resultado e imprimir no console_

Para resolver essa questão foi feito uma função para cada operação aritmética, onde recebem num1 e num2 para realizar a operação. E por meio da estrutura condicional Switch/Case foi verificada a operação desejada e chamada a função para que o resultado fosse impresso no console.

