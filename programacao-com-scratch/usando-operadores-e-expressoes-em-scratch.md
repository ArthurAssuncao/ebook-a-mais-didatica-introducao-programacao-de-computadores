# 6.2 Usando operadores e expressões em Scratch

Se você chegou neste capítulo considero que já tenha estudado os conceitos de variáveis no capítulo [Operadores e Expressões](../conceitos-de-programacao/operadores-e-expressoes.md). Agora vamos aplicar esses conceitos ao Scratch e utilizar um pouco da nossa metodologia.

No Scratch temos a categoria Operadores para tratar de operadores e expressões, porém alguns comandos/operadores são vistos em outras categorias. Primeiro, iremos abordar os operadores aritméticos, lembre que na seção anterior [Usando variáveis em Scratch](usando-variaveis-em-scratch.md) você aprendeu a usar o operador de atribuição com o comando `mude <variável> para <0>`. Agora iremos ver os operadores relativos a operações matemáticas, são eles:

![Figura 6.2.1. Operadores Aritm&#xE9;ticos do Scratch.](../.gitbook/assets/image%20%2842%29.png)

![Figura 6.2.2. Operadores de concatena&#xE7;&#xE3;o de strings do Scratch.](../.gitbook/assets/image%20%2838%29.png)

![Figura 6.2.3. Operador Aritm&#xE9;tico de resto da divis&#xE3;o do Scratch.](../.gitbook/assets/image%20%2845%29.png)

Para usar esses operadores precisaresmo atribuí-los a uma variável ou usá-los em comandos mais avançados que ainda não aprendemos, por isso vamos utilizar na atribuição de variáveis.

{% tabs %}
{% tab title="Veja exemplos" %}
1\) Mudar a idade para o valor da soma entre 1 e 2.

![](../.gitbook/assets/image%20%2841%29.png)

2\) No código abaixo, a variável `numero1` receberá 5 e a variável `numero2` receberá o resultado da multiplicação entre o valor de `numero1` e `2`, ou seja, receberá `10`.

![](../.gitbook/assets/image%20%2832%29.png)

3\) O código abaixo atribui `0` ou `1` a variável `parImpar`. Não ficou claro? O código atribui `5` a variável `numero1`, depois atribui o resto da divisão entre `numero1` e `2` à variável `numero2`, ou seja, `numero2` receberá o resto da divisão inteira entre `numero1` e o valor `2`, o resto de qualquer número por `2` ou é `0` ou é `1`, dúvida?

Vamos fazer as seguintes contas como divisão inteira, ou seja, divisão entre números inteiros com resultado inteiro e tendo resto.

```text
2 / 2 = 1 e resta 0
3 / 2 = 1 e resta 1
4 / 2 = 2 e resta 0
15 / 2 = 7 e resta 1
16 / 2 = 8 e resta 0
```

Perceba que todo número impar dividido por 2 resulta em um resto 1 e todo número par resulta em um resto 0. Agora vamos ver o código no Scratch com ficará.

![](../.gitbook/assets/image%20%2814%29.png)
{% endtab %}

{% tab title="Aprenda com erros" %}
1\) Vamos somar 2 a um número que começou com 0, mas esqueça de inicializar o valor do número com 0 e teste o código algumas vezes para ver o que acontece.
{% endtab %}

{% tab title="Reflita!" %}
1\) Se quero usar o valor de uma variável em uma expressão matemática, preciso que essa variável tenha um valor definido anteriormente ou não? Explique.
{% endtab %}

{% tab title="Dividir para conquistar" %}
Devido o uso inicial de expressões ser muito simples, iremos abordar esse item nas próximas seções.
{% endtab %}

{% tab title="Passo a passo" %}
1\) Crie um código que subtraia a sua idade do ano atual e armazene o valor em uma nova variável.

```text
Crie uma variável idade
Crie uma variável ano_atual
Crie uma variável para o resultado, chame-a de resultado
Mude o valor da variável idade para a sua idade
Mude o valor da variável ano_atual para o ano atual
Mude o valor da variável resultado para a subtração de ano_atual - idade
```
{% endtab %}

{% tab title="Leia o código" %}
1\) Leia o código abaixo e diga o que ele parece fazer.

![](../.gitbook/assets/image%20%2823%29.png)
{% endtab %}

{% tab title="Do it!" %}
1\) Crie duas varíaveis com nomes `numero1` e `numero2`. E defina o valor 0 para a primeira e 5 para a segunda, após isso some as duas e coloque o resultado em uma nova variável chamada `resultado`.
{% endtab %}
{% endtabs %}

Os operadores relacionais e lógicos serão abordados na seção de estruturas condicionais no Scratch, pois ficará mais fácil entender e utilizar.

