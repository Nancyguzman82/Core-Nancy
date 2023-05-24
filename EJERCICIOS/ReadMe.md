Algoritmo SalarioPorHoras
	Escribir " ingrese la cntidad de horas trabajadas "
	Leer cantidadDeHoras
	
	escribir"ingrese el valor del salario por cada hora trabajada(tarifa)"
	leer precioPorHora
	
	si cantidadDeHoras > 40 Entonces
		horasOrdinarias = 40 
		salarioOrdinario = horasOrdinarias * preciosPorHora
		
		horasExtras= cantidadDeHoras - horasOrdinarias
		precioPorHOraExtra=precioPorHora+precioPorHora *(50/100)
		salarioExtraordinario = horasExtras *precioPorHOraExtra
		salariototal = salarioOrdinario + salarioExtraordinario
		Imprimir "el salario es (horas extras) ", salariototal
	SiNo
		salario = cantidadDeHoras*precioPorHora
		Imprimir "El salario es ( sin horas extras)", salario
	FinSi
	FinAlgoritmo
