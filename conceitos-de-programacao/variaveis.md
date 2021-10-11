# 5.1. Variáveis

Antes de tudo devemos aprender que um **literal** é um valor fixo, "cru", de diversos tipos, como número inteiro, texto, números de ponto flutuante (número reais ou com casas decimais), booleanos (verdadeiro e falso) etc. Por exemplo: `10` é um literal do tipo número inteiro, `"arthur"` é um literal do tipo string(texto, lista \[vetor] de caracteres) e assim por diante.

Imagine a situação, você encontra dois antigos amigos na rua e quer anotar o seus números de telefone, mas no momento você está sem o seu celular, então resolve anotar com papel e caneta, assim você pensa em anotar um número abaixo do outro, mas na hora percebe que isso te confundiria, afinal qual número é da Maria e qual o do João, então você faz diferente do que pensou, faz de uma forma melhor. De um lado do papel você coloca o número de telefone e do outro lado você coloca o nome da pessoa para, assim, saber de quem é aquele número. Neste exemplo, você armazenou dados de pessoas em papéis (**variáveis**) e, para identificá-los (**identificador/nome da varíavel**) você usou o nome da pessoa. Este é um ótimo exemplo de uso de variáveis. A variável é o papel que pode receber um valor, caso você erre, basta apagar e escrever novamente, afinal é variável, pode mudar. De um lado está o valor da variável e do outro está o seu identificador, como mostra a Figura 5.1.1.

![Figura 5.1.1. Exemplo de uso de variáveis usando papéis. A primeira coluna é o nome de cada variável e na segunda coluna o valor da variável.](<../.gitbook/assets/image (12).png>)

Em termos técnicos, uma **variável** é uma região de memória para armazenar um valor (como um literal) que é identificada por um **identificador** (nome), sendo um nome simbólico para referenciar (ou é associado a) um valor que pode ser alterado ao longo do código. É como se fosse um papel onde você anota o número de telefone de alguém. Lembre da cena: você encontrou seus antigos amigos, então pegou um papel para anotar os números de telefone, escreveu com lápis de um lado dele `João` e do outro lado anotou o número de telefone. Nesta cena, o papel é a região de memória onde o telefone será escrito e `Joao` é o nome da variável que é o papel, o nome no outro lado do papel poderia ser `Amigo de infância 1`. Caso `João` mude o número de telefone, você pode apagar o número anotado e colocar o novo número, pois o papel recebe valores variáveis, que podem mudar ao longo do tempo, é so apagar e reescrever. Perceba que você define o nome da variável e o valor dela (número de telefone) pode ser alterado ao longo do tempo.

Em códigos será muito comum o uso de variáveis, pois você sempre precisará guardar informações para utilizar posteriormente. No caso do telefone do `João`, você poderia pegar esse número de dar a alguém ou apenas exibir ele para uma pessoa, por exemplo.

Para utilizar uma variável precisamos conhecer o **operador de atribuição**. Este operador varia de linguagem para linguagem, mas geralmente é um sinal de igual (`=`) e significa que o valor à direita será atribuído a variável à esquerda. Este é o comportamento mais comum, mas pode ter alterações. O código abaixo mostra uma variável de identificador `nome` recebendo o valor `"Arthur"`, sabemos que ela recebe tal valor, pois é utilizado o operador de atribuição.

```
nome = "Arthur"; // a variável de identificador nome recebe o valor "Arthur"
```

Os nomes de variáveis precisam ser bem descritivos, não tem problema ser muito **verboso** (grande), o importante é ter seu propósito bem nítido, por exemplo, veja os códigos abaixo e nos diga qual deles é mais fácil entender o propósito da variável.

```
inteiro x = 29
```

```
inteiro idade = 29
```

```
inteiro idade_usuario = 29
```

Percebeu a diferença entre os identificadores (nomes) das variáveis acima? Portanto, de agora em diante, escolha bons identificadores para as suas variáveis. Além disso, o identificador de uma variável deve seguir algumas regras, cada linguagem tem as suas, contudo recomendo seguir as seguintes regras para criar identificadores de variáveis:

* iniciar com letra minúscula, nunca com número ou letra maiúscula;
* ter todas letras em maiúscula, se e somente se, for uma constante (variável que não se altera, como uma variável para o número Pi). Na próxima seção explico o conceito de constante;
* utilizar um padrão de identificador, ver capítulo [Boas práticas e Padrões de Código](boas-praticas-e-padroes-de-codigo.md); e
* ser bem descritivo, deve ser fácil entender o que tal variáveis irá armazenar apenas lendo o seu identificador.

