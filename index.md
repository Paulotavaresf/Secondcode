Algoritmo "meu segundo código"
Var
  valor , juros, parcela, montante: real
Inicio
   Escreva("Qual o valor do emprestimo? ")
   leia(valor)
   juros <- valor*20/100
   Escreva("Em quantas vezes quer dividir? ")
   leia(parcela)
   montante <- (juros + valor) / parcela
   escreva("vou pagar em",parcela," parcelas de R$", montante, " reais")
Fimalgoritmo