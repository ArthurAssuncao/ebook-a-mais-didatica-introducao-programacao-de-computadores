# 6.1. Usando variáveis em Scratch

Se você chegou neste capítulo considero que já tenha estudado os conceitos de variáveis no capítulo [Variáveis](../conceitos-de-programacao/variaveis.md). Agora vamos aplicar esses conceitos ao Scratch e utilizar um pouco da nossa metodologia.

No Scratch temos uma categoria chamada Variáveis para tratar do assunto, os comandos possíveis são vistos na Figura 6.1.1. As variáveis no Scratch podem receber valores de tipos número, texto e booleano, contudo não é necesário indicar qual tipo da variável, basta utilizar. Portanto, podemos dizer que o Scratch tem tipagem dinâmica, pois o tipo da variável se altera ao longo da execução do código.

![Figura 6.1.1. Blocos de comandos para uso de vari&#xE1;veis em Scratch.](../.gitbook/assets/image%20%2811%29.png)

A primeira opção `Criar um Variável` auxilia a declarar uma nova varíavel com um nome \(identificador\), caso queira indicar um valor para essa variável, seja um valor inicial ou ao longo do código, deverá usar o comando `mude <minha variável> para <0>`, perceba que `minha variável` é o nome da sua variável e o `0` é o valor, portanto você, provavelmente, precisará alterar os dois.

Caso você queira usar a variável no código pode usar o comando com o nome da variável, por exemplo o comando `minha variável` permite o uso dessa variável, como ilustra a Figura 6.1.2.

![Figura 6.1.2. Comandos para usar o valor de uma vari&#xE1;vel no c&#xF3;digo ou exibir na tela \(palco\).](../.gitbook/assets/image%20%289%29.png)

Além disso, é possível adicionar um valor a variável, com o comando `adicione <1> a <minha variável>` normalmente ele adiciona o número na varíavel, ou seja, soma o número passado pro comando ao valor atual da variável. Ainda é possível, mostrar ou ocultar uma variável, mas caso queira mostrar a variável o tempo todo você pode marcar o campo _checkbox_ do comando com o nome da variável, como mostra a Figura 6.1.2.

Além disso, é possível criar uma lista que é como um vetor, mostrado no capítulo [Variáveis](../conceitos-de-programacao/variaveis.md). Agora aprenda com a minha metodologia a partir das informações abaixo.

{% tabs %}
{% tab title="Veja exemplos" %}
O código abaixo altera o valor de uma variável já criada chamada `pontuação` seja alterada para 0. Podemos também entender que a variável foi inicializada com o valor 0, pois esse código está no topo do bloco de códigos.

![](../.gitbook/assets/image%20%285%29.png)

O código abaixo adiciona o valor 5 a variável `pontuação`, portanto ela passa a ter o valor 5. Seria como se fizesse um código assim, em linguagem textual:

```text
pontuação = pontuação + 5 // pontuação recebe o valor de pontuação mais 5
```

![](../.gitbook/assets/image%20%286%29.png)

O código abaixo adiciona o valor 5 a variável `pontuação` e depois adiciona 1, portanto ela passa a ter o valor 6, ao final do código. Seria como se fizesse um código assim, em linguagem textual:

```text
pontuação = pontuação + 1 // pontuação recebe o valor de pontuação mais 1
```

![](../.gitbook/assets/image%20%2816%29.png)
{% endtab %}

{% tab title="Aprenda com erros" %}
Devido o uso inicial de variáveis ser muito simples, não temos situações de erro para abordar.
{% endtab %}

{% tab title="Reflita!" %}
1\) Quero criar um código com uma variável para idade do usuário, o que devo fazer?
{% endtab %}

{% tab title="Passo a passo" %}
1\) Criar um algoritmo que tenha uma variável resposta que inicie com o valor 0.

1. Ir na categoria `Eventos` e puxar o comando `Quando <bandeira> for clicado` para a área de código.
2. Ir na categoria Variáveis e Criar uma variável com o nome `resposta`.
3. Colocar o comando `Mude <minha variável> para <0>` embaixo do comando `Quando <bandeira> for clicado`.
4. Mude o valor `minha variável` do comando do passo anterior para a variável `resposta`.
{% endtab %}

{% tab title="Dividir para conquistar" %}
 Devido o uso inicial de variáveis ser muito simples, não temos situações deste item para abordar.
{% endtab %}

{% tab title="Leia o código" %}
1\) O que o código abaixo faz?

![](../.gitbook/assets/image%20%2835%29.png)
{% endtab %}

{% tab title="Do it!" %}
1\) Crie duas varíaveis com nomes `numero1` e `numero2`.
{% endtab %}
{% endtabs %}







