<h1 align="center">📘 1. Básicos de Redes de Computadoras</h1>

<p align="center">
  <em>Conceptos fundamentales, clasificación de redes, arquitectura y modelos de referencia OSI e Internet.</em>
</p>

---

## 📌 Overview

> Esta sección describe los conceptos básicos, clasificación, arquitectura y los procesos de encapsulación de datos utilizados en las redes de computadoras.

---

## 🌐 Clasificación de Redes
![Clasificacion de redes](images/wan.png)

| Tipo de red | Alcance aproximado | Descripción |
|-------------|--------------------|-------------|
| **LAN** (Local Area Network) | Hasta 10 km | Red de área local, conecta dispositivos dentro de un edificio o campus. |
| **MAN** (Metropolitan Area Network) | 10 km a 100 km | Red de área metropolitana, conecta varias LANs en una ciudad. |
| **WAN** (Wide Area Network) | Más de 100 km | Red de área amplia, conecta redes a nivel nacional o mundial. |

---

## 🧱 Modelo de Referencia OSI (7 capas)

![Modelo Osci](images/modeloOSCI.png)

| Capa | Nombre | Función principal |
|------|--------|-------------------|
| 7 | Aplicación | Interfaz entre los servicios de red y el usuario. |
| 6 | Presentación | Formato de datos, cifrado/descifrado, compresión. |
| 5 | Sesión | Establece, mantiene y termina sesiones entre aplicaciones. |
| 4 | Transporte | Control de flujo, detección de errores, puertos. |
| 3 | Red | Direccionamiento lógico y selección de ruta. |
| 2 | Enlace de datos | Conexiones lógicas, direccionamiento físico (MAC), corrección de errores. |
| 1 | Física | Transmisión y desconexión de señales físicas. |

---

## 🌐 Modelo de Referencia de Internet (5 capas)

| Capa | Equivalencia OSI | Función |
|------|------------------|---------|
| Aplicación | Capas 5, 6 y 7 | Servicios a la aplicación del usuario |
| Transporte | Capa 4 | Comunicación extremo a extremo |
| Internet | Capa 3 | Direccionamiento IP y enrutamiento |
| Enlace de datos | Capa 2 | Acceso al medio y direccionamiento físico |
| Física | Capa 1 | Transmisión de bits |

---

## 🔄 Proceso de Encapsulación de Datos

![Proceso de encapsulacion](images/encapsulacion.png)

Cuando se transmite información, cada capa del modelo añade su propia cabecera al paquete de datos.  
El proceso se invierte en el receptor (desencapsulación).

```plaintext
Aplicación -> Presentación -> Sesión -> Transporte -> Red -> Enlace de Datos -> Física
