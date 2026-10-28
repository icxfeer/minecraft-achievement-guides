# 🏆 Minecraft Bedrock Achievement Guide & Tracker

¡Bienvenido al repositorio oficial de guías y pistas para el **Achievement Book** de Minecraft Bedrock Edition! Este proyecto está diseñado para ofrecer un sistema de pistas dinámico, ultraligero y sincronizado con Xbox, integrado de forma impecable mediante una interfaz flotante estilo libro de rol.

---

## ✨ Características Principales

* **🌐 Base de Datos en la Nube:** Todas las guías de los 133+ logros se cargan instantáneamente desde este repositorio mediante un archivo `guias.json`.
* **🤖 Respaldo Inteligente (Gemini AI):** Si un logro es completamente nuevo (de una actualización reciente) y aún no figura en el archivo JSON, el sistema consulta dinámicamente a la API de Google Gemini Pro para generar una pista precisa al vuelo.
* **⚡ Cero Consumo de RAM:** Diseñado para correr de forma local con Python (`tkinter` / `customtkinter`), garantizando fluidez total sin afectar el rendimiento de tu juego ni de la Xbox API.
* **📖 Interfaz Inmersiva:** Un libro flotante interactivo con flechas de navegación en pixel-art y alterncriptores de guías integrados.

---

## 📂 Estructura del Repositorio

* `guias.json`: Archivo central en formato JSON que contiene el listado completo de los logros oficiales de Minecraft Bedrock traducidos al español y sus respectivas guías de resolución paso a paso.

---

## 🚀 Uso e Integración

Este repositorio funciona como el backend de pistas para la aplicación de escritorio **Achievement Book Tracker**. 
* La aplicación descarga este archivo automáticamente en segundo plano al iniciar.
* Puedes actualizar, añadir o corregir guías directamente editando el archivo `guias.json` aquí en GitHub, y los cambios se reflejarán de inmediato en la app de todos los usuarios sin necesidad de actualizar el ejecutable.

---

## 👨‍💻 Autor
Desarrollado por **icxfeer**. ¡Disfruta completando tus logros al 100%!
