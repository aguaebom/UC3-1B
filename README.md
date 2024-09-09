# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
**ARRAY**

Uma maneira de listar dados
```js
const livros = ["Javascript Assertivo", "Engenharia de testes", "Clean code", "Scrum", "Guia HTMLS e CSS3","MongoD8"]

livros.sort();

console.log(livros)
```
o array pode ter diversos metodos sendo eles os seguintes:
```js
console.log(livros.length);//retorna a quantidade de elementos de um array
console.log(livros.pop());//remove o último elemento de um array e retorna este elemento
console.log(livros.push("Vagabond"));//adiciona um ou mais elementos ao final de um array e retorna a este elemento
console.log(livros.shift());//remove o primeiro elemento de um array e retorna esse elemento
console.log(livros.unshift("vue.js"));//adiciona um ou mais elementos no início de um array e retorna o tamanho deste array
console.log(livros);

var lista = ["primeiro","segundo","terceiro"]
console.log(lista[lista.length - 1])//inicia a contagem da quantidade de elementos(nesse caso são 3)
```
um exemplo de junção de elementos
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
**STRING**

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
variaveis
switch
prompt
tipos primitivos
## Atividades desenvolvidas
lista de frutas(switch), compra de frutas(array), string e o vídeo.


