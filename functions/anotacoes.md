/* Prototype

    * prototype-base language
    * prototype chain
    * _proto_
*/

/* Type conversion ( typecasting) vs coersion 
    * alteracao de um tipo de dado para outro tipo

*/   

/*
    // Manipulando Strings e Numeros

    // TRansformar String em Numero e Numero em string

            let string ="123"
            Number(string)
            let number =321
            console.log(String(number))
*/

/*
// Manipulando Strings e Numeros

// Conta quantos caracteres te uma palavra e quantos digitos tem um numero
        let word = "Paralepipedo"
        console.log(word.length)
        console.log(String(number.length))

// Transformar um numero quebrado com 2 casas decimais e trocar ponto por virgula
        let number =345.664
        console.log(number.toFixed(2).replace(".", ","))   


   // Transforma letras minusculas em maiusculas.Faca o contrario disso tambem
            let word = "Programar e muito bacana!"
            console.log(word.toUpperCase()) transfoma em maiuscula

            console.log(word.toLowerCase()) troansorma em minuscula

    // Separe um texto que contem espaços, em um novo array onde cada texto é uma posicao do array.Depois disso , transforme o array em um texto e onde eram espaços , coloque _

            let phrase = "Eu queroviver o Amor!"
            let myArray = phrase.split(" ")
            let phraseWithUnderscore = myArray.join("_")
            console.log(phraseWithUnderscore)


    // Verificar se o texto contem a palavra Amor
            let phrase = "Eu quero viver o "
            console.log(phrase.incluides("Amor"))
 */       

 /* 
 //  Manipulando Arrays

  // Criar Array com construtor
        let myArray = new Arrya('a', 'b', 'c')
        console.log(myArray)

   // Contar elementos de um Array
   console.log(["a", "b", "c"]. length)     


   // Transformar uma cadeia de caracteres em elementos de um array
            let word = "manipulacao"
            console.log(Array.from(word))

   //       let techs = ["html", "css", "js"]

    // adicionar um item no fim
            techs.push("node.js)
    // adicionar no começo
            techs.unshift("sql")
    // remover do fim
        techs.pop()
    // remover do começo  
        techs.shift()
    //pegar somente alguns elementos do array
        console.log(techs.slice(1,3))
     // remover 1 ou mais items em qualquer posicao do  do array
            techs.splice(1, 1)  
    // encontrar a posicao de um elemento no array
            let index = techs.index('css')

            console.log(index)
/* Expressoes e Operadores

        -Expressions
        -Operators
        Binary
        Unary
        Ternary
 */

 /* Operedores Aritimeticos
        // multiplicacao *
        console.log(3*2)     
        //divisao /
        console.log(12 / 2) 
        //soma +
        console.log(2 + 5) 
        subtracao -
        console.log(10 - 8)

        //resto da divisao %
        let remainder
        remaider = 11 % 9
        console.log(remainder)

        // incremento ++
        let increment
        console.log(increment++)
        console.log(increment)

        //decremento --
          let decrement = 0
          console.log(decrement)

        // exponencial **
        console.log(2**3)  

    /* Operedores de comparacao

    // Ira comparar valores e retornar um boolean como resposta a comparacao

        let one = 1
        let two = 2    

    // ==    igual a 

        console.log(two == 1)
        console.log(one == "1")

    // !=    diferente de 

        console.log(one !=  two)
        console.log(one != 1)
        console.log(one != "1")   

   // === estritamente igual a

        console.log( one === "1")
        console.log( one === 1)

   //  !==    estritamente diferente de

        console.log( two !== "2")
        console.log( two !== 2)

   let one = 1
   let two = 2

   // >   Maior que
        console.log( one > two)

   // >=   Maior igual a
        console.log(one >= 1) 
        console.log( two >= 1)

   //  <     Menor que
        console.log( one < two)         

   // <=   Menor iqual a 
        console.log( one <= two)
        console.log( one <= 1)
        console.log( one <= 0)     

   // Operadores de atribuição (Assignment)
let x

// assignment normal:
x = 1

// addition assignment (adição):
x += 2

// subtraction assignment (subtração):
x -= 1

// multiplication assignment (multiplacação):
x *= 2

// division assignment (divisão):
x /= 2

// exponetiation assignment (exponenciação):
x **= 2

// remainder assignment (resto de divisão):
x %= 2


  // Operadores logicos (logical operators)

  // -2 valores booleanos, quando verificados,resultara em verdadeiro ou falso

        let pao = true
        let queijo = false

  // AND &&
        console.log(pao && queijo)

  // OR || 
        console.log(pao || queijo)

  // NOT !
        console.log(!pao)    

 //  Os operadores ternários, conhecidos como operadores de condição, como o nome sugere, são dependentes de condições e podem entregar valores diferentes com base nelas.

Funciona da seguinte forma;      
        condição ? valor1 : valor2             

   Exemplo de uso:

// Café da manhã top
let pao = false
let queijo = false

const niceBreakfast = pao || queijo ? 'Café top' : 'Café ruim'

console.log(niceBreakfast)     

// Temos também os string operators, os operadores de string, e nós até já vimos um desses antes, o comparison operator, ou ==, para os mais íntimos.

Agora vamos ver sobre a concatenação, que é o retorno da união de duas strings.

Seu símbolo é o de + (positivo), e seu uso é simples, algo próximo de:
        console.log('a' + 'a')
// nesse caso, o retorno da string seria aa.

// O falsy é quando um valor é considerado falso em contextos que onde um booleano é obrigatório (condicionais e loops), exemplo a seguir:

        /*
	Todos os valores abaixo seriam representados como false em um boolean.
		false
    0
    -0
    ""
    null
    undefined
    NaN
*/

