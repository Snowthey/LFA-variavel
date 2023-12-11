# LFA-variavel
Projeto de prova sobre um autômato finito focado em variáveis de compiladores 

1) Você foi contratado para trabalhar em um projeto de desenvolvimento de um Compilador. E uma das atribuiçoes é implementar um Autômato para reconhecer uma variável. A linguagem formal que define uma variável <var> é:
<var> ::= ('_' ou <letra> ) {'_'| <letra>| <digito>}
Os demais simbolos poderão ser '_' ou <letra> ou <digito>
Por estarem entre chaves '{}' podem repetir 0 ou n vezes.
<letra> :: = a-z
digito :: = 0-9

a) Representação gráfica do Autômato - utilizar o Jflap
b) Utiizando C#, implemente o autômato projetado. O programa deve apresentar uma interface gráfica, com um campo para o usuario digitar uma palavra. Ao clicar no botão "compilar", o programa deve apresentar passo a passo a execução do autômato.
O programa deve exibir a mensagem "Variável" ou "não é Variável"
