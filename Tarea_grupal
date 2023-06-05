Funcion ej1 ()
	//1)Leer un carácter y deducir si está o no comprendido entre las
	//letras 'a'... 'z' y 'A'...'Z' ambas inclusive y sino verificar si es un signo de puntuacion ", . ; :"
	//y si no presentar solo el caracter.
	//Enttrada : caract (leer)
	//Proceso : Para poder realizar este ejercicio tenemos que comparar el carácter ingresado es "a" mayor 
	//a y menor a "z" o si el carácter mayor "A" o menor a "Z" si se comple el mensaje a presentar es El carácter 
	//ingresado es una letra si esto no se cumple tenemos que preguntar si el
	//Carácter ingresado es igual a "," o a ":", ";" y por ultimo preguntamos por el "." si alguna de estas
	//comparaciones son correctas el mensaje a presentar e:s Es un carácter ingresado, es un signo de puntuación si no se cumple
	//solo presentamos el carácter
	//salida: El resultado de las comparaciones.
	Definir caract Como Caracter;
	Escribir "Por favor ingrese un carácter :";
	Leer caract;
	si (caract >= "a" y caract <= "z") o (caract >= "A" y caract <= "Z") Entonces
		Escribir caract ," : El carácter ingresado es una letra";
	SiNo
		si caract = "," o caract = "."o caract = ";"o caract = ":" Entonces
			Escribir caract ," : Es un carácter ingresado, es un signo de puntuación";
		SiNo
			Escribir "El carácter es :",caract;
		FinSi
	FinSi
FinFuncion

Funcion ej2()
	//2)Leer un carácter y deducir si este es un numero(0..9) o una vocal(a,e,i,o,u)
	//Entrada :carac(leer) (0..9)(a,e,i,o,u)
	//Proceso : usaremos segun para capturar lo que el usuario ingrese dependiendo lo que 
	//el usuario ingrese se va a enviar un mensaje o otro si el caracter ingreado no esta en
	//el rango de (0..9)(a,e,i,o,u) se dira que el caracter ingresado no es valido.
	//Salida :El carácter ingresado si está en el rango dicho anterior mente o 
	//el carácter ingresado no es válido
	Definir carac Como Caracter;
	Escribir "Por favor ingrese un carácter";
	Leer carac;
	Segun carac Hacer
		"0":
			Escribir "El carácter ingresado es 0";
		"1":
			Escribir "El carácter ingresado es 1";
		"2":
			Escribir "El carácter ingresado es 2";
	    "3":
			Escribir "El carácter ingresado es 3";
		"4":
			Escribir "El carácter ingresado es 4";
		"5":
			Escribir "El carácter ingresado es 5";
	    "6":
			Escribir "El carácter ingresado es 6";
		"7":
			Escribir "El carácter ingresado es 7";
		"8":
			Escribir "El carácter ingresado es 8";
		"9":
			Escribir "El carácter ingresado es 9";
		"a":
			Escribir "El carácter ingresado es a";
		"e":
			Escribir "El carácter ingresado es e";
		"i":
			Escribir "El carácter ingresado es i";
	    "o":
			Escribir "El carácter ingresado es o";
		"u":
			Escribir "El carácter ingresado es u";
		"A":
			Escribir "El carácter ingresado es A";
	    "E":
			Escribir "El carácter ingresado es E";
		"I":
			Escribir "El carácter ingresado es I";
		"O":
			Escribir "El carácter ingresado es O";
		"U":
			Escribir "El carácter ingresado es U";
		De Otro Modo:
			Escribir "El caracter ingresado no es valido";
			
	FinSegun
FinFuncion
Funcion ej3()
	//		3) Dado un caracter vocal presentar su respectivo valor ascii
	//Entrada :vocal(leer) a,e,i,o,u 
	//Proceso : Si el usuario ingresa una de estas vocales se le enviará un mensaje
	//donde se le indique que letra es y su valor en código ASCII usaremos un según
	// para capturar los caracteres ingresados por el usuario.
	//Salida : El carácter ingresado con su respectivo valor en el código ASCII caso 
	//contrario se le dirá que el carácter ingresado no es válido.
	
	Definir vocal Como Caracter;
	Escribir "Ingrese una vocal :";
	Leer vocal;
	segun vocal Hacer
		"a":
			Escribir "El carácter ingresado es a y su valor en código ASCII es 97";
		"e":
			Escribir "El carácter ingresado es e y su valor en código ASCII es 101";
		"i":
			Escribir "El carácter ingresado es i y su valor en código ASCII es 105";
		"o":
			Escribir "El carácter ingresado es o y su valor en código ASCII es 111";
		"u":
			Escribir "El carácter ingresado es u y su valor en código ASCII es 117";
		"A":
			Escribir "El carácter ingresado es A y su valor en código ASCII es 65";
		"E":
			Escribir "El carácter ingresado es E y su valor en código ASCII es 69";
		"I":
			Escribir "El carácter ingresado es I y su valor en código ASCII es 73";
		"O":
			Escribir "El carácter ingresado es O y su valor en código ASCII es 79";
		"U":
			Escribir "El carácter ingresado es U y su valor en código ASCII es 85";
		De Otro Modo:
			Escribir "Error el carácter ingresado no es válido";
	FinSegun
FinFuncion

Funcion ej4()
	//4) Leer dos nombres y verificar si estos son iguales, si el primer nombre es menor
	//que el segundo dado su contenido.
	//Entrada : nombre1 , nombre2 (leer)
	//Proceso : Lo primero que tenemos que realizar es hacer que el usuario pueda ingresar los dos 
	//nombres lo siguiente sería comprar los dos nombres y si son iguales escribiríamos un mensaje 
	//que diga que los nombres son iguales si no preguntaríamos si el primer nombre es mayor que él
	//segundo y si esto se cumple se enviara un mensaje al usuario.
	//Salida : El mensaje que dirá si el nombre es igual o el primero es mayor que el segundo.
	Definir nombre1, nombre2 como caracter;
	Escribir "Ingrese el primer nombre:";
	Leer nombre1;
	Escribir "Ingrese el segundo nombre:";
	Leer nombre2;
	Si nombre1 = nombre2 Entonces
		Escribir nombre1," = ",nombre2," Los nombres son iguales";
	Sino 
		Si nombre1 < nombre2 Entonces
			Escribir nombre1 ," < ",nombre2," El primer nombre es menor que el segundo";
		Sino
			Escribir nombre1 ," < ",nombre2," El primer nombre es mayor que el segundo";
		Fin Si
	FinSi
FinFuncion

Funcion ej5()
	//5) Ingresar dos numeros y determinar si son iguales o si el primer numero es menor
	//que el segundo dado su valor 
	//Entrada :num1,num2(leer)
	//Proceso : Primero definimos las variables y hacemos que el usuario ingrese dos números
	//Posteriormente preguntamos si num1 = num2 si esto se cumple se le dirá al usuario que los dos 
	//Números son iguales y si esto no se cumple preguntaremos si num1 < num2 si esto se cumple le enviaremos 
	//un mensaje al usuario que diga que el primer número es menor que el segundo, si esto no se cumple le diríamos que
	//ninguna opción planteada se cumple.
	//Salida :El mensaje de resultado de la comparación que se cumple
	Definir num1,num2 Como Real;
	Escribir "Ingrese un número :"
	Leer num1;
	Escribir "Ingrese un número :"
	leer num2;
	si num1 = num2 Entonces
		Escribir "Los números ingresados son iguales"
	SiNo
		si num1< num2 Entonces
			Escribir "El primer número es menor que el segundo";
		sino 
			escribir "Ninguna opción planteada se cumple";
		FinSi
	FinSi
