//JOGO DO NUMERO SECRETO

alert('Boas vindas ao jogo do número secreto');
let numeroSecreto = 3;
console.log(numeroSecreto)
let chute 

while (chute != numeroSecreto){
    chute = prompt('Escolha um número entre 1 e 10');

    // se chute for igual ao número secreto
    if (chute == numeroSecreto) {
        alert(`Isso ai! Você descobriu o número secreto ${numeroSecreto}`);
    } else {
        //alert('Você errou :(')
        if (chute > numeroSecreto){
            alert(`O número secreto é menor que ${chute}`);
        } else{
            alert(`O número é maior que ${chute}`);
        }

    }

}
