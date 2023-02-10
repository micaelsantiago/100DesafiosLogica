## Desafio 010

- Faça um algoritmo que leia a largura e altura de uma parede, calcule e mostre a área a ser pintada e a quantidade de tinta necessária para o serviço, sabendo que cada litro de tinta pinta uma área de 2metros quadrados.

`
	let largura = Number(prompt('Largura:'));
	let altura = Number(prompt('Altura:'));
	let area = largura * altura;
	let qntTinta = area / 2
	alert(`Área a ser pintada: ${area} metros \nQuantidade de tinta que será usada: ${qntTinta.toFixed(1)} litros`)
`