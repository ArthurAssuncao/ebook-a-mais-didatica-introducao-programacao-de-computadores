---
description: >-
  Antes de aprendermos os conceitos de programação usando Scratch, vamos
  aprender um pouquinho do Scratch sem qualquer conceito de programação. Você
  verá como o Scratch é intuitivo e fácil.
---

# 4. Introdução ao Scratch

## O que é Scratch

O Scratch é um software de programação em blocos voltado para o ensino de programação para crianças e está na versão 3.0. Esta programação em blocos se difere da programação tradicional por conter blocos pré-definidos de códigos em formato visual de bloco em vez da forma escrita. Foi desenvolvido pelo MIT e está disponível de forma online por meio do acesso ao [site do Scratch](https://scratch.mit.edu/) em um navegador de internet, como o Google Chrome ou Firefox, ou pelo download do programa, disponível para Windows, Mac, ChromeOS e Android. Uma antiga versão, a 1.4, era compatível com distribuições Linux, contudo seu suporte foi descontinuado.

### Por quê utilizar o Scratch

Porque é muito mais motivador utilizá-lo, os programas criados são animações ou jogos que são mais legais e, ainda, podemos utilizar o Scratch para:

* **ensinar programação**: muitos alunos têm dificuldade em aprender a programar, pois são conceitos novos que envolvem lógica, algo que considero pouco desenvolvido nos alunos;
* **ensinar os conceitos**: é possível ver os conceitos básicos da programação no Scratch e de forma fácil e rápida, além de visual; e
* **motivar dos alunos**: o scratch motiva os alunos, pois eles conseguem criar projetos incríveis e muito visuais.

### Onde podemos utilizar o Scratch

O melhor local para usar é no ensino, por ser uma ferramenta voltada à educação, e na criação de animações e jogos simples.

### Onde NÃO vamos utilizar o Scratch

Não iremos utilizar para programas de forma geral e para criar jogos ou animações mais complexas e, claro, de forma comercial, pois o Scratch tem seu apelo didático apenas.

### Quais problemas o Scratch resolve

O principal benefício do Scratch é facilitar o ensino de programação 1\) reduzindo a dificuldade no domínio das palavras reservadas, 2\) no entendimento das estruturas do código, 3\) a forma abstrata de se pensar, 4\) tornar a programação mais interessante e visual, dentre outras.

Dessa forma, visando o aprendizado de forma mais fácil e motivador, vamos iniciar o ensino da programação com o Scratch, que é desenvolvido pelo MIT e que consiste em um sistema para programação em blocos. A linguagem em blocos é muito mais simples que a linguagem tradicional, textual com sentenças. É como brincar de Lego, e, assim, é fácil, intuitiva e motivadora.

No Scratch, temos diversos conceitos de lógica de programação, como **variáveis**, **comandos de entrada e saída**, **desvio condicional**, **estruturas de repetição**, **criação de funções** e mais. A partir disso, podemos dizer que o Scratch é uma ferramenta completa para o ensino dessas disciplinas introdutórias a programação.

Ainda, temos o Scratch como uma ferramenta que permite a criação de animações e jogos de forma simples e com visual bastante bonito, dependendo apenas da criatividade e dons com softwares de edição de imagens.

Em resumo, o Scratch permite o ensino de forma simples e motivador, algo que as linguagens não costumam permitir. Contudo é importante lembrar que ele pode ser usado nas primeiras aulas, umas 8 aulas podem ser suficiente e depois pode-se iniciar o ensino das linguagens tradicionais, seja Portugol, Python ou C, por exemplo, esta última apenas se for realmente necessário para a formação do aluno, devido a sua dificuldade.

