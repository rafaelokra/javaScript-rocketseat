 # variaveis

* Nomes simbolos para receber algum valor
* Atalhos de codigo
* Identificadores
* 3 palavras reservadas para criar uma variavel
  
    * var
    * let
    * const

O JS é uma linguagem fracamente tipada dinamica  
    Variaveis nao precisam ter um tipo
  previamente definido
    Podemos mudar o conteudo da variavel.

#  Scope

  * Escopo determina a visibilidade de alguma variavel no JS  

# Block statement
 
  // vamos inicia um bloco
  {
    // aqui dentro é um bloco e posso colocacr qualquer codigo
    
  } // aqui fevhamos o bloco

   O bloco , tambem criara um novo escopo.chamamos de   block-scoped

## var

// var e global e podera funcionar fora de um escopo de bloco
 /* console.log('> existe x antes do bloco? ',x)

 {
    var x = 0
 }

 console.log('>existe x depois do bloco? ', x) */

 // cons e let sao locais e so funionam no escopo onde foi criada 

 ## Para criar nomes

  * Js e case-sensitive( sensivel ao caso)
  * Js aceira a cadeia de caracteres unicode


  -Posso:
    
    * iniciar co esses caracteres especiais:$ _
    * inciciar com letras
    * colocar acentos
    * Letras maisculas e minusculas fazen diferencas

  - Nao posso:

     * Iniciar com numeros
     * colocar espalos vazios no nome

  - Ideal:

    * criar nomes que fazem sentido
    * Que explique o que a variavel é ou faz
    * camelCase
    * Snake_case
    * Escrever em ingles     