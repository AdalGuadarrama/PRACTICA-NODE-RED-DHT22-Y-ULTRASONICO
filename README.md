# PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO
En este repositorio se muestra cómo programar ESP32 con sensor DHT11, sensor ultrasónico y cómo reflejar los datos obtenidos en el programa Node-RED mediante conexión a internet.
## INTRODUCCION 
Usamos Esp32 en el ambiente de recolección de datos, en esta práctica usaremos el sensor DTH11 para recolectar la temperatura y humedad del ambiente, y el sensor ultrasonico para el registro de distancia. También trabajaremos de forma visual y esquemática la programación gráfica de flujos de información utilizando el programa Node-red, y podremos observar los resultados en la interfaz Node-Red y el programa WOKWI.
### MATERIAL 
* Programa Node-RED
* Programa WOKWI
* Tarjeta ESP 32
* Programa Node-RED
* Sensor HC-SR04
* Sensor DHT11
#### INSTRUCCIONES 
1. Abrimos nuestros programas WOKWI Y NODE-RED
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s0.0.png)
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/u1.png)

2. Abrir la terminal de programación wokwi y colocamos nuestro codigo
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/u2.png)
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/u3.png)

3. Instalamos las librerias de DHT sensor library for ESPx, PubSubClient y ArduinoJson.
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s13.png)

4. Procedemos a hacer la conexion de DHT11 y  el sensor ultrasonico con la ESP32 como se muestra en la siguente imagen.
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/u4.png)

5. Abrimos nuestro programa Node-red y colocamos el bloque de mqtt in.
6. 