FinFuncion

Funcion ej6()
	//6) Ingresar 3 números, determinar cuál es el mayor o si son iguales
	//Entrada :num1,num2,num3 (leer)
	//Proceso : Para realizar el ejercicio tenemos que comparar cada número
	//planteado de esta manera num1 > num2 y num1 > num3 esto es cuando el primer número
	//ingreado es mayor.num2 > num1 y num2 > num3 esto es cuando el segundo número es mayor y cuando 
	//el tercer número es mayor queda de esta manera num3 > num1 y num3 > num2 por último si ninguna de estas opciones
	//se cumple décimos que los tres numeros son iguales.
	//Salida :El numero mayor o si los numeros son iguales.
	
	Definir num1,num2,num3 Como Real;
	Escribir "Ingrese un número :"
	Leer num1;
	Escribir "Ingrese un número :"
	leer num2;
	Escribir "Ingrese un número : "
	Leer num3;
	Si num1 > num2 y num1 > num3 Entonces
        Escribir "El primer número es el mayor :",num1;
    Sino 
		Si num2 > num1 y num2 > num3 Entonces
			Escribir "El segundo número es el mayor :",num2;
		Sino 
			Si num3 > num1 y num3 > num2 Entonces
				Escribir "El tercer número es el mayor :",num3;
			Sino
				Escribir "Los tres números son iguales"
			Fin Si
		FinSi
	FinSi
FinFuncion

Funcion ej7()
	//7) Ingresar un numero y determinar si es neutro, positivo o negativo
	//Entrada: num (Leer)
	//Proceso:Definimos núm. como variable y hacemos que el usuario ingrese un número 
	// y hacemos una comparación si num = 0 entonces el número es neuto si num > 0 Entonces
	//es positivo sino es negativo.
	//Salida : La respuesta de las comparaciones.
	Definir num como entero
	
	Escribir "Ingrese un número:"
	Leer num
	
	Si num = 0 Entonces
		Escribir "El número es neutro"
	Sino 
		Si num > 0 Entonces
			Escribir "El número es positivo"
			Sino
				Escribir "El número es negativo"
			FinSi
		Fin Si
FinFuncion

Funcion eje8()
	//8) Determinar cuanto se debe pagar por x cantidad de lápices,
	//considerando que si son más de 1000 el costo es de 1 , caso contrario el precio será 1,50
	Escribir "Ingrese la cantidad de lápices a comprar: "
	Leer cantidadLapices
	
	Si cantidadLapices > 1000 Entonces
		precioPorLapiz <- 1
	Sino
		precioPorLapiz <- 1.50
	FinSi
	
	montoAPagar <- cantidadLapices * precioPorLapiz
	
	Escribir "El monto a pagar es: ", montoAPagar
FinFuncion

Funcion eje9()
	//9) Almacén "Somos Mas" tiene una promoción: a todos los trajes que tienen un precio superior a 2500, se les aplicará un descuento del 15%,
    //a todo los demás se les aplicará sólo el 8%.
	Definir precioTraje, descuento, precioFinal Como Real
	
	Escribir "Ingrese el precio del traje: "
	Leer precioTraje
	
	Si precioTraje > 2500 Entonces
		descuento <- 0.15
	Sino
		descuento <- 0.08
	FinSi
	
	precioFinal <- precioTraje - (precioTraje * descuento)
	
	Escribir "El precio final con descuento es: ", precioFinal
FinFuncion

Funcion eje10()
	//10) 
//Somos Mas" es una empresa dedicada a ofrecer banquetes; sus tarifas son as siguientes:El costo de platillo por persona es de $95.00, pero si el número de
//personas es mayor a 200 pero menor o igual a 300, el costo es de $85.00.
//Para más de 300 personas el costo por platillo es de $75.00. Se requiere un
	//algoritmo que ayude a determinar el presupuesto que se debe presentar a los
	//clientes que deseen realizar un evento.
	Definir numPersonas, costoPorPersona, presupuesto Como Entero
	
	Escribir "Ingrese el número de personas en el evento: "
	Leer numPersonas
	
	Si numPersonas > 300 Entonces
		costoPorPersona <- 75
	Sino 
		Si numPersonas > 200 Entonces
			costoPorPersona <- 85
		Sino
			costoPorPersona <- 95
		FinSi
		
		presupuesto <- numPersonas * costoPorPersona
		
		Escribir "El presupuesto para el evento es: $", presupuesto
	FinSi
	
FinFuncion

Funcion eje11()
//11)La asociación de vinicultores tiene como política fijar un precio inicial al kilo
//de uva, la cual se clasifica en tipos A y B, y además en tamaños 1 y 2.
//Cuando se realiza la venta del producto, ésta es de un solo tipo y tamaño, se
//requiere determinar cuánto recibirá un productor por la uva que entrega en un
//embarque, considerando lo siguiente:Si es de tipo A, se le cargan 20¢ al precio
//inicial cuando es de tamaño 1; y 30¢ si es de tamaño 2. Si es de tipo B, se rebajan
//30¢ cuando es de tamaño 1, y 50¢ cuando es de tamaño 2.
//Realice un algoritmo para determinar la ganancia obtenida
	Definir tamanoUva, precioInicial, ganancia Como Real
	Definir tipoUva Como Caracter
	Escribir "Ingrese el tipo de uva (A o B): "
	Leer tipoUva
	
	Escribir "Ingrese el tamaño de uva (1 o 2): "
	Leer tamanoUva
	
	Si tipoUva = "A" Entonces
		Si tamanoUva <- 1 Entonces
			precioInicial <- precioInicial + 0.20
		Sino Si tamanoUva = 2 Entonces
				precioInicial <- precioInicial + 0.30
			FinSi
		Si tipoUva = "B" Entonces
				Si tamanoUva = 1 Entonces
					precioInicial <- precioInicial - 0.30
				Sino Si tamanoUva = 2 Entonces
						precioInicial <- precioInicial - 0.50
					FinSi
				FinSi
				
				ganancia <- precioInicial
				
				Escribir "La ganancia obtenida es: $", ganancia
			FinSi
		FinSi
	FinSi
	
FinFuncion

funcion eje12()
	//12) 
//l director de carrera de software está organizando un viaje de estudios,
//y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar
//a la compañía de viajes por el servicio. La forma de cobrar es la siguiente:
//si son 100 alumnos o más, el costo por cada alumno es de $65.00;
//de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos
//de 30, el costo de la renta del autobús es de $4000.00, sin importar el número
//de alumnos.Realice un algoritmo que permita determinar el pago a la compañía
//de autobuses y lo que debe pagar cada alumno por el viaje
	Definir numAlumnos, costoPorAlumno, costoTotal, costoAutobus Como Entero
	
	Escribir "Ingrese el número de alumnos: "
	Leer numAlumnos
	
	Si numAlumnos >= 100 Entonces
		costoPorAlumno <- 65
	Sino Si numAlumnos >= 50 Entonces
			costoPorAlumno <- 70
		Sino Si numAlumnos >= 30 Entonces
				costoPorAlumno <- 95
			Sino
				costoPorAlumno <- 0
				costoAutobus <- 4000
			FinSi
			
			costoTotal <- numAlumnos * costoPorAlumno
			
			Escribir "El pago a la compañía de autobuses es: $", costoAutobus
			Escribir "El costo que debe pagar cada alumno es: $", costoPorAlumno
			Escribir "El costo total del viaje es: $", costoTotal
		FinSi
	FinSi
	
FinFuncion

