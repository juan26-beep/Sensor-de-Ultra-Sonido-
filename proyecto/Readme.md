# Proyecto final: Radar

## Autores

- _Roger Moreno Giraldo_
- _Juan Felipe _

## Descripción

Este proyecto tiene como objetivo principal aplicar los conocimientos de la asignatura aprendidos en las clases magistrales y las prácticas de laboratorio, para ello se van a utilizar los siguientes actuadores y sensores: Sensor JoyStick, sensor ultrasonido y un servomotor.

## Contenido

1. [Autores](#autores)
2. [Descripción](#descripción)
3. [Marco Teórico](#marco-teórico)
   3.1. [Sensores](#sensores)
   3.1.1. [Sensor de ultrasonido HC-SR04](#sensor-de-ultrasonido-HC-SR04)
   3.2. [Actuadores](#actuadores)
   3.2.3. [Servo Motor SG90](#servo-Motor-SG90)
   3.3. [FPGA](#fpga)
5. [Materiales](#materiales)
6. [Resultados](#resultados)
7. [Análisis de resultados](#Análisisderesultados)
8. [Conclusiones](#conclusiones)
9. [Referecicas bibliográficas.](#Referenciasbibliográficas)

## Marco Teórico.

**1. Sensores.**
Un sensor es un dispositivo o instrumento que detecta y responde a ciertos cambios en su entorno físico. Estos cambios pueden incluir variaciones en temperatura, luz, presión, movimiento, humedad, entre otros. Los sensores convierten estas variaciones en señales eléctricas u ópticas que pueden ser leídas y procesadas por otros dispositivos, como un controlador o una computadora.

- **Sensor de ultrasonido HC-SR04:** El sensor de ultrasonido HC-SR04 es un dispositivo utilizado para medir distancias mediante la emisión y recepción de ondas ultrasónicas. Funciona emitiendo un pulso ultrasónico y  midiendo el tiempo que tarda en rebotar el eco del objeto y regresar al sensor. Con base en el tiempo de retorno del eco, el sensor calcula la distancia que se encuentra el objeto.
- - _**Datasheet Sensor Ultrasonico HC-SR04.**_
  
      Voltaje de Operación: 5V DC
      
      Corriente de reposo: < 2mA
      
      Corriente de trabajo: 15mA
      
      Rango de medición: 2cm a 450cm
      
      Precisión: +- 3mm
      
      Ángulo de apertura: 15°
      
      Frecuencia de ultrasonido: 40KHz
      
      Duración mínima del pulso de disparo TRIG (nivel TTL): 10 μS
      
      Duración del pulso ECO de salida (nivel TTL): 100-25000 μS
      
      Dimensiones: 45*20*15 mm
      
      Tiempo mínimo de espera entre una medida y el inicio de otra 20ms (recomendable 50ms)
**2. Actuadores.**
Dispositivo que recibe energía y la convierte en una salida eléctrica, movimiento, fuerza. Los actuadores pueden ser de tipo lineal o rotativos.

- **Actuadores lineales:** Se caracterizan por mover objetos en línea recta, además de su repetibilidad y precisión de posicionamiento. Se usan para tareas de empuje, tracción, elevación y posicionamiento.
  
- **Servo Motor SG90:** Es un actuador rotativo compuesto por un motor eléctrico de corriente contínua, El SG90 funciona recibe una señal PWM (modulación por ancho de pulso) en su pin de control. Según la duración del pulso, el eje del servo se posicionará en un ángulo específico dentro del rango de 0° a 360° a una frecuencia de 50Hz, de esta forma se determina la dirección y y la posición.
- - _**Datasheet Servo Motor SG90:**_
    
       Voltaje de operación DC: 4.8V a 6V.
    
       Velocidad de operación: 0.12 s/60º (4.8V).
    
       Torque: 1.8 kg*cm (4.8V) y 2.2 Kg*cm (6V).
    
       Piñonería plástica.
    
       Incluye 3 accesorios plásticos y su tornillo de sujeción, 2 tornillos para montaje del servo y cable de conexión con conector.
    
       Conector universal tipo "S" compatible con la mayoría de receptores incluyendo Futaba, JR, GWS, Cirrus, Blue Bird, Blue Arrow, Corona, Berg, Spektrum y Hitec, entre otros.
  
       Longitud del cable: 25 cm.
    
       Dimensiones: 23 mm x 13 mm x 29 mm.
    
       Peso: 9 gr.
  
**3. FPGA**.  La FPGA un circuito integrado digital compuesto por una matriz de bloques lógicos configurables (CLBs) interconectados a través de una red de conmutación programable, lo que permite implementar diversas funciones de hardware de manera simultánea.. Las FPGA se componen de compuertas lógicas AND, OR, memoria RAM Y controladores de reloj, por lo que es idea para el diseño de sistemas embebidos con microprocesadores.
 ![Imagen](Imágenes/fpga.png)

- **Documentación**
A continuación se presentan las epecificaciones del proyecto.

- _**Datasheet Sensor Ultrasonico HC-SR04.**_