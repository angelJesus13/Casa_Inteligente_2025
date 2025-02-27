# Proyecto Casa Inteligente

##  Descripción
iHome es un sistema de automatización del hogar basado en IoT (Internet de las Cosas), diseñado para mejorar la comodidad y eficiencia energética de los usuarios. Integra dispositivos de hardware inteligentes, como luces, electrodomésticos, cerraduras y sensores, con un backend robusto y un frontend intuitivo. Esto permite a los usuarios controlar y monitorear su hogar de forma remota a través de aplicaciones móviles y web.

---
## Logos
<p align="center">
  <img src="https://github.com/angelJesus13/Casa_Inteligente_2025/blob/iHome_docs/Assets/iHOME.jpg" width="350">
</p>


Se aceptan sugerencias
---

## Objetivo
El proyecto se desplegará a escala para demostrar su funcionalidad, permitiendo a los usuarios:
- **Controlar dispositivos inteligentes:** Como luces, electrodomésticos, cerraduras y sensores, desde cualquier lugar a través de aplicaciones móviles o web.
- **Seguridad mejorada:** Monitoreo en tiempo real mediante alarmas y sensores de movimiento.
- **Eficiencia energética:** Optimización del uso de energía, programando el encendido/apagado de dispositivos según las necesidades del hogar y el consumo.
---

##  Alcances
### **Características clave:**
- **Automatización de dispositivos:** El sistema controlará dispositivos como luces, electrodomésticos y cerraduras estas incluyen ventanas. Los dispositivos deberán ser integrados mediante protocolos como Wi-Fi o Bluetooth.

- **Monitoreo en tiempo real:** Implementación de sensores de movimiento en la entrada principal, integrados con un foco inteligente que se encenderá al detectar presencia.

- **Interfaz de usuario:** Desarrollo de una plataforma web y móvil intuitiva para interactuar con los dispositivos inteligentes.


- **Eficiencia energética:** Integración de sistemas para optimizar el consumo energético, como programación de encendido y apagado de luces y electrodomésticos.

- **Escalabilidad:** Posibilidad de expandir el sistema con nuevos dispositivos según las necesidades del usuario.

### **Limitaciones:**
- **Compatibilidad de dispositivos:** No todos los dispositivos inteligentes en el mercado son compatibles entre sí. Será necesario elegir dispositivos que utilicen los mismos estándares de comunicación esto con el fin de evitar fallas en el sistema.

- **Dependencia de la conectividad:** El sistema dependerá de una conexión a Internet estable y de la cobertura de red en el hogar. En áreas rurales o con mala conectividad, esto puede ser un problema.

- **Costo inicial:** Aunque el ahorro energético a largo plazo es significativo, la inversión inicial en dispositivos inteligentes, infraestructura y desarrollo del sistema puede ser alta.

- **Seguridad de datos:** Como el sistema involucrará datos personales y del hogar, es esencial implementar altos estándares de seguridad para proteger la privacidad de los usuarios.

---

##  Requerimientos para escalado real
### **Hardware:**
- **Dispositivos IoT:** Luces inteligentes, electrodomésticos compatibles, termostatos, cerraduras inteligentes, cámaras de seguridad, sensores de movimiento, sensores de puertas/ventanas, etc.
  - **Costo estimado:** Los dispositivos IoT suelen variar en precio dependiendo de la marca y el tipo. Por ejemplo:
    - Focos inteligentes: $200 - $800 por unidad.
    - Cerraduras inteligentes: $1,500 - $5,000.
    - Sensores de movimiento: $400 - $500 por sensor.
    - Sensores de niel de agua: $150 - $500 por sensor.
    - Sensores para humedad y temperatura: $100 - $300.
    - Bomba de Agua:  $1,000 - $3,000 esto dependera de la marca y la capacidad de la bomba.
    - Actuadores para ventanas y puertas: $1,500 - $4,000 por unidad.
    - Ventiladores o aires acondicionados: 
      - $800 - $2,500 para ventiladores
      - $6,000 - $15,000 para aires acondicionados
    