> Desenvolva códigos legíveis, pois códigos são lidos com muito mais frequência do que são escritos. 

Essas variáveis podem ser de diversos **tipos**, ou melhor, podem receber valores de diversos tipos. Note que é possível existir o tipo da variável (uma região da memória pode receber um determinado tipo) e o tipo do valor da variável (o valor é de um tipo específico), mas cada linguagem funciona de uma forma, então não se preocupe por enquanto. Cada linguagem tem o seu conjunto de tipos disponíveis, abaixo apresento os mais comuns: 

* números inteiros;
* números em ponto-flutuante (números reais, números com casas decimais);
* caracteres;
* textos (lista de caracteres); e
* arrays, conhecidos como vetores e matrizes (conjunto de variáveis).

Os vetores e matrizes são conjuntos de variáveis. Na Figura 5.1.2 são ilustradas as regiões de memória para uma variável simples, um vetor (matriz de uma dimensão) e uma matriz. Perceba que um vetor e uma matriz são conjuntos de variáveis, podendo ser de qualquer tipo disponível (há linguagens que permitem vários tipos diferentes em um vetor ou matriz).

![Figura 5.1.2 Representação visual de uma variável simples, um vetor e uma matriz.](../.gitbook/assets/variavel-vetor-matriz.png)

## 5.1.1. Constantes

Constantes são regiões de memória que recebem um valor inicialmente, mas que não permitem a alteração, pois têm valores constantes. Em outras palavras, são "variáveis" que não podem ter alteração de valor ao longo do tempo, geralmente a própria linguagem acusa erro de sintaxe durante a compilação (linguagem compilada) ou interpretação (linguagem interpretada). Portanto, são nomes atribuídos a valores que não serão alterados, podendo ser utilizadas para definir valores de constantes matemáticas, como o número `pi`. Ressalto que há linguagens que têm palavras-chave específicas para indicar que uma variável é constante facilitando o uso. Abaixo ilustro um exemplo em linguagem JavaScript apenas para facilitar o entendimento, porém cada linguagem aborda o conceito de uma forma diferente.

```
const pi = 3.1415 // Não acusa erro, pois o valor pode ser atribuído na declaração da variável
pi = 3.141592 // Acusa erro, pois a variável pi é constante.
```

## 5.1.2. Tipos Primitivos

As variáveis e constantes podem ser de vários tipos ou receber valores de diversos tipos, como um número inteiro, um número em ponto flutuante (números reais (R)), vulgarmente números com vírgula, um texto, um valor booleano (verdadeiro ou falso) etc.

Esses tipos podem ser primitivos ou complexos, os tipos primitivos são, como o nome diz, primitivos, como um número inteiro. Já os tipos complexos são tipos que utilizam tipos primitivos, são tipos novos, como classes em uma linguagem orientada a objetos. Cada linguagem tem sua tabela de tipos pré-definidos.

## 5.1.3. Tipos de Tipagem

Essa seção é bastante complicada e muito controvérsa, pois os conceitos não são muito bem definidos por ninguém, portanto não tente entender perfeitamente, leia apenas por alto. Alguns conceitos em programação costumam ser bastante confundidos, tudo relacionado a tipagem entra nessas confusões, então abaixo veja as definições mais aceitas.

As linguagens de programação podem ter **tipagem dinâmica** ou **estática** e serem **forte** ou **fracamente tipadas**, estes conceitos são importantes, pois cada um tem suas características, além disso é preciso saber o que é **inferência de tipo** abaixo cada conceito é explicado.

**Inferência de tipo** significa que a linguagem consegue definir o tipo de uma variável em tempo de execução ou compilação, por exemplo a linguagem Java em sua versão 9 propôs algo parecido com o que já existe no C#, o "tipo" var. Abaixo segue um exemplo em Java 9:

```
var name = "Arthur Assuncao"; // ao atribuir o valor, o compilador atribuirá o tipo String à variável
var number = 26; // ao atribuir o valor, o compilador atribuirá o tipo int/Integer à variável
```

### 5.1.3.1. Tipagem Estática

A tipagem estática está relacionada a linguagem garantir que uma variável nunca alterará seu tipo, podendo alterar apenas seu valor, ou seja, uma variável de tipo inteiro não pode se tornar uma variável do tipo texto, assim uma variável do tipo inteiro só poderá receber valores do tipo inteiro, por exemplo:

Em Portugol Studio podemos testar essa situação da seguinte forma:

