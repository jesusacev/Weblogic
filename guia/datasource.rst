Creación de Datasource en Weblogic
=========


- En la consola de Weblogic nos vamos a  Estructura de Dominio, seleccionamos Servicios ---> Orígenes de Datos, y le damos a nuevo para crear un datasource para conexión a la base de datos:


.. image:: ../imagenes/dominio_despliegue/006.png


- Seleccionamos Origen de datos Genérico:


.. image:: ../imagenes/dominio_despliegue/007.png


- Le asignamos el nombre al datasource:


.. image:: ../imagenes/dominio_despliegue/008.png


- Seleccionamos el controlador de base de datos que en nuestro caso es este:


.. image:: ../imagenes/dominio_despliegue/009.png


- Las opciones de transacción las dejamos por defecto:


.. image:: ../imagenes/dominio_despliegue/010.png


- Ingresamos el nombre de base de datos, la ip del servidor, el puerto y el usuario de base de datos con su contraseña:


.. image:: ../imagenes/dominio_despliegue/011.png


- Luego le damos a Probar Configuración, para certificar que conecte a la base de datos:


.. image:: ../imagenes/dominio_despliegue/012.png


- Le damos siguiente y tildamos el dominio, y luego le damos a finalizar:


.. image:: ../imagenes/dominio_despliegue/013.png


- Ya el datasource se debe haber creado de manera exitosa:


.. image:: ../imagenes/dominio_despliegue/014.png


- Sí queremos aumentar el pool de conexiones posterior a la creación del datasource, lo seleccionamos y le damos a la pestaña Pool de Conexiones, y a donde dice Capacidad Máxima, colocamos el valor de nuestro gusto:


.. image:: ../imagenes/dominio_despliegue/015.png


.. image:: ../imagenes/dominio_despliegue/016.png


- A continuación la consola nos enviará un mensaje de que se han activado los cambios y que no es necesario reiniciar:


.. image:: ../imagenes/dominio_despliegue/017.png

