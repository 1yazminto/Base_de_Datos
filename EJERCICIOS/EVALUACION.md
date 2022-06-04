## Práctica 1.

1. Introducción a base de datos

Objetivo: Identificar el nivel de comprensión de los conceptos de base de datos,
mediante preguntas abiertas.
 
Preguntas:

1. ¿Cuáles son las cinco funciones principales del administrador de bases de datos?
(valor 1.5)
ASEGURA EL BUEN FUNCIONAMIENTO
RETENCION DE INFORMACON DE LA BASE DE DATOS
EVITAR PERDIDA DE DATOS
SOLUCIONAR INCIDENCIAS Y PERDIDA DE DATOS
ASEGURAR LA SEGURIDAD DE LOS DATOS
2. Indíque cinco responsabilidades del sistema gestor de bases de datos (valor 1.5)
3. DEFINICION DEL ESQUEMA
4. DEFINICION DELA ESTRUCTURA Y DEL METODO DE ACCESO
5. MODIFICACION DEL ESQUEMA Y DE LA ORGANIZACION FISICA
6. CONCESION DE AUTORIZACION PARA EL ACCESO A LOS DATOS
7. MANTENIMIENTO RUTINARIO

3. En una BD al usuario del sistema se le brindarán recursos para realizar diversas
operaciones sobre estos archivos, tales como: (valor 1.5)
DETERMINA EL PROPOSITO DE LA BASE DE DATOS
BUSCAR Y ORGANIZAR LA INFORMACION NECESARIA
DIVIDIR LA INFORMACION EN TABLAS
CONVERTIR LOS ELEMENTOS DE INFORMACION EN COLUMNAS
ESPECIFICAR LAS CLAVES PRINCIPALES

4. ¿Qué es un Sistema de Información? 
5. ES UN CONJUNTO DE DATOS Y ELEMENTOS QUE INTERACTUAN ENTRE SI Y QUE TIENEN UN FIN ESPECIFICO, QUE EN GENERAL TIENEN QUE VER CON SATISSFACER UNA NECESIDAD.(valor 1.5)

## Práctica 2.

2. Diseño de un modelo relacional

Objetivo: Representar desde un modelo entidad relación un problema


Ejercicio:

Tenemos que diseñar una base de datos sobre proveedores y disponemos de la siguiente
información:

Realiza el modelo entidad relación. (valor 6)

Tenemos esta información sobre una cadena editorial:

● La editorial tiene varias sucursales, con su domicilio, teléfono y un código de
sucursal.

● Cada sucursal tiene varios empleados, de los cuales tendremos su nombre,
apellidos, NIF y teléfono. Un empleado trabaja en una única sucursal.

● En cada sucursal se publican varias revistas, de las que almacenaremos su título,
número de registro, periodicidad y tipo.

● Una revista puede ser publicada por varias sucursales.

● La editorial tiene periodistas (que no trabajan en las sucursales) que pueden
escribir artículos para varias revistas. Almacenaremos los mismos datos que para
los empleados, añadiendo su especialidad.

● También es necesario guardar las secciones fijas que tiene cada revista, que
constan de un título y una extensión.

● Para cada revista, almacenaremos información de cada ejemplar, que incluirá la
fecha, número de páginas y el número de ejemplares vendidos.

![Captura de Pantalla 2022-06-03 a la(s) 18 19 46](https://user-images.githubusercontent.com/103079658/171965987-4962f349-bb2f-492e-b932-8e78e531efb0.png)

https://www.db-fiddle.com/f/cTToWBaovenzee3ZeHXw63/0

https://www.db-fiddle.com/f/nyz8icwHhnPZSa43gwddt2/13
