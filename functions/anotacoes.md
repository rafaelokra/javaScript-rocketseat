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