Funcion eje13()
//eje13
// Una compañía de viajes cuenta con tres tipos de autobuses (A, B y C),
//cada uno tiene un precio por kilómetro recorrido por persona, los costos respectivos son $2.0,
//$2.5 y $3.0. Se requiere determinar el costo total y por persona del viaje considerando que
//cuando éste se presupuesta debe haber un mínimo de 20 personas, de lo contrario el cobro se
//realiza con base en este número límite.
	Definir tipoAutobus Como Caracter
	Definir costoPorKilometro, costoTotal, costoPorPersona Como Real
	Definir numPersonas Como Entero
	
	Escribir "Ingrese el tipo de autobús (A, B o C): "
	Leer tipoAutobus
	
	Escribir "Ingrese el número de personas: "
	Leer numPersonas
	
	Segun tipoAutobus Hacer
		Caso "A":
			costoPorKilometro <- 2.0
		Caso "B":
			costoPorKilometro <- 2.5
		Caso "C":
			costoPorKilometro <- 3.0
	FinSegun
	
	Si numPersonas >= 20 Entonces
		costoTotal <- numPersonas * costoPorKilometro
		costoPorPersona <- costoPorKilometro
	Sino
		costoTotal <- 20 * costoPorKilometro
		costoPorPersona <- costoTotal / 20
	FinSi
	
	Escribir "El costo total del viaje es: $", costoTotal
	Escribir "El costo por persona es: $", costoPorPersona
FinFuncion

Funcion eje14()
	//14) Determinar cuanto se debe pagar por cierta cantidad de colas,
	//considerando que si son más de 23 colas, el costo por unidad
	//es de $0,50 caso contrario el precio será 20% mas.
	//Al costo resultante calcular el 12% del iva. Se pide presentar:
	//cantidad comprada, el costo ´por unidad, el total sin iva
	//el iva y el total a pagar.
	Definir cantidadColas, costoPorUnidad, totalSinIVA, iva, totalAPagar Como Real
	
	Escribir "Ingrese la cantidad de colas: "
	Leer cantidadColas
	
	Si cantidadColas > 23 Entonces
		costoPorUnidad <- 0.50
	Sino
		costoPorUnidad <- costoPorUnidad * 1.20
	FinSi
	
	totalSinIVA <- cantidadColas * costoPorUnidad
	iva <- totalSinIVA * 0.12
	totalAPagar <- totalSinIVA + iva
	
	Escribir "Cantidad comprada: ", cantidadColas
	Escribir "Costo por unidad: $", costoPorUnidad
	Escribir "Total sin IVA: $", totalSinIVA
	Escribir "IVA: $", iva
	Escribir "Total a pagar: $", totalAPagar
	
FinFuncion

Funcion eje15()
// En un Supermercado se tiene la siguiente promocion.
//Si se compra mas de 19 productos a estos se le aplica
//un descuento del 10 por ciento al precio del producto y si se compra
//	menos de 20 productos se le aplica un descuento del 20 por ciento
//al precio del producto. Al costo obtenido se le aplica descuento
//adicional del 5 por ciento. Se pide presentar :
//cantidad comprada, el precio orginal, el descuento inicial
	//el total, el descuento adicional y el valor a pagar.
	//entrada: nproductos,descto10,costo,totalpagar,total,totalfinal,f ()
	//proceso:nproductos>=19 un descuento del 10 por ciento al precio del producto
	// nproductos<20 se le aplica un descuento del 20 por ciento
	//al precio del producto.
	//salida: presentar cantidad comprada, el precio orginal, el descuento inicial
	//el total, el descuento adicional y el valor a pagar.
	definir nproductos,descto10,costo,totalpagar,total,totalfinal,f como reales;
	escribir "digiten el numero de productos:";
	leer nproductos;
	escribir "digite el precio a pagar:";
	leer totalpagar;
	si nproductos>=19 Entonces
		descto10<- totalpagar*0.10;
		total<- totalpagar-descto10;
		escribir "el precio a pagar es de:",total,"con el descto10";
	FinSi
	si nproductos<20 Entonces
		descto10<-totalpagar*0.10;
		total<-totalpagar-descto10;
	FinSi
	f<-total*0.5;
	totalfinal<-f-total;
	escribir "cantidad comprada:",nproductos;
	escribir  " el precio original:",totalpagar;
	escribir "descto inicial:",total;
	escribir "el total:",totalfinal;
	Escribir "el descto adicional:",totalfinal;
	escribir "valor a pagar:",totalfinal;
FinFuncion


Funcion eje16()
	//El consultorio del Dr. Paez tiene como política cobrar la consulta con
	//base en el número de cita, de la siguiente forma:
	//Las tres primeras citas a $200.00 c/u.
	//Las siguientes dos citas a $150.00 c/u.
	//Las tres siguientes citas a $100.00 c/u.
	//Las restantes a $50.00 c/u, mientras dure el tratamiento.
	//Se requiere un algoritmo para determinar:
	//Cuánto pagará el paciente por la cita.
	//El monto de lo que ha pagado el paciente por el tratamiento.
	//Para la solución de este problema se requiere saber qué número de cita se efectuará, con el
	//cual se podrá determinar el costo que tendrá la consulta y cuánto se ha gastado en el
	//tratamiento.
	//entrada:Ingresa el valor de numero de cita:
	//proceso:numero_de_cita>=1 Y numero_de_cita<=3 Entonces
	//pago_por_la_cita <- 200; monto_que_ha_pagado <- numero_de_cita*200;
	// numero_de_cita>=4 Y numero_de_cita<=5 Entonces pago_por_la_cita <- 150; monto_que_ha_pagado <- 3*200+(numero_de_cita-3)*150;
	//numero_de_cita>=6 Y numero_de_cita<=9 Entonces pago_por_la_cita <- 100; monto_que_ha_pagado <- 3*200+2*150+(numero_de_cita-5)*100;
	//numero_de_cita>=10 Entonces pago_por_la_cita <- 50; monto_que_ha_pagado <- 3*200+2*150+3*100+(numero_de_cita-9)*50;
	//salida: número de cita se efectuará, con el
	//cual se podrá determinar el costo que tendrá la consulta y cuánto se ha gastado en el
	//tratamiento. 
	definir numero_de_cita,pago_por_la_cita,monto_que_ha_pagado como reales;
	Escribir"Ingresa el valor de numero de cita:";
	Leer numero_de_cita;
	pago_por_la_cita <- 0;
	monto_que_ha_pagado <- 0;
	Si numero_de_cita>=1 Y numero_de_cita<=3 Entonces
		pago_por_la_cita <- 200;
		monto_que_ha_pagado <- numero_de_cita*200;
	FinSi
	Si numero_de_cita>=4 Y numero_de_cita<=5 Entonces
		pago_por_la_cita <- 150;
		monto_que_ha_pagado <- 3*200+(numero_de_cita-3)*150;
	FinSi
	Si numero_de_cita>=6 Y numero_de_cita<=9 Entonces
		pago_por_la_cita <- 100;
		monto_que_ha_pagado <- 3*200+2*150+(numero_de_cita-5)*100;
	FinSi
	Si numero_de_cita>=10 Entonces
		pago_por_la_cita <- 50;
		monto_que_ha_pagado <- 3*200+2*150+3*100+(numero_de_cita-9)*50;
	FinSi
	Escribir "Valor de monto que ha pagado: ", monto_que_ha_pagado;
	Escribir "Valor de pago por la cita: ", pago_por_la_cita;
FinFuncion

