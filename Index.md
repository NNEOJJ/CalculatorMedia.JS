# CalculatorMedia.JS
Olá, meu nome é NeoJJ, criei essa simples calculadora de média para ser usada em colégios, é uma simples tarefa que ela executa, voce irá colocar sua nota e ela simplesmente dirá se voce foi APROVADO ou REPROVADO. ByNEOJJ 


/ * VALORES * /

 const calculateMedia = (nota1, nota2) => {
let media = (nota1 + nota2) /2;

return media;

}

/* LEITURA */

let resultado= calculateMedia (7, 7);
console.log (resultado);

if (resultado >=7)
console.log ("APROVADO");
else
console.log ("REPROVADO");

