[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/X95J9nr6)
# Examen Packet Tracer. Switches.

Realiza la configuración de los escenarios que se adjunta en Packet Tracer. Añade al final de los ficheros entregados tu nombre y apellidos. `Examen practicoUD3 SWITCHESNombre Apellido1Apellido2`
Todos los dispositivos pertenecen a la red **10.0.N.0/24** siendo N tu número de orden dentro de la clase. El examen tiene dos versiones. Realiza la versión que te corresponde según tu número sea par o impar

## Nota con número de clase

Recuerda que en una nota del escenario, ARRIBA A LA IZQUIERDA, debe aparecer SIEMPRE tu **nombre y número de clase**.

1. Ruiz Ballesteros, Hendrie
2. Crespo Crespo, Rafael
3. Llamas Rodríguez, Yolanda María
4. Marinero Jabalera, Antonio
5. Ayllón Laguía, Sergio
6. Carreras Morales, Rafael
7. Santacruz Ostos, Rubén
8. Villarejo Conde, Diego
9.  Polo Merlo, Gabriel Eduardo
10. Romero Granados, José Álvaro
11. Ruiz Plaza, Saúl
12. Díaz Mata, Jesús
13. Luna Paredes, Alejandro
14. Palacios Moreno, Mario
15. Caballero Yáñez, Francisco
16. Ruiz Villatoro, Sergio
17. Sereno Cambrón, Raúl
18. Pérez Mariscal, Manuel Jesús
19. Quirós Arenas, Santiago

## Instrucciones

1. Abre el primer Packet Tracer que te corresponda: [pares](pt/Examen-practicoUD3-Pares.pka) o [impares](pt/Examen-practicoUD3-Impares.pka). Recuerda guardarlo con tu nombre y apellidos. En el Switch0:
   1. Asigna el nombre de host del switch: tuApellido2
   2. Configura el siguiente mensaje MOTD: IES Gran Capitán. tuApellido1 tuApellido2, tuNombre
   3. Acceso a un switch por el puerto de consola mediante credenciales de usuario. Un equipo terminal debe poder acceder al switch con el hyperterminal utilizando  un usuario y contraseña indicados en una nota junto al dispositivo y cable.   Ambos deben ser tuApellido.
   4. Configure acceso seguro al switch por ssh. Mediante usuario y contraseña. Ambos deben ser tuApellido.
2. Portátil
   1. Comprueba la conexión ssh con el Portátil. Entrega aquí pantallazo que lo demuestre.
3. Ehterchannel
   1. Configura la agregación de puertos entre switch0 y switch 1. Crea el canal 1 con los cuatro interfaces del escenario. Cambia el balanceo de carga por defecto
4. Switch 1
   1. MAC segura persistente
      1. El puerto Fa0/2 del switch1 admite como máximo 1 dirección MAC segura persistente. La dirección del servidor será aprendida por el switch.  Entrega aquí pantallazo que lo demuestre.
   2. MAC segura estática
      1. Al puerto Fa0/1 del switch1 sólo puede conectarse el servidor. El intento de conexión por parte de otro dispositivo tiene que provocar la desactivación del puerto.  Entrega aquí pantallazo que lo demuestre.
   3. En el switch 1 inhabilita todos los puertos que no se utilizan
   4. Guarda la configuración del switch.
   5. Entrega aquí pantallazo que lo demuestre.
5. Abre el segundo Packet Tracer sobre Spanning Tree que te corresponda: [pares](pt/Examen-practicoUD3-STP-Pares.pka) o [impares](pt/Examen-practicoUD3-STP-Impares.pka). Recuerda guardarlo con tu nombre y apellidos. 
   1. Localiza la raíz que se genera de forma automática. Cámbiale el nombre del host a raiz-tuNombre.  Entrega aquí pantallazo que lo demuestre.
   2. Establece el switch 0 como raíz primaria. Indica en la nota adjunta por qué es el idóneo.
   3. Designa al switch 3 como raíz secundaria.  Entrega aquí pantallazo que lo demuestre.
   4. Activa el enlace entre el switch 0 y el switch 4 para que el switch 4 alcance la raíz directamente por el puerto Fa0/5. Entrega aquí pantallazo que lo demuestre.
6. Al finalizar ambos escenarios se comprobará la comunicación entre los dispositivos finales del escenario. Indica con una nota la dirección ip asignada a cada uno, así como el usuario y la contraseña.
7. Recuerda que toda la configuración deberá mantenerse tras arrancarse los dispositivos.
