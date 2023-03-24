**Documentación Tareas**

**Tarea 1: Pruebas de API**

Las pruebas de la API de posts fueron realizadas mediante Postman, se debe tener en cuenta lo siguiente:

1.	Es importante tener Postman descargado para la versión de su sistema operativo, por medio del siguiente enlace se realiza la descargar https://www.postman.com/downloads/ 
2.	Ejecutar los siguientes pasos para verificar las pruebas realizadas:
1.	Abrir Postman.
2.	Verificar encontrarse ubicado en el ítem del menú que se encuentra a la izquierda “Collections” -> Colecciones.
3.	Visualizar el botón “Import” y dar click en él.
4.	Dar click en el enlace de “Files”.
5.	Ubicar el archivo en su computadora Pruebas_API_Posts.postman_collection.json
6.	Seleccionar el mismo para importar.

**Configuración de Environments:**

Antes de ejecutar cada una de las pruebas, es importante realizar la configuración del ambiente o environment para que cada uno de los request funcionen correctamente, para ello, ejecutar los siguientes pasos:

Precondición: Postman previamente instalado y abierto.

1.	Ubicar en el ítem del menú que se encuentra a la izquierda “Environments” -> Ambientes y dar click en él.
2.	Click en “Globals”.
3.	Visualizar una tabla con 4 encabezados, “Variable”, “Type”,”Initial Value”,”Current Value”.
4.	En la tabla se van a configurar únicamente las columnas de “Variable” - “Initial Value” de la siguiente manera.
-	Variable: API Posts
-	Initial Value: https://jsonplaceholder.typicode.com/
5.	Ubicar el botón “Save” y dar click en él para guardar.

Teniendo previamente configurado el ambiente, es necesario, ingresar nuevamente en “Collections”, ubicar la colección “Pruebas_API_POST”, seleccionar alguno de los request y validar mediante el botón “Send”.

---

**Tarea 2: Pruebas Automáticas de UI**

Las pruebas automatizadas se realizan con la ayuda de la extensión Selenium IDE, para configurar correctamente el ambiente y ejecutar el test, se deberán seguir los siguientes pasos:

1.	Instalar la extensión “Selenium IDE” en su navegador de preferencia mediante el siguiente enlace https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd 
2.	Abrir Selenium IDE.
3.	Visualizara una ventana con 4 opciones, dar click en la opción 2 “Open an existing Project”.
4.	Ubicar el archivo Automation_AidForAids.side y seleccionarlo para abrir.
5.	Ubicar el botón ▷ con el cual se ejecutará el test al dar Click.

