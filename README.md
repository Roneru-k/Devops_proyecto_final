# Devops_proyecto_final
Proyecto final de devops

# Librería El Saber - Pruebas Automatizadas con Selenium

Este proyecto es una pagina web de una libreria al cual se le implementan pruebas automatizadas para verificar la funcionalidad del sitio web de la **Librería El Saber** utilizando **Selenium WebDriver** y **ExtentReports** con **C#**. 

El objetivo principal es asegurar que las funcionalidades esenciales, como la carga del sitio, la visibilidad y funcionalidad de los enlaces, y la captura de pantalla, funcionen correctamente.

## Características del Proyecto

- **Pruebas Automatizadas**: Validación de los enlaces "Inicio" y "Contacto".
- **Reporte Detallado**: Generación de reportes en formato HTML con capturas de pantalla.
- **Fácil Configuración**: Ejecutable en cualquier entorno con soporte para **.NET** y **Selenium**.
- **Pruebas Visuales**: Captura de pantalla del estado actual del sitio.

---

## Requisitos del Sistema

Antes de ejecutar este proyecto, asegúrate de tener lo siguiente instalado en tu máquina:

### Requisitos de Software

- **Sistema Operativo**: Windows, macOS o Linux.
- **.NET SDK**: [Descargar .NET](https://dotnet.microsoft.com/download)
- **Google Chrome**: Navegador web.
- **ChromeDriver**: Controlador para Google Chrome. Descárgalo desde [ChromeDriver](https://sites.google.com/chromium.org/driver/).
- **Laragon**: Para pruebas en local y conexion a base de datos.

### Subir a un Host
El host utilizado es Infinityfree, crea una cuenta y sigue los pasos para subir la pagina web al host.

### Librerías Necesarias

Instala las siguientes dependencias utilizando **NuGet Package Manager** en **Visual Studio Code**:

```bash
Install-Package Selenium.WebDriver
Install-Package Selenium.Chrome.WebDriver
Install-Package AventStack.ExtentReports


