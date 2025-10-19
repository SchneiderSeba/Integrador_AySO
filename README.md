# 💻 TPI: Virtualización con Máquinas Virtuales y Ejecución de Código Python ✨

## 🛠️ Tecnologías y Herramientas Utilizadas
Este proyecto se centró en configurar un ambiente de trabajo estandarizado y aislado utilizando la virtualización de Tipo 2.

| Tecnología | Rol en el Proyecto | Referencia |
| :--- | :--- | :--- |
| **Oracle VirtualBox** | [cite_start]**Hipervisor de Tipo 2** (Hosted) para crear y gestionar la VM sobre el sistema operativo anfitrión (Windows 11)[cite: 442, 443, 444]. [cite_start]| [cite: 443] |
| **Ubuntu 24.04.3 LTS** | [cite_start]Sistema Operativo Invitado (Guest OS) instalado en la VM[cite: 443, 454]. [cite_start]| [cite: 454] |
| **Python3** | [cite_start]Lenguaje de programación utilizado para el caso práctico (análisis de ventas)[cite: 456, 694, 731]. [cite_start]| [cite: 456] |
| **Terminal / Bash** | [cite_start]Utilizado para la gestión del sistema operativo y la ejecución del código[cite: 455, 685, 700, 701, 702, 704]. [cite_start]| [cite: 455] |
| **Nano** | [cite_start]Editor de texto basado en terminal para escribir el código Python[cite: 457, 704]. [cite_start]| [cite: 457] |

---

## 🎯 Objetivos del Proyecto

[cite_start]El objetivo principal fue **diseñar, configurar y poner en funcionamiento una Máquina Virtual (VM)** con un programa escrito en Python[cite: 421]. [cite_start]Esto se logró para demostrar una habilidad clave en el mercado laboral de IT: utilizar entornos estandarizados, seguros y homogéneos para el trabajo profesional[cite: 422, 423].

## ⚙️ Proceso de Implementación

Se siguió un proceso detallado de configuración:

1.  **Creación y Configuración de la VM:**
    * [cite_start]Instalación y uso de **Oracle VirtualBox**[cite: 443].
    * [cite_start]Asignación de recursos mínimos para Ubuntu: **2 GB de RAM** y **20 GB** de disco virtual[cite: 597, 629].
2.  **Instalación del Sistema Operativo:**
    * [cite_start]Montaje de la imagen ISO de **Ubuntu 24.04.3 LTS**[cite: 454, 538].
    * [cite_start]Configuración de la instalación desatendida, incluyendo el usuario y la contraseña[cite: 557].
3.  **Configuración del Entorno de Desarrollo (Bash):**
    * [cite_start]Apertura de la Terminal con `Ctrl + Alt + T`[cite: 685].
    * [cite_start]Verificación de `python3`[cite: 685, 694].
    * [cite_start]Creación de la carpeta de trabajo (`mkdir AySO`) y navegación (`cd AySO`)[cite: 700, 701].
    * [cite_start]Creación del archivo Python (`touch main.py` y `nano main.py`)[cite: 702, 704].

---

## 🐍 Caso Práctico: Programa Python de Análisis de Ventas

El código Python ejecutado en el entorno virtualizado consistió en un script de análisis de datos:

### 🌟 Funcionalidad del Script

[cite_start]El programa toma una **matriz de ventas** (4 ítems x 7 días) y la procesa mediante ciclos `for` anidados para determinar métricas clave[cite: 731]:

* **Venta Total por Producto:** Calcula el total vendido para cada uno de los 4 ítems.
* [cite_start]**Día de Mayor Venta:** Identifica el día de la semana con el mayor volumen de ventas[cite: 731].
* [cite_start]**Producto Más Vendido:** Determina cuál de los 4 productos tuvo las mayores ventas totales[cite: 731].

### 🖥️ Resultado de la Ejecución

[cite_start]La ejecución exitosa del programa (`python3 main.py`) dentro de la VM demostró el **correcto funcionamiento del entorno virtualizado**[cite: 735].

---

## 🚀 Conclusiones y Próximos Pasos

[cite_start]El proyecto permitió una inmersión en la **Virtualización de Tipo 2**, entendiendo su funcionamiento (hipervisor), la gestión de recursos y los beneficios de aislamiento y portabilidad[cite: 737].

### 💡 Áreas de Mejora:

[cite_start]Se identificaron alternativas más modernas y eficientes para el futuro[cite: 737, 738]:

* [cite_start]**Plataformas en la Nube:** Utilizar soluciones como **Google Cloud Shell** para obtener un ambiente listo para usar sin dividir recursos de la máquina local[cite: 737].
* [cite_start]**Contenedores (Dockerización):** Ahondar en el uso de **Docker** para un manejo más ágil y ligero de los ambientes de ejecución[cite: 737].

---
[cite_start]_Trabajo presentado para la Tecnicatura Universitaria en Programación - UTN_[cite: 375].