Cambio en Configuración de Seguridad del Node Manager
========


- Sí no tenemos ningún certificado asociado al puerto por el que escucha el node manager, entonces debemos modificar el archivo nodemanager.properties ubicado en la ruta $DOMAIN_HOME/nodemanager:


.. image:: ../imagenes/node/14-03-201911-29-06.png


- El parámetro SecureListener lo debemos colocar en "false":


.. image:: ../imagenes/node/14-03-201911-29-41.png