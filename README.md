# RespostasTarget

Respostas dos testes do processo seletivo

1.
Ao final do processamento o resultado da variável SOMA será 91.

2. 
Utilizando a linguagem Javascript podemmos ter o seguinte programa:

let numero = parseInt(prompt("Digite um número:"));
let a = 0;
let b = 1;

while (b < numero) {
  let proximo = a + b;
  a = b;
  b = proximo;
}

if (b === numero) {
  console.log(numero + " pertence à sequência de Fibonacci.");
} else {
  console.log(numero + " não pertence à sequência de Fibonacci.");
}

3.
a) o próximo número da sequência é o 9
lógica: adicionar +2 ao número anterior

b) o próximo número é o 128
lógica: multiplicar o número anterior por 2

c) o próximo número é o 49
lógica: elevar o número ao índice 2

d) o próximo número é o 100
lógica: número pares elevados ao índice 2

e) o próximo número é o 13
lógica: a soma dos dois últimos números

f) o próximo número é o 20
lógica: a soma do primeiro e segundo digito do último número

4.
Para resolver essa questão utilizei a fórmula de Vm (velocidade média)

Vm = ΔS/Δt
Tempo do carro = 100km/110km/h
Tempo do casso = 0,91h

Tempo do caminhão = 100m/80km/h
Tempo do caminhão = 1,25h 
com os pedágios = 1,25 + (2 * 5) = 1,42h

Logo, quando eles se encontrarem o carro vai estar mais perto de Ribeirão preto ddo que o caminhão, já que ele percorre a distância entre as duas cidades no menor tempo

5.
Programa que inverte os caracteres de um string em Javascript

// definindo a string que será invertida
let str = "exemplo";

// convertendo a string em um array de caracteres
let arr = str.split("");

// invertendo a ordem dos caracteres no array
let reversedArr = [];
for (let i = arr.length - 1; i >= 0; i--) {
  reversedArr.push(arr[i]);
}

// convertendo o array de volta para uma string
let reversedStr = reversedArr.join("");

// exibindo a string invertida no console
console.log(reversedStr); // output: "olpmexe"

