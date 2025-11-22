# 🎵 SyncFlow - Music Transfer Platform

> **La forma más limpia y sencilla de transferir tus playlists entre Spotify, Apple Music y YouTube Music.**

![Project Status](https://img.shields.io/badge/Status-Prototype-orange) ![License](https://img.shields.io/badge/License-MIT-blue)

SyncFlow es una aplicación web diseñada con una estética minimalista que permite a los usuarios migrar sus bibliotecas musicales entre diferentes servicios de streaming. El proyecto está preparado para monetización mediante **Google AdSense** e incluye un sistema de soporte integrado.

## ✨ Características Principales

* **🎨 Diseño Clean/Minimalista:** Interfaz de usuario basada en "Glassmorphism", tipografía Inter y espacios limpios, optimizada para móviles y escritorio.
* **🔄 Interfaz de Transferencia:** Flujo visual para seleccionar plataforma de origen y destino (Spotify, Apple Music, YouTube, Tidal).
* **📊 Dashboard de Estadísticas:** Sección visual para mostrar al usuario sus artistas y canciones más escuchadas (Top Tracks, Top Artists).
* **💰 Monetización Ready:** Espacios reservados y optimizados para banners de Google AdSense (728x90).
* **📩 Soporte Integrado:** Formulario de contacto funcional listo para conectar con Formspree/EmailJS.

## 🚀 Instalación y Uso

Este proyecto es actualmente un prototipo Frontend funcional. Para visualizarlo:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/TU_USUARIO/SyncFlow.git](https://github.com/TU_USUARIO/SyncFlow.git)
    ```
2.  **Abrir el archivo:**
    Simplemente abre el archivo `index.html` en tu navegador favorito (Chrome, Safari, Edge).

## ⚙️ Configuración para Producción

Para que la aplicación sea 100% funcional en un entorno real, se deben realizar las siguientes integraciones en el código:

### 1. Conexión de APIs (Backend)
El Frontend actual simula la transferencia. Para realizar la migración real de datos, se debe conectar la función `startTransfer()` a un backend (Node.js/Python) que gestione:
* **Spotify Web API:** Autenticación OAuth 2.0.
* **Apple MusicKit JS:** Token de desarrollador.
* **YouTube Data API:** Gestión de playlists.