- **odulos Wemos D1 Mini:** Para gestionar la comunicación entre dispositivos y el backend.
  -  $99 - $200, dependiendo de la capacidad y configuraciones necesarias.
- **Red de comunicaciones:** Módem/router Wi-Fi de alta capacidad, posiblemente repetidores de señal si el hogar es grande.

Todos los costos especificados en la lista son un aproximado del costo final del despliegue del proyecto, recordando que los costos esta en la moneda nacional (Pesos Méxicanos).

### **Software:**
- **Backend:** Node.js, Express y MongoDB para la gestión de dispositivos, usuarios y eventos en tiempo real.
  - **Costo estimado:** Dependiendo del enfoque, si se utiliza un servicio en la nube como AWS o Google Cloud, los costos mensuales pueden variar entre 100 y 500 dependiendo del tráfico y los servicios utilizados.
- **Frontend:** Angular para una experiencia de usuario fluida y atractiva.
  - **Costo estimado:** El desarrollo de una aplicación web y móvil puede llevar de 3 a 6 meses, con un costo de desarrollo que puede oscilar entre 5,000 y 15,000 si se contrata a un equipo profesional.


### **Conectividad y Mantenimiento:**
- **Red de comunicación:** Dependencia de la red Wi-Fi de alta velocidad, con cobertura para todo el hogar.
- **Mantenimiento:** Los dispositivos IoT pueden requerir actualizaciones de firmware y mantenimiento regular. Se debe considerar un servicio de soporte post-venta para los usuarios.
  - **Costo estimado de mantenimiento anual:** Aproximadamente $500 - $1,000 dependiendo de la cantidad de dispositivos y el soporte requerido.

---

# Viabilidad y Consideraciones Finales  

## Viabilidad técnica  
- El proyecto es técnicamente viable con los recursos adecuados, utilizando módulos **Wemos D1 Mini** como controladores principales. La integración de sensores de nivel de agua, actuadores para ventanas y puertas, iluminación inteligente y control de temperatura requiere una programación eficiente y una infraestructura estable de comunicación inalámbrica. Se recomienda utilizar protocolos como **MQTT** para la comunicación entre dispositivos.  

## Viabilidad económica  
- Aunque el costo inicial puede representar una inversión considerable debido a la cantidad de sensores, actuadores y dispositivos inteligentes necesarios, la optimización del consumo energético y el control automatizado de agua y temperatura pueden generar **ahorros significativos a largo plazo**. Además, la escalabilidad del sistema permite que los usuarios inviertan progresivamente según sus necesidades.  

## Escalabilidad  
- La arquitectura basada en **Wemos D1 Mini** y sensores distribuidos permite expandir el sistema fácilmente, agregando nuevos dispositivos sin necesidad de una reconfiguración mayor. La implementación **modular** facilita la personalización para distintos hogares o necesidades específicas.  

## Competencia  
- Existen soluciones comerciales como **Amazon Alexa, Google Home y Apple HomeKit**, pero un sistema basado en **hardware accesible y open-source** ofrece **flexibilidad y adaptabilidad** sin depender de plataformas propietarias. La personalización en seguridad, eficiencia energética y control específico del hogar brinda una **ventaja competitiva** para usuarios que buscan soluciones más ajustadas a sus necesidades.  


## integrantes

| Rol                | Integrantes asignados                                                                 |
|--------------------|---------------------------------------------------------------------------------------|
| **Líder de Proyecto** | *Por definir*                                                                         |
| **IoT Codificación**   | Jesús Domínguez Ramírez, Derek Sesni Carreño, Obed Guzmán Flores                      |
| **Conexiones de IoT**         | José Arturo García González , Adrián Pérez Jiménez, Dulce Yadira Salvador Antonio |
| **Backend**            | Jesús Domínguez Ramírez, Adrián Pérez Jiménez, Ángel de Jesús Baños Téllez            |
| **Frontend**              | Al Farias Leyva , Dulce Yadira Salvador Antonio                             |
| **Base de datos**      | Obed Guzmán Flores, Derek Sesni Carreño, José Arturo García González           |
| **Mano de obra**       | *Todos los integrantes*                                                               |
| **Documentación**      | Ángel de Jesús Baños Téllez                                                           |