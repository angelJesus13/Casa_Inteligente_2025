# Proyecto Casa Inteligente

## 📖 Descripción
Casa Inteligente Automatizada es un sistema de automatización del hogar basado en IoT (Internet de las Cosas), diseñado para mejorar la comodidad, seguridad y eficiencia energética de los usuarios. Integra dispositivos de hardware inteligentes, como luces, electrodomésticos, cerraduras, cámaras de seguridad y sensores, con un backend robusto y un frontend intuitivo. Esto permite a los usuarios controlar y monitorear su hogar de forma remota a través de aplicaciones móviles y web.

---
## 🖥️ Logos
Por definir
---

## 🎯 Objetivo
El objetivo de este proyecto es crear un ecosistema de automatización para el hogar a escala real, que permita a los usuarios:
- **Controlar dispositivos inteligentes:** Como luces, electrodomésticos, cerraduras y sensores, desde cualquier lugar a través de aplicaciones móviles o web.
- **Seguridad mejorada:** Monitoreo en tiempo real mediante cámaras de seguridad, alarmas y sensores de movimiento.
- **Eficiencia energética:** Optimización del uso de energía, programando el encendido/apagado de dispositivos según las necesidades del hogar y el consumo.
- **Alertas inteligentes:** Notificaciones en tiempo real sobre el estado del hogar, por ejemplo, si una puerta quedó abierta, si hay movimiento en áreas restringidas, etc.

---

## 📌 Alcances
### **Características clave:**
- **Automatización de dispositivos:** El sistema controlará dispositivos como luces, termostatos, electrodomésticos y cerraduras. Los dispositivos deberán ser integrados mediante protocolos como Zigbee, Z-Wave, Wi-Fi o Bluetooth.
- **Monitoreo en tiempo real:** Implementación de cámaras de seguridad y sensores de movimiento para monitorear la casa en tiempo real.
- **Interfaz de usuario:** Desarrollo de una plataforma web y móvil intuitiva para interactuar con los dispositivos inteligentes.
- **Alertas y notificaciones:** Sistema de alertas inteligentes para notificar al usuario sobre eventos como cambios de temperatura, apertura de puertas, movimientos no autorizados, etc.
- **Eficiencia energética:** Integración de sistemas para optimizar el consumo energético, como programación de encendido y apagado de luces y electrodomésticos.
- **Escalabilidad:** Posibilidad de expandir el sistema con nuevos dispositivos según las necesidades del usuario.

### **Limitaciones:**
- **Compatibilidad de dispositivos:** No todos los dispositivos inteligentes en el mercado son compatibles entre sí. Será necesario elegir dispositivos que utilicen los mismos estándares de comunicación.
- **Dependencia de la conectividad:** El sistema dependerá de una conexión a Internet estable y de la cobertura de red en el hogar. En áreas rurales o con mala conectividad, esto puede ser un problema.
- **Costo inicial:** Aunque el ahorro energético a largo plazo es significativo, la inversión inicial en dispositivos inteligentes, infraestructura y desarrollo del sistema puede ser alta.
- **Seguridad de datos:** Como el sistema involucrará datos personales y del hogar, es esencial implementar altos estándares de seguridad para proteger la privacidad de los usuarios.

---

## 🛠️ Requerimientos
### **Hardware:**
- **Dispositivos IoT:** Luces inteligentes, electrodomésticos compatibles, termostatos, cerraduras inteligentes, cámaras de seguridad, sensores de movimiento, sensores de puertas/ventanas, etc.
  - **Costo estimado:** Los dispositivos IoT suelen variar en precio dependiendo de la marca y el tipo. Por ejemplo:
    - Luces inteligentes: $10 - $50 por dispositivo.
    - Cerraduras inteligentes: $100 - $250.
    - Sensores de movimiento: $20 - $60 por sensor.
    - Cámaras de seguridad: $50 - $200.
- **Raspberry Pi o servidores:** Para gestionar la comunicación entre dispositivos y el backend.
  - **Costo estimado:** $35 - $150, dependiendo de la capacidad y configuraciones necesarias.
- **Red de comunicaciones:** Módem/router Wi-Fi de alta capacidad, posiblemente repetidores de señal si el hogar es grande.

### **Software:**
- **Backend:** Node.js, Express y MongoDB para la gestión de dispositivos, usuarios y eventos en tiempo real.
  - **Costo estimado:** Dependiendo del enfoque, si se utiliza un servicio en la nube como AWS o Google Cloud, los costos mensuales pueden variar entre $20 y $200 dependiendo del tráfico y los servicios utilizados.
- **Frontend:** React para una experiencia de usuario fluida y atractiva.
  - **Costo estimado:** El desarrollo de una aplicación web y móvil puede llevar de 3 a 6 meses, con un costo de desarrollo que puede oscilar entre $5,000 y $15,000 si se contrata a un equipo profesional.
- **Sistema de notificaciones:** Servicios de envío de notificaciones como Firebase o Twilio.
  - **Costo estimado:** En su mayoría gratuitos hasta ciertos límites, después puede generar costos adicionales.

### **Conectividad y Mantenimiento:**
- **Red de comunicación:** Dependencia de la red Wi-Fi de alta velocidad, con cobertura para todo el hogar.
- **Mantenimiento:** Los dispositivos IoT pueden requerir actualizaciones de firmware y mantenimiento regular. Se debe considerar un servicio de soporte post-venta para los usuarios.
  - **Costo estimado de mantenimiento anual:** Aproximadamente $500 - $1,000 dependiendo de la cantidad de dispositivos y el soporte requerido.

---

## Viabilidad y Consideraciones Finales
- **Viabilidad técnica:** El proyecto es técnicamente viable con los recursos adecuados, pero la complejidad de integrar múltiples dispositivos de diferentes fabricantes puede ser un desafío. Es crucial elegir estándares comunes como Zigbee o Z-Wave, que faciliten la interoperabilidad entre dispositivos.
- **Viabilidad económica:** El costo inicial puede ser alto, especialmente si se requiere una gran cantidad de dispositivos. Sin embargo, los usuarios pueden recuperar su inversión a través de la optimización energética y la seguridad mejorada a largo plazo. Además, si se comercializa como un paquete de soluciones para hogares grandes, el proyecto tiene un buen potencial de rentabilidad.
- **Escalabilidad:** Es importante diseñar el sistema con una arquitectura que permita añadir más dispositivos en el futuro, a medida que los usuarios amplíen sus hogares o sus necesidades cambien.
- **Competencia:** Existen competidores en el mercado (como Amazon Alexa, Google Home, y Apple HomeKit), pero un sistema personalizado con un enfoque en la seguridad, eficiencia energética y un control total podría ofrecer ventajas significativas a ciertos usuarios.

## 👩🏼‍🦯 integrantes

| Rol                | Integrantes asignados                                                                 |
|--------------------|---------------------------------------------------------------------------------------|
| **Líder de Proyecto** | *Por definir*                                                                         |
| **IoT**   | Jesús Domínguez Ramírez, Derek Sesni Carreño, Obed Guzmán Flores                      |
| Conexiones         | José Arturo García González , Adrián Pérez Jiménez, Dulce Yadira Salvador Antonio |
| Backend            | Jesús Domínguez Ramírez, Adrián Pérez Jiménez, Ángel de Jesús Baños Téllez            |
| Front              | Al Farias Leyva , Dulce Yadira Salvador Antonio                             |
| Base de datos      | Obed Guzmán Flores, Derek Sesni Carreño, José Arturo García González           |
| Mano de obra       | *Todos los integrantes*                                                               |
| Documentación      | Ángel de Jesús Baños Téllez                                                           |