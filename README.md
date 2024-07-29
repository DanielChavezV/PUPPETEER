# #**Proyecto de Automatización de Pruebas con Puppeteer**

Este repositorio contiene el proyecto final del Curso Avanzado de Automatización de Pruebas con Puppeteer. En este proyecto, se implementaron diversas pruebas automatizadas utilizando Puppeteer para interactuar y validar el comportamiento de una aplicación web en diferentes escenarios.

## **Tabla de Contenidos**
- Introducción
- Requisitos Previos
- Instalación
- Uso
- Ejecución de Pruebas
- Estructura del Proyecto
- Contribuciones
- Licencia

## Introducción

Este proyecto está diseñado para demostrar las capacidades avanzadas de Puppeteer en la automatización de pruebas de aplicaciones web. Incluye casos de prueba que cubren la navegación, la interacción con formularios, la captura de pantallas, la emulación de dispositivos, la geolocalización, y más.

### Requisitos Previos

Antes de comenzar, asegúrate de tener lo siguiente:

- Node.js (versión 10.18.1 o posterior).
- Conocimientos básicos de JavaScript y Node.js.
- npm (generalmente viene con Node.js).

### Instalación
Sigue estos pasos para instalar el proyecto en tu máquina local:

1. Clona el repositorio:

```bash
git clone https://github.com/tuusuario/proyecto-puppeteer-automatizacion.git
cd proyecto-puppeteer-automatizacion

```

### **USO**
Para ejecutar los scripts de Puppeteer, puedes seguir estos pasos:
1. Importa Puppeteer en tu script:

```bash
 	const puppeteer = require('puppeteer');

```
Corre tu script: 

```bash
node tu-script.js
```
### Ejecución de Pruebas
Para ejecutar las pruebas automatizadas, utiliza el siguiente comando:

```bash
npm test
```
### **Estructura del Proyecto**
El proyecto está organizado de la siguiente manera:
```bash
proyecto-puppeteer-automatizacion/
├── tests/                  # Scripts de pruebas automatizadas
│   ├── accesibilidad.test.js
│   ├── capturaDePantalla.test.js
│   ├── emulacionDispositivos.test.js
│   ├── firefox.test.js
│   ├── geolocalizacion.test.js
│   └── modoIncognito.test.js
├── utils/                  # Utilidades y funciones de soporte
│   └── helper.js
├── screenshots/            # Capturas de pantalla tomadas durante las pruebas
│   └── ...
├── package.json            # Dependencias y scripts del proyecto
└── README.md               # Este archivo
```

### **Descripción de las Pruebas**
- accesibilidad.test.js: Pruebas de accesibilidad utilizando AxePuppeteer para analizar y reportar problemas de accesibilidad en la web.

- capturaDePantalla.test.js: Captura de pantallas completas, seleccionadas y con fondo omitido de una página web.

- emulacionDispositivos.test.js: Emulación de dispositivos móviles, tablets y escritorio para probar la responsividad de la web.

- firefox.test.js: Prueba de navegación y captura de información del título y URL utilizando Firefox con Puppeteer.

- geolocalizacion.test.js: Prueba de cambio de geolocalización y validación de comportamiento de la web en diferentes ubicaciones.

- modoIncognito.test.js: Pruebas en modo incógnito emulando diferentes dispositivos y configuraciones de viewport.

### **Licencia**
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
