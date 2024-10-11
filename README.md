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
# SWITCH CASE
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


prompt
tipos primitivos
## Atividades desenvolvidas
lista de frutas(switch), compra de frutas(array), string e o vídeo.


