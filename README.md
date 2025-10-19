# 💻 TPI: Virtualización con Máquinas Virtuales y Ejecución de Código Python ✨

## 🛠️ Tecnologías y Herramientas Utilizadas
Este proyecto se centró en configurar un ambiente de trabajo estandarizado y aislado utilizando la virtualización de Tipo 2.

| Tecnología | Rol en el Proyecto | Referencia |
| :--- | :--- | :--- |
| **Oracle VirtualBox** | *Hipervisor de Tipo 2** (Hosted) para crear y gestionar la VM sobre el sistema operativo anfitrión (Windows 11). |
| **Ubuntu 24.04.3 LTS** | Sistema Operativo Invitado (Guest OS) instalado en la VM[cite: 443, 454].  [cite: 454] |
| **Python3** | Lenguaje de programación utilizado para el caso práctico (análisis de ventas)[cite: 456, 694, 731]. |  |
| **Terminal / Bash** | Utilizado para la gestión del sistema operativo y la ejecución del código[cite: 455, 685, 700, 701, 702, 704]. | [cite: 455] |
| **Nano** | Editor de texto basado en terminal para escribir el código Python[cite: 457, 704]. |  |

---

## 🎯 Objetivos del Proyecto

El objetivo principal fue **diseñar, configurar y poner en funcionamiento una Máquina Virtual (VM)** con un programa escrito en Python. Esto se logró para demostrar una habilidad clave en el mercado laboral de IT: utilizar entornos estandarizados, seguros y homogéneos para el trabajo profesional.

## ⚙️ Proceso de Implementación

Se siguió un proceso detallado de configuración:

1.  **Creación y Configuración de la VM:**
    * Instalación y uso de **Oracle VirtualBox**.
    * Asignación de recursos mínimos para Ubuntu: **2 GB de RAM** y **20 GB** de disco virtual.
2.  **Instalación del Sistema Operativo:**
    * Montaje de la imagen ISO de **Ubuntu 24.04.3 LTS**.
    * Configuración de la instalación desatendida, incluyendo el usuario y la contraseña.
3.  **Configuración del Entorno de Desarrollo (Bash):**
    * Apertura de la Terminal con `Ctrl + Alt + T`.
    * Verificación de `python3`.
    * Creación de la carpeta de trabajo (`mkdir AySO`) y navegación (`cd AySO`).
    * Creación del archivo Python (`touch main.py` y `nano main.py`).

---

## 🐍 Caso Práctico: Programa Python de Análisis de Ventas

El código Python ejecutado en el entorno virtualizado consistió en un script de análisis de datos:

### 🌟 Funcionalidad del Script

El programa toma una **matriz de ventas** (4 ítems x 7 días) y la procesa mediante ciclos `for` anidados para determinar métricas clave:

* **Venta Total por Producto:** Calcula el total vendido para cada uno de los 4 ítems.
* **Día de Mayor Venta:** Identifica el día de la semana con el mayor volumen de ventas.
* **Producto Más Vendido:** Determina cuál de los 4 productos tuvo las mayores ventas totales.

### 🖥️ Resultado de la Ejecución

La ejecución exitosa del programa (`python3 main.py`) dentro de la VM demostró el **correcto funcionamiento del entorno virtualizado**.

---

## 🚀 Conclusiones y Próximos Pasos

El proyecto permitió una inmersión en la **Virtualización de Tipo 2**, entendiendo su funcionamiento (hipervisor), la gestión de recursos y los beneficios de aislamiento y portabilidad.

### 💡 Áreas de Mejora:

Se identificaron alternativas más modernas y eficientes para el futuro:

* **Plataformas en la Nube:** Utilizar soluciones como **Google Cloud Shell** para obtener un ambiente listo para usar sin dividir recursos de la máquina local.
* **Contenedores (Dockerización):** Ahondar en el uso de **Docker** para un manejo más ágil y ligero de los ambientes de ejecución.

---
_Trabajo presentado para la Tecnicatura Universitaria en Programación - UTN_