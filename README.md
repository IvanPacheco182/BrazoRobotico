 # BrazoRobotico
 ## ========Brazo robótico industrial de 4 grados de libertad=======
 Proyecto de simulación del funcionamiento de un brazo robótico industrial capaz de grabar pasos de ejecución 
 mediante control de aplicativo Java y uso 
 de microcontrolador ARDUINO UNO.
 
 # Descripción General
 El circuito desarrollado ejemplifica el trabajo de un brazo robótico industrial, 
 el cual cuenta con dos modos de trabajo: programador y ejecución. El brazo robotico 
 plantedo puede ser controlado y programdo en secuancia de pasos de ejecución mediante
 un aplicativo desarrollado con la tecnología Java. El brazo róbtico posee 
 cutro grados de libertad para el movimiento, por lo cual tendrá la capacidad de movimeinto 
 en cuatro motores distintos (tres servomotores y un motor a pasos). Además de poder ser
 controlado por un aplicativo en Java, el brazo planteado  cuenta con la funcionalidad de
 guardar pasos de ejecución (en memoria EEPROM de del dispositivo Arduino) según el usuario 
 lo desee y ejecutarlos en cualquier momento a menos que un botón de aborto sea accionado. 
 Finalmente, cuando se trabaja en modo de ejecución el brazo debe seguir con su flujo normal 
 de ejecución de pasos, sin importar si ocurrió un fallo en energía y perdida de comunicación 
 serial con el aplicativo Java. 
 
 
 ## Requisistos Básicos
 Para la elaboración y ejecución del circuito digital se necesita lo 
 siguiente:
 * Arduino UNO
 * Protoboard
 * 3 servomotores (microservomotores)
 * 1 Motor a pasos con controladora 28BYJ-48
* 1 Resistencia de 220 Ohms
* 1 Pulsador
* Conectores rápidos MM (20 Apróximadamente)
* 4 Conectores rápidos HM
* Pantalla LCD de 16x2
* Driver i2c
* Contar con JDK y/o JVM en la computadora en la cual se ejecutará la aplicación Java 
* IDE de desarrollo Java (NetBeans, Eclipse, etc)
* Kit de armado para brazo robótico de 4 grados de libertad (De acrilico)
* Librería y archivos para comunicación vía puerto serial Panamahitek(libre y disponible en https://sourceforge.net/projects/arduinoyjava/files/v2.7.0/)
 
# Diagrama del brazo robótico:
![diagrama del brazo robotico](https://github.com/IvanPacheco182/BrazoRobotico/blob/master/Diagrama.png)

# Interfaz de comunicación desarrollada en Java.
Se muestra la interfaz desarrollada en java para poder hacer la comunicación y poder programar el brazo robotico. Contiene un botón para cada movimiento. Para mover una parte del brazo de usa una cantidad en grados.

![CapturaJava](https://github.com/IvanPacheco182/BrazoRobotico/blob/master/CapturaJava.png)


# Fotos del brazo ya funcionando y programado.
![evidencia1](https://github.com/IvanPacheco182/BrazoRobotico/blob/master/evidencia1.jpg)
![evidencia2](https://github.com/IvanPacheco182/BrazoRobotico/blob/master/evidencia2.jpg)
![evidencia3](https://github.com/IvanPacheco182/BrazoRobotico/blob/master/evidencia3jpg)
![evidencia4](https://github.com/IvanPacheco182/BrazoRobotico/blob/master/evidencia4.jpg)

 ## =============Información de Contacto=============
Elaborado por: Oscar Iván Pacheco Vargas, Erick Alejandro Ochoa Gonzalez y Carlos Leonardo Luna Castillo.

correos electronicos de los contactos:

Heavy.pacheco@gmail.com

 ## Derechos de Autor 
El material mostrado para la elaboración del circuito digital 
 planteado es libre para su uso y modificación futura por cualquier
 colaborador