Funcion eje17()
	//Fábricas "El Baraton" produce articulos con claves (1, 2, 3, 4, 5 y 6). Se requiere
	//un algoritmo para calcular los precios de venta, para esto hay que considerar lo
	//siguiente:
	//Costo de producción = materia prima + mano de obra + gastos de fabricación.
	//Precio de venta = costo de producción + 45 % de costo de producción.
	//El costo de la mano de obra se obtiene de la siguiente forma: para los productos con clave 3 o
	//4 se carga 75 % del costo de la materia prima; para los que tienen clave 1 y 5 se carga 80 %, y
	//para los que tienen clave 2 o 6, 85 %.
	//Para calcular el gasto de fabricación se considera que si el articulo que se va a
	//producir tiene claves 2 o 5, este gasto representa 30 % sobre el costo de la
	//materia prima; si las claves son 3 o 6, representa 35 %; si las claves son 1 o 4,
	//representa 28 %. La materia prima tiene el mismo costo para cualquier clave
	//entrada:clave, materia_prima, mano_obra, gastos_fabricacion, costo_produccion, precio_venta (leer todo esto)
	//proceso:Si (clave = 3) o (clave = 4) Entonces
	//mano_obra <- materia_prima * 0.75;Sino Si (clave = 1) o (clave = 5) Entonces mano_obra <- materia_prima * 0.80;Sino
	//si (clave = 2) o (clave = 6) Entonces mano_obra <- materia_prima * 0.85;
	//salida: calcular los precios de venta

	Definir clave, materia_prima, mano_obra, gastos_fabricacion, costo_produccion, precio_venta como reales;
    
    Escribir "Ingrese la clave del producto:";
    Leer clave;
    
    Escribir "Ingrese el costo de la materia prima:";
    Leer materia_prima;
    
    Si (clave = 3) o (clave = 4) Entonces
        mano_obra <- materia_prima * 0.75;
    Sino 
		Si (clave = 1) o (clave = 5) Entonces
			mano_obra <- materia_prima * 0.80;
		Sino
			si (clave = 2) o (clave = 6) Entonces
				mano_obra <- materia_prima * 0.85;
			FinSi
		FinSi
	FinSi
	
	
	Si (clave = 2) o (clave = 5) Entonces
		gastos_fabricacion <- materia_prima * 0.30;
	Sino 
		Si (clave = 3) o (clave = 6) Entonces
			gastos_fabricacion <- materia_prima * 0.35;
		Sino
			si (clave = 3) o (clave = 6) Entonces
				gastos_fabricacion <- materia_prima * 0.28;
			FinSi
		FinSi
	FinSi
	
	costo_produccion <- materia_prima + mano_obra + gastos_fabricacion;
	
	precio_venta <- costo_produccion + (costo_produccion * 0.45);
	
	Escribir "El precio de venta del producto es: ",precio_venta;
FinFuncion

Funcion eje18()
	//18) 
	//El banco XYZ ha decidido aumentar el límite de crédito de las tarjetas de crédito
	//de sus clientes, para esto considera que:
	//Si su cliente tiene tarjeta tipo 1, el aumento será del 25%.
	//Si tiene tipo 2 el aumento será del 35%
	//Si tiene tipo 3, el aumento será del 40%
	//Para cualquier otro tipo será del 50%
	//Realizar un diagrama de flujo que ayude al banco a determinar el nuevo límite
	//de crédito que tendrá una persona en su tarjeta
	//entrada: nombre_del_cliente,limite_actual,tipo_de_tarjeta
	//proceso:clasificacion_actual <- tipo_de_tarjeta;Si tipo_de_tarjeta = 1 Entonces aumento <- limite_actual*0.25;FinSi Si tipo_de_tarjeta = 2 Entonces
	//aumento <- limite_actual*0.35;FinSi Si tipo_de_tarjeta = 3 Entonces aumento <- limite_actual*0.4; FinSi Si tipo_de_tarjeta>=1 Y tipo_de_tarjeta>=2 Y tipo_de_tarjeta>=3 Entonces
	//aumento <- limite_actual*0.5;
	//salida:el nuevo límite de crédito que tendrá una persona en su tarjeta
	definir nombre_del_cliente Como Caracter;
	definir limite_actual,tipo_de_tarjeta,techo_actual,aumento,nuevo_limite,clasificacion_actual Como Real;
	Escribir "Ingresa el nombre del cliente:";
	Leer nombre_del_cliente;
	Escribir "Ingresa el valor de limite actual:";
	Leer limite_actual;
	Escribir "Ingresa el valor de tipo de tarjeta:";
	Leer tipo_de_tarjeta;
	aumento <- 0;
	techo_actual <- limite_actual;
	clasificacion_actual <- tipo_de_tarjeta;
	Si tipo_de_tarjeta = 1 Entonces
		aumento <- limite_actual*0.25;
	FinSi
	Si tipo_de_tarjeta = 2 Entonces
		aumento <- limite_actual*0.35;
	FinSi
	Si tipo_de_tarjeta = 3 Entonces
		aumento <- limite_actual*0.4;
	FinSi
	Si tipo_de_tarjeta>=1 Y tipo_de_tarjeta>=2 Y tipo_de_tarjeta>=3 Entonces
		aumento <- limite_actual*0.5;
	FinSi
	nuevo_limite <- limite_actual+aumento;
	Escribir "Nombre del cliente: ", nombre_del_cliente;
	Escribir "Valor de aumento: ", aumento;
	Escribir "Valor de clasificacion actual: ", clasificacion_actual;
	Escribir "Valor de nuevo limite: ", nuevo_limite;
	Escribir "Valor de techo actual: ", techo_actual;

FinFuncion


Funcion eje19()
	//Una compañía de paquetería internacional tiene servicio en algunos países de
	//América del Norte, América Central, América del Sur, Europa y Asia. El costo por
	//el servicio de paquetería se basa en el peso del paquete y la zona a la que va
	//dirigido. Ver tabla
	//Parte de sus políticas implica que los paquetes con un peso superior a 5kg
	//no son transportados , esto es por cuestión de logística y de seguridad.
	//1  América del Norte $11
	//2  América Central $10
	//3  América del Sur $12
	//4  Europa $24
	//5  Asia $27
	//entrada: Ingresa el peso del paquete en kilogramos
	//proceso: ver las opciones de la tabla
	//salida:escribir "El cobro por el envio del paquete es: ",costo;
	//escribir "El paquete tiene un peso de:",peso,"kilogramos"
	definir peso,costo Como Real;
	definir zona Como Entero;
	escribir "Ingresa el peso del paquete en kilogramos:";
	leer peso;
	si peso>5 Entonces
		escribir " El paquete no se puede transportar";
	SiNo
		escribir "Ingrese la zona donde va dirigido:";
		escribir "1: America del norte";
		escribir "2: America central";
		escribir "3:America del sur";
		escribir "4: Europa";
		Escribir "5: Asia";
		leer zona;
		si zona >=1 y zona <=5 Entonces
			si zona ==1 Entonces
				costo<-peso*1000*11;
				escribir "1: America del norte";
			sino 
				si zona ==2 Entonces
					costo<-peso*1000*10;
					escribir "2: America central";
				sino 
					si zona ==3 Entonces
						costo<-peso*1000*12;
						escribir "3:America del sur";
					SiNo
						si zona ==4 Entonces
							costo<-peso*1000*24;
							escribir "4: Europa";
						sino 
							costo<-peso*1000*27;
							Escribir "5: Asia";
						FinSi
					FinSi
				FinSi
			FinSi
			escribir "El cobro por el envio del paquete es: ",costo;
			escribir "El paquete tiene un peso de:",peso,"kilogramos";
		sino 
			escribir "El paquete no se puede enviar a esa zona";
		FinSi
	FinSi
FinFuncion

