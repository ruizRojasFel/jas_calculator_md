<div align="center">

<h1> 🌲 Calculadora JAS </h1>

*Sistema de cubicación de trozos de madera según norma JAS*

[![Demo](https://img.shields.io/badge/Ver_sitio-jascalculatorapp.netlify.app-lightblue)](https://jascalculatorapp.netlify.app) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ruizRojasFel/calculator-jas_md/blob/main/LICENSE)

> ⚠️ **El código fuente de este proyecto es privado.** Este repositorio existe para documentar y presentar el proyecto de manera pública. Para mayor información [pinchar aquí](https://historical-scraper-167.notion.site/Calculator-JAS-APP-3c631ae318578044b70fd0c8613946fc).
</div>

<br>

## Tabla de Contenidos

- [Tabla de Contenidos](#tabla-de-contenidos)
- [Descripción](#descripción)
- [Instalación](#instalación)
  - [En iOS](#en-ios)
  - [En Android](#en-android)
- [Uso](#uso)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Características](#características)
- [Licencia](#licencia)

<br>

## Descripción

**Calculadora JAS** automatiza y digitaliza el proceso de recepción y cálculo volumétrico de trozas de madera para empresa forestal chilena. Reemplaza el método manual de conteo en papel por una solución cliente-servidor (App iOS + API REST), implementando de forma dinámica el estándar de cálculo JAS para mejorar la precisión matemática y la velocidad en terreno.

<br>

## Instalación

Dado que el código fuente es privado, puedes instalar y probar la versión de demostración directamente en tu dispositivo móvil como una **PWA (Progressive Web App)** sin pasar por las tiendas de aplicaciones.

### En iOS
1. Abre el enlace de la demo en **Safari**.
2. Toca el botón **Compartir** (📤) en la barra inferior.
3. Desliza hacia abajo y selecciona ➕ **"Agregar a inicio"**.
4. Confirma tocando **Agregar** en la esquina superior derecha.

### En Android
1. Abre el enlace de la demo en **Google Chrome**.
2. Toca el **menú de opciones** (⋮) en la esquina superior derecha.
3. Selecciona 📱 **"Instalar aplicación"** o ➕ **"Agregar a la pantalla principal"**.
4. Confirma la instalación en la ventana emergente.

> ⚠️ **Almacenamiento y Privacidad:** El historial de recepciones se guarda localmente en la base de datos de tu navegador (IndexedDB). El espacio disponible depende de tu dispositivo (típicamente 50 MB o más). **Los datos son privados y no se sincronizan entre distintos dispositivos.**

<br>

## Uso

Una vez instalada la PWA en tu pantalla de inicio:

1. **Configuración inicial:** Entra a la app y guarda los datos de la empresa, faena y origen para agilizar los ingresos futuros.
2. **Registro de Guía:** Ingresa los datos de cabecera (proveedor, chofer, vehículo, fecha y largo base de la carga).
3. **Conteo en terreno:** Utiliza la interfaz de conteo rápido para sumar trozos por diámetro (números pares del 12 al 60). La app calculará instantáneamente el volumen total en $m^3$ aplicando la fórmula JAS correspondiente al largo.
4. **Generación de documento:** Visualiza el resumen y genera un PDF exportable con el detalle completo de la recepción.

<br>

## Tecnologías Utilizadas

El proyecto completo fue construido con las siguientes tecnologías.

| Categoría    | Tecnología                        |
|--------------|-----------------------------------|
| Frontend     | Swift (iOS Nativo, MVVM)          |
| Backend      | Java 25, Spring Boot (REST API)   |
| Bases Datos  | PostgreSQL (Neon Serverless)      |
| PWA          | Web App Manifest                  |
| Deploy       | Render / Neon                   |

<br>

## Características

| Funcionalidad | Descripción |
|---|---|
| 📐 **Cubicación automática** | Aplica la fórmula JAS según el largo del trozo (< 6 m. o >= 6 m.) |
| 📋 **Registro por diámetro** | Ingresa trozos de 12 a 60 cm con un largo común por recepción |
| 📄 **Exportación PDF** | Genera un documento descargable con el detalle completo de la recepción |
| 🗂️ **Historial con filtros** | Busca recepciones por N° de documento o fecha |
| ⚙️ **Configuración precargada** | Guarda empresa, faena y otros datos para agilizar el ingreso |
| 🔔 **Auto-actualización** | Notifica al usuario cuando hay una nueva versión disponible |
| 📴 **100% offline** | Funciona sin internet después de la primera carga |

<br>

## Licencia

Este proyecto está bajo la licencia [MIT](https://github.com/ruizRojasFel/calculator-jas_md/blob/main/LICENSE).

<br>

---

<div align="center">

<h2> Developer </h2>

<h3> Felipe Andrés Ruiz Rojas </h3>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-linkedin.com%2Fin%2Fruizrojasfel-blue)](https://www.linkedin.com/in/ruizrojasfel) [![Website](https://img.shields.io/badge/Website-felruiz--dev.netlify.app-lightblue)](https://felruiz-dev.netlify.app/)

Copyright © 2026 Fel Ruiz
</div>
