# 🚀 Portafolio de Automatización e Inteligencia Artificial

Bienvenido a mi repositorio de automatizaciones. Aquí consolido una selección de flujos de trabajo diseñados en **n8n**, demostrando la integración de sistemas híbridos, orquestación de datos complejos y uso de agentes de IA.

> **Nota:** Este repositorio ha sido creado para demostrar capacidades técnicas en el marco de mi postulación como **Analista Sr. de Inteligencia Artificial**.

## 🛠 Stack Tecnológico

![n8n](https://img.shields.io/badge/n8n-Early_Adopter_v2.0-FF6B6B?style=for-the-badge&logo=n8n)
![OpenAI](https://img.shields.io/badge/AI-OpenAI_GPT4-412991?style=for-the-badge&logo=openai)
![Python](https://img.shields.io/badge/Code-Python_%2F_JS-3776AB?style=for-the-badge&logo=python)
![Git](https://img.shields.io/badge/Version-Control-F05032?style=for-the-badge&logo=git)

## 📂 Estructura del Repositorio

Los flujos se encuentran en la carpeta `/workflows` y están optimizados para la arquitectura de **n8n v2.0**.

| Flujo / Workflow | Descripción Técnica | Tags |
| :--- | :--- | :--- |
| Informe Matutino Inteligente (Resumen Ejecutivo) | Ingesta de PDFs vía Webhook, OCR, extracción de entidades con LLM (GPT-4) y guardado estructurado en SQL. | `IA` `OCR` `SQL` |
| Radar de Oportunidades y Fuga (CRM en Tiempo Real) | Sincronización bidireccional de datos con manejo de errores (Error Trigger) y lógica de reintentos automática. | `ETL` `Error Handling` |
| Auditoría de Legajos con IA (Visión Artificial) | Extracción de métricas vía API, transformación con código (Python/JS) y generación de reporte HTML. | `Data` `Python` `Reporting` |

## ⚙️ Mentalidad de Ingeniería & Buenas Prácticas

En estos desarrollos priorizo la estabilidad y la escalabilidad:

1.  **Manejo de Errores (Error Handling):** Uso de nodos específicos (Error Triggers) para capturar fallos, registrar logs y notificar al equipo técnico sin detener la operación completa.
2.  **Seguridad:** Todas las credenciales y API Keys han sido desacopladas de los flujos mediante variables de entorno. Los archivos JSON aquí compartidos están **sanitizados**.
3.  **n8n v2.0:** Los flujos aprovechan las mejoras de rendimiento y la nueva interfaz de anotaciones de la versión 2.0.
4.  **Modularidad:** Diseño flujos modulares (sub-workflows) para facilitar el mantenimiento y la reutilización de lógica.

## 🚀 Cómo utilizar estos flujos

1. Descarga el archivo `.json` de la carpeta `/workflows`.
2. En tu instancia de n8n, ve a **"Import from File"**.
3. Configura tus propias credenciales (Nodos de Credenciales) para los servicios conectados.

---
Desarrollado por Solohaga Fabio - 2025*
https://www.linkedin.com/in/fabio-adrian-solohaga-32b8b3246?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
