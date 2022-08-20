# Security storage
Link al video del proyecto:
https://youtu.be/vJm_1Inp9Sg

## Integrantes
-Christopher Ivan Garcia Avila

-Francisco Álvares Ramírez

-Cesar Guerrero Cruz

## Justificacion
La realización de este proyecto es inspirado por mantener la segura la identidad de una persona, donde esta pueda ser reflejada en objetos físicos que mantienen un gran valor para el propietario. Mantener almacenados dichos objetos de valor en un lugar seguro puede evitarse de problemas como el robo de identidad (al tratarse de documentos de información personal o tarjetas de banco) y el robo o perdida de objetos de valor (por ejemplo, joyas, fotografías o cualquier otro objeto). Con el uso de tecnologías como identificación biométrica o digital, permite que el usuario sienta mayor seguridad de sus pertenencias considerando que solo se puede acceder por una identificación que él posee.
## Objetivo del proyecto
-> El proyecto espera resolver la conservación y monitoreo de objetos personales
<p>
-> Permitir que el usuario tenga una mayor atención de la seguridad al momento de guardar un objeto de valor
  
## Descrpcion general
El proyecto va dirigido para cualquier tipo de usuario que tenga en mente la protección de sus elementos privados o de valor. La realización del prototipo consta de la utilizacion de tecnologías como el internet de las cosas (IoT por sus siglas en ingles), que permite aumentar la seguridad del producto pudiendo accionarse de la forma que él desee.
	
## Software empleado:
°App Inventor 
°Arduino IDE
°Firebase	
	
## Material de uso
  
