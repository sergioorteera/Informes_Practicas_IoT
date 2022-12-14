# Practica 4
**Por** *Sergio Erazo*

## Desarrollo de la práctica - Evidencia

**I. Desplegar una aplicación en la nube**

  1. Descargar deta ejecutando en la terminal:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/1.PNG?raw=true)

  2. Agregando la variable de entorno:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/2.PNG?raw=true)

  3. Iniciar sesión en Deta ejecutando en la terminal:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/3.PNG?raw=true)

  4. Crear un punto de entrada de la aplicación. El archivo src/index.ts debe quedar de la siguiente forma:
     En la raíz del proyecto crear un nuevo archivo index.js con el siguiente contenido:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/4.PNG?raw=true)

  5. Publicar la aplicación ejecutando en la terminal:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/5.PNG?raw=true)

  6. Para desplegar la aplicación ejecutamos en la terminal:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/6.PNG?raw=true)

  7. Para activar los logs de la aplicación ejecutamos en la terminal:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/7.PNG?raw=true)

  8. Respuesta implementada en el método get del servicio:
  
![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/8.PNG?raw=true)

En esta parte no pude solucionar el error, ya que debería mostrarme los datos del servicio. Cuando ejecuto el servidor de manera local y hago uso del GET si me muestra correctamente los valores. Revise el código, intente borrarlo y volver a hacer la práctica y no se soluciono.

Link del repositorio: https://github.com/sergioorteera/Practica_02_servidor/tree/practica_04_noBD

**II. Conectado a una base de datos**

  1. Instalar las dependencias de TypeORM y MongoDB.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/9.PNG?raw=true)

  2. URL mongo.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/10.PNG?raw=true)
  
  3. Modifique el archivo src/app.module.ts.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/11.PNG?raw=true)
  
  4. Cree un archivo para modelar la entidad.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/12.PNG?raw=true)
  
  5. Es necesario modificar los métodos para que utilicen el repositorio.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/13.PNG?raw=true)

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/14.PNG?raw=true)
  
  También fue necesario modificar los archivos de tablets.controller.ts y tabletsImpl.controller.ts para que usaran la entidad creada anteriormente.
  
  6. Finalmente, si se ejecuta el proyecto localmente con npm run start:dev, ejecute un POST para crear un nuevo elemento. Si la respuesta es satisfactoria y si al        ejecutar el GET se recupera el elemento creado, entonces la conexión con la base de datos fue exitosa.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_04/Imagenes/15.PNG?raw=true)
  
  Como se puede observar a la hora de ejecutar el servidor aparece un error para conectarse con Mongo, intente solucionar este error
  revisando que la URL de conexión estuviera correctamente el usuario y el pass. 
  También validé la conexión a internet de la máquina.
  Comprobé la URL de la base de datos conectando con mongo compass.
  A mi criterio todo esta funcionando bien pero no logré solucionar dicho error.
  
  Link del repositorio: https://github.com/sergioorteera/Practica_02_servidor/tree/practica_04_BD







