# Desafios-DIO
Aqui estarão trabalhos feitos após o curso do DIO

#Primeiro desafio DIO, esté desafio foi pedido pelo Felipe Aguiar o Professor do Bootcamp.
- OBS: o meu código não estará aberto para execução pois não possuo todas as ferramentas necessárias para este funcionamento,entrertanto busco a mudança. -

O pedido foi uma criação de um classificador de nível de Herói.

CÓDIGO

let nomeHeroi = ["Garry"]
let xpHeroi = 3000

switch (true) {
    case (xpHeroi <= 1000):
        console.log("O Herói " + nomeHeroi + " está no nível Ferro")
        break

    case (xpHeroi >= 1001 && xpHeroi <= 2000):
        console.log("O Herói " + nomeHeroi + " está no nível Bronze")
        break

    case (xpHeroi>= 2001 && xpHeroi <= 5000):
        console.log("O Herói " + nomeHeroi + " está no nível Prata")
        break

    case (xpHeroi >= 6001 && xpHeroi <= 7000):
        console.log("O Herói " + nomeHeroi + " está no nível Ouro")
        break
    
    case (xpHeroi >= 8001 && xpHeroi <= 9000):
        console.log("O Herói " + nomeHeroi + " está no nível Ascendente")
        break
    
    case (xpHeroi >= 9001 && xpHeroi <= 10000):
        console.log("O Herói " + nomeHeroi + " está no nível Imortal")
        break
    
    case (xpHeroi >= 10001):
        console.log("O Herói " + nomeHeroi + " está no nível Radiante")
        break
}
