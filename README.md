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
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/u.30.png)

3. Instalamos las librerias de DHT sensor library for ESPx, PubSubClient y ArduinoJson.
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s13.png)

4. Procedemos a hacer la conexion de DHT11 y  el sensor ultrasonico con la ESP32 como se muestra en la siguente imagen.
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/u4.png)

5. Abrimos nuestro programa Node-red y colocamos el bloque de mqtt in.
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s0.0.png)
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s1.png)

6. Configuramos el bloque con el puerto mqtt con el ip 18.193.219.109 y configuramos.
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s3%20(2).png)

7. Colocamos un segundo bloque con la descrioccion json y lo configuras como en la siguiente imagen.
"[.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s4.png)

8. A continuacion insertamos dos bloques function con el siguiente codigo, uno distinto para cada function.
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s5..png)
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s6.png)
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/U5.png)

9. Despues los bloques Chart y Guage a cada una de las funciones y configuramos respectivamente (TEMPERATURA, HUMEDAD, DISTANCIA).
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s7.png)
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/s8.png)

10. Finalmente la temperatura, humedad y distancia  dando doble click al sensor DHT11 Iniciar junto a nuestro sensor ultrasonico, el simulador en Node-RED dando click izquierdo en el botón Deploy y despues abrir la interfaz.
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/u7.png)
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/u8.png)

### RESULTADOS 
* Visualizamos la interfaz y podremos manilular nuestro resltulados con el programa WOKWI.
* Podras observar los valores dentro del monitor serial y la interfaz como se muestra en las siguentes imagenes.
![.](https://github.com/AdalGuadarrama/PRACTICA-NODE-RED-DHT22-Y-ULTRASONICO/blob/main/u.9.png)

#### CREDITOS
Ing. Guadarrama Lome Adalberto 
