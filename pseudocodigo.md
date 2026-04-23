algoritmo "Controle de Acesso Sala de Aula"

var
nome_aluno, resposta_lista: caractere
total_alunos, contador: inteiro

inicio

escreva("Quantos alunos estão na fila? ")
leia(total_alunos)

contador <- 1

enquanto (contador <= total_alunos) faca
escreval("Verificação do Aluno ", contador)
escreva("Digite o nome do aluno: ")
leia(nome_aluno)

  escreva("O nome '", nome_aluno, "' consta na lista oficial? ")
  leia(resposta_lista)

  se (resposta_lista = "S") ou (resposta_lista = "s") entao
     escreval("RESULTADO: Acesso Permitido. Seja bem-vindo!")
  senao
     escreval("Acesso Negado")
  fimse
  
  contador <- contador + 1
fimenquanto

escreval("Fim da fila. Todos os alunos foram verificados.")
fimalgoritmo