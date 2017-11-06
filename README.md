# El ahorcado de Tiquicia

Este programa realiza el famoso juego del ahorcado con argot costarricense. El programa recibe la dificultad que el usuario desea para la partida, y le dará una, dos o ninguna pista según la dificultad elegida. Estas pistas son: darle la frase de argot en inglés (Por ejemplo: "Manda huevo" sería "Send egg") o simplemente darle una letra para que tenga una mejor idea ("Manda huevo" sería -A--A -----). Al final de la partida, el programa le reportará al usuario cuántas palabras ha adivinado y con cuántas pistas.

Un ejemplo del programa podría ser el siguiente:

	$ java Hangman
	Dificultad: Elija entre fácil, normal o díficil: fácil
	Palabra de tres letras: _ _ _
	Desea una pista? (1 = Si 2 = No) 1
	Le queda 1 pista.
	M _ _
	Desea una pista? (1 = Si 2 = No) 2
	Agregue una letra: A
	Correcto: M A _ 
	Letras utilizadas: M, A.
	Desea una pista? (1 = Si 2 = No) 2
	Agregue una letra: K
	Incorrecto: 
	_
	Letras utilizadas: M, A, K.
	Desea una pista? (1 = Si 2 = No) 2
	Agregue una letra: E
	Correcto! Ha adivinado la palabra MAE, y se ha salvado.
	Desea jugar otra vez? (1 = Si 2 = No) 2
	Ha adivinado 1 palabra(s) y ha utilizado 1 pista(s). Gracias por jugar!









