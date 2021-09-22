# 6.3. Usando comandos de Entrada e Saída de dados em Scratch

Após ter estudado um pouco sobre [Entrada e saída de dados](../conceitos-de-programacao/7.-entrada-e-saida-de-dados.md) você deve estar ansioso para ver a aplicação desses conceitos no Scratch. Digo a você que agora a programação começa a ficar mais interessante.

No Scratch temos os comandos de saída na categoria Aparência e os comandos de entrada na categoria Sensores, abaixo \(Figuras 6.3.1 e 6.3.2\) eu apresento os comandos disponíveis.

![6.3.1. Comandos de sa&#xED;da no Scratch.](../.gitbook/assets/image%20%2840%29.png)

![6.3.2. Comandos de entrada no Scratch.](../.gitbook/assets/image%20%2837%29.png)

Quando o Scratch executar o comando `pergunte <Qual o seu nome?> e espere`, aparecerá uma barra para o usuário digitar uma informação e apertar `Enter` ou clicar no botão à direita, a barra é como a da Figura 6.3.3.

![6.3.3. Campo de entrada de dados do Scratch.](../.gitbook/assets/image%20%2844%29.png)

Além desses comandos, caso queira comentar alguma parte do código no Scratch basta clicar com o botão direito do mouse e escolher a opção comentar, o comentário fica como na Figura 6.3.4.

![6.3.4. Coment&#xE1;rio no Scratch.](../.gitbook/assets/image%20%2817%29.png)

Vamos agora aprender a usar esses comandos por meio da nossa metodologia.

{% tabs %}
{% tab title="Veja Exemplos" %}
1\) Apresente a mensagem "`Olá, tudo bem?`" por 5 segundos. 

![Resolu&#xE7;&#xE3;o](../.gitbook/assets/image%20%2828%29.png)

2\) Pergunte qual a idade do usuário e, em seguida, mostre essa idade na tela. Nesse caso usamos o valor `resposta` que é uma variável do Scratch para termos acesso a resposta que o usuário nos deu.

![Resolu&#xE7;&#xE3;o](../.gitbook/assets/image%20%2818%29.png)

3\) Pergunte o nome do usuário e mostre, na tela, a mensagem "`Olá, <Fulano>` por 5 segundos. Atenção, substitua Fulano pelo nome fornecido pelo usuário. Agora podemos usar o comando `junte <maça> com <banana>` para concatenar a mensagem Olá com o nome fornecido.

![Resolu&#xE7;&#xE3;o](../.gitbook/assets/image%20%2846%29.png)

4\) Pergunte o nome do usuário e mostre, na tela, a  mensagem "`Olá, <Fulano>, tudo bem?` por 5 segundos. Atenção, substitua Fulano pelo nome fornecido pelo usuário.

![Resolu&#xE7;&#xE3;o](../.gitbook/assets/image%20%2815%29.png)

5\) Pergunte ao usuário o valor dos dois lados de um retângulo e mostre qual a área desse retângulo. Neste exercício você precisará usar variáveis para armazenar os valores lidos, pois a variável resposta é sobreescrita após toda resposta do usuário e precisaremos perguntar duas vezes \(lado 1 e lado 2\).

![](../.gitbook/assets/image%20%2821%29.png)

6\) João pretende viajar para uma cidade do litoral que fica a `300km` de sua casa e irá de carro, portanto ele precisa calcular o custo da viagem. Ele sabe que seu carro faz `13km/litro` e que a gasolina  \(o litro\) está custando `R$ 6,50`. Faça os calculos e mostre ao usuário quantos litros ele irá gastar nesta viagem. Note que usamos `6.5` e não `6,5`, pois as linguagens costumam usar a notação internacional com separador de unidades sendo o ponto.

![Resultado](../.gitbook/assets/image%20%2836%29.png)

7\) José trabalha em uma agência de viagens e costuma vender diárias de hotéis para pessoas que pretendem viajar de carro. Essas pessoas sempre lhe perguntam qual o custo para realizar uma viagem de x quilômetros de distância e ele é obrigado a sempre realizar o cálculo usando uma calculadora. Para facilitar a vida de josé, crie um programa que pergunte ao usuário a `distância` em quilômetros, o `valor do litro da gasolina` e quantos `km/litro` o carro faz e, ao final, mostra o custo em reais da gasolina gasta para realizar a viagem.

{% embed url="https://scratch.mit.edu/projects/572105767/" caption="Teste o código." %}

