## Desafio 005

- Faça um programa que leia as duas notas de um aluno em uma matéria e mostre na tela a sua média na disciplina.

	Ex:
	Nota 1: 4.5
	Nota 2: 8.5
	A média entre 4.5 e 8.5 é igual a 6.5

`
	let nota1 = Number(prompt('Nota 1:'));
	let nota2 = Number(prompt('Nota 2:'));
	alert(`A média entre ${nota1} e ${nota2} é igual a ${(nota1 + nota2) / 2}`)
`