## Desafio 009

- Faça um algoritmo que leia quanto dinheiro uma pessoa tem na carteira (em R$) e mostre quantos dólares ela pode comprar. Considere US$1,00 = R$3,45.

`
	let carteira = Number(prompt('Dinheiro em carteira: (R$)'));
	alert(`Com R$${carteira} você pode comprar US$${(carteira * 3.45).toFixed(2)}`)
`