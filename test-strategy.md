#################### ERRORES #####################

1. Math.random me devuelve un valor aleatorio flotante y para este programa necesitamos un valor entero entre 1 y 100 para solucionar esto se uso el comando Math.floor que redondea un número hacia el número entero anterior.

2. Comando addEventListener escrito de forma incorrecta para la constante guessSubmit y la variable resetButton

3. Correccion en numero de intentos constante ATTEMPS de 5 a 10.

4. Correccion de tipo de dato de string a numero en la variable userGuess con el comando Number() debido que las comparaciones exigen un tipo de dato numerico.

5. Se modifico la condicion "guessCount === ATTEMPS" por "guessCount <= ATTEMPS" para poder observar que datos ingreso el usuario anteriormente y no solo cuando se ha acabado el numero de intentos.

6. Error en el orden de los textos en las condiciones de ganador y perdedor se procedio a ordenar cada enunciado segun la condicion.

7. Se elimino  el comando lowOrHi.textContent = ''; en la condicion de perdiste debido a que no representaba  ningun importancia en la condicion e interferia con el cierre del juego.

8. Se modifico la linea de comando "const lowOrHi = document.querySelector('.lowOrHi');" donde hacia falta el punto en "lowOrHi" para indicar que se estaba seleccionando una clase.

9. Se modifico el comando randomNumber = Math.floor(Math.random()+1); en la funcion reset por randomNumber = Math.floor(Math.random()*100); debido a que el numero aleatorio al jugar de nuevo siempre era 1.

10. Se encontro un error en el ingreso de datos, el usuario podia ingresar numeros negativos, simbolos y decimales y el programa lo aceptaba, para este error  se agrego una condicion "if" donde solo se permitia el 
acceso a numeros enteros el comando agregado es: "userGuess-Math.floor(userGuess)==0 && userGuess > 0" donde la diferencia me indica si es un numero decimal y el mayor igual si es un numero negativo.

11. Se agrego una alerta cuando la condidicion no se cumple para indicarle al usuario que el dato que ingreso no es valido.

12. Por ultimo se arreglaron los colores en cada una de las instrucciones segun lo especificado por el documento.