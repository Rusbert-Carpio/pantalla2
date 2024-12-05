Rusbert Junior Carpio Rosario 2023-0682

Mandato

Tarea pantalla
En este espacio suba el siguiente ejercicio

 Crear una aplicación que permita registrar la configuración de mostrado normal o 

“Top Most”, también las opciones de: confirmar el cierre de la ventana, utilizar color 

de fondo, conectarse a una base de datos, tipos de posibilidades de bases de datos 

(Informix, SQL Server, Oracle).

2- Subir aqui el replanteamiento de pantalla. 

---------------------------------------------------------------------------------------------------------------------------

Esta pantalla está diseñada para permitir al usuario configurar varias opciones relacionadas con una aplicación.

<img width="948" alt="cap1" src="https://github.com/user-attachments/assets/5284ce70-4dcd-4ac5-a59f-9c504b85cadc">

Opción "Top Most":

Si el usuario marca esta casilla, indica que la ventana de la aplicación debe mantenerse siempre visible en la parte superior de otras ventanas.
Confirmar cierre de ventana:

Si el usuario activa esta opción, la aplicación deberá mostrar una confirmación antes de cerrarse, evitando cierres accidentales.

<img width="955" alt="cap2" src="https://github.com/user-attachments/assets/1431b890-a5fb-4f3e-8e65-1ddffc8dc1f2">

Personalización de la Apariencia
Esta sección permite ajustar el aspecto visual de la aplicación:

Usar color de fondo:

Activar esta opción habilita un selector de color.
El usuario puede elegir un color que se aplicará como fondo de la página.
Si esta opción está activada, cualquier imagen de fondo será eliminada para evitar conflictos.
Usar imagen de fondo:

Activar esta opción habilita un selector de archivos.
El usuario puede cargar una imagen desde su dispositivo, que se aplicará como fondo de la página.
Al seleccionar una imagen, cualquier color de fondo previamente configurado será eliminado.

<img width="959" alt="cap3" src="https://github.com/user-attachments/assets/2665a937-bf22-43a1-bd47-432ce9c18d8e">

Configuración de Base de Datos
Esta sección controla la conexión a bases de datos:

Conectar a una base de datos:

Activar esta opción permite al usuario configurar el tipo de base de datos.
Se habilita un menú desplegable donde el usuario puede seleccionar entre:
Informix
SQL Server
Oracle
También se activa el botón de Probar conexión.
Probar conexión:

Una vez que el usuario selecciona un tipo de base de datos, puede hacer clic en este botón para simular una prueba de conexión.
Si no se ha seleccionado ningún tipo de base de datos, se muestra un mensaje de alerta.


<img width="957" alt="cap4" src="https://github.com/user-attachments/assets/56e973bf-c4d8-4acf-ad74-f5411a8e7a8d">

Botones de Acción
Guardar:

Este botón recopila todas las configuraciones seleccionadas por el usuario.
Se muestra un resumen de las opciones configuradas en formato JSON dentro de un cuadro de alerta.
Cancelar:

Este botón reinicia todos los cambios realizados.
Antes de reiniciar, solicita una confirmación para evitar perder configuraciones accidentales.


<img width="959" alt="cap5" src="https://github.com/user-attachments/assets/5dfde7c4-dca6-40e8-ac4b-6d81dedda18e">

Control condicional de opciones:

Las opciones de color de fondo, imagen de fondo y configuración de bases de datos están vinculadas a checkboxes. Solo se habilitan si la opción correspondiente está activada.
Cohabitación entre color e imagen:

Al activar el color de fondo, se desactiva automáticamente la imagen de fondo.
De manera similar, al activar la imagen de fondo, se elimina el color aplicado.
Cargador de imágenes:

Utiliza la API de FileReader para leer el archivo de imagen cargado por el usuario y establecerlo como fondo de la página.
