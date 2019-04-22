# Linguagem de Programação (5LIEE-NT1)

Repositório referente a disciplina Linguagem de Programação(5LIEE-NT1) ministrada pelo professor [João Ronaldo Cunha](https://about.me/joaoronaldocunha) para o curso de Análise e Desenvolvimento de Sistemas da [Unimetrocamp](https://www.wyden.com.br/unimetrocamp).

## Integrantes

Nome  | RA
------------- | -------------
Bruno Zambote  | 171151797
Mateus M. Pinto  | 171151666
Pedro J. B. Bruno  | 171150770
Victor G. do Nascimento  | 171152158

## Prática Aula 02

**Enunciado:** Para cada linguagem foco, definir: 

* Paradigmas de Programação
* Tipo da Linguagem (Complilada x Interpretada/ Fortemente x Fracamente Tipada/ Linguagem Script x Programação)
* Principais Aplicações: Web, IoT, Aplicações Desktop etc
* Exemplos de uso

### Paradigmas de Programação ###

Dentre os paradigmas de programação do Javascript podemos citar o modelo imperativo, procedural e também orientado a objetos através do uso de protótipos, além de também existir uma grande influência da programação orientada a eventos

### Tipo da Linguagem ###

```
Compilado em tempo de execução através do motor V8 que utiliza compilação JIT
Fracamente tipada
Linguagem de programação
```

### Principais Aplicações ###

O uso de Javascript está principalmente ligado a Web, tanto no client side quanto no back-end(node.js por exemplo), porém
hoje já é possível encontrar o uso de JS em aplicações Desktop utilizando Electron por exemplo.


### Exemplo de uso ###

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

## Prática Aula 03

**Enunciado:** Para a linguagem foco selecionada(*Javascript*) pesquisar **síntaxe** e **semântica**.

* Palavras reservadas
* Literais
* Operadores
* If ternário

### Palavras reservadas ###

```javascript
abstract,
else,
instanceof,
super
boolean,
enum,
int,
switch
break,
export,
interface,
synchronized
byte,
extends,
let,
this
case,
false,
long,
throw
catch,
final,
native,
throws
char,
finally,
new,
transient
class,
float,
null,
true
const,
for,
package,
try
continue,
function,
private,
typeof
debugger,
goto,
protected,
var
default,
if,
public,
void
delete,
implements,
return,
volatile
do,
import,
short,
while
double,
in,
static,
with
alert,
frames,
outerHeight
all,
frameRate,
outerWidth
anchor,
function,
packages
anchors,
getClass,
pageXOffset
area,
hasOwnProperty,
pageYOffset
Array,
hidden,
parent
assign,
history,
parseFloat
blur,
image,
parseInt
button,
images,
password
checkbox,
Infinity,
pkcs11
clearInterval,
isFinite,
plugin
clearTimeout,
isNaN,
prompt
clientInformation,
isPrototypeOf,
propertyIsEnum
close,
java,
prototype
closed,
JavaArray,
radio
confirm,
JavaClass,
reset
constructor,
JavaObject,
screenX
crypto,
JavaPackage,
screenY
Date,
innerHeight,
scroll
decodeURI,
innerWidth,
secure
decodeURIComponent,
layer,
select
defaultStatus,
layers,
self
document,
length,
setInterval
element,
link,
setTimeout
elements,
location,
status
embed,
Math,
String
embeds,
mimeTypes,
submit
encodeURI,
name,
taint
encodeURIComponent,
NaN,
text
escape,
navigate,
textarea
eval,
navigator,
top
event,
Number,
toString
fileUpload,
Object,
undefined
focus,
offscreenBuffering,
unescape
form,
open,
untaint
forms,
opener,
valueOf
frame,
option,
window
onbeforeunload,
ondragdrop,
onkeyup,
onmouseover
onblur,
onerror,
onload,
onmouseup
ondragdrop,
onfocus,
onmousedown,
onreset
onclick,
onkeydown,
onmousemove,
onsubmit
oncontextmenu,
onkeypress,
onmouseout,
onunload
```

### Literais ###

Um literal é um valor inserido de maneira hardcode no Javascript, com por exemplo:
```javascript
var obj = "sushi"
```

O valor de obj é o valor fixo sushi.

### Operadores ###

Atribuição    x = y    x = y <br />
Atribuição de adição    x += y    x = x + y <br />
Atribuição de subtração    x -= y    x = x - y <br />
Atribuição de multiplicação    x *= y    x = x* y <br />
Atribuição de divisão    x /= y    x = x / y <br />
Atribuição de resto    x %= y    x = x % y <br />
Atribuição exponencial    x `**`= y    x = x `**` y <br />
Atribuição bit-a-bit por deslocamento á esquerda    x <<= y    x = x << y <br />
Atribuição bit-a-bit por deslocamento á direita    x >>= y    x = x >> y <br />
Atribuiçãode bit-a-bit deslocamento á direita não assinado    x >>>= y    x = x >>> y <br />
Atribuição AND bit-a-bit    x &= y    x = x & y <br />
Atribuição XOR bit-a-bit    x ^= y    x = x ^ y <br />
Atribuição OR bit-a-bit    x |= y    x = x | y <br />
Igual (==) <br />
Não igual (!=) <br />
Estritamente igual (===) <br />
Estritamente não igual (!==) <br />
Maior que (>) <br />
Maior que ou igual (>=) <br />
Menor que (<) <br />
Menor que ou igual (<=) (edited) <br />

Módulo (%) <br />
Incremento (++) <br />
Decremento (--) <br />
Negação (-) <br />
Adição (+) <br />
Operador de exponenciação (`**`) <br />

AND    a & b <br />
OR    a | b <br />
XOR    a ^ b <br />
NOT    ~ a <br />

Deslocamento à esquerda    a << b  <br />
Deslocamento à direita com propagação de sinal    a >> b <br />
Deslocamento à direita com preenchimento zero    a >>> b <br />

AND lógico (&&) <br />
OU lógico (||) <br />
NOT lógico (!) <br />

### If ternário ###

condicao ? valor1 : valor2

## Prática Aula 04

* Principais versões do Javascript/Typescript
* Conjunto de ferramentas de desenvolvimento
* Diferenças entre Javascript x Typescript

### Principais versões do Javascript/Typescript ###

Javascript:
```
ECMAScript 1 (1997)
ECMAScript 2 (1998)
ECMAScript 3 (1999)
ECMAScript 4	Never released.
ECMAScript 5 (2009)
ECMAScript 5.1 (2011)
ECMAScript 2015
ECMAScript 2016
ECMAScript 2017
ECMAScript 2018
```

Typescript
```
TypeScript 1
TypeScript 2
TypeScript 3 (Atualmente 3.4.2)
```

### Conjunto de ferramentas de desenvolvimento ###

Para o uso de Javascript e Typescript, a maioria das ferramentas se assemelham como por exemplo uma IDE ou editor de código como o VS Code e um browser como o Chrome.
Para o caso do Typescript que precisa ser transpilado para JS é necessário o uso de algumas ferramentas adicionais. Como por exemplo NodeJS para a instação das dependências e de um compilador para ECMAScript.

### Diferenças entre Javascript x Typescript ###

Por se tratar de um superset do JS, o Typescript herda todas as funcionalidades e ainda acrescenta algumas, como por exemplo:

```
Tipagem opcionalmente estática
Classes (já há alguma coisa no JS), interfaces e mixins
Módulos
Enumeração
Generics
Parâmetros opcionais e com valores default
Tuplas
Union types
Alias de tipos
entre outros
```

* Estrutura mínima para um programa em NodeJS
* Hello World em JS
* Hello World em Typescript

### Estrutura mínima para um programa em NodeJS ###

```javascript
var http = require('http');
http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello Node.JS!');
}).listen(8080);
```

### Hello World em JS ###

```javascript
alert("Hello World!"); // Hello World
```

### Hello World em Typescript ###

```javascript
function hello(): string {
    return "Hello World";
}

console.log(hello()); // Hello World
```

## Prática Aula 05

### Levantamento de tipos primitivos simples ###

Null: o conjunto com o único elemento null.
Boolean: o conjunto com os dois elementos false e true.
Number: o conjunto de todos os números.
String: o conjunto de todas as strings.

### Levantamento de tipos primitivos compostos ###

Any: Uma variável do tipo Any pode assumir qualquer valor.
Void: O void é usado para determinar que um método não retorna nenhum valor.
Enum: são velhos conhecidos do C#, e usados como “datatype”, que podem definir um status por exemplo.

### Conversão de tipos  ###

https://bit.ly/2IC6wvt

### Coleções  ###

https://bit.ly/2IBy0RY

### Categorias básicas de fluxos de controle  ###

https://bit.ly/2GC3QMk

### Input e Output de informações usando o teclado e o console  ###

https://bit.ly/2Vmvipx

### Exercício 01 - Conversão de Temperatura  ###

https://bit.ly/2Ux2eac

### Exercício 02 - Reajuste de salário  ###

https://bit.ly/2GAizqU