Funcion eje20()
	// Se desea realizar una estadistica de los pesos de los alumnos
	//de la UNEMI de acuerdo a la siguiente tabla
	//alumnos de menos 40 kg
	//alumnos entre 40 y 50 kg
	//alumnos mas de 50 y menos de 60 kg
	//alumnos mas de 60 kg.
	//La entrada de los pesos se terminará cuando se ingrese el valor
	//de peso cero. Al final deberá presentar cuantos alumnos hay por
	//rengo de pesos y el promedio de cada rango.
	definir alumnos,peso,i Como Entero;
	definir cantidad,peso40,peso40y50,peso50y60,peso60 como entero;
	peso40<-0;
	peso40y50<-0;
	peso50y60<-0;
	peso60<-0;
	escribir "ingrese la cantidad de alumnos:";
	leer cantidad;
	para i<-1 Hasta  cantidad con paso 1 Hacer
		escribir " ingrese el peso del i alumno:";
		leer peso;
		si peso<40 Entonces
			peso40<-peso40+1;
		FinSi
		si peso >=40 y peso<=50 Entonces
			peso40y50<- peso40y50+1;
		FinSi
		si peso >=50 y peso<=60 Entonces
			peso50y60<-peso50y60+1;
		FinSi
		si peso >=60 Entonces
			peso60<- peso60+1;
		FinSi
	FinPara
	escribir " Alumnos con pesos:",cantidad;
	escribir " menos de 40 kilos:",peso40;
	escribir " entre 40 y 50 kilos:",peso40y50;
	escribir "mas de 50 y menos de 60 kilos:",peso50y60;
	escribir " mas de 60 kilos:",peso60;

FinFuncion


Funcion eje21()
	//Escribir un algoritmo que lea cuatro números y determine si el numero 1
	//es la mitad del numero 2; Y si el numero 3 es divisor del 4.
	//entrada:ingresar las 74 notas (leer)
	//Proceso :  Si (numero1 = numero2 / 2) Y (numero3 % numero4 = 0)
	//salida:"Sí, número1 es la mitad de número2 y número3 es divisor de número4";
	//"No se cumple alguna de las condiciones";
	Definir numero1,numero2,numero3,numero4 como Enteros;
    Escribir "Ingrese el número 1:";
    Leer numero1;
    
    Escribir "Ingrese el número 2:";
    Leer numero2;
    
    Escribir "Ingrese el número 3:";
    Leer numero3;
    
    Escribir "Ingrese el número 4:";
    Leer numero4;
    
    Si (numero1 = numero2 / 2) Y (numero3 % numero4 = 0) Entonces
        Escribir "Sí, número1 es la mitad de número2 y número3 es divisor de número4";
    Sino
        Escribir "No se cumple alguna de las condiciones";
    FinSi
FinFuncion

Funcion eje22()
	//22
	//Escribir un algoritmo que lea tres números y determine si el numero1 doble del numero 2 y 20% menos que el numero 3.
	Definir n1,n2,n3 Como Real
	Escribir " Ingrese tres numeros "
	Leer n1,n2,n3
	Si n1 = (n2 * 2) y n1=trunc(n3-n3*0.20)  Entonces
		Escribir "El número 1 es el doble del número 2 y 20% menos que el número 3"
    Sino
        Escribir "El número 1 no es el doble del número 2 y 20% menos que el número 3"
    Fin Si
FinFuncion

Funcion eje23()
	//23
	//Realizar un programa que ingrese un número presentar un mensaje equivalente a los días
	//de la semana.
	Definir nums Como Real
	Escribir " Ingrese un numero del 1 al 7 "
	Leer nums
	Segun nums Hacer
		1:
			Escribir " dia lunes "
		2:
			escribir " dia martes "
		3:
			Escribir "dia miercoles "
		4:
			Escribir " dia jueves "
		5:
			Escribir " dia viernes"
		6:
			Escribir " dia sabado"
		7:
			Escribir " dia domingo"
		De Otro:
			Escribir " el numero ingresado es un error"
	Fin Segun
FinFuncion
Funcion eje24()
	//Realizar un programa que ingrese un número presentar un mensaje equivalente a los
	//nombres de los meses del año
	Definir nums Como Real
	Escribir " Ingrese un numero del 1 al 12 "
	Leer nums
	Segun nums Hacer
		1:
			Escribir " El numero ingresado equivale al mes de ENERO "
		2:
			escribir " El numero ingresado equivale al mes de FEBRERO "
		3:
			Escribir " El numero ingresado equivale al mes de MARZO "
		4:
			Escribir " El numero ingresado equivale al mes de ABRIL "
		5:
			Escribir " El numero ingresado equivale al mes de MAYO "
		6:
			Escribir " El numero ingresado equivale al mes de JUNIO "
		7:
			Escribir " El numero ingresado equivale al mes de JULIO "
		8:
			Escribir " El numero ingresado equivale al mes de AGOSTO "
		9:
			Escribir " El numero ingresado equivale al mes de SEPTIEMBRE "
		10:
			Escribir " El numero ingresado equivale al mes de OCTUBRE "
		11:
			Escribir " El numero ingresado equivale al mes de NOVIEMBRE "
		12:
			Escribir " El numero ingresado equivale al mes de DICIEMBRE "
		De Otro modo
			Escribir " el numero ingresado es un error"
	Fin Segun
FinFuncion
Funcion eje25()
	//25
	//Se requiere un algoritmo para obtener la estatura promedio de un grupo de personas, cuyo
	//número de personas se desconoce, el ciclo debe efectuarse siempre y cuando se tenga una
	//estatura registrada.
	Definir sumaEstaturas, contadorPersonas como Entero
    Definir estatura, promedio como Real
    
    sumaEstaturas <- 0
    contadorPersonas <- 0
    
    Escribir "Ingrese la estatura de cada persona (ingrese 0 para finalizar):"
    
    Leer estatura
    
    Mientras estatura <> 0 Hacer
        sumaEstaturas <- sumaEstaturas + estatura
        contadorPersonas <- contadorPersonas + 1
        Leer estatura
    Fin Mientras
    
    Si contadorPersonas > 0 Entonces
        promedio <- sumaEstaturas / contadorPersonas
        Escribir "La estatura promedio es:", promedio
    Sino
        Escribir "No se ingresaron estaturas"
    Fin Si
	
FinFuncion

Funcion eje26()
	//26
	//Realizar un algoritmo para generar e imprimir los números pares comprendidos entre 0 y 100
	Definir num como Entero
    Para num <- 0 Hasta 100 Hacer
        Si num % 2 = 0 Entonces
            Escribir num
        Fin Si
    Fin Para
FinFuncion

Funcion eje27()
	//27
	//Realizar un programa que realice la suma sucesiva de 10 números que ingrese por teclado,
	//presente el resultado de la suma acumulada
	Definir numero, suma como Entero
    
    suma <- 0
    
    Para i <- 1 Hasta 10 Hacer
        Escribir "Ingrese el número ", i, ":"
        Leer numero
        suma <- suma + numero
    Fin Para
    
    Escribir "El resultado de la suma acumulada es:", suma
FinFuncion

Funcion eje28()
	//28
	//Se requiere un algoritmo para obtener la edad promedio de un grupo de N alumnos
	Definir N, edad, suEdades, contAlumnos como Entero
    Definir promEdad como Real
    
    sumaEdades <- 0
    contadorAlumnos <- 0
    
    Escribir "Ingrese el número de alumnos:"
    Leer N
    
    Para i <- 1 Hasta N Hacer
        Escribir "Ingrese la edad del alumno ", i, ":"
        Leer edad
        suEdades <- suEdades + edad
        contAlumnos <- contAlumnos + 1
    Fin Para
    
    Si contAlumnos > 0 Entonces
        promEdad <- suEdades / contAlumnos
        Escribir "La edad promedio del grupo es:", promEdad
    Sino
        Escribir "No se ingresaron edades"
    Fin Si
