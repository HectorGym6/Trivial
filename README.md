# Trivial

## Problema 0 

Extraemos el codigo duplicado a un unico metodo "nuevaPosicionJugador", al que llamamos de ambos sitios.

Creamos test unitarios "si_al_principio_saco_un_1_voy_a_casilla_1"  

## Problema 1

Para saber si esta todo ok creo el test "si_hay_menos_de_2_jugadores" y listo. 

Uso el Metodo esJugable para qu el programa funcione. 
De no ser posible aparecerá un mensaje indicando que el número de jugadores es incorrecto

## Problema 2

Vemos que hay un error, corregimos esa parte y limitamos el 
método esJugable para que solo devuelva true si los jugadores son de 2 a 6.
El método agregar lo modificamos para que dependa del método esJugable.

## Problema 2

Vemos que hay un error, corregimos esa parte y limitamos el 
método esJugable para que solo devuelva true si los jugadores son de 2 a 6.
El método agregar lo modificamos para que dependa del método esJugable.

## Problema 3

Añado la instrucción de salir de la cárcel en el método (tirarDado) en el supuesto de sacar un número impar y estar en la cárcel.
Creo el test  (sacar_numero_impar_y_salir_de_la_cárcel) donde el jugador 1 va a la cárcel y sale después de sacar un número impar avanzando hasta la casilla.

## Problema 2

Vemos que hay un error, corregimos esa parte y limitamos el 
método esJugable para que solo devuelva true si los jugadores son de 2 a 6.
El método agregar lo modificamos para que dependa del método esJugable.

## Problema 3

Añado la instrucción de salir de la cárcel en el método (tirarDado) en el supuesto de sacar un número impar y estar en la cárcel.
Creo el test  (sacar_numero_impar_y_salir_de_la_cárcel) donde el jugador 1 va a la cárcel y sale después de sacar un número impar avanzando hasta la casilla.

## Problema 4

El método JugadorHaGanado devuelve true, pero como se cumple cuando aún no ha habido jugador, cambiamos el nombre del método. 
El metodo ahora pasa a llamarse JugadorNoHaGanado y cambiamos el nombre de la variable noGanador a Ganador

