# SISPRG
RepoSensor
# Tectijuana
## SENSORES
### Rolando Arellano Munguia 18210453


### Exposicion de Sensores A4988 Stepper Motor Driver Y ESP-01 WiFi Modem
----------------------------------------------------------------------------------------------------------------------------------
![cooltext419182783801920](https://user-images.githubusercontent.com/80436392/190012028-4200ed3c-ac84-479d-b4e8-f517f33f6e4f.png)

----------------------------------------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------------------------------------

## Sensor A4988 Stepper Motor Driver-
----------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/80436392/190012379-924f6bbd-0e15-4232-9e34-afe4b681d783.png)

### El uso de un driver Pololu para el control de un motor paso a paso nos simplifica mucho el trabajo ya que este driver se encarga de generar todas las señales necesarias para su funcionamiento y además nos añade las protecciones necesarias de temperatura y corriente. Otra ventaja que nos proporciona es que solo necesitaremos un par de puertos del micro, en este caso Arduino para controlarlo todo, dejando más puertos libres para otras funciones.

### Este producto es una placa de soporte o una placa de arranque para el controlador del A4988 de Allegro con protección contra sobrecorriente


## Especificaciones Tecnicas

- Voltaje de alimentación-potencia(VMOT): 8V-35V DC (recomendado 12V/24VDC)
- Voltaje de alimentación-control(VDD): 3V-5V DC
- Voltaje de control lógico: 3.3V-5V DC
- Corriente de salida: 1A por bobina (máx. 2A con ventilación)
- 5 resoluciones de pasos: full-step, half-step, 1/4, 1/8 y 1/16
- Salidas : Low RDS (ON)
- Detección de caída de corriente automático
- Rectificación síncrona para una baja disipación de potencia
- UVLO Interno
- Protección de corriente-crossover
- Circuito de protección térmica interno
- Circuito de Falla de Tierra
- Protección de cortocircuito
- Pin-compatible con el Driver DRV8825 


## Ejemplos 

Driver Pololu A4988  ideal para impresoras 3D (RepRap, Prusa, Mendel). Maneja motores Paso a paso de hasta 2 A y microstepping de 1/16.
![imgen](https://moviltronics.com/wp-content/uploads/2020/01/portada-a4988-1-667x445.jpg)

------------------------------------------------------------------------------------------------------------------------------------------------------------

![cooltext419182713989624](https://user-images.githubusercontent.com/80436392/190011712-5ed4c0a0-a6fd-4156-9d0d-b79c1173eafe.png)

## ESP-01 WiFi Modem

### Conectar tus proyectos a internet por WiFi ya no será un problema con la ayuda del Módulo ESP-01. Está basado en el SoC (System on Chip) ESP8266, un chip altamente integrado, diseñado para las necesidades de un mundo conectado. Integra un potente procesador con Arquitectura de 32 bits y conectividad WiFi. Ofrece una completa y autocontenida solución WiFi Networking, permitiéndole trabajar como host de aplicaciones o reducir la carga de WiFi Networking de otro procesador. a nivel de conectividad el modulo puede trabajar en 2 modos: como estación WiFi (WiFi Station) o como Punto de Acceso (Access Point). Al trabajar como estación el módulo se conecta a la red WiFi presente en nuestro hogar. El modo Access Point se usa si queremos crear una red propia en el chip y asi conectarnos directamente. 

### La plataforma ESP8266 permite el desarrollo de aplicaciones en diferentes lenguajes como: Arduino, Lua, MicroPython, C/C++, Scratch. Al trabajar dentro del entorno Arduino podremos utilizar un lenguaje de programación conocido y hacer uso de un IDE sencillo de utilizar, ademas de hacer uso de toda la información sobre proyectos y librerías disponibles en internet. La comunidad de usuarios de Arduino es muy activa y da soporte a plataformas como el ESP8266. Al trabajar con Lua podemos experimentar con un lenguaje interpretado. Dentro de las principales placas de desarrollo o módulos basados en el ESP8266 tenemos: ESP-01, ESP-12E, Wemos D1 mini y NodeMCU v2.

### Especificciones tecnicas
- Voltaje de Alimentación: 3.3V DC
- Voltaje de Entradas/Salidas: 3.3V DC (No usar 5V)
- SoM: ESP-12E (Ai-Thinker)
- SoC: ESP8266 (Espressif)
- CPU: Tensilica Xtensa LX3 (32 bit)
- Frecuencia de Reloj: 80MHz/160MHz
- Instruction RAM: 32KB
- Data RAM: 96KB
- Memoria Flash Externa: 4MB
- Pines Digitales GPIO: 4
- UART: 1
- 802.11 b/g/n
- Wi-Fi Direct (P2P), soft-AP
- Stack de Protocolo TCP/IP integrado
- PLLs, reguladores, DCXO y manejo de poder integrados
- Potencia de salida de +19.5dBm en modo 802.11b
- Corriente de fuga menor a 10uA
- El procesador integrado de 32-bit puede ser utilizado como procesador de aplicación
- SDIO 1.1/2.0, SPI, UART
- STBC, 1×1 MIMO, 2×1 MIMO
- A-MPDU & A-MSDU aggregation & 0.4ms guard interval
- Wake up and transmit packets in < 2ms
- Consumo de potencia Standby < 1.0mW (DTIM3)
- Dimensiones: 25*15 mm
- Peso: 5 gramos

### Conectividad

-SDIO 2.0, SPI, UART
- Empaque QFN de 32-pines
- Integra RF switch, balun, 24dBm PA, DCXO y PMU
- Posee un procesador RISC, memoria en chip e interface para memoria externa
- Procesador MAC/Baseband integrado
- Interface I2S para apliaciones de audio de alta calidad
- Reguladores de voltaje lineales "low-dropout" en chip
- Arquitectura propietaria de generacion de clock "spurious free"
- Módulos WEP, TKIP, AES y WAPI integrados

### Partes el sensor
![image](https://user-images.githubusercontent.com/80436392/191360361-e1e25bdd-d2ce-4dc8-9722-7a5572b24fcc.png)

### Ejemplo de implementacion

![image](https://user-images.githubusercontent.com/80436392/191360531-5ed79a79-77db-44d1-917e-46f6808f9750.png)
### GIF
https://c.tenor.com/K_p22efpBGsAAAAd/adachi-true.gif


