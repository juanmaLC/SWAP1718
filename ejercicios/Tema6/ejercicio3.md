EJERCICIO 3 / TEMA 6:

1-Escaneo de puertos: Es utilizada por los piratas infórmaticos para descubrir los servicios expuestos de un servidor. Se pueden evitar de la siguiente manera:

-Cerrar todos los puertos de los servicios que no estemos utilizando.
-Herramientas como PortSentry detecta las solicitudes de conexión a los puertos que tengas configurados y las limita.

2-Ataque de secuencia TCP: es un intento de predecir el número de secuencia utilizado en una conexión TCP. El atacante utiliza este paquete para hacerse con la conexión o para entregar un paquete con información maligna.Se puede envitar de las siguientes maneras:

-Información como diferencia de tiempo o información de capas bajas de protocolo pueden hacer al host destino diferenciar los paquetes falsos.
-Otra solución es configurar un cortafuegos para no permitir que entren paquetes externos con una ip interna.