![Resolu&#xE7;&#xE3;o](../.gitbook/assets/image%20%2848%29.png)
{% endtab %}

{% tab title="Aprenda com erros" %}
1\) Qual o erro do código abaixo?

![](../.gitbook/assets/image%20%2825%29.png)

2\) Por que o código abaixo não funciona adequadamente para calcular a área do retângulo?

![](../.gitbook/assets/image%20%2834%29.png)

3\) Por que o código abaixo também não funciona adequadamente para calcular a área do retângulo?

![](../.gitbook/assets/image%20%2827%29.png)

4\) Pegue o exemplo 6 do item Veja Exemplos e mude uma parte no código, onde está:

![](../.gitbook/assets/image%20%2824%29.png)

Para:

![](../.gitbook/assets/image%20%2839%29.png)

Teste o código completo e perceba a diferença entre cada caso e explique o motivo do resultado ser diferente.
{% endtab %}

{% tab title="Reflita!" %}
1\) Se quero realizar um cálculo a partir de um dado fornecido pelo usuário, preciso primeiro usar um comando de entrada e depois realizar o cálculo ou não? Explique.

2\) Se preciso mostrar uma mensagem ao usuário que seja a junção de um texto com o valor de uma variável devo pensar em fazer o que?

3\) E se eu precisar juntar um texto com o valor de uma variável e um segundo texto em seguida?

4\) Os dois códigos abaixo fazem a mesma coisa, porém pergunto: Qual a diferença entre os códigos? Para você qual é melhor e por que?

![](../.gitbook/assets/image%20%2849%29.png)

![](../.gitbook/assets/image%20%2830%29.png)
{% endtab %}

{% tab title="Passo a passo" %}
1\) Escreva um programa que leia dois números e calcule a diferença entre eles e mostre ao usuário a mensagem: `A diferença entre os números é <valor>`, por exemplo `A diferença entre os números é 10`.

```text
Pense nas variáveis que irá precisar
Crie três variáveis: numero1, numero2 e resultado
Peça ao usuário para fornecer o primeiro número
Armazene a resposta na variável numero1
Peça ao usuário para fornecer o segundo número
Armazene a resposta na variável numero2
Use um operador de subtração com os dois números e armazene o valor da subtração a variável resultado
Mostre o resultado para o usuário conforme pedido, use a concatenação de strings para formar a frase completa
```

2\) Escreva um programa que leia dois números e calcule a diferença entre eles e mostre ao usuário a mensagem: `A diferença entre os números <numero1> e <numero2> é <valor>`, por exemplo `A diferença entre os números 8 e 5 é 3`.

```text
Pense nas variáveis que irá precisar
Crie três variáveis: numero1, numero2 e resultado
Peça ao usuário para fornecer o primeiro número
Armazene a resposta na variável numero1
Peça ao usuário para fornecer o segundo número
Armazene a resposta na variável numero2
Use um operador de subtração com os dois números e atribua o valor da subtração a variável resultado
Mostre o resultado para o usuário conforme pedido, use a concatenação de strings para formar a frase completa
```

3\) Faça um programa que calcule a média de consumo de combustível de um carro onde o usuário irá fornecer a quilômetragem inicial marcada no painel do carro \(ex: 50200\) e a quilômetragem final \(ex: 50400\) e quantos litros foram gastos no trajeto.

```text
Pense nas variáveis que irá precisar
Crie quatro variáveis: kmInicial, kmFinal, litrosGastos e mediaConsumo
Peça ao usuário para fornecer a quilômetragem inicial
Armazene a resposta na variável kmInicial
Peça ao usuário para fornecer a quilômetragem inicial
Armazene a resposta na variável kmFinal
Calcule a média de consumo com a fórmula (kmInicial - kmFinal) / litrosGastos. Cuidado para não errar a fórmula.
Atribua o resultado do cálculo à variável mediaConsumo
Exiba uma mensagem ao usuário apresentando o resultado
```
{% endtab %}

{% tab title="Dividir para conquistar" %}
1\) Escreva um programa que leia dois números e calcule a média aritmética dos dois números e mostre ao usuário a mensagem: `A média é <valor>`, por exemplo `A média é 10`.

Vamos dividir o problema em 4 partes, cada parte é um subproblema:

1. Criar as três variáveis \(numero1, numero2 e media\);
2. Ler os números para as variáveis numero1 e numero2;
3. Calcular a média aritmética e armazenar em uma variável;
4. Mostrar a mensagem ao usuário;

