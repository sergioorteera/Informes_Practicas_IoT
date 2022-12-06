# Practica 3
**Por** *Sergio Erazo*

## Desarrollo de la práctica - Evidencia
**I. Arquitectura hexagonal**

   1. Cree una rama llamada hexagonal a partir de master partiendo del código.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_03/Imagenes/1.PNG?raw=true)
    
   2. Modifique el código para que se aplique la arquitectura hexagonal.
 
![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_03/Imagenes/2.PNG?raw=true)
    
   3. Es momento de migrar la funcionalidad implementada en el controlador a un servicio. 

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_03/Imagenes/3.PNG?raw=true)
  
   4. Modificar el controlador player.controller.ts para que se emplee el la implementación del servicio.
   
![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_03/Imagenes/4.PNG?raw=true)
    
**II. Implementado seguridad**

   1. Instalar el paquete @nestjs/passport y passport, que permitirá implementar la autenticación y autorización.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_03/Imagenes/5.PNG?raw=true)

   2. NestJS integra un método para generar módulos rápidamente, primero se creará un módulo para autenticación.

![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_03/Imagenes/6.PNG?raw=true)

   3. Asi mismo se creará un módulo para gestionar usuarios con los comandos:
   
      nest g module users
      
      nest g service users

   4. Enpoint POST del servidor.
   
![imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_03/Imagenes/7.PNG?raw=true)

Link repositorio: https://github.com/sergioorteera/Practica_02_servidor/tree/practica_03_seguridad

**III. Autenticación con JWT**




