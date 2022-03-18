# exercicio2 java-18-03-22
const valorDigitado = document.getElementById("txtNumeros");
const valorParaEscrever = document.getElementById("escreverNumero");

let valor = 0;
const listaNumeros = [];

function salvar() {

console.log('blaaaaaa');
    

  valor = valorDigitado.value; // value é valor digitado em ingles, valor no
  listaNumeros.push(valor);
  console.log(listaNumeros);
}

function calcularMedia() {
  valorParaEscrever.textContent = valor * 5;
}
