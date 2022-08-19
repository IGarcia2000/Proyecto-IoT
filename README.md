# Security storage
## Justificacion
La realización de este proyecto es inspirado por mantener la segura la identidad de una persona, donde esta pueda ser reflejada en objetos físicos que mantienen un gran valor para el propietario. Mantener almacenados dichos objetos de valor en un lugar seguro puede evitarse de problemas como el robo de identidad (al tratarse de documentos de información personal o tarjetas de banco) y el robo o perdida de objetos de valor (por ejemplo, joyas, fotografías o cualquier otro objeto). Con el uso de tecnologías como identificación biométrica o digital, permite que el usuario sienta mayor seguridad de sus pertenencias considerando que solo se puede acceder por una identificación que él posee.
## Objetivo del proyecto
-> El proyecto espera resolver la conservación y monitoreo de objetos personales
<p>
-> Permitir que el usuario tenga una mayor atención de la seguridad al momento de guardar un objeto de valor
  
## Descrpcion general
El proyecto va dirigido para cualquier tipo de usuario que tenga en mente la protección de sus elementos privados o de valor. La realización del prototipo consta de la utilizacion de tecnologías como el internet de las cosas (IoT por sus siglas en ingles), que permite aumentar la seguridad del producto pudiendo accionarse de la forma que él desee.
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
  

## Prototipo
