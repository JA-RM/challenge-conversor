APP Conversor:

1. Manual Usuario
2. Manual Técnico

********************
***MANUAL USUARIO***
********************

1. Ejecute el software desde consola:

Desde la Ubicación del archivo:

java -jar conversor.jar

2. Seleccione EL tipo de Conversión que desea: 1. Moneda y 2. Temperaturas.

3. En los dos conversores se sigue el mismo patrón:

3.1 Elegir medidas a convertir en double (Si ingresa otro carácter obtendrá una alerta que le advertira de un carácter no valido y por lo mismo deberá elegir si retornar al menú principal o cerrar la aplicación)

4. Si ingresó un número se realizará la conversión y tras esto preguntará si desea o no retornar al menú inicial.

************************
***MANUAL TÉCNICO***
************************

Desarrollado en Eclipse 4.23
Java 11
GNU/Linux Debian 11


El programa está desarrollado en POO y consta de tres clases:

1. Temperatura

En está están los métodos para generar las conversiones de temperatura.

2. Moneda

En está están los métodos para generar las conversiones de monedas.

3. Conversor

En está está el método main que en su interior alberga un if que conduce a dos switch ya sea para las opciones de conversión de moneda o de temperatura.
