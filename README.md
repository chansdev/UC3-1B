# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico

### O Que É JavaScript
JavaScript é uma linguagem de progamação, geralmente ultilizada para front-end, que interage com os elementos da página.

### Var
Var é uma maneira de criar uma variável no JavaScript.  
Uma variável var pode ser usada e modificada de qualquer escolpo do progama.
**Exemplo:**
  ```js
    var exemplo = 'exemplo'
    console.log(exemplo) // 'exemplo'
  ```

### let
Let é uma maneira de criar variável no JavaScript.  
Uma variável let só pode ser usada por algo no mesmo escolpo ou em um inferior, e só pode ser modificada por uma variável const ou outra let.
  ```js
    let exemplo = 'exemplo'
    console.log(exemplo) // 'exemplo'
  ```

### const
Cost é uma maneira de criar variável no JavaScript.
Uma variável const não pode ser modificada por nenhuma outra variavel e pode ser usada por algo no mesmo escolpo ou em um inferior.
  ```js
    const exemplo = 'exemplo'
    console.log(exemplo) // 'exemplo'
  ```
### String
String é um dos elementos primários do JavaScript.  
Ele representa um texto puro e pode ser facilmente concatenado ultilizando a adição.
  ```js
    string1 = 'Oi '
    string2 = 'pessoa!'
    novaString = 'Oi pessoa!'
    console.log(novaString) // 'Oi pessoa!'
  ```

### Number
Number é um dos elementos primários do JavaScript.  
Ele representa um número e com ele podemos facilmente fazer cálculos matemáticos.
  ```js
    n1 = 2
    n2 = 3
    somaN = n1 + n2
    console.log(somaN) // 5 
  ```

### Boolean
Boolean é um dos elementos primários do JavaScript.  
Ele representa um valor de true(verdadeiro) ou false(falso). Isso é muito usado quando precisamos saber quando uma condição que criamos é verdadeira para assim aplicar o que acontecera se isso for verdade.

  ```js
    console.log(isNaN('texto')) // true
    console.log(isNaN(1)) // false
    // isNaN é uma função que checa se algo inserido não é um número. Se não for um número ele retorna o valor booleano true.
  ```

### Operadores Lógicos
Os operadores lógicos são operadores que nos permitem juntar, inverter ou escolher uma das condições que criamos.
  ```js
    // && Verifica se as duas condições são verdadeiras
    console.log(isNaN('texto') && isNaN('texto2')) // true
    console.log(isNaN('texto') && isNaN(2)) // false

    // || Verifica se pelomenos uma das condições são verdadeiras
    console.log(isNaN('texto') || isNaN(3)) // true
    console.log(isNaN(2) || isNaN(3)) // false

    // ! Inverte a condição
    console.log(!isNaN(4)) // true
  ```

### Operadores Comparativos
Os operadores comparativos são operadores que nos permitem comparar uma condição com algo.
  ```js
    // == compara se o resultado é igual a algo.
    const texto = 'texto'
    console.log(texto == 'texto') // true
    // Está comparando uma variavel com uma String com valor "texto" a uma String, fora de variavel, com valor "texto".

    // === compara se o valor e o tipo são iguais a alto
    const numero = '3'
    console.log(numero === 3) // false
    // Está comparando uma variavel com uma String com valor "3" a um Number, fora de variavel, com valor 3.

    // Lembrando que mesmo que a String e o Number tenham o mesmo valor eles são elementos diferentes. 
  ```

### If e Else
O if e else permite-nos definir uma condição e fazer que algo aconteça quando essa condição for verdadeira.
  ```js
    resposta = '5'

    if (resposta == '5') {
      console.log('Resposta correta!') // 'Resposta correta!'
    } else {
      console.log('Resposta errada...') // 'Resposta errada...'
    }

  // O if compara uma condição expecifica e retorna algo, e o else, colocado no final, retorna algo se nenhum das condições
  // acima forem verdadeiras
  ```

## Atividades desenvolvidas

### Caixa Eletrônico | Sistema de Notas | Jogo de adivinhação

#### Nesse pen eu desenvolvi 3 projetos bem básicos.
##### Caixa Eletronico (_Linha 1 a 19_)
Um algorítimo semelhante a um caixa eletrônico que pergunta o valor, a quantidade, o imposto e o desconto do produto selecionado e faz os calculos necessários para retornar o valor que o cliente precisa pagar por esse produto.

##### Sistema de Notas (_Linha 21 a 41_)
Nesse algorítimo é perguntado a nota final de todas as matérias do aluno, assim ele retorna a média e informa se o aluno passou de ano ou não.

##### Jogo de Adivinhação (_Linha 43 a 69_)
Nesse o algorítimo pergunta se você aceita jogar o jogo. Se você aceitar ele te da uma dica do que pode ser a resposta e fica perguntando qual é até você acertar, e se você recusar ele te chinga.

###### *No final do pen tem um estudo de Array que eu agora nem entendi do que se tratava*

__[PROJETO](https://codepen.io/Heitor-Chans/pen/poXPMLo)__

### Hortifruti
#### Simula uma loja de frutas online
O que acontece basicamente é que a página pergunta se você quer comprar frutas e aceitando é exibido a lista de frutas disponíveis no momento. Quando você escola uma fruta aparece a fruta que você comprou no console.  
É um sistema muito básico na verdade, até porque não aparece o preço da fruta que você quer comprar.

__[PROJETO](https://codepen.io/Heitor-Chans/pen/GRbyxza)__

### Locadora
#### Simula uma locadora online
Esse pen é uma versão mais avançada do anterior, pois ele apresenta mais opções e tem a capacidade de indentificar se a opção que você escolheu está presente nas opções citadas. Assim ele pede para você reescrever o que quer se você escreveu algo errado.  
Além disso tudo isso só acontece quando você clica no botão "comprar".  
*Não fui eu que fiz o css desse botão*

__[PROJETO](https://codepen.io/Heitor-Chans/pen/yLdGbWL)__

### Feriados nacionais
#### Informa os feriados nacionais de cada mês
Esse é um projeto bem básico e simples. Ele apenas mostra cada feriado nacional presente no mês escolhido ultilizando o switch case.

__[PROJETO](https://codepen.io/Heitor-Chans/pen/bGXePxY)__

### Palindromo
#### Diz se a frase ou palavra digitada é um palindromo
Esse projeto, apesar de simples, ultiliza um código um pouco mais avançado. Ele pega a frase ou palavra escrita, inverte ela e diz se fica igual a se ela não estivesse invertida.

__[PROJETO](https://codepen.io/Heitor-Chans/pen/wvVGQpp)__

### Pokemon
#### Simula uma batalha de pokemon
Esse é o projeto que eu tenho mais orgulho até agora, pois ele é bem complexo.  
Eu trabalhei nele como "front-end" junto com o meu amigo [João Mendonça](https://github.com/JoaoPapaya). Nele você controla um dragonite e tem que vencer uma batalha contra um gengar. Pode parecer simples mas tenha certeza que não foi. Eu fiquei muito tempo tentando descobrir uma maneira de como fazer com que a barra de vida funcionasse, mas no final deu tudo certo.

__[PROJETO](https://codepen.io/Heitor-Chans/pen/QWeLLKe)__
