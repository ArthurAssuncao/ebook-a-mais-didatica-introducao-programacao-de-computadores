# 5.2. Operadores e Expressões

Para realizar operações ou comparações existem operadores, como na matemática. Essas operações são úteis para, por exemplo somar, subtrair, dividir, multiplicar valores literais ou variáveis, comparar se uma variável é maior que um valor literal ou outra variável e muito mais. Caso não tenha entendido, imagine que um usuário digite a idade em um sistema de compra de bebida alcoólica, o sistema pode verificar se está idade é igual ou maior que 18 \(idade mínima para consumo de bebidas alcoólicas no Brasil\).

## 5.2.1. Expressões literais e aritméticas

Para criar expressões literais e aritméticas precisamos dos operadores de atribuição e aritméticos, cada linguagem tem o seu conjunto de operadores onde os principais são atribuição, adição, subtração, multiplicação, divisão, módulo \(resto da divisão inteira\) e exponenciação.

Abaixo apresento a tabela 6.1 com os principais operadores de atribuição e aritméticos de cada linguagem apresentada neste livro. Ressalto que há muitos outros em cada linguagem, contudo não são muito usados.

Tabela 6.1. Operadores de Atribuição, Aritméticos e concatenação de strings.

| Operador | Scratch \(comando\) | Portugol Studio | Linguagem C |
| :--- | :--- | :--- | :--- |
| Atribuição | `mude <variável> para <0>` | = | = |
| Atribuição por adição | `adicione <1> a <variável>` | += | += |
| Incremento\* | Não tem | ++ | ++ |
| Decremento\* | Não tem | -- | -- |
| Adição | + | + | + |
| Subtração | - | - | - |
| Multiplicação | \* | \* | \* |
| Divisão | / | / | / |
| Resto de divisão inteira | `resto de <> por <>` | % | % |
| Exponenciação | Não tem | ^ | Não tem |
| Concatenação de string | `junta <maça> com <banana>` | + | Não tem |

\*A linguagem C permite o uso dos operadores de incremento e decremento de duas formas, pré e pós-fixado, enquanto a linguagem Portugol 2.0 apenas o pós-fixado.

Há algo novo na tabela, o conceito de concatenação, esta é uma operação com valores tipo carácter e string \(conjunto de caracteres\) onde a adição realiza a junção de dois ou mais valores. Por exemplo, `'arthur' + ' assuncao'` resulta em `'arthur assuncao'`. Contudo, perceba que nem todas linguagens realizam tal operação, como a linguagem C. Além disso, muitas linguagens permitem a adição de um número a uma string/caractere, onde é realizada a coerção implícita do valor numérico, ou seja, o valor numérico é convertido para string e então é juntado à string, por exemplo `'arthur' + 27` resulta em `'arthur27'`.

Código 6.1. Diferença entre operadores de incremento e decremento pré e pós-fixado em Linguagem C.

```text
#include<stdio.h>

int main(){
	int a = 10;
	int b = 10;
	int c = 10;
	int d = 10;
	printf("%d\n", a++); // imprime 10 e, depois, 'a' passa a valer 11
	printf("%d\n", ++b); // imprime 11, 'b' vale 11
	printf("%d\n", c--); // imprime 10 e, depois, 'c' passa a valer 9
	printf("%d\n", --d); // imprime 9, 'd' vale 9
	return 0;
}
```

Além disso, foi apresentada a ideia de operadores de incremento e decremento \(código 6.1 e 6.2\), essa parte deve ser analisada apenas por quem este aprendendo Portugol Studio ou C. Primeiro deve-se saber que são operadores que aumentam ou diminuem o valor de um número em uma unidade, ou seja, `x++` é o mesmo que `x = x + 1`. Há diferenças entre pré e pós-fixado, uma é quanto a sintaxe, o pré-fixado se escreve `++x` e o pós-fixado `x++` e sua diferença é percebida quando a expressão é usada como valor para alguma outra expressão, pois esta diferença se dá pelo momento que a variável é incrementada, se é antes ou depois de seu uso, por exemplo, veja o código 6.1.

