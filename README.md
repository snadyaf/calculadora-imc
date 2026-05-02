# Calculadora IMC

let peso = Number(prompt('Digite seu peso em kg: '));
let altura = Number(prompt('Digite sua altura em m (Ex: 1.56): '));

let imc = peso/altura**2;

if (imc < 18.5){
    console.log(`Seu IMC é ${imc.toFixed(2)}. Você está abaixo do peso normal.`)
} else if (imc < 24.9){
    console.log(`Seu IMC é ${imc.toFixed(2)}. Você está no peso normal.`)
} else if (imc < 29.9){
    console.log(`Seu IMC é ${imc.toFixed(2)}. Você está com excesso de peso.`)
} else if (imc < 34.9){
    console.log(`Seu IMC é ${imc.toFixed(2)}. Você está com excesso de peso. Obesidade Classe I.`)
} else if (imc < 39.9){
    console.log(`Seu IMC é ${imc.toFixed(2)}. Você está com excesso de peso. Obesidade Classe II.`)
} else{
    console.log(`Seu IMC é ${imc.toFixed(2)}. Você está com excesso de peso. Obesidade Classe III.`)
}
