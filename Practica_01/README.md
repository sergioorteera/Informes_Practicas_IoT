# Practica 1
**Por** *Sergio Erazo*

## Desarrollo de la práctica - Evidencia
1. Configuración del entorno: El estudiante deberá configurar su dispositivo de elección para ejecutar una imagen virtualizada de Linux, este será un suministro    importante para el resto de prácticas.
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/1.PNG?raw=true)
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/2.PNG?raw=true)
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/3.PNG?raw=true)
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/4.PNG?raw=true)
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/5.PNG?raw=true)
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/6.PNG?raw=true)
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/7.PNG?raw=true)

2. Instalar docker.
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/8.PNG?raw=true)
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/9.PNG?raw=true)

3. Reconocimiento de herramientas de red: Identificar configuración de red por medio del comando ip e ifconfig. Identificar servicios y puertos ocupados en el      sistema con los comandos ss, netstat y lsof.

   comando ip:
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/ip.PNG?raw=true)
   
   comando ifconfig:
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/ifconfig.PNG?raw=true)
   
   comando ss:
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/ss.PNG?raw=true)
   
   comando netstat:
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/netstat.PNG?raw=true)
   
   comando lsof:
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/lsof.PNG?raw=true)

4. Identificar servicios desplegados: El estudiante deberá identificar 5 servicios diferentes listados por las herramientas de red y determinar a qué              aplicaciones posiblemente están relacionados.
5. Evaluar scripts en Python: Al estudiante se le entregarán scripts en Python para desplegar un ejemplo de cliente servidor con protocolos TCP y UDP, el        estudiante evaluará el rendimiento de los dos servicios y debe descubrir la ocupación de los puertos por medio de las herramientas previamente                estudiadas.
   
   ## Servidor TCP:
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/Servidor_tcp.PNG?raw=true)
   
   Ocupación del puerto:
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/servidor_tcp_2.PNG?raw=true)
   
   ## Servidor UDP:
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/servidor_udp.PNG?raw=true)
   
   Ocupación del puerto:
   
   ![Imagen](https://github.com/sergioorteera/Informes_Practicas_IoT/blob/main/Practica_01/Imagenes/servidor_udp2.PNG?raw=true)
   
   
   TCP: Es un protocolo de internet estándar para la transmisión de datos el cual utiliza validaciones es decir que cuando se envía un mensaje, es necesario      que se reciba otro mensaje de confirmación.
   
   UDP: Es un protocolo para streams, este protocolo no usa validaciones, simplemente alguien puede estar recibiendo el stream de datos o no.
   
   El uso de estos protocolos depende del contexto en el cual se vayan a usar.
   
   
   
   
   
   
   
   
   