```
inteiro numero = 26 // a variável name é do tipo inteiro
numero = "Arthur" // Erro. Vai gerar um erro de compilação, pois a variável é do tipo inteiro
```

### 5.1.3.2. Tipagem Dinâmica

Já a tipagem dinâmica é quando a linguagem permite que uma variável mude seu tipo em tempo de execução, realizando a inferência de tipo. Nesse tipo de linguagem, as variáveis não costumam ter tipos definidos na declaração das variáveis, assim uma variável pode assumir qualquer tipo dependendo do momento.

Em JavaScript podemos fazer o seguinte:

```
var name = "Arthur Assuncao" //a variável name é do tipo string
name = 26 //a variável agora é do tipo number (número)
```

### 5.1.3.3. Fracamente Tipada ou Tipagem Fraca

**Tipagem fraca** significa que o compilador/interpretador não verifica os tipos das variáveis nas operações em tempo de execução ou compilação, por exemplo, você pode somar um número com um texto e ele gerará algum resultado sem qualquer erro, gerando assim uma **coerção implícita**, ou seja, mudança no tipo do valor para que a operação execute sem erros.

Por exemplo, em JavaScript é possível fazer como no código abaixo, perceba que a linguagem converte o valor `1` para `'1'` e então **concatena** as strings, a string `'1'` com `'1'`, o mesmo acontece na segunda linha. **Concatenação** é a junção de strings (textos).

```
'1' + 1 // o resultado será '11'
'1' + false // o resultado será '1false'
```

### 5.1.3.4. Tipada ou Tipagem Forte

**Tipagem forte** significa que o compilador/interpretador verifica os tipos durante a execução ou compilação das operações. Caso os tipos não sejam compatíveis, um erro é gerado.

### 5.1.3.5. Resumo de Tipagem

* Variável tem tipo definido então é tipagem estática;
* Variável não tem tipo definido então é tipagem dinâmica;
* Valor tem tipo definido e não sofre coerção implícita então é tipagem forte;
* Valor não tem tipo definido e sofre coerção implícita então é tipagem fraca;

## 5.1.4. Escopo de Variável

Escopo de uma variável é o bloco de código que delimita a existência dessa variável, algumas linguagens têm todas suas variáveis com escopo global, ou seja, que existem de forma global em relação ao código, assim existindo em todo o código. Por padrão, vamos entender que o escopo de uma variável é o bloco de código onde ela foi criada e todos os sub-blocos deste.

O código abaixo mostra o escopo da variável `contador`, veja que ela não existe fora do bloco onde foi definida/declarada. Na linha 3 a variavel `contador` é declarada com o valor 1, na linha 5, tentamos imprimir o valor da variável na tela, porém gera um erro indicando que a variável `contador` não existe (contador não está definido), pois ela só existe dentro do bloco do comando `if`.

```
let idade = 25
if (idade > 18) {
  let contador = 1 // contador passa a existir aqui e só existe dentro desse bloco
}
console.log(contador) // error: Uncaught ReferenceError: contador is not defined
```

## 5.1.5. Exercícios:

1. O que é um literal? 
2. O que é uma string? 
3. O que é uma variável? 
4. O que é um identificador de variável? 
5. O que é o valor da variável? 
6. O que é e para que serve um operador de atribuição? 
7. Dê um exemplo sobre o uso de variável no mundo real, diferente do exemplo apresentado neste capítulo. 
8. O que é uma constante? 
9. Qual a diferença entre um vetor e uma variável?
10. O que é Tipagem dinâmica? 
11. O que é Tipagem estática? 
12. O que é Tipagem forte? 
13. O que é Tipagem fraca? 
14. O que é Inferência de tipo? 
15. O que é Coerção implícita? 
16. O que é Concatenação de strings? 
17. O que é Escopo de Variável?
18. Assinale os identificadores (nomes de variáveis) que são válidos e não marque os inválidos, considere regras mais comuns como eu explico neste capítulo: 

* [ ] (X)
* [ ] XMU2
* [ ] AH!
* [ ] NOTA1
* [ ] nota1
* [ ] nota\_1
* [ ] 5NOTA
* [ ] "NOTA1"
* [ ] A\[4]
* [ ] A\\\&B
* [ ] A+B
* [ ] I00001
* [ ] NOTA/2
* [ ] PEDROEPAULO

[Aprenda a usar variáveis em Scratch](../programacao-com-scratch/usando-variaveis-em-scratch.md)

Aprenda a usar variáveis em Portugol Studio

Aprenda a usar variáveis em Linguagem C
