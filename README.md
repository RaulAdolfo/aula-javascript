# Curso de JavaScript :computer::play_or_pause_button:
#### Aulas do Curso de JavaScript e ECMAScript para Iniciantes, criado pelo professor Gustavo Guanabara para o canal CursoemVideo.



### :bookmark_tabs: Aulas 5

:question: **O que é uma variável?**

 :point_right: **Resposta:** Variável é um espaço reservado na memória do computador que serve para armazenar um determinado tipo de informação. Exemplo uma variável que armazena o nome de uma pessoa, ela terá a função de armazenar o nome de uma certa pessoa, e variáveis só podem receber um valor de cada vez, não podendo conter mais de um valor em simultâneo. 



:question: **Como declarar uma variável numérica Inteira ou Real usando JS?**

 :point_right: **Resposta:**  Algumas das formas para declaramos variáveis em JavaScript é utilizarmos a palavras _var_ ou _let_ depois o nome da variável(sabendo que nem todo o nome pode ser dado como nome da variável), e depois fazer que ela receba um valor inteiro como 1, 2, 0, -1 ou um valor real como 0.5, 0.2, 10.5. 5.55.  



:question: **Quais são os tipos primitivos do JS?** 

:point_right: **Resposta:** Os tipos primitivos do JS(JavaScript) são: Number, String, Boolean, Null, Undefined, Symbol. 



:question: **O que significa colocar o valor null dentro de uma variável?** 

:point_right: **Resposta:**  O significado é que como se a variável não tivesse nada, ela está em um estado null, sem nada.



### :bookmark_tabs:  Aula 6 e 7

 :question: **Como é possível guardar o valor digitado em um prompt() dentro de uma variável?**

:point_right: **Resposta:** Armazenando o resultado dentro de uma variável. Ex: var tempoDuração = Number.parseInt(window.prompt('Qual é o tempo de duração da aula em segundos')) 

:question: **Como fazer com que o número digitado em um prompt() possa ser usado em cálculos?** 

:point_right: **Resposta:** O valor lido deve ser convertido para um tipo numérico, como float ou int, utilizando: Number.parseInt , para inteiros (_Ex: 1,2,3,10,25_), ou  Number.parseFloat , para numeros quebrados _(Ex: 1.5, 7.2, 15.8)_.

:question: **Como transformar um texto todo para letras maiúsculas?**

:point_right: **Resposta:** Utilizando: var nome = window.prompt('Digite o seu nome: ').toUpperCase()  

:question: **Como mostrar um número formatado como um valor monetário?** 

:point_right: **Resposta:** Demonstração: var preco = 199.50  preco = preco.toLocaleString('pt-br', {style: 'currency', currency: 'BRL'}) window.prompt(`${preco}`)



### :bookmark_tabs: Aula 8

:question: **Qual é a diferença entre usar =, == e === em códigos escritos em JS?**

:point_right: **Resposta:** 

- O = é um operador de atribuição, serve para atribuir um valor a uma varável 
- O == é um operador relacional, serve para comparar se duas coisas são iguais 
- O === igualdade restrita. 

:question: **Em uma mesma expressão, temos os operadores || e &&. Quem eu resolvo primeiro? **

:point_right: **Resposta:** Primeiro séria o operador &&(conjunção) depois o ||(disjunção).

:question: **Sabe usar o operador ternário para colocar um entre dois valores em uma variável?**

:point_right: **Resposta:** var gostouVideo = opiniao == true ? 'Ele(a) gostou do Vídeo':'Ele(a) não gostou do video'
