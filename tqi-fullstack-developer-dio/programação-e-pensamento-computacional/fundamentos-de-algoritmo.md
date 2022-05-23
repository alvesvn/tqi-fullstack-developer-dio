# Tipologia e Variáveis



Qual a função do computador? processar informações compostas por dados e instruções. 

**Tipos de dados existentes:** 

**Numéricos:** 

- Inteiros: positivos ou negativos que não possui casas decimais
- Reais: positivos e negativos com casas decimais

**Caracteres:**

- Tudo aquilo que não representa um numero. 
- Letras, símbolos, números. 

**Booleano - Lógico**: 

- Verdadeiro - 1. 
- Falso - 0. 



**O que é uma variável?** 

- É um tipo de estrutura que pode variar dentro do seu valor, inconstante. 

- Pode modificar.

- Estrutura que ira receber um tipo de dado, mas que nao tem certeza do seu valor. 

- Pode assumir qualquer um dos valores de um determinado conjunto de valores. 

- Ela esta restrita ao seu tipo, ex: se é numérica, só vai receber números. Se for caracteres, só caracteres. 

- Imagine um armário, com varias gavetas, cada uma dessas gavetas é uma variável, com um tipo e seus respectivos dados.

  

![Gavetas! Introdução à Variáveis em Linguagem C - Tiago Salem](https://tiagosalem.com.br/wp-content/uploads/2017/02/variaveis-em-linguagem-c.png)



**BOAS PRATIAS PARA UTILIZAR VARIÁVEL - REGRAS.** 

- Atribuição de um ou mais caracteres
- Primeira letra - não número
- Sem espaços em branco
- Vedado utilização de palavras reservadas
- Caracteres e números. 

Ex: x2, Nome_usuário, Telefone. 



**OBJETIVO DA VARIÁVEL:**

- Ação - modificação de estado do algoritmo.
- Controle: vigiada, controle - de alguma estrutura. 



Tudo aquilo que é fixo ou estável - **constante** 

Objetivo da constante: dados tratados e processados - não podem ser variados. 



# Instruções primitivas 



 Cálculo matemáticos   -> operadores  > binário ou unário. 

- variáveis

- constantes

  

  **Instruções**: linguagem de palavra chave determinada de programação que tem por finalidade comandar um computador que ira tratas os dados. 

  

  entrada > processamento e saída de dados. - estrutura sequencial. 

  

# Estruturas condicionais e operadores



**ENTENDENDO OS CONCEITOS.**

Estado de uma pessoa ou coisa -> condição 

Que expressão ou condição ou suposição > condicional. 



**Estrutura condicional**

- **Simples**: condição > operação
- **Composta**: Condição > exceção / operação. 
- **Encadeada**: condição > condição > exceção. 7

**OPERADORES RELACIONAIS** 

![Operadores Relacionais em C](data:image/png;base64,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)



**ESTRUTURA CONDICIONAL** **COMPOSTA**

Se/Se não

![Estruturas condicionais e de repetição | Blog TreinaWeb](https://dkrn4sk0rn31v.cloudfront.net/uploads/2020/10/Estrutura-Condicional-Simples.png)



**ESTRUTURA CONDICIONAL ENCADEADO.** 

![Estruturas de Condição Encadeadas](http://www.cristiancechinel.pro.br/my_files/algorithms/bookhtml/img180.png)



**OPERADORES LÓGICOS** 

- AND 

- OR

- NOT

**Quando utilizar?** 

- AND: verifica as entradas que devem ser satisfeitas. 

- OR: apenas uma das condições - deve ser verdadeira. (UNIAO)
- NOT - operador de negação. 



**ESTRUTURAS DE REPETIÇÃO**

- Laço - repetição - controle de fluxo - loop. 
- Condições de parada: numero de repetições pré-fixada, condições a ser satisfeita.
- Podemos utilizar e mesclar estruturas uma dentro da outra. 

Essas estruturas acarretam uma redução de linhas, compreensão facilitada, redução de erro. 



# Vetores e Matrizes 

Vetores é uma sequencia de tipos de dados. 

**Vetor** (array uni-dimensional) **é uma** variável que armazena várias variáveis do mesmo tipo. 

**Definição**: "*um vetor é caracterizado por uma variável dimensionada com tamanho pré-fixado*"

- Numéricos: 

   Inteiros

   Reais 

**Definição matriz:** matriz é uma tabela organizada em linhas e colunas no formato m x n, onde o m representa o número de linhas (horizontal) e o n o número de colunas (vertical).

**Ex:** 

vetor conjunto [1..8]  <inteiro

vetor [15] 

vetor []

 

# Funções 

 Similar ao conceito de função matemática. 

Elemento A -> B 

Definição formal: 

- As funções, ou sub-rotinas sao blocos de instruções que realizam tarefas específicas. 

  Vem da ideia de decomposição do algoritmo. 

**MODULARIZAÇÃO DO PROBLEMA.** 

**Benefícios:** código mais claro, conciso, reutilização de instruções. 



**Funções**

- Definição
- Nome
- Invocação
- Variável local 

São destruídas ao encerrar a função

Dados enviados a função > retornado o resultado da operação proposta a ser executada.

**Exemplo**

​					funcao mediaescolar (nota1, nota2)

​						resultado = 0

​						resultado = (nota1 + nota2 ) /2

​						retorne resultado

​						fim funcao

Se você precisa alterar a média, não tem muito trabalho na alteração do código. 



# Instruções de entrada e saída. 



*Dados > Processamento > Resultado* 



Quais os tipos de dados e como inserir os dados? 

Como exibir meu resultado? 



**Definição formal:** 

- Instruções de entrada e saída: *consiste na inserção e recebimento de dados do mundo real por meio de ação de alguma interface, seja teclado, mouse, arquivos, entre outros.* 

  

Temos interface relacionadas ao computador que permitem inserir dados e imprimir dados. 

**Definição saída:** 

- *Consiste na impressão dos dados do mundo abstrato, digital por meio de ação de alguma interface. Os formatos podem varias desde simples arquivos binários até complexas querys de banco de dados.* 

Impressão em tela, banco de dados, sistemas. 

**INSTRUÇÕES DE ENTRADA E SAÍDA.** 

- Saída programada: condicional ou incondicional. 

  Quando condicional guarda o dispositivo para imprimir os resultados. 

- Saída por interrupção: saída definida pelos periféricos 

**PARA TODA SAÍDA:** 

Bem sucedida

Erro de sintaxe ou outro 

Erros de programação 

Problemas de interface. 

