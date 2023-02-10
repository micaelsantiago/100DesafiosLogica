## Desafio 008

- Desenvolva um programa que leia uma distância em metros e mostre os valores relativos em outras medidas.

	Ex:
	Digite uma distância em metros: 185.72
	A distância de 85.7m corresponde a:
	0.18572Km      1857.2dm
	1.8572Hm       18572.0cm
	18.572Dam      185720.0mm

`
	let distancia = parseFloat(prompt('Digite uma distância em metros: '));
	alert(`
		A distância de ${distancia} corresponde a: \n
		${distancia / 1000}Km     ${distancia * 10}dm \n
		${distancia / 100}Hm      ${distancia * 100}cm \n
		${distancia / 10}Dam      ${distancia * 1000}mm
		`)
`