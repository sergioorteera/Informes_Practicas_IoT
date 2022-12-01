# Practica 2
**Por** *Sergio Erazo*

## Desarrollo de la práctica - Evidencia
**I. Instalar NodeJS y NestJS**

  1. En debian, ubuntu, raspbian, etc. Abrir la terminal y ejecutar el comando:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/1.PNG?raw=true)

  2. Actualizar Nodejs:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/2.PNG?raw=true)

  3. Validar las versiones instaladas, ejecute:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/3.PNG?raw=true)

  4. Creando un espacio para los recursos globales en nodejs:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/4.PNG?raw=true)

  5. Finalmente, para instalar NestJS se deben ejecutar los comandos:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/5.PNG?raw=true)

**II. Ejecutando el ejemplo Hello World**

  Para esta parte cambie de maquina virtual debido a unos errores que me aparecían, el profesor me ayudo con esto en una asesoría.
   
  1. Para iniciar seleccione o cree una carpeta donde se alojará el proyecto.
  
![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/6.PNG?raw=true)
  
  2. Crear un proyecto NestJS ejecutando el comando nest new, para el nombre del proyecto no usar espacios ni caracteres especiales.
  
![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/7.PNG?raw=true)
  
  3. Es necesario identificar la dirección IP de la máquina.  
  
![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/8.PNG?raw=true)
  
  4. Node utiliza el archivo package.json para definir los scripts que se ejecutan con el comando npm run o yarn run.
  
![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/9.PNG?raw=true)
  
     Para verificar los scripts disponibles.
![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/10.PNG?raw=true)
     
  5. Con lo anterior el servidor nos indica que está listo para recibir peticiones con el metodo GET en la ruta raíz. Por defecto el servidor escucha en el        puerto 3000.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/11.PNG?raw=true)

Luego ya se puede probar el servidor con el comando en otra terminal:

  curl http://localhost:3000
  
La terminal responderá con la siguiente información:

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/12.PNG?raw=true)

**IV. Los verbos HTTP**
  1. Conecte VSCode a la máquina virtual, para esto se debe seleccionar el botón Remote-SSH: Connect to Host... en la sección Remote Explorer.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/14.PNG?raw=true)

  2. Comprobación funcionamiento del servidor.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/15.PNG?raw=true)

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/16.PNG?raw=true)

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/17.PNG?raw=true)

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/18.PNG?raw=true)

*PUNTO 8*

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/19.PNG?raw=true)

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_02/Imagenes/20.PNG?raw=true)

 Implementación de los verbos HTTP y comprobación con el programa postman

 Nombre completo: Sergio Eduardo Erazo Ortega.
 Nombre de la asignatura: Electiva Desarrollo de Software - Web Semántica loT
 Fecha de realización: 1/12/2022
 Link del repositorio del servidor: 

