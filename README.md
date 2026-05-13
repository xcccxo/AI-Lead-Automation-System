# AI Lead Automation System

Sistema de automatización inteligente para gestión y clasificación de leads desarrollado con n8n, Google Gemini AI, Google Sheets y Slack.

El proyecto implementa una arquitectura basada en eventos utilizando webhooks para capturar leads en tiempo real desde formularios web. Posteriormente, los datos son analizados mediante inteligencia artificial (Gemini) para evaluar la calidad del lead, asignar un score y clasificarlo automáticamente como “Caliente”, “Tibio” o “Frío”.

Dependiendo de la clasificación obtenida, el sistema ejecuta distintos flujos automatizados:

* Registro de leads en Google Sheets
* Separación automática de spam o leads de baja prioridad
* Notificaciones instantáneas en Slack
* Generación de enlaces dinámicos de contacto vía WhatsApp
* Integración con Calendly para agendamiento de llamadas

## Tecnologías utilizadas

* n8n
* Google Gemini AI API
* Webhooks
* JSON Parsing
* Google Sheets API
* Slack API
* WhatsApp wa.me links
* Calendly

## Funcionalidades principales

* Captura de leads en tiempo real
* Clasificación automática mediante IA
* Lead scoring
* Automatización de workflows
* Routing lógico con nodos IF
* Persistencia de datos
* Notificaciones comerciales automatizadas

## Objetivo del proyecto

Reducir el tiempo de respuesta comercial (“Lead to Speed”) mediante automatización e inteligencia artificial, optimizando la gestión de oportunidades de negocio y el seguimiento de clientes potenciales.

## Arquitectura del sistema

Formulario → Webhook → Gemini AI → JSON Parser → IF Router → Google Sheets / Slack / WhatsApp

## Caso de uso

Desarrollado como solución de automatización comercial para una agencia de marketing y tecnología enfocada en generación y gestión de leads.
