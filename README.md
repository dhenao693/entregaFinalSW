# entregaFinalSW

### Autor
Esta es la entrega final de Daniel Henao Sanchez.

### Contenido

Esta entrega contiene:

- Proyecto de **serviciosweb**, el cual es la api creada con sprinboot y lombook
- Proyecto de **serviciosWebFront**, es cual es toda la interfaz de usuario para pdoer consumir la api; el consumo se realizo con axios de JS
- El archivo **SCRIPT.sql** con la base de datos creada y dos usuarios de defecto, ubicado en la raiz

### Proceso para ejecutar

Para poder realizar la ejecución se debe llevar a cabo lo siguientes paso:

- Modificar el archivo **application.properties** con los datos pertinentes del caso ubicado en ***entregaFinalSW\serviciosweb\src\main\resources\application.properties***
- Ejecutar el SCRIPT.sql en el gestor de bases MySql de datos de preferencia (Se trabajo desde Dbeaber y phpMyAdmin)
- Levantar el api en forma local mediante su main ubicado en ***entregaFinalSW\serviciosweb\src\main\java\com\itm\servicioswebmaven\ServiciosWebMavenApplication.java***
- Ubicar el proyecto **serviciosWebFront** dentro de la carpeta *\xampp\htdocs\ (Debido a que se trabajo con Xampp)
- Levantar los servicios de Apache y MySql de xampp (Servidor con el que se trabajo)
- Acceder al localhost:"puerto seleccionado en el **application.properties**"/serviciosWebFront

### Notas

En el momento se trabajo la consulta del usuario para el login y la consulta de las listas de usuarios para presentarlas en una tabla, adicional a esto por facilidad se apoyo de componentes de boostrap


