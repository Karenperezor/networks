# 🌐 02 - Modelo OSI y TCP/IP

## 📁 Introducción a los Modelos de Referencia

Los modelos **OSI** y **TCP/IP** describen cómo se comunican los dispositivos en una red. Estos modelos están divididos en **capas**, y cada capa se encarga de funciones específicas dentro del proceso de transmisión de datos.

---

## 🔄 Modelo OSI (Open Systems Interconnection)

Tiene **7 capas**, desde la más cercana al usuario hasta la más cercana al hardware físico.

| Capa | Nombre                | Funciones principales                                  |
|------|-----------------------|--------------------------------------------------------|
| 7    | Aplicación            | Interfaz con el usuario. Correo, navegador, FTP.       |
| 6    | Presentación          | Codificación, cifrado, compresión.                     |
| 5    | Sesión                | Control de sesiones y conexiones.                      |
| 4    | Transporte            | Control de errores, segmentación. Protocolos: TCP, UDP |
| 3    | Red                   | Direccionamiento IP, encaminamiento.                   |
| 2    | Enlace de datos       | Detección de errores, control de tramas (MAC).         |
| 1    | Física                | Transmisión de bits por el medio físico.               |

> 📌 Ejemplo: Al enviar un correo, pasa por todas estas capas hasta llegar al destinatario.

---

## 🛠️ Modelo TCP/IP

Es un modelo práctico y más usado en Internet. Consta de **4 capas** que se mapean al modelo OSI:

| Capa TCP/IP          | Equivalente OSI                      | Función                                               |
|----------------------|--------------------------------------|--------------------------------------------------------|
| Aplicación           | Aplicación + Presentación + Sesión   | Servicios al usuario: HTTP, FTP, DNS, SMTP            |
| Transporte           | Transporte                           | Control de flujo, fiabilidad. Protocolos: TCP, UDP    |
| Internet             | Red                                  | IP, ICMP, direccionamiento y ruteo                    |
| Acceso a red (o Enlace) | Enlace de datos + Física          | Hardware, drivers, interfaces físicas                 |

---

## 📊 Comparación Visual (Resumen)

| OSI                 | TCP/IP          |
|---------------------|------------------|
| 7 - Aplicación       | Aplicación        |
| 6 - Presentación     | Aplicación        |
| 5 - Sesión           | Aplicación        |
| 4 - Transporte        | Transporte        |
| 3 - Red               | Internet          |
| 2 - Enlace de datos   | Acceso a red      |
| 1 - Física            | Acceso a red      |

---

## 🧠 ¿Por qué son importantes?

- 📚 Facilitan la comprensión del funcionamiento de las redes.
- 🧩 Permiten la interoperabilidad entre fabricantes.
- 🧪 Son base para resolución de problemas y configuración de redes.

---

## ⏭️ ¿Qué sigue?

👉 Continuar con: [03_Dispositivos_de_Red](../03_Dispositivos_de_Red/README.md)
