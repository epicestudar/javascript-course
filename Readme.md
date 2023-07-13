Curso de JS do professor Guanabara!

Anotações que considero importante deixarei anotado aqui, especificando a aula e o módulo da respectiva anotação!


Dando os Primeiros passos - Curso JS #03:

Livros para aprender mais sobre JS: 
- Javascript - O guia definitivo --- David Fanagan (?) --- é pago
- Javascript - Guia do programador --- Maurício ---  é pago

- Guia de referência mozilla (link: https://developer.mozilla.org/pt-BR/)
- Guia de referência ecma


Variáveis e Tipos Primitivos - curso JS #05
 - vaga a1 = carro 1 ---- um único sinal de igual em JS significa RECEBE, ou seja, vaga a1 RECEBE carro 1
 - no JS, definimos uma variável como "var" ou como "let"  
 - os nomes das variáveis que formos criar, chamadas de IDENTIFICADORES, possuem algumas regras:
 1. podem começar com letra, $ ou _
 2. NÃO podem começar com números
 3. PODE usar acentos e símbolos
 4. NÃO podem conter espaços
 5. NÃO podem ser paçavras reservadas que já existam na linguagem
 


 Tratamento de Dados - Curso JS #06
 - Sinal de + serve para concatenar as strings
 - Com o comando Number vc transforma string em número (está na pasta aula06 e no arquivo ex003)
 - Para passar número para String: String(nome da variável que quer transformar)

 - `O aluno ${nome} com ${idade} anos tirou a nota ${nota}` -- neste comando, você constrói a frase dentro das duas crases invertidas fazendo uso do ${nome de sua variável}

 - Formatando strings:
 var s = 'Javascript'
 s.lenght -- quantas caracteres a string tem
 s.toUpperCase() -- tudo para maiúscula
 s.toLowerCase -- tudo para minúscula

 - document.write('Algum texto') --  este comando exibe a mensagem no documento do texto e não mais no prompt da janela. Para entender melhor vá até a pasta aula06 e no arquivo ex004.html

 
 Operadores (parte1) - curso JS #07
 5 + 2 = 7 -- SOMA
 5 -2 = 3 -- SUBTRAÇAO
 5 * 2 = 10 -- MULTIPLICAÇAO
 5 / 2 = 2.5 -- DIVISAO
 5 % 2 = 1 -- RESTO DA DIVISAO
 5 ** 2 = 25 -- POTENCIAÇAO

 - Ordem de precedência dos operadores aritméticos: 
 1 . ()
 2. **
 3. * / %
 4. + -


 - Simplificando:
 n = n + 4 ------- n +=4
 n = n - 4 ------- n -=4
 n = n * 4 ------- n *=4
 n = n / 4 ------- n /=4
 n = n ** 4 ------- n **=4
 n = n % 4 ------- n %=4



 Operadores (parte 2) - curso JS #08

 - IDENTIDADE DE OPERADORES RELACIONAIS:
 5 == 5 --- true
 5 == '5' -- true
 5 === '5' --- false, os três sinais de iguais comparam tanto o valor como o tipo, enquanto os dois sinais testam apenas os valores
 5 === 5 --- true dnv 

 - PRECEDÊNCIA DOS OPERADORES LOGICOS:
 Primeiro o "!"
 Depois o "&&"
 E por último o "||"

 - OPERADORES TERNÁRIOS: 
 ? e : em uma mesma expressão
 Sintaxe: teste ? true : false
 Exemplo: media >= 7.0?"Aprovado":"Reprovado"