FinFuncion

Funcion eje29()
	//29) Una empresa tiene el registro de las horas y el valor hora que trabaja diariamente un
	//empleado durante los 20 días del mes. Requiere determinar el total de éstas, así como el sueldo
	//que recibirá por las horas trabajadas. Realizar el algoritmo que resuelva este problema
	//Inicio : numHoras(Leer), sueldo(Leer)
	//Proceso :  Lo primero que tenemos que hacer es un bucle para que cuente de 1 hasta 20 esto nos
	//servirá para ir sumando las horas totales que nos pide el ejercicio después preguntaremos al usuario
	// que nos diga el valor por hora de trabajo para poder sacar el sueldo total que lo sacamos multiplicando él 
	//total de horas con el sueldo por hora.
	//Salida : El total de horas trabajadas y el sueldo a pagar.
	
	Definir numHoras,tot Como Entero;
	Definir sueldo,totsueldo Como Real;
	Para i <-1 Hasta 20 Hacer
		Escribir "Ingrese el numero de horas trabajadas el dia ",i;
		Leer numHoras;
		tot <- tot + numHoras;
	FinPara
	Escribir "Ingrese el valor por hora trabajas";
	Leer sueldo;
	totsueldo<- tot * sueldo;
	Escribir "El numero de horas trabajadas es :",tot;
	Escribir "El el sueldo a pagar es :",totsueldo;
	
FinFuncion
Funcion eje30()
	//30) Un empleado de la tienda "Somos Más" realiza N ventas durante el día, se requiere saber
	//cuántas de ellas fueron mayores a $1000, cuántas de ellas fueron mayores a $500 pero menores
	//o iguales a $1000, y cuantas fueron menores o iguales a $500. Además, se requiere saber el
	//monto de lo vendido en cada categoría y de forma global. Realizar un algoritmo.
	//Inicio : n(leer) venta (leer)
	//Proceso  :Inicializamos el contador en 1 y contadorMayor1000,contadorMayor500,contadorMenorIgual500,
	//montoMayor1000,montoMayor500,montoMenorIgual500,montoTotal para que no tengamos ningún inconveniente 
	//en la ejecución después le decimos al usuario que ingrese la cantidad de ventas realizadas por día 
	//y creamos un ciclo mientras hasta que contador sea menor o igual que el número de ventas realizadas durante el día.
	//Creamos una variable contadora para contar el monto total por día, ya que el ejercicio nos pide ese monto
	//Después de esto comparamos con un condicional si entonces si venta es mayor a 1000 si esto se cumple se sumará 1 
	//al contador de ventas mayores a 1000 si esto no se cumple se preguntará si la venta es mayor a 500
	// si esto se cumple se sumará 1 al contador de ventas mayores a 500, si no se cumple esto la venta se sumará al contador
	//de ventas menores o iguales a 1500 y al final se contará una venta, esto se hará hasta que contador sea menor o igual a 
	//el número de ventas ingresadas por el usuario.
	//salida :Cantidad de ventas mayores a $1000,Monto vendido en ventas mayores a $1000,
	//Cantidad de ventas mayores a $500 pero menores o iguales a $1000,
	//Cantidad de ventas menores o iguales a $500,Monto vendido en ventas menores o iguales a $500,Monto total vendido.
	Definir N, venta, contador, contadorMayor1000, contadorMayor500, contadorMenorIgual500 Como Entero;
	Definir montoMayor1000, montoMayor500, montoMenorIgual500, montoTotal Como Real;
	
	contador <- 1;
	contadorMayor1000 <- 0;
	contadorMayor500 <- 0;
	contadorMenorIgual500 <- 0;
	montoMayor1000 <- 0;
	montoMayor500 <- 0;
	montoMenorIgual500 <- 0;
	montoTotal <- 0;
	
	Escribir "Ingrese la cantidad de ventas realizadas durante el día: ";
	Leer N;
	
	Mientras contador <= N Hacer
		Escribir "Ingrese el monto de la venta ", contador, ": ";
		Leer venta;
		
		montoTotal <- montoTotal + venta;
		
		Si venta > 1000 Entonces
			contadorMayor1000 <- contadorMayor1000 + 1;
			montoMayor1000 <- montoMayor1000 + venta;
		Sino 
			Si venta > 500 Entonces
				contadorMayor500 <- contadorMayor500 + 1;
				montoMayor500 <- montoMayor500 + venta;
			Sino
				contadorMenorIgual500 <- contadorMenorIgual500 + 1;
				montoMenorIgual500 <- montoMenorIgual500 + venta;
			FinSi
			
			contador <- contador + 1;
		FinSi
		
		
	FinMientras
	
	
	Escribir "Cantidad de ventas mayores a $1000: ", contadorMayor1000;
	Escribir "Monto vendido en ventas mayores a $1000: $", montoMayor1000;
	Escribir "Cantidad de ventas mayores a $500 pero menores o iguales a $1000: ", contadorMayor500;
	Escribir "Monto vendido en ventas mayores a $500 pero menores o iguales a $1000: $", montoMayor500;
	Escribir "Cantidad de ventas menores o iguales a $500: ", contadorMenorIgual500;
	Escribir "Monto vendido en ventas menores o iguales a $500: $", montoMenorIgual500;
	Escribir "Monto total vendido: $", montoTotal;
FinFuncion

Funcion eje31()
	//31) Se dispone de las calificaciones de n alumnos del primer semestre
	//	de la carrera de software de la unemi. Se tiene la nota final y la asignatura
	//	('logica','requerimientos','calculos'). Se pide el promedio de
	//	cada asignatura y el promedio general de todas las asignaturas de los
	//	alumnos del primer semestre.
	// Inicio :n(leer) notaFinal(leer)
	//Proceso : El usuario ingresa la cantidad de alumnos para posterior mente hacer un bucle para qué va a ir 
	// de 1 hasta el número de alumnos ingresados por el usuario, esto lo hacemos para poder contar 
	// la cantidad de notas ingresadas por el usuario en cada materia, lo que se hace dentro de
	// del bucle para es preguntarle al usuario la nota de cada asignatura y sumarla después de que el usuario 
	// la ingresé después con la suma de todas las notas de cada asignatura la dividimos para el número de alumnos ingresados
	//anteriormente por el usuario. Para poder sacar el promedio general lo que debemos hacer es sumar el total de la suma de
	//las calificaciones y posteriormente multiplicar la cantidad de alumnos ingresados para 3 y dividir para el resultado 
	//de la multiplicación de esta forma:(sumaLogica + sumaRequerimientos + sumaCalculos) / (n * 3).
	//Salida :Promedio de la asignatura de Lógica,Promedio de la asignatura de Requerimientos,
	//Promedio de la asignatura de Cálculos,Promedio general de todas las asignaturas.
	Definir n, notaFinal, sumaLogica, sumaRequerimientos, sumaCalculos Como Entero;
	Definir promedioLogica, promedioRequerimientos, promedioCalculos, promedioGeneral Como Real;
	
	sumaLogica <- 0;
	sumaRequerimientos <- 0;
	sumaCalculos <- 0;
	
	Escribir "Ingrese la cantidad de alumnos: ";
	Leer n;
	
	Para i <- 1 Hasta n Con Paso 1 Hacer
		Escribir "Ingrese la nota final del alumno ", i , " en la asignatura de Lógica: ";
		Leer notaFinal;
		sumaLogica <- sumaLogica + notaFinal;
		
		Escribir "Ingrese la nota final del alumno ", i , " en la asignatura de Requerimientos: ";
		Leer notaFinal;
		sumaRequerimientos <- sumaRequerimientos + notaFinal;
		
		Escribir "Ingrese la nota final del alumno ", i , " en la asignatura de Cálculos: ";
		Leer notaFinal;
		sumaCalculos <- sumaCalculos + notaFinal;
	FinPara
	
	promedioLogica <- sumaLogica / n;
	promedioRequerimientos <- sumaRequerimientos / n;
	promedioCalculos <- sumaCalculos / n;
	promedioGeneral <- (sumaLogica + sumaRequerimientos + sumaCalculos) / (n * 3);
	
	Escribir "Promedio de la asignatura de Lógica: ", promedioLogica;
	Escribir "Promedio de la asignatura de Requerimientos: ", promedioRequerimientos;
	Escribir "Promedio de la asignatura de Cálculos: ", promedioCalculos;
	Escribir "Promedio general de todas las asignaturas: ", promedioGeneral;
