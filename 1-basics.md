<h1 align="center">📘 1. Básicos de Redes de Computadoras</h1>

<p align="center">
  <em>Resumen del modelo OSI, arquitectura de red, clasificación y encapsulación de datos.</em>
</p>

---

## 📌 Overview

> 🔹 This section describes the basic concepts, classification, architecture, and data encapsulation processes involved in computer networks.

---

## 🧠 Conceptos Clave

- **Red de computadoras**: Conjunto de dispositivos interconectados que comparten recursos y datos.
- **Clasificación de redes**: Según su alcance o tamaño (LAN, MAN, WAN).
- **Arquitectura de red**: Diseño lógico y físico de la red.
- **Encapsulación de datos**: Proceso de empaquetado de información en capas para su transmisión.

---

## 🧱 Modelo OSI (Open Systems Interconnection)

El modelo OSI se compone de **7 capas**, cada una con funciones específicas que ayudan en la comunicación de datos a través de una red.

| Capa | Nombre | Función principal |
|------|--------|-------------------|
| 7 | Aplicación | Interacción directa con el usuario |
| 6 | Presentación | Formateo y cifrado de datos |
| 5 | Sesión | Gestión de sesiones de comunicación |
| 4 | Transporte | Control de flujo y errores (ej: TCP/UDP) |
| 3 | Red | Enrutamiento de paquetes (ej: IP) |
| 2 | Enlace de datos | Direccionamiento físico y acceso al medio (MAC) |
| 1 | Física | Transmisión de bits por el medio físico |

---

## 🔁 Proceso de Transmisión de Datos

1. **Encapsulación**: Los datos se envuelven con información de cada capa OSI.
2. **Transmisión**: Los datos viajan por la red desde el emisor al receptor.
3. **Desencapsulación**: El receptor va eliminando las capas hasta obtener los datos originales.

```plaintext
Aplicación -> Presentación -> Sesión -> Transporte -> Red -> Enlace de Datos -> Física
