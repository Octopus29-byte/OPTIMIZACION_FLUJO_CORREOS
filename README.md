# AIDTC: Asistente Inteligente de Detección de Tareas Críticas

Este proyecto es una implementación práctica de los conceptos de **Cognición Extendida** y **Sistemas de Apoyo Cognitivo**. El objetivo es crear un "órgano auxiliar" digital que libere la carga mental asociada a la gestión de tareas académicas.

## Propósito del Proyecto
Desarrollar un software que funcione como una extensión de los procesos cognitivos (atención y memoria), contribuyendo directamente al apoyo académico en la Licenciatura en Inteligencia Artificial.

## Arquitectura del Sistema
El sistema utiliza un flujo de automatización en **n8n** que conecta diferentes servicios:

1.  **Gmail Trigger:** Monitoreo proactivo de comunicaciones entrantes.
2.  **Google Gemini (IA):** Clasificación semántica del contenido para determinar su relevancia (Importante vs. Irrelevante).
3.  **JavaScript Engine (Code Node):** Procesamiento determinista de fechas y corrección de anclaje temporal.
4.  **Google Calendar:** Externalización de la memoria prospectiva mediante eventos clasificados por colores (Rojo: Exámenes, Amarillo: Tareas, Azul: Eventos).
5.  **Telegram Bot:** Notificación inmediata para reducir la latencia de respuesta del usuario.

<img width="1013" height="359" alt="image" src="https://github.com/user-attachments/assets/2ebafc54-bc40-456e-81d8-d5c63033174b" />


## Fundamentación Teórica
El AIDTC se basa en la premisa de que los procesos cognitivos no se limitan al cerebro, sino que se extienden al entorno mediante herramientas tecnológicas. 

- **Reducción de Carga Cognitiva:** Al delegar el filtrado de "ruido" y la organización de fechas, el estudiante puede dedicar sus recursos mentales al aprendizaje profundo.
- **Acoplamiento Funcional:** El sistema está diseñado para ser confiable y accesible, cumpliendo con los criterios de un sistema cognitivo extendido.

## Instalación y Configuración
1. Importar el archivo `Correos.json` en tu instancia de n8n.
2. Configurar las credenciales para:
   - Gmail API.
   - Google Gemini API.
   - Google Calendar API.
   - Telegram Bot API.
3. Configurar las variables de entorno para el Chat ID de Telegram.

---
*Desarrollado para la materia: Introducción a la Cognición - Licenciatura en Inteligencia Artificial.*
