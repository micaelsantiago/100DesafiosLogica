## Desafio 006

- Faça um programa que leia um número inteiro e mostre o seu antecessor e seu sucessor.

	Ex:
	Digite um número: 9
	O antecessor de 9 é 8
	O sucessor de 9 é 10

`
	let numero = parseInt(prompt('Digite um número:'))
	alert(`O antecessor de ${numero} é ${numero - 1} \nO sucessor de ${numero} é ${numero + 1}`);
`