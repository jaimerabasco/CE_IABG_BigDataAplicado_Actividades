# Actividad 3 módulo de Big Data Aplicado.

Para el desarrollo de esta práctica necesitarás un fichero csv con un dataset. Puedes descargar alguno que te interese desde la página web: 
Tras descargar el fichero
[https://www.kaggle.com/datasets](https://www.kaggle.com/datasets)

La actividad consistirá en desarrollar un cuadernillo de Google Colab que contenga los siguientes ejercicios:

## Ejercicio 1.
Ingesta de datos vía Flume. Nuestro agente, cuyo source será de tipo spooldir, comprobará un determinado directorio, donde debería de encontrar nuestro fichero csv, y procesará los archivos para colocar su contenido en un directorio final de HDFS. Esta acción podría generar en el destino uno o varios ficheros nuevos

## Ejercicio 2.
Acceso a los datos usando Spark-Hive. Una vez que ya tenemos el dataset en HDFS, cargaremos el contenido de un fichero csv y lo mostraremos por pantalla. Además de lo anterior, realizaremos un par de consultas sobre el dataset para comprobar que podemos interactuar con él sin problemas.

## Ejercicio 3.
Limpieza de datos con Pig. Como punto final de la actividad, procesaremos el fichero anterior para eliminar valores nulos. Este proceso constará de los siguientes pasos::

* Lectura del fichero csv.
* Obtención, por pantalla, de las columnas existentes.
* Chequeo de nulos.
* Creación de fichero de configuración para limpieza y ejecución.
  
Como elemento de referencia podéis utilizar el [cuadernillo](
https://colab.research.google.com/drive/1G3U7EseeSrByzvxOJZ6-7sML_eZN4NgR)

## Solución

* La actividad está integramente realizada en [Google Colab](https://colab.research.google.com/drive/1iyn87vFYMHDwe7C9WcsoHIWxbbzkMA8u)
* También puedes subir a Google Colab cuaquiera de los 2 archivos de esta carpeta.

***Cualquier sugerencia, advertencia de error o cualquier otro aporte será más que bienvenido***

![Jaime Rabasco Ronda](../imagenes/mi_signature_dpto.png)