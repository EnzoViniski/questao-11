Algoritmo "Divisível"

var
   n1, divi, divi2: real
   
inicio
   //Entrada de dados
   escreva("Digite o número: ")
   leia(n1)
   
   //Operações
   divi <- n1 % 3
   divi2 <- n1 % 5
   
   //Saída de dados
   se (divi = 0) e (divi2 = 0) entao
      escreva("O NUMERO E DIVISIVEL")
   senao
      escreva("O NUMERO NAO E DIVISIVEL")
   fimse
fimalgoritmo