2\) Crie um algoritmo em Scratch que calcule o tempo em minutos para um carro ir de um ponto a outro. O usuário irá fornecer a distância e a velocidade média do carro em km/h.

Vamos dividir em 5 subproblemas:

1. Criar as variáveis distancia, velocidadeMedia, tempoHoras e tempoMinutos;
2. Ler os dados para as variáveis distancia e velocidadeMedia;
3. Calcular o tempo, em horas, para percorrer o trajeto e armazenar na variável tempoHoras;
4. Converter as horas para minutos e armazenar na variável tempoMinutos;
5. Exibir o tempo em minutos para o usuário.
{% endtab %}

{% tab title="Leia o código" %}
1\) O que o código faz? Execute linha a linha mentalmente ou com um papel e caneta. As variáveis e mensagens não estão bem descritivas para dificultar o entendimento do código e mostrar a importância de bons nomes de variáveis e de boas mensagens.

![](../.gitbook/assets/image%20%2826%29.png)
{% endtab %}

{% tab title="Do it!" %}
1\) \(Adaptado de Lopes \(2014\)\) Faça um programa que solicite ao usuário o valor do litro de combustível \(ex. 3,05\) e quanto em dinheiro ele deseja abastecer \(ex. 50,00\). Calcule quantos litros de combustível o usuário obterá com esses valores.

2\) \(Adaptado de Lopes \(2014\)\) Faça um programa que calcule o valor a ser pago por uma dívida em atraso. O usuário deve informar o valor original da dívida \(ex. R$ 100,00\), a quantidade de dias em atraso \(ex. 10 dias\) e o valor da multa por dia de atraso \(ex. R$ 0,10\).

3\) \(Retirado de Menoti \(2005\)\) Uma P.A. \(progressão aritmética\) fica determinada pela sua razão \(`r`\) e pelo primeiro termo ****\( $$a_1$$ \). Escreva um algoritmo que seja capaz de determinar qualquer termo de uma P.A., dado a razão e o primeiro termo.

4\) \(Retirado de Menoti \(2005\)\) Uma P.G. \(progressão geométrica\) fica determinada pela sua razão \(q\) e pelo primeiro termo \( $$a_1$$ \). Escreva um algoritmo que seja capaz de determinar qualquer termo de uma P.G., dado a razão e o primeiro termo. $$a_n = a_1 \times q^{(n-1)}$$

5\) \(Retirado de Menoti \(2005\)\) Escreva um algoritmo que leia uma temperatura em graus centígrados e apresente a temperatura convertida em graus Fahrenheit. A fórmula de conversão é: $$F = \dfrac{9.C + 160}{5}$$ onde `F` é a temperatura em Fahrenheit e `C` é a temperatura em centígrados

6\) \(Retirado de Menoti \(2005\)\) Criar um algoritmo para calcular e apresentar o valor do volume de uma lata de óleo, utilizando a fórmula: $$V = \pi \times R^2 \times h$$ onde `V` é o volume, `R` é o raio e `h` é a altura.

7\) \(Retirado de Menoti \(2005\)\) Criar um algoritmo que leia dois valores para as variáveis `A` e `B`, e efetue a troca dos valores de forma que a variável `A` passe a ter o valor da variável `B` e que a variável `B` passe a ter o valor da variável `A`. Apresente os valores trocados. Utilize o Teste de Mesa para te auxiliar a pensar na resposta.

**Referências**

Lopes, A. \(2014\). Lista de exercícios 1 – entrada/saída/operadores matemáticos. Disponível em: [http://docente.ifrn.edu.br/abrahaolopes/2014.1-subsequente/1.2411.1v-algoritmos/lista-de-exercicios-1-entrada-saida-calculos/at\_download/file](http://docente.ifrn.edu.br/abrahaolopes/2014.1-subsequente/1.2411.1v-algoritmos/lista-de-exercicios-1-entrada-saida-calculos/at_download/file). Acesso em 22 de setembro de 2021. 

Menoti, D. \(2005\). Lista de exercícios 01 – algoritmos – seqüência simples. Disponível em: [http://www2.dcc.ufmg.br/disciplinas/pc/pc05-1/lista01/listaexerc\_algoritmos\_entradasaida.pdf](http://www2.dcc.ufmg.br/disciplinas/pc/pc05-1/lista01/listaexerc_algoritmos_entradasaida.pdf). Acesso em 22 de setembro de 2021.
{% endtab %}
{% endtabs %}





















