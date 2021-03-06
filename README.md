# -Practica04-Mi-Correo-Electr-nico
### **CARRERA:** INGENIERIA DE SISTEMAS/COMPUTACIÓN. **ASIGNATURA:** HIPERMEDIAL
### **NRO. PRÁCTICA:** 4. **TITULO PRÁCTICA:** Resolución de problemas sobre PHP y MySQL.
### **OBJETIVO**:
   * Entender y organizar de una mejor manera los sitios de web en Internet 
   * Diseñar adecuadamente elementos gráficos en sitios web en Internet
   * Crear sitios web aplicando estándares actuales. 
  ### INSTRUCCIONES
  Con base al archivo*Práctica 04 – Creación de una aplicación web usando PHP y Base de Dato*, se pide realizar los siguientes ajustes: 
   * Agregar roles a la tabla usuario. Un usuario puede tener un rol de “admin” o “user” 
   * Los usuarios con rol de “admin” pueden únicamente: modificar, eliminar y cambiar la contraseña de cualquier usuario de la base de datos.
   * Los usuarios con rol de “user” pueden modificar, eliminar y cambiar la contraseña de su usuario. 
 
Luego, con base a estos ajustes realizados, se pide desarrollar una aplicación web usando PHP y Base de Datos que permita gestionar 
(enviar y recibir) mensajes electrónicos entre usuarios de la aplicación. De los mensajes electrónicos se desea conocer la fecha y 
hora, remitente, destinatario, asunto y mensaje. Para lo cual, se pide como mínimo los siguientes requerimientos:

Usuario con rol de **user**:
  * Visualizar en su página principal (index.php) el listado de todos los mensajes electrónicos   recibidos, ordenados por los más recientes.
  * Visualizar el listado de todos los mensajes electrónicos enviados, ordenados por los más recientes.
  * Enviar mensajes electrónicos a otros usuarios de la aplicación web.
  * Buscar todos los mensajes electrónicos recibidos. La búsqueda se realizará por el correo del usuario remitente y se deberá aplicar Ajax para la búsqueda.
  * Buscar todos los mensajes electrónicos enviados. La búsqueda se realizará por el correo del usuario destinatario y se deberá aplicar Ajax para la búsqueda. 
  * Modificar los datos del usuario. 
  * Cambiar la contraseña del usuario. 
  * Agregar un avatar (fotografía) a la cuenta del usuario. 
Usuario con rol de **admin**: 
  * No puede recibir ni enviar mensajes electrónicos. 
  * Visualizar en su página principal (index.php) el listado de todos los mensajes electrónicos, ordenados por los más recientes. 
  * Eliminar los mensajes electrónicos de los usuarios con rol “user”.
   * Eliminar, modificar y cambiar contraseña de los usuarios con rol “user”. 
Por ultimo, se debe aplicar  parámetros de seguridad a través del uso de sesiones. Para lo cual, se debe tener en cuenta: 
   * Un usuario “anónimo”, es decir, un usuario que no ha iniciado sesión puede acceder únicamente a los archivos de la carpeta pública. 
   * Un usuario con rol de “admin” puede acceder únicamente a los archivos de la carpeta admin --> vista --> admin y admin --> controladores --> admin 
   * Un usuario con rol de “user” puede acceder únicamente a los archivos de la carpeta admin --> vista --> user y admin --> controladores --> user 
 ### Prototipo de ejemplo de archivos de index de la practica:
 
 ![alt text](https://github.com/aReinoso007/-Practica04-Mi-Correo-Electr-nico/blob/master/imagenes/fig2%20(1).png)
 
 
 <Figura 1.  *Index del usuario con rol "user"*>
 
 ![alt text](https://github.com/aReinoso007/-Practica04-Mi-Correo-Electr-nico/blob/master/imagenes/fig2%20(2).png)
 
  <Figura 1.  *Index del usuario con rol "admin"*>


###  ACTIVIDADES A DESARROLLAR
 1. Generar el diagrama E-R para la solución de la práctica 
 2. Crear un repositorio en GitHub con el nombre “Practica04 – Mi Correo Electrónico” Enlace al repositorio: https://github.com/aReinoso007/-Practica04-Mi-Correo-Electr-nico.git 
 3.  Realizar un commit y push por cada requerimiento de los puntos antes descritos.  
 4. Luego, se debe crear el archivo README del repositorio de GitHub. 
 5. Generar informe de los resultados en el formato de prácticas. Debe incluir:
     * El diagrama E-R de la solución propuesta
     * Nombre de la base de datos .  
     * Sentencias SQL de la estructura de la base de datos 
     * El desarrollo de cada uno de los requerimientos antes descritos. 
     * La evidencia del correcto diseño de las páginas HTML usando CSS. Para lo cual, se puede generar fotografías instantáneas (pantallazos).  
     * La evidencia del correcto funcionamiento de cada uno de los puntos requeridos. 
     * El informe debe incluir conclusiones apropiadas
     * En el informe se debe incluir la información de GitHub (usuario y URL del repositorio de la práctica) 
     * En el informe se debe incluir la firma digital del estudiante. 
 6. En el archivo README del repositorio debe constar la misma información del informe de resultados de la práctica que se indica en el punto anterior. 
 ### RESULTADO(S) OBTENIDO(S):
  * Tener el conocimiento suficiente para que el estudiante pueda entender y organizar de una mejor manera los sitios de web y de negocios en Internet 
 ### CONCLUSIONES:
  * Los estudiantes podrán organizar sitios web basados en el lenguaje de programación PHP para persistir información en una base de datos relacional.
 ### RECOMEDACIONES:
  * Probar la solución de la práctica en al menos tres navegadores web; Google Chrome, Firefox y Safari