FinFuncion
Funcion eje32()
	//32) Se dispone de los sueldos y categorias de los profesores de la unemi.
	//segun la categoria estos reciben un bono adicional de porcentaje al sueldo:
	//			categoria="Auxiliar" incremento del 10%
	//			categoria="Agregado" incremento del 20%
	//			categoria="principal" incremento del 50%
	//			Se pide obtener el promedio de los sueldos y del bono de cada categoria
	//			El programa termina cuando se ingresa una categoria inexistente
	//Inicio : categoria, sueldo (leer)
	//Proceso : Inicializamos las variables que van a hacer algún tipo de cálculo en 0 
	//creamos un bucle mientras hasta que categoría <> "Salir" para que cuando el usuario ingrese 
	//salir el programa se termine y podamos saber los resultados de lo que ingreso el usuario
	//en el bucle mientras le vamos a decir al usuario que ingrese la categoría ya sea (Auxiliar, Agregado, Principal)
	//y si el usuario ingresa Auxiliar, entonces le decimos al usuario que ingrese el sueldo del profesor
	//y hacemos lo siguiente :sumaSueldos <- sumaSueldos + sueldo;
	//sumaBonoAuxiliar <- sumaBonoAuxiliar + (sueldo * 0.10);
	//contadorAuxiliar <- contadorAuxiliar + 1;
	//Si el usuario ingresa Agregado entonces nuevamente le preguntamos el sueldo del profesor y 
	//hacemos lo siguiente  :sumaSueldos <- sumaSueldos + sueldo;
	//sumaBonoAgregado <- sumaBonoAgregado + (sueldo * 0.20);
	//contadorAgregado <- contadorAgregado + 1;
	//Y por último si el usuario ingresa Principal lo preguntamos el sueldo y 
	// hacemos esto:sumaSueldos <- sumaSueldos + sueldo;
	//sumaBonoPrincipal <- sumaBonoPrincipal + (sueldo * 0.50);
	//contadorPrincipal <- contadorPrincipal + 1;
	//por ultimo preguntamos lo siguiente  : 
	//Si contadorPrincipal > 0 Entonces
	//		promedioSueldosPrincipal <- sumaSueldos / contadorPrincipal;
	//		promedioBonoPrincipal <- sumaBonoPrincipal / contadorPrincipal;
	//		Escribir "Promedio de sueldos de la categoría Principal: ", promedioSueldosPrincipal;
	//		Escribir "Promedio del bono de la categoría Principal: ", promedioBonoPrincipal;
	//	FinSi
	//	Si contadorAgregado > 0 Entonces
	//		promedioSueldosAgregado <- sumaSueldos / contadorAgregado;
	//		promedioBonoAgregado <- sumaBonoAgregado / contadorAgregado;
	//		Escribir "Promedio de sueldos de la categoría Agregado: ", promedioSueldosAgregado;
	//		Escribir "Promedio del bono de la categoría Agregado: ", promedioBonoAgregado;
	//	FinSi
	//	Si contadorPrincipal > 0 Entonces
	//		promedioSueldosPrincipal <- sumaSueldos / contadorPrincipal;
	//		promedioBonoPrincipal <- sumaBonoPrincipal / contadorPrincipal;
	//		Escribir "Promedio de sueldos de la categoría Principal: ", promedioSueldosPrincipal;
	//		Escribir "Promedio del bono de la categoría Principal: ", promedioBonoPrincipal;
	//	FinSi
	// Esto se hace por si no se ha agregado ningún sueldo a alguna de las categorías para que no se presente.
	
	Definir sueldo, bono, contadorAuxiliar, contadorAgregado, contadorPrincipal Como Entero;
	Definir sumaSueldos, sumaBonoAuxiliar, sumaBonoAgregado, sumaBonoPrincipal Como Real;
	Definir categoria Como Cadena;
	
	contadorAuxiliar <- 0;
	contadorAgregado <- 0;
	contadorPrincipal <- 0;
	sumaSueldos <- 0;
	sumaBonoAuxiliar <- 0;
	sumaBonoAgregado <- 0;
	sumaBonoPrincipal <- 0;
	
	Mientras categoria <> "Salir" Hacer
		Escribir "Ingrese la categoría del profesor (Auxiliar, Agregado, Principal) o Salir para terminar: ";
		Leer categoria;
		
		Si categoria = "Auxiliar" Entonces
			Escribir "Ingrese el sueldo del profesor: ";
			Leer sueldo;
			sumaSueldos <- sumaSueldos + sueldo;
			sumaBonoAuxiliar <- sumaBonoAuxiliar + (sueldo * 0.10);
			contadorAuxiliar <- contadorAuxiliar + 1;
		FinSi
		
		Si categoria = "Agregado" Entonces
			Escribir "Ingrese el sueldo del profesor: ";
			Leer sueldo;
			
			sumaSueldos <- sumaSueldos + sueldo;
			sumaBonoAgregado <- sumaBonoAgregado + (sueldo * 0.20);
			contadorAgregado <- contadorAgregado + 1;
		FinSi
		
		Si categoria = "Principal" Entonces
			Escribir "Ingrese el sueldo del profesor: ";
			Leer sueldo;
			
			sumaSueldos <- sumaSueldos + sueldo;
			sumaBonoPrincipal <- sumaBonoPrincipal + (sueldo * 0.50);
			contadorPrincipal <- contadorPrincipal + 1;
		FinSi
	FinMientras
	
	
	Si contadorAuxiliar > 0 Entonces
		promedioSueldosAuxiliar <- sumaSueldos / contadorAuxiliar;
		promedioBonoAuxiliar <- sumaBonoAuxiliar / contadorAuxiliar;
		Escribir "Promedio de sueldos de la categoría Auxiliar: ", promedioSueldosAuxiliar;
		Escribir "Promedio del bono de la categoría Auxiliar: ", promedioBonoAuxiliar;
	FinSi
	
	Si contadorAgregado > 0 Entonces
		promedioSueldosAgregado <- sumaSueldos / contadorAgregado;
		promedioBonoAgregado <- sumaBonoAgregado / contadorAgregado;
		Escribir "Promedio de sueldos de la categoría Agregado: ", promedioSueldosAgregado;
		Escribir "Promedio del bono de la categoría Agregado: ", promedioBonoAgregado;
	FinSi
	
	Si contadorPrincipal > 0 Entonces
		promedioSueldosPrincipal <- sumaSueldos / contadorPrincipal;
		promedioBonoPrincipal <- sumaBonoPrincipal / contadorPrincipal;
		Escribir "Promedio de sueldos de la categoría Principal: ", promedioSueldosPrincipal;
		Escribir "Promedio del bono de la categoría Principal: ", promedioBonoPrincipal;
	FinSi
