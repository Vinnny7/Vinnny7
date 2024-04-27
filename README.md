Algoritmo "semnome"

Var
   Nota: inteiro
   soma,i: inteiro
   media: real


Inicio
   para i de 1 ate 2 passo 1 faca
      repita
         escreval("Digite a ", i, " nota do aluno: ")
         leia(Nota)

         se (nota < 0) ou (nota > 10) entao
            escreval("Nota inválida. Digite uma nota entre 0 e 10.")
            escreval
         fimse

      ate (nota >=0) e (nota <=10)

      soma <- soma + nota
   fimpara

   media <- soma / 2
   escreval("Média: ", media)


Fimalgoritmo
