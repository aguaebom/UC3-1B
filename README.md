# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
# VARIAVEIS

Servem como um elemento base para a progamação, pois pode armazenar cada dado.

**Var**- Permite alterações de reatribuir variável e valores.

**let**- Não permite reatribuir variáveis, mas permite reatribuir valores.

**const**- Permite nem reatribuir variáveis nem valores.

# TIPOS PRIMITIVOS
**NUMBER**

São dados numéricos que podem armazenar até 15 dígitos. Com eles, é possivel realizar contas matemáticas

```js
let a = 2;
let b = 2;
let soma = (a + b)
```
**Como transformar converter string para número**

parseInt()- Converte uma string para número inteiro.

paeseFloat()- Converte uma string para número decimal. 

[Para saber de maneira mais detalhada, clique aqui](https://pt.stackoverflow.com/questions/134453/como-converter-uma-string-para-int-em-javascript)

[Ou aqui](https://www.alura.com.br/artigos/convertendo-string-para-numero-em-javascript?utm_term=&utm_campaign=%5BSearch%5D+%5BPerformance%5D+-+Dynamic+Search+Ads+-+Artigos+e+Conte%C3%BAdos&utm_source=adwords&utm_medium=ppc&hsa_acc=7964138385&hsa_cam=11384329873&hsa_grp=164068847699&hsa_ad=703934793962&hsa_src=g&hsa_tgt=dsa-2273097816642&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=CjwKCAjwmaO4BhAhEiwA5p4YLzpUEZtJdNOtHJ_oRvsItvjjBEoDUgbq9xO8jT8KUKTOvCswDNXSHBoCdScQAvD_BwE)

***BOOLEAN**

Um Boolean é um valor no qual define de uma função para descobrir se uma variável é real (true) ou falsa (false).

Para isso é necessário condições e separações

 comparação | significado      
------------|---------------
   ==       | igual
   ===      | igual
 '>'        | maior
 '<'        | menor
 '>='       | maior igual
  '<='      | menor igual a
   !==      | diferente
   !=       | diferente


por favor ignorem as aspas no maior que e menor que (tinha que encontrar uma maneira de não travar a lista)

**NULL**

Valor vazio

**UNDEFINED**

Indefinido

# STRING
Maneira de representar um dado em maneira de texto
-Podendo ser represendado pelas "", '' ou ``

exemplos de fixação
```js
console.log("Hello world");
console.log("Hello" + " " + "world"); 
//casos com variaveis
const nome = naju
console.log("Hello" + " " + nome)
console.log(`Hello ${nome}`)
```
# ESTRUTURA CONDICIONAL

**IF & ELSE**

Como o nome já fala, if e else são estruturas condicionais que agem de acordo com o seguinte comando:
```js
if(resposta == variável ou sla){ //se tal coisa for isso
console.log(faça isso)
} else {  //se não
console.log(faça isso)
}
```
também podemos usar else if como uma nova condição.

**SWITCH CASE**

O switch case consiste em ser um if else, porém usando blocos de código

vamos supor que a nossa situação é de uma livraria

```js
 
const produto = prompt('Qual livro/mangá você deseja?')
switch(produto){  //O () vai se referir a resposta da variável
  case "Oyatsumi punpun": //o case serve como um valor possível
  console.log("A Oyatsumi pun pun custa R$47,00.")
  break; //o break serve para evitar repetições
case "Diário de um banana":
case "Azumanga Daioh":
  console.log("O diário de um banana e Azumanga Daioh custam R$20,00.")
  break;
  case "Five nights at freddy's-olhos prateados":
  console.log("A Fnaf-Olhos prateados custa R$50.");
  break;
  case "O corpo fala":
  console.log("O corpo fala custa R$46.");
   break;
  default : //O default é tipo um else, caso nenhum dos cases sejam atendidos ele realiza a tal funÇão abaixo
  console.log("Ish...Não temos o que você deseja :c");
}
```
# ARRAY
Uma maneira de listar dados
```js
const livros = ["Javascript Assertivo", "Engenharia de testes", "Clean code", "Scrum", "Guia HTMLS e CSS3","MongoD8"]

livros.sort();

console.log(livros)
```
o array pode ter diversos metodos sendo eles os seguintes:
```js
//retorna a quantidade de elementos de um array
console.log(livros.length); 
//remove o último elemento de um array e retorna este elemento
console.log(livros.pop());
//adiciona um ou mais elementos ao final de um array e retorna a este elemento
console.log(livros.push("Vagabond"));
//remove o primeiro elemento de um array e retorna esse elemento
console.log(livros.shift());
//adiciona um ou mais elementos no início de um array e retorna o tamanho deste array
console.log(livros.unshift("vue.js"));
console.log(livros);

var lista = ["primeiro","segundo","terceiro"]
console.log(lista[lista.length - 1])//inicia a contagem da quantidade de elementos(nesse caso são 3)
```
um exemplo de junção de elementos(concat)
```js
const livros = ["I have no mouth and i must scream", "All tomorrows", "Olhos de prata", "Fetch", "O corpo fala"]
const HQSeMangás = ["Vagabond", "oyatsumi punpun", "Hunter x Hunter", "Jujutsu kaisen", "Evangelion", "Nana"]
const JuntarLivros = livros.concat(HQSeMangás)

alert(JuntarLivros)//pode colocar console.log também
```
um exemplo de adição e a atualização de elementos
```js
const livros = ["I have no mouth and i must scream", "All tomorrows", "Olhos de prata", "Fetch", "O corpo fala"]

let pergunta = prompt("Qual livro você deseja?")

const atualizandoLivros = livros.splice(3,0, pergunta);
                                  //(indice de localização, n. de elementos a deletar, adicionar)
console.log(atualizandoLivros);

alert(livros)//pode ser console.log também :V
```
# FUNCTION
como o nome ja fala, é uma função

um exemplo:
```js
function falar(){ //parâmetro
             //(dado de entrada)
  return 'hihihihhah'
}
console.log(falar())
```

## Atividades desenvolvidas
[atividade 1](https://codepen.io/Ana-j-lia-Gouveia/pen/MWMvoOV)

[atividade 2](https://codepen.io/Ana-j-lia-Gouveia/pen/yLdPMMj)

[atividade 3](https://codepen.io/Ana-j-lia-Gouveia/pen/OJeQQyp)

[atividade 4](https://codepen.io/Ana-j-lia-Gouveia/pen/zYVyzyp)

[atividade 5](https://codepen.io/Ana-j-lia-Gouveia/pen/MWNWjrP)

[atividade 6](https://codepen.io/Ana-j-lia-Gouveia/pen/yLmOGjY)

[atividade 7](https://codepen.io/Ana-j-lia-Gouveia/pen/RwXRzLr)

[atividade 8](https://codepen.io/Ana-j-lia-Gouveia/pen/oNKYEmy)