FinFuncion
Funcion eje33()
	//	33) Dado una serie de n cantidad de viajes dado cada pasaje y su recorrido determinar
	//	el precio de cada pasaje segun el recorrido en kilometros
	//	si el recorrido es hasta 100 km el pasaje no tiene incremento
	// si el reccorido es mas de 100 km el pasaje tiene un incremento
	// del 20%. Presentar el promedio y la cantidad de pasajes con recorrido
	// hasta 100km y mayor de 100 km.
	//Inicio : n(leer) recorrido(leer)
	//Proceso : inicializamos las variables contadoras en 0 y le preguntamos al usuario la cantidad de pasajes 
	//con un bucle para que comience desde el 1 hasta el número de pasajes ingresados por el usuario 
	// y dentro de ese bucle le vamos a preguntar al usuario por cada iteración del bucle el recorrido 
	//en kilómetros del pasaje y hacemos un condicional que diga si el recorrido es menor o igual a 100 que
	//haga lo siguiente:precio <- recorrido
	//	contadorHasta100km <- contadorHasta100km + 1
	//	sumaPreciosHasta100km <- sumaPreciosHasta100km + precio
	//	si esto no se cumple prosederiamos con lo siguiente :
	//	precio <- recorrido + (recorrido * 0.20)
	//	contadorMayor100km <- contadorMayor100km + 1
	//	sumaPreciosMayor100km <- sumaPreciosMayor100km + precio
	//Después hacemos las siguientes condicionales estos 
	//condicionales se hacen para que si el usuario no ingresa ninguna cantidad no se presente esto:
	//Si contadorHasta100km > 0 Entonces
	//	promedioHasta100km <- sumaPreciosHasta100km / contadorHasta100km
	//	Escribir "Promedio de precios de los pasajes hasta 100 km: ", promedioHasta100km
	//	Escribir "Cantidad de pasajes hasta 100 km: ", contadorHasta100km
	//Fin Si
	//Si contadorMayor100km > 0 Entonces
	//	promedioMayor100km <- sumaPreciosMayor100km / contadorMayor100km
	//	Escribir "Promedio de precios de los pasajes mayores a 100 km: ", promedioMayor100km
	//	Escribir "Cantidad de pasajes mayores a 100 km: ", contadorMayor100km
	//Salida : El promedio de pasajes y la cantidad de pasajes.
	Definir n, recorrido, precio, contadorHasta100km, contadorMayor100km Como Entero
	Definir sumaPreciosHasta100km, sumaPreciosMayor100km Como Real
	Definir promedioHasta100km, promedioMayor100km Como Real
	
	contadorHasta100km <- 0
	contadorMayor100km <- 0
	sumaPreciosHasta100km <- 0
	sumaPreciosMayor100km <- 0
	
	Escribir "Ingrese la cantidad de pasajes: "
	Leer n
	
	Para i <- 1 Hasta n Con Paso 1 Hacer
		Escribir "Ingrese el recorrido en kilómetros del pasaje ", i, ": "
		Leer recorrido
		
		Si recorrido <= 100 Entonces
			precio <- recorrido
			contadorHasta100km <- contadorHasta100km + 1
			sumaPreciosHasta100km <- sumaPreciosHasta100km + precio
		Sino
			precio <- recorrido + (recorrido * 0.20)
			contadorMayor100km <- contadorMayor100km + 1
			sumaPreciosMayor100km <- sumaPreciosMayor100km + precio
		Fin Si
	Fin Para
	
	Si contadorHasta100km > 0 Entonces
		promedioHasta100km <- sumaPreciosHasta100km / contadorHasta100km
		Escribir "Promedio de precios de los pasajes hasta 100 km: ", promedioHasta100km
		Escribir "Cantidad de pasajes hasta 100 km: ", contadorHasta100km
	Fin Si
	
	Si contadorMayor100km > 0 Entonces
		promedioMayor100km <- sumaPreciosMayor100km / contadorMayor100km
		Escribir "Promedio de precios de los pasajes mayores a 100 km: ", promedioMayor100km
		Escribir "Cantidad de pasajes mayores a 100 km: ", contadorMayor100km
	Fin Si
FinFuncion
Funcion eje34()
	//	34) Diseñar un algoritmo que lea y presente una serie de números distintos de
	//	cero. El algoritmo debe terminar con un valor cero que no se debe presentar.
	//	Finalmente se desea obtener la cantidad y el promedio de los valores distintos de cero
	//Inicio :num(leer)
	//Proceso : Le decimos al usuario que ingrese una serie de números distintos de cero y creamos un bucle Mientras 
	// y la condición sería si num es diferente de 0 hacer que el contador de números sume 1 y hacemos que lo que ingrese el usuario sé 
	//sume en la variable suma después con un condicional preguntamos si contador > 0 si esto se cumple hacemos lo siguiente:suma / contador
	//para tener el promedio de los valores distintos de cero y presentamos la cantidad de valores distintos de cero si esto no se cumple se dirá 
	//que no se ingresaron valores distintos a 0.
	//Salida : Cantidad de valores distintos de cero,Promedio de los valores distintos de cero.
	Definir num, contador, suma Como Entero
	Definir promedio Como Real
	contador <- 0
	suma <- 0
	Escribir "Ingrese una serie de números distintos de cero (ingrese 0 para terminar): "
	Leer num
	Mientras num <> 0 Hacer
		contador <- contador + 1
		suma <- suma + num
		Leer num
	Fin Mientras
	Si contador > 0 Entonces
		promedio <- suma / contador
		Escribir "Cantidad de valores distintos de cero: ", contador
		Escribir "Promedio de los valores distintos de cero: ", promedio
	Sino
		Escribir "No se ingresaron valores distintos de cero."
	Fin Si
FinFuncion

Funcion eje35()
	//	35) Dada una serie de números positivos lea y presente el numero.
	//	El algoritmo debe terminar con un valor negativo que no se debe presentar.
	//	Finalmente se desea obtener la cantidad y el total de los números positivos
	//	múltiplos de 3.
	//Inicio : num (leer)
	//Proceso :Le pedimos al usuario que ingrese un número positivo y creamos un bucle mientras y que la condición sea si 
	//num >= 0 si eso se cumple hacemos un condicional que diga que sí num mod 3 = 0 Entonces
	//contador <- contador + 1;
	//total <- total + num;
    // Fuera de la condicional hacemos que el número ingresado se presente con el mensaje y 
	//se lea num para cuando el usuario ingrese un número negativo se termine el programa 
	//Salida :Cantidad de números positivos múltiplos de 3,Total de los números positivos múltiplos de 3.
	Definir num , contador, total Como Entero
	contador <- 0;
	total <- 0;
	Escribir "Ingrese una serie de números positivos (ingrese un número negativo para terminar): "
	Leer num;
	Mientras num >= 0 Hacer
		Si num mod 3 = 0 Entonces
			contador <- contador + 1;
			total <- total + num;
		Fin Si
		Escribir "Número ingresado: ", num;
		Leer num;
	Fin Mientras
	
	Escribir "Cantidad de números positivos múltiplos de 3: ", contador;
		Escribir "Total de los números positivos múltiplos de 3: ", total;
FinFuncion
	
Algoritmo ejercicios
	//ej1();
	//ej2();
	//ej3();
	//ej4();
	//ej5();
	//ej6();
	//ej7();
	//eje8()
	//eje9()
	//eje10()
	//eje11()
	//eje12()
	//eje13()
	//eje14()
	//eje15()
	//eje16()
	//eje17()
	//eje18()
	//eje19()
	//eje20()
	//eje21()
	//eje22()	
	//eje23()
	//eje24()
    //eje25()
	//eje26()
	//eje27()
	//eje28()
	//eje29()
	//eje30()
	//eje31()
	//eje32()
	//eje33()
	//eje34()
	//eje35()
FinAlgoritmo