Pensando nisso, no ano de 2019, ao iniciar a primeira turma do curso Técnico em Automação, começamos a disciplina de programação com uma aula motivando os alunos sobre a área de programação, explicando como é o mercado de trabalho para um desenvolvedor, os conceitos de algoritmos e, em seguida, o ensino do Scratch. Essas aulas de Scratch podem ser encontradas no seguinte endereço [Introdução ao Scratch](https://scratch.arthurassuncao.com/). Essas aulas foram feitas com CSS e RevealJS. O ensino de lógica costuma ser com os seguintes conteúdos, na ordem que estão:

* Variáveis;
* Entrada e Saída de dados;
* Operações aritméticas;
* Operadores lógicos;
* Operadores relacionais;
* Estrutura condicional;
* Estrutura de repetição;
* Criação de funções;

E mais, no Scratch, temos tudo isso, primeiro vamos utilizar todos esses conceitos sem explicações para que você perceba o quanto o Scratch é didático e intuitivo, nas próximas seções teremos explicações abordando os conceitos, pois essa é a nossa maior finalidade. 

Para iniciar com Scratch, é possível realizar o download ou usar a interface web. Vamos usar a versão Web e, para isso, acessar o site [Scratch.mit.edu](http://scratch.mit.edu/) e clicar em Comece a Criar. Isso nos leva a interface web do Scratch, como a Figura 4.1 apresenta. 

![Figura 4.1. Tela Inicial do Scratch Web.](../.gitbook/assets/scratch-tela.png)

### Como Começar

Podemos começar de várias formas, nos slides do link acima, começo apresentando o que o Scratch permite fazer e vou incrementando as funções ensinando cada comando a medida que é necessario, chamo isso de **aprendizado por demanda**. Considero ótima forma de se aprender uma linguagem ou tecnologia de forma rápida e mais interessante, pois remove o excesso de teoria e se aprende com base no que é necessário a cada momento, o ponto negativo é que não se aprende tudo, pois se limita ao que foi necessitado, portanto perde um pouco dos conceitos fundamentais. Mas imagine, em vez de ler um livro ou fazer um curso de React \(tecnologia para desenvolvimento de sistemas web no front end\) você pode ler um código base e então comece a montar seu site e a cada necessidade você pesquise como fazer, assim você aprende e faz o que precisa, tudo por demanda e sem ter que esperar dias/mês para começar a montar algo de verdade. E num momento posterior você pode estudar mais a fundo seja com livro ou curso.

Antes da explicação, apresento alguns conceitos básicos da ferramenta:

* **Sprite**: são os objetos e personagens da animação e jogo;
* **Stage**: é o palco onde os sprites irão se movimentar;
* **Cenário**: é o plano de fundo do stage;
* **Script**: é o roteiro do jogo/animação ou, seja, o conjunto de blocos de comandos que dão vida à animação ou jogo. Cada sprite e cenário pode ter um Script;

Ainda na Figura 4.1, você pode observar cada uma das áreas de acordo com a legenda, esta legenda foi adicionada a imagem para facilitar seu entendimento. Nela temos:

* **Área de Stage \(Palco\)**: é o palco onde ficarão os sprites;
* **Área de Sprite \(Ator\)**: esta área é a **Sprite List** onde ficam exibidos os **thumbnails \(miniaturas\)** dos sprites incluidos no jogo/animação, esta área permite o acesso mais fácil a cada sprite;
* **Área de Abas**: esta área exibe as abas disponíveis;
* **Área de Categorias**: esta parte apresenta as categorias de blocos de comandos disponíveis;
* **Área de Blocos de Comando**: área que mostra os comandos da categoria escolhida;
* **Área de Script \(Roteiro\)**: esta área mostram os blocos de comando sendo utilizados pelo sprite ou cenário atual;

O stage tem um tamanho pré-definido e utiliza o sistema de coordenadas cartesianas \(x, y\) e tem 480 pontos no eixo X e 360 pontos no eixo Y, sendo metade desses valores para cada sentido em cada eixo, como ilustra a Figura 4.2.

![Figura 4.2. Plano cartesiano do Palco do Scratch.](../.gitbook/assets/scratch-stage-cartesiano.png)

Além disso, é permitida a rotação de um personagem no stage, esta rotação utiliza os ângulos de uma circunferência, como a Figura 4.3 apresenta.

![Figura 4.3. &#xC2;ngulos de uma circunfer&#xEA;ncia.](../.gitbook/assets/scratch-rotacao.png)

Esta plataforma, tem diversas categorias com comandos e blocos que podem ser utilizados, cada categoria representa um tipo diferente de conjunto de blocos onde os comandos em azul são referentes à Movimento, os roxos são referentes à Aparência, magenta à Som, amarelo à Eventos, laranja à Controle, ciano à Sensores, verde à Operadores, laranja escuro à Variáveis e ainda é possível criar os seus próprios blocos que ficam em um tom de vermelho. Essas categorias podem ser vistos na Figura 4.4.

![Figura 4.4. Categorias presentes no Scratch web.](../.gitbook/assets/scratch-categorias.png)

Antes de aprendermos conceitos sobre programação, vamos fazer exercícios no Scratch. A finalidade será mostrar que é fácil usar o Scratch. Ainda não começamos a aplicar nossa metodologia. Quero apenas mostrar para você que é legal e interessante usar o Scratch, ou seja, quero te motivar. Então vamos botar as mãos à massa.

### Exercícios

Vamos fazer alguns exercícios, não se preocupe caso tenha alguma dificuldade.

#### Exercício Prático: Primeiros Movimentos no Scratch

**Exercício 1**

Arraste o sprite Gato pela área do stage \(palco\) e observe a posição X e Y indicada no campo X e Y.

![Figura 4.5. Ator Gato no palco.](../.gitbook/assets/image%20%283%29.png)

**Exercício 2**

Vamos fazer um Gato andar para frente ao clicar no comando Mova.

1. Vamos fazer o Gato \(sprite\) se movimentar na tela \(palco ou stage\);
2. Na categoria Movimento: arraste o botão `Mova <10> passos` para a área de comandos \(scripts\);
3. Mantenha o valor 10 no comando Mova;
4. Teste clicando duas vezes sobre o comando na área de código;
5. Teste com outros valores no comando Mova;
6. Veja a solução na Figura 4.6.

![Figura 4.6. Solu&#xE7;&#xE3;o do exerc&#xED;cio 2.](../.gitbook/assets/image%20%281%29.png)

**Exercício 3**

Que tal analisarmos um código?

1. Vá no projeto [Esconde-Esconde](http://scratch.mit.edu/projects/24155933);
2. Selecione `Ver interior`;
3. Analise o código e o jogo, focando nas coordenadas;
4. O que você aprendeu?

**Exercício 4**

Podemos criar um código onde um Gato anda para frente, diz "Olá" e, em seguida, volta e diz "Voltei!".

1. Abra um Novo arquivo e, na categoria Movimento, adicione ao roteiro o comando `mova <10> passos` com o valor 100;
2. Na categoria Eventos, adicione o comando `quando <bandeira-verde> for clicado` acima do primeiro comando e clique na bandeira verde para testar;
3. Na categoria Aparência, adicione o comando `diga <Olá> por <2> segundos` ao roteiro;
4. Na categoria Movimento, use o comando `aponte para a direção <90>` com o valor -90;
5. Para corrigir o problema do ator ficar de cabeça para baixo, use o comando `defina o estilo de rotação para <esquerda-direita>`;
6. Use mais um comando `mova <10> passos`;
7. Coloque mais uma fala, agora com a mensagem `Voltei!`;
8. Em Movimento, coloque o comando `aponte para a direção <90>`;
9. Adicione o comando `Sempre` em volta dos comandos para que fique em loop infinito;

Abaixo, na Figura 4.7 apresento a solução do exercício 4.

![Figura 4.7. Solu&#xE7;&#xE3;o do exerc&#xED;cio 4.](../.gitbook/assets/scratch-exercicio-ola-voltei-solucao.gif)

**Exercício 5**

E se criarmos uma animação onde o personagem dança Hip-Hop?

Quando criamos um novo projeto o único ator \(sprite\) é o do Gato, mas podemos usar outro;

1. Crie um novo projeto;
2. Escolha um novo ator, use o Anina Hip-Hop;
3. Delete o Gato da lista de atores;
4. Faça uma animação com o ator usando o comando `próxima fantasia`;
5. Coloque um comando `espere <0.5> seg` para que as fantasias não mudem muito rápido;

Abaixo, na Figura 4.8 apresento a solução do exercício 5.

![Figura 4.8. Solu&#xE7;&#xE3;o do exerc&#xED;cio 5.](../.gitbook/assets/scratch-exercicio-anina-hip-hop-solucao.gif)

### Interação com o Usuário

É possível ter um programa com interação com o usuário, algo fundamental em um jogo. Para ensinar estas interações, usarei exemplos práticos.

#### Bola seguindo o Mouse

Faça a bola seguir o cursor do mouse infinitamente, para isso inclua um sprite de bola e use o comando `vá para <ponteiro do mouse>`.

#### Mirando com o Mouse

Vamos criar um bastão que irá seguir parcialmente o mouse a ponto de ser utilizado como mira, ficará como na Figura 4.7. Faça o seguinte:

1. Mude o ator para o Magic Ward, use o botão `Selecione um Ator` \(Figura 4.7\);
2. Vá na aba Fantasias, clique sobre cada um dos raios amarelhos e os apague;
3. Volte para a aba Código.
4. Coloque o comando `quando <bandeira> for clicado`, da categoria Eventos.
5. Junte o comando `sempre` no comando anterior para que sempre aponte;
6. Coloque o comando `aponte para <ponteiro do mouse>` , da categoria Movimento, dentro do comando anterior para que ele aponte para o mouse sempre;
7. Na categoria Movimento, marque os botões `Posição x`, `Posição y` e `Direção`;
8. Teste clicando no botão Ir \(Bandeira verde\), acima do palco. Para parar, clique no botão Pare \(botão vermelho acima do palco\).
9. Veja a solução na Figura 4.8.

![Figura 4.7. Bot&#xE3;o Selecione um Ator.](../.gitbook/assets/image%20%282%29.png)

![Figura 4.8. Mirando com o Mouse no Scratch.](../.gitbook/assets/mirando-mouse.gif)

#### Colisão de um bola com a borda

Vamos fazer um bola seguir em uma direção e ao colidir com a borda do stage voltar na direção oposta. Para isso:

1. inclua um sprite de bola e;
2. adicione o comando 'se tocar na borda, volte'.

**Colisão de um bola com um sprite**

A partir do código anterior, vamos colocar mais um sprite no stage e, quando a bola tocar nele, ela irá voltar na direção oposta. Assim, adicione um outro sprite na tela, como ilustra a Figura 4.8. Após isso, adicione o comando `se <> então` e dentro do espaço do `se <> então` coloque o comando `tocando em <NomeOutroSprite>`, onde o NomeOutroSprite deve ser o nome do sprite que você adicionou recentemente.

![Figura 4.8. Colis&#xE3;o de uma bola com um sprite.](../.gitbook/assets/scratch-bola-tocar-sprite.png)

#### **Exercício Prático**

Criando o primeiro jogo em Scratch

Crie um jogo de colher maça, como na Figura 4.9. Para isso:

1. Crie o jogo da colheita de maça;
2. Use um sprite como o Bowl e a maça, Apple;
3. Faça a maça cair aleatóriamente sempre começando do topo, variando apenas o eixo X;
4. Faça a tigela \(Bowl\) movimentar junto com o mouse, variando apenas o eixo X;
5. **Desafio**: Adicione pontuação.

![Figura 4.9. Exemplo de como ficar&#xE1; o exerc&#xED;cio de colher ma&#xE7;a.](../.gitbook/assets/scratch-colher-maca.png)

Até aqui você utilizou diversos recursos de programação sem saber exatamente seus conceitos, isso é incrível, pois mostra o quanto o Scratch é intuitivo, então, agora vou lhe ensinar todos os conceitos que servirão de base para o aprendizado de qualquer uma das linguagens nas próximas seções. 



