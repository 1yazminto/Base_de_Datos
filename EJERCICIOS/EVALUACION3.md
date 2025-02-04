
## Práctica 4
### Data warehouse

Objetivo: Demostrar la identificación de los elementos que componen data warehouse y
su esquema

Ejercicio:

1. ¿Qué es un DataWarehouse?(valor 2)
2. ES UN SISTEMA QUE AGREGA Y TOMA INFORMACION DE DIFERENTES FUENTES EN UN ALMACEN

2. Realiza un diseño del modelo en estrella (valor 2)
![imagen](https://user-images.githubusercontent.com/103079658/171660833-89c38bb2-166c-4b0d-aae4-fa2a98f7e736.png)

3. Realiza un diseño del modelo copo de nieve (valor 2)
![imagen](https://user-images.githubusercontent.com/103079658/171660728-e3ef720b-df2d-44aa-b65b-728695ec4e87.png)


## Práctica 7
### Funciones en SQL
Objetivo: Demostrar el uso y aplicación en una base de datos para mejorar la gestión

Ejercicio:

1. Calcula el número total de productos que hay en la tabla productos. (valor 4.5)
2. 
![image](https://user-images.githubusercontent.com/103079658/171884860-808b8812-4591-4f71-8fc7-c7d285872491.png)


2. Muestra el número total de productos que tiene cada uno de los fabricantes. El listado
también debe incluir los fabricantes que no tienen ningún producto. El resultado
mostrará dos columnas, una con el nombre del fabricante y otra con el número de
productos que tiene. Ordene el resultado descendentemente por el número de
productos. (valor 4.5)
![image](https://user-images.githubusercontent.com/103079658/171883414-b103b8d8-8256-405e-9ddf-38e48c1c98fd.png)


3. Muestra el precio máximo, precio mínimo y precio medio de los productos de cada
uno de los fabricantes. El resultado mostrará el nombre del fabricante junto con los
datos que se solicitan. (valor 4.5)

![image](https://user-images.githubusercontent.com/103079658/171886086-41e22cb1-394f-42ea-8451-6ac4bc37b5b3.png)

4. Muestra el nombre de cada fabricante, junto con el precio máximo, precio mínimo,
precio medio y el número total de productos de los fabricantes que tienen un precio
medio superior a 200€. Es necesario mostrar el nombre del fabricante. (valor 4.5)

![image](https://user-images.githubusercontent.com/103079658/171882808-a157e650-d570-4419-844e-ebd9cbbce724.png)

https://www.db-fiddle.com/f/94Wb9kUzGiD4FRs74Zn2DU/3

## Práctica 8.
### Disparadores (Triggers)

  PREGUNTAS:
  
  1.- QUE ES UN TRIGGERS
      SE USAN EN EL LENGUAJE DE PROGRAMACION SQL, ES UNA SERIE DE REGLAS PREDEFINIDAS ASOCIADAS A UNA TABLA, PARA SE ASOCIAN A DETERMINADAS OPERACIONES EN       LA TABLA, CUANDO SE ANADEN, ACTUALIZAN O ELIMINAN REGISTROS, Y SE DESENCADENAN DE MANERA AUTOMATICA, AL PRODUCIRSE CIERTOS EVENTOS, LO QUE PERMITE CAPTURARLOS,CONTROLARLOS E INTERVENIR EN ELLOS 
  
  2.- CUAL ES LA FUNCION DE UN TRIGGERS
      CONTRIBUYE A MEJORAR LA GESTION DE LA BASE DE DATOS, YA QUE SE REALIZA DE MANERA AUTOMATICA, SIN LA INTERVENCION HUMANA,DE TAL FORMA AUMENTA LA           SEGURIDAD E INTEGRIDAD DE LA INFORMACION, PARA ESTO ES NECESARIO TENER PERMISOD DE INSERT, DELETE Y UPDATE.
  
  3.-CUALES SON LOS ESCENARIOS DE USO DE UN TRIGGERS
      SON DOS:
      EL PRIMERO ES CUANDO NO SE INTERVIENE EN EL CODIGO FUENTE DE LA APLICACION QUE TRABAJA SOBRE LA BASE DE DATOS, SOBRE LA QUE QUEREMOS ACTUAR O REACCIONAR A SUS EVENTOS
      EL SEGUNDO ES QUE DISPONIENDO DE UN CODIGO, ESTE PERTENECE A UN SOFTWARE DESARROLLADO POR TRCEROS Y EXISTE LA POSIBILIDAD RELATIVAMENTE ALTA DE APLICAR ACTUALIZAIONES , Y DECIDIMOS MODIFICAR EL CODIGO FUENTE LO MENOS POSIBLE PARA FACILITAR ESTE TIPO DE TAREA
  
    
  4.- CUANDO SE PUEDE USAR UN TRIGGERS
  
  EN INTEGRACIONES DE SOFTWARE EN LAS QUE AL MENOS UNO DE LOS PROOGRAMAS QUE INTERVIENEN ES DE CODIGO CERRADO. EN ESTA SITUACION LOS TRIGGERS NOS PERMTEN CAPTURAR LOS EVENTOS QEU MODIFICAN LA BASE DE DATOS Y ACTUAR EN CONSECUENCIA, EVITANDO CREAR TAREAS PROGRAMADAS E INCLUSO TABLAS DE INTEGRACION

Objetivo: Demostrar las operaciones que se realizan en una base de datos.

Ejercicio: Crea una base de datos llamada test que contenga una tabla llamada
alumnos con las siguientes columnas. (valor 18)

Evaluación:

Creación de la base de datos : 9 puntos.

Creación de los Disparadores(Triggers): 9 puntos.

Tabla alumnos:

● id (entero sin signo)

● nombre (cadena de caracteres)

● apellido1 (cadena de caracteres)

● apellido2 (cadena de caracteres)

● nota (número real)

Una vez creada la tabla escriba dos triggers con las siguientes características:

● Trigger 1: trigger_check_nota_before_insert

  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de inserción.
  
  o Si el nuevo valor de la nota que se quiere insertar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere insertar es mayor que 10, se
  guarda como 10.

● Trigger2 : trigger_check_nota_before_update
  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de actualización.
  
  o Si el nuevo valor de la nota que se quiere actualizar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere actualizar es mayor que 10, se
  guarda como 10.
  
Una vez creados los triggers escribe varias sentencias de inserción y actualización
sobre la tabla alumnos y verifica que los triggers se están ejecutando
correctamente.