console.log( NaN ? 'verdadeiro' : 'falso' )


// já o truthy é o oposto, quando um valor é considerado verdadeiro (true) em contextos onde um booleano é obrigatório (condicionais e loops), exemplo a seguir:

        /* 
	Todos os valores abaixo seriam representados como false em um boolean.
		true
    {}
    []
    1
    3.23
    "0"
    "false"
    -1
    Infinity
    -Infinity
*/

console.log( Infinity ? 'verdadeiro' : 'falso' )


// Nesta aula mostraremos a precedência dos operadores, ou seja, a ordem de importância de cada um deles.

// De cima para baixo, do mais importante ao menos importante.

* grouping                      ( )
* negação e incremento          ! ++ --
* multiplicação e divisão       * /
* adição e subtração            + -
* relacional                    < <= > >=
* igualdade                     == != === !==
* AND                           && 
* OR                            ||
* condicional                   ?:
* assignment (atribuição)       = += -= *= %= 

 if e o else, que ajudam nossa aplicação a tomar diferentes caminhos, ou seja, alteram o fluxo da nossa aplicação.

Sua sintaxe é simples, como pode ver a seguir:

if (condição) {
    //apenas será executado o bloco de código caso condição seja true
} else {
  // apenas será executado o bloco de código caso condição do if seja false
}
O exemplo utilizado pelo professor no vídeo é o seguinte, acompanhe para poder visualizar o processo até chegarmos nesse código.

let temperature = 36.9
let highTemperature = temperature >= 37.5
let mediumTemperature = temperature < 37.5 && temperature >= 37

if(highTemperature) {
    console.log('Febre alta')
} else if(mediumTemperature) {
    console.log('Febre moderada')
} else {
    console.log('Saudável')
}



Vamos usar uma declaração chamada switch, que tem um papel muito similar ao if e ao else if, vistos na aula passada, porém a estrutura é bem diferente, e aqui veremos essa estrutura.

let expression = ''

switch (expression) { // puxa a expressão para o switch
  case 'a': // confere se o valor da expressão é o correto
    console.log('a')
    break // para a execução do switch apenas se verdadeiro
  case 'b':
    console.log('b')
    break
  default: // caso nenhum valor seja o correto, realizará a 
					 //instrução dentro de si.
    console.log('default')
    break
}


throw e try/catch. São parte do controle de fluxo da aplicação.

Throw em inglês significa lançar, disparar, catch quer dizer pegar e try tentar.

Isso significa que vamos tentar executar um bloco de código, e se der algum erro, será disparado e capturado na nossa aplicação. Suponhamos que haja uma função que dispare um erro caso não seja passado um parâmetro dessa função.

function sayMyName(name = '') {
    if (name === '') {
        throw 'Nome é obrigatório'
    }

    console.log(name)
}
Nesse caso, se o nome vier vazio, será disparada uma mensagem.

Precisamos agora usar o try/catch para capturarmos esse erro, caso contrário, ele irá encerrar nossa aplicação, e nós o faremos da seguinte maneira:

try {
    sayMyName()
} catch(e) {
    console.log(e)
}

console.log('após ao try/catch')
O try irá executar a função, enquanto o catch vai capturar o erro e atribuir à variável e, que só existe dentro do catch. Após isso, mesmo com o erro, nossa aplicação não será interrompida por completo.

Estrutura de repeticao

// for
//break-para a execucao do loop
// continue - pula a execucao do momento

A estrutura de repetição for tem a seguinte sintaxe:

for(inicialização de uma variável; condição de continuação para o loop; expressão final)

//while

usar quando nao saber o momento da parada

// for ...of

serve tanto para string como para array

// for ...in

vai criar um loop em cima de um objeto