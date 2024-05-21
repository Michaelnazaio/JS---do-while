/*2) Os números primos possuem várias aplicações dentro da Computação, por exemplo, na criptografia. Um número primo é aquele que é divisível apenas por um e por ele mesmo. Faça um programa que peça ao usuário para digitar cinco números inteiros e mostre na tela se são primos ou não.*/

let numeroUm
let cont = 2
let cinco = 5

while(cinco > 0){
    numeroUm = Number(prompt('Digite um número: '))
    cinco--

    do{
        if(numeroUm%cont == 0){
            break
        }
        cont++    
    }
    while(cont < numeroUm){
        if(cont == numeroUm){
           alert('O número ' + numeroUm + ' é primo')
        }
        else{
            alert('O número ' + numeroUm + ' não é primo')
        }
    cont = 2
    }    
}
