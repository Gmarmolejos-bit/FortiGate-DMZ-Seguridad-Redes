# FortiGate DMZ - Seguridad de Redes

## 🎥 Video demostrativo

**Video:** [Agregar enlace de YouTube o OneDrive]

En el video se muestra el funcionamiento general de la topología y las principales pruebas realizadas para comprobar que las políticas de seguridad están funcionando correctamente.

---

## 📌 Propósito del laboratorio

El objetivo de esta práctica fue crear una infraestructura de red segmentada y segura utilizando FortiGate, VLAN, una zona DMZ y diferentes políticas de acceso.

La idea principal fue separar correctamente la red de usuarios de la red de servidores y controlar qué tipo de comunicación puede existir entre ellas.

También se buscó evitar que los servidores ubicados en la DMZ pudieran comunicarse libremente con la red interna o con Internet. En lugar de darles acceso completo, solo se permitió la comunicación necesaria para las actualizaciones del sistema.

Además, se aplicaron configuraciones básicas de seguridad en el switch para proteger los puertos utilizados por los usuarios y deshabilitar aquellos que no forman parte de la topología.

---

## 🖥️ Topología

La infraestructura utilizada está compuesta por:

- 1 FortiGate
- 1 switch Cisco
- 2 usuarios
- 2 servidores Web
- 1 servidor de Base de Datos
- 1 WebTerm utilizado para la administración
- 1 conexión NAT para representar la salida hacia Internet

Los servidores utilizados fueron:

- **WEB-CAJA**
- **WEB-INVENTARIO**
- **DB-SERVER**

Los usuarios se encuentran separados en:

- **PC1:** VLAN 10
- **PC2:** VLAN 20

El diagrama de la topología se encuentra a