| Componente | Imagen | Descripcion | Cantidad |
|------------|--------|-------------|----------|
|ESP32| ![image](https://user-images.githubusercontent.com/97042355/177398997-ebb97cb2-ff4b-4a45-98bb-c70f8f9ec271.png)| •	Procesador 32 bits de doble núcleo. *	36 pines GPIO. * 520kb de memoria RAM. *	Bluetooth 4.2 2.4Ghz. *	Wifi integrado *	Frecuencia reloj 240Mhz * Implementado para multiples funciones en aplicación móvil|1|
|Sensor Ultrasónico|![image](https://microside.com/wp-content/uploads/2021/10/Ultrasonico-700x347-1.png)|* Voltaje de alimentación: 5 a 12 VDC * Consumo promedio: 1.5 mA * Rango de distancia: 2cm hasta 200cm ajustable * Angulo de detección: 15°|1|
|Sensor vibración|![image](https://www.e-ika.com/images/thumbs/0004703_sensor-de-vibracion-sw-420_600.jpeg)|* Voltaje de alimentación: 7 a 12 VDC * Voltaje de operación: 5V * Memoria Flash: 32KB * implementado para sistema de alarma anti robo |1|  
|Sensor flama|![image](https://uelectronics.com/wp-content/uploads/2017/06/AR0044-Modulo-KY-026-Sensor-de-Flama-v4-1.jpg)|* Voltaje de operación: 3.3V a 5V * Angulo de detección: 60° * Dimensiones: 40.5 x 20.5 x 17 mm * implementado para dar advertencia de incendio|1|
|Servomotor|![image](https://www.hwlibre.com/wp-content/uploads/2022/03/servo-sg90.jpg)|* Voltaje de operación: 1.5V a 5V * Rango de generación de tonos:  1.5 Hz – 2.5 kHz. * Dimensiones: 18mm x 15mm * implementado para dar advertencia|1|
|Sensor Humo|![image](https://leantec.es/wp-content/uploads/2018/02/p_1_3_8_7_1387-MQ-2-modulo-sensor-detector-humo-y-gas-combustible-Arduino.jpg)|* Voltaje de alimentación: 7 a 12 VDC * Voltaje de operación: 3V - 7V * Torque: 1.8Kg-cm * Angulo de rotación: 180° * Funciona para bloquear la puerta|1| 
|Buzzer|![image](https://www.hwlibre.com/wp-content/uploads/2019/08/buzzer-zumbador.jpg)|* Voltaje de operación: 1.5V a 5V * Rango de generación de tonos:  1.5 Hz – 2.5 kHz. * Dimensiones: 18mm x 15mm * implementado para dar advertencia|1|
  
## Historias de usuario
| Numero | Epica |
|--------|-------|
|1|Yo como trabajador de seguridad quiero un almacén que me permita guardar objetos de valor que además permanezcan seguros y estar al pendiente en todo momento de lo que pasa con mis cosas.|
|2|	Yo como ciudadano quiero un producto inteligente donde se puedan almacenar objetos pequeños donde y estar enterado de su manipulación.|
|3|Yo como gerente de empresa requiero un producto inteligente que me permita mantener documentos importantes con la capacidad de estar notificado a la hora de alguna anomalía dentro de la oficina.|
|4|Yo como padre de familia quiero un equipo inteligente con el que personalmente pueda interactuar y almacenar objetos y se mantengan protegidos contra cualquier persona del hogar.|
|5|Yo como trabajador docente quiero un sistema de almacenamiento que me permita mantener objetos en resguardo y que este pueda bloquearse o desbloquearse de manera sencilla.|
  

## Diseño
![image](https://user-images.githubusercontent.com/97042355/185761473-57fd3725-265e-4c9b-98f1-a0f6ee80dd74.png)

## Registro de las Actividades
		
![image](https://user-images.githubusercontent.com/106643035/185762598-7fc493f7-1197-429f-bd1c-a9ce2c902d83.png)


## Arquitectura: 
El proyecto se compone de la construcción de una caja de madera para asegurar las pertenencias que se almacenen, ademas se integra el circuito para hacer su funcionamiento. Cuenta con actuadores para manipular el bloqueo o desbloqueo de la caja, a su vez, integra sensores que advierten al usuario en caso de que pueda incendiarse la caja
Estos sensores estan conectados a la placa principal ESP32CAM que es alimentada a 5V mediante cable USB. La placa principal permite conexión a internet para mandar o traer datos de los sensores almacenados en una base de datos en tiempo real con Firebase Console, esto en conjunto con la aplicación desarrollada en el software App Inventor, permite al usuario tener una interfaz sencilla y agradable y poder manipular ciertas funcionalidades de la caja gracias a la conexión con Firebase mediante internet
	
## Bloques App Inventor:
| Página | Bloques de código |
|--------|-------------------|
|Página de inicio de sesión |<img width="475" alt="image" src="https://user-images.githubusercontent.com/106187515/185768291-6d39a19d-cdeb-4bb9-b469-3369b972fc32.png">|
|Página de registro de usuarios|<img width="423" alt="image" src="https://user-images.githubusercontent.com/106187515/185768337-e7260f48-064d-4bef-8f4a-ca06203efd34.png">|
|Página principal|<img width="399" alt="image" src="https://user-images.githubusercontent.com/106187515/185768469-041b7df8-e5ad-4e42-85ad-514633bdac4f.png">|
 
## Codigoo Arduino
```	
#include <WiFi.h>
#include <Servo.h>
#include <FirebaseESP32.h>
	
// Provide the token generation process info.
	
#include <addons/TokenHelper.h>

// Provide the SD card interfaces setting and mounting
	
#include <addons/SDHelper.h>

// Provide the RTDB payload printing info and other helper functions.
	
#include <addons/RTDBHelper.h>

#define WIFI_SSID "FrikiLap"
#define WIFI_PASSWORD "123456789"

#define API_KEY "AIzaSyAr5P2YasdxUsXNLYAB3OFG05NU2BFNkJs"

int SensorFlama = 15;
int SensorHumo = 12;

int leds = 16;
Servo servoSeguro;

// ULTRASONICO----------
int pinTrig = 2;
int pinEcho = 14;
unsigned long tiempo, distancia;
// ULTRASONICO----------

#define DATABASE_URL "https://esp32-cam-3f64c-default-rtdb.firebaseio.com/" //<databaseName>.firebaseio.com or <databaseName>.<region>.firebasedatabase.app

// Insert Authorized Email and Corresponding Password
	
#define USER_EMAIL "ninjamexica@gmail.com"
#define USER_PASSWORD "Hakainoh4nt40"

// Insert Firebase storage bucket ID e.g bucket-name.appspot.com
	
#define STORAGE_BUCKET_ID "AIzaSyAr5P2YasdxUsXNLYAB3OFG05NU2BFNkJs"

FirebaseData fbdo;
FirebaseAuth auth;
FirebaseConfig configF;

bool taskCompleted = false;
String puerta="true";

String nodo = "/Sensores";
bool iterar = true;


void setup()
{
  Serial.begin(115200);

  pinMode(pinEcho, INPUT);
  pinMode(pinTrig, OUTPUT);
  pinMode(leds, OUTPUT);

  servoSeguro.attach(4);
  WiFi.begin(WIFI_SSID, WIFI_PASSWORD);
  Serial.print("Conectado al Wifi");
  while (WiFi.status() != WL_CONNECTED)
  {
    Serial.print(".");
    delay(300);
  }


  // Firebase
	
  //  Assign the api key
	
  configF.api_key = API_KEY;
	
  // Assign the user sign in credentials
  auth.user.email = USER_EMAIL;
	
  auth.user.password = USER_PASSWORD;

  configF.database_url = DATABASE_URL;
  // Assign the callback function for the long running token generation task
	
  configF.token_status_callback = tokenStatusCallback; // see addons/TokenHelper.h

  Serial.println("");
  Firebase.begin(&configF, &auth);
  Firebase.reconnectWiFi(true);
  Firebase.setDoubleDigits(5);
  servoSeguro.write(0);

}

void loop()
{
  // while(iterar){
  if (digitalRead(SensorFlama) == LOW)
  {
    Serial.println("Se detecta FLAMA");
    Firebase.setBool(fbdo, nodo + "/sensorFlama", true);
    //servoSeguro.write(0);
  }
  else
  {
    Serial.println("NO se detecta FLAMA");
    Firebase.setBool(fbdo, nodo + "/sensorFlama", false);
    delay(1000);
    //servoSeguro.write(90);
  }
  if (digitalRead(SensorHumo) == HIGH)
  {
    Serial.println("Se detecto HUMO");
    Firebase.setBool(fbdo, nodo + "/sensorHumo", true);
  }
  else
  {
    Serial.println("NO se detecto HUMO");
    Firebase.setBool(fbdo, nodo + "/sensorHumo", false);
    delay(1000);
  }

  digitalWrite(pinTrig, LOW);
  delayMicroseconds(2);

  digitalWrite(pinTrig, HIGH);
  delayMicroseconds(10);
  digitalWrite(pinTrig, LOW);

  tiempo = pulseIn(pinEcho, HIGH);

  distancia = tiempo / 58;

  // imprimir la distancia medida al monitor serial
	
  Serial.print(F("Distancia: "));
  Serial.print(distancia);
  Serial.println(F(" cm"));

  // esperar un segundo antes de realizar otra medición
	
  delay(1000);

  if (distancia > 40)
  {
    Serial.println("La caja esta abierta");
    Firebase.setBool(fbdo, nodo + "/sensorSU", true);
    digitalWrite(leds, HIGH);
  
  }
  else
  {
    Serial.println("La caja NO esta abierta");
    Firebase.setBool(fbdo, nodo + "/sensorSU", false);
    digitalWrite(leds, LOW);         
  }

  Firebase.getString(fbdo, nodo + "/servoC1");
  puerta = fbdo.stringData();
  Serial.println(puerta);

  if(puerta=="true"){
    servoSeguro.write(90);
    }else{
     servoSeguro.write(0);
    }
  

  Serial.println("_____________________________________");
}
```

## Conclusión
El trabajo realizado por los integrantes de este equipo ha sido conforme a los conocimientos adquiridos a lo largo de nuestra estancia en la materia de IoT, estos mismos conocimentos fueron los que a su vez ayudaron a los integrantes a saber que aplicaciones o que usos tiene IoT.
El uso de estas herramientos que proporciona la materia fue el punto principal de un objetivo impuesto por los mismo integrantes sobre una solucion o varias soluciones a problemas cotidianos del ser humano, entender que soluciones practicas podemos aplicar y con que herramientas solucionar dicho problema.

Para la realización de este proyecto pusimos a prueba nustros conocimientos y aplicamos difirentes herramientas informaticas para la conclusion final de nuestra caja. Para dicha caja, el motivo principal fue usar la cantidad correcta de sensores y actuadores y acomodarlos en un entorno donde dependiendo de las necesidades de el cliente, o bien, en este caso las epicas procpuestas por el equipo, cumplamos con los requerimientos y las necesidades solicitadas.

  