Código 6.2. Diferença entre operadores de incremento e decremento pré e pós-fixado em Linguagem C.

```text
#include<stdio.h>

int main(){
	int a = 10;
	int b = 10;
	int c = 10;
	int d = 10;
	printf("%d\n", a++); // imprime 10 e, depois, 'a' passa a valer 11
	printf("%d\n", ++b); // imprime 11, 'b' vale 11
	printf("%d\n", c--); // imprime 10 e, depois, 'c' passa a valer 9
	printf("%d\n", --d); // imprime 9, 'd' vale 9
	return 0;
}
```

## 5.2.2. Expressões lógicas e relacionais

Para realizar comparações formando expressões relacionais, ou seja, que relacionam dois valores, usamos os operadores relacionais. Imagine que você ter uma variável para o dinheiro do usuário e ele só poderá comprar algo se o saldo for maior que o valor do produto, então poderíamos comparar se o saldo é maior ou igual ao valor do produto, isso é feito com esses operadores relacionais. Perceba  que uma relação gera sempre um valor verdadeiro ou falso, afinal uma comparação é falsa ou verdadeira.

Os operadores relacionais costumam ser operadores binários, ou seja, que utilizam dois valores e são símbolos que representam as seguintes comparações: menor que, maior que, menor ou igual, maior ou igual e diferente. E, claro, que cada linguagem pode utilizar um símbolo diferente e até ter mais ou menos operadores. Contudo, o único que costuma variar é o símbolo do diferente. Abaixo apresento a tabela 6.2 com os operadores das linguagens desse livro.

Tabela 6.2. Operadores Relacionais \(Comparação\).

| Operador | Scratch | Portugol Studio | Linguagem C |
| :--- | :--- | :--- | :--- |
| Maior que |  | &gt; | &gt; |
| Maior ou igual |  | &gt;= | &gt;= |
| Menor que |  | &lt; | &lt; |
| Menor ou igual |  | &lt;= | &lt;= |
| Igual a |  | == | == |
| Diferente de |  | != | != |

Podemos precisar de combinar comparações, por exemplo pegue o exemplo anterior do saldo, mas agora você precisa de permissão do usuário pai para comprar, então precisamos do saldo e da permissão do pai, percebe que temos que verificar duas coisas ao mesmo tempo? Para isso podemos utilizar operadores lógicos, normalmente temos dois operadores binários, o E e o Ou e um operador unário, o Não. No exemplo acima usamos o operador E. Abaixo mostro a tabela 6.3 com os operadores de cada linguagem.

Código 6.3. Operadores Lógicos

| Operador | Scratch | Portugol Studio | Linguagem C |
| :--- | :--- | :--- | :--- |
| e |  | && | && |
| ou |  | \|\| | \|\| |
| não |  | ! | ! |

Por fim, apresento uma tabela verdade com os operadores lógicos \(Tabela 6.4\), uma tabela verdade é uma tabela onde verificamos qual valor booleano/lógico \(verdadeiro ou falso\) será gerado com o uso de tal operador. Nas próximas seções, os operadores serão apresentados em cada uma das linguagens.

Tabela 6.4. Tabela Verdade dos Operadores Lógicos.

| p | q | p e q | p ou q | não p |
| :--- | :--- | :--- | :--- | :--- |
| V | V | V | V | F |
| V | F | F | V | F |
| F | V | F | V | V |
| F | F | F | F | V |

## 5.2.3. Exercícios

1\) Qual a primeira operação a ser executada em cada em dos comandos abaixo:

* x + y - z
* v + v / c²
* nota 1 + nota 2 / 2
* ponto\_extra + media / n
* x + y + a \* b
* a \* b / c \* d

2\) Monte uma tabela verdade para os operadores lógicos E\(AND\), OU\(OR\) e NÃO\(NOT\). Não olhe a tabela acima, faça com seu conhecimento.

| p | q | p e q | p ou q | não p |
| :--- | :--- | :--- | :--- | :--- |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |

3\) Monte uma lista com os operadores relacionais e explique um pouco de cada um.

