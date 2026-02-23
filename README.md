🤖 Descripción

Este proyecto implementa un asistente inteligente de WhatsApp utilizando n8n e inteligencia artificial. El sistema responde automáticamente mensajes entrantes, mantiene memoria conversacional y puede ejecutar tareas como cálculos, búsquedas de información y envío de correos electrónicos.

El objetivo es crear un asistente personal automatizado capaz de gestionar solicitudes reales desde WhatsApp.

⚙️ Funcionamiento

El workflow sigue el siguiente flujo:

WhatsApp Trigger

Detecta mensajes entrantes en tiempo real desde WhatsApp Cloud API.

AI Agent

Analiza el mensaje del usuario.

Decide cómo responder según la intención.

Utiliza herramientas disponibles cuando es necesario.

Memoria Conversacional

Guarda el historial reciente del usuario.

Permite conversaciones naturales con contexto.

Herramientas disponibles

Calculator → Resuelve operaciones matemáticas.

Wikipedia → Busca información factual.

Gmail Tool → Envía emails generados por IA.

Respuesta automática

El asistente genera una respuesta con OpenAI.

n8n envía el mensaje automáticamente por WhatsApp.

🧠 Tecnologías utilizadas

n8n

OpenAI (GPT-4o-mini)

WhatsApp Cloud API

LangChain Agents

Gmail API

Memory Buffer (context handling)

✨ Características principales

Respuestas automáticas en WhatsApp

Conversaciones con memoria contextual

Uso de herramientas mediante AI Agent

Envío automático de emails

Búsqueda de información en tiempo real

Automatización sin intervención manual

🚀 Casos de uso

Asistente personal automatizado

Atención básica al cliente

Automatización de consultas frecuentes

Gestión rápida de tareas desde WhatsApp

Integración IA + mensajería

🛠️ Requisitos

Cuenta de n8n (local o cloud)

OpenAI API Key

WhatsApp Cloud API configurada

Cuenta de Gmail conectada mediante OAuth2

▶️ Cómo usar

Importar el workflow en n8n.

Configurar credenciales:

OpenAI

WhatsApp API

Gmail OAuth2

Activar el workflow.

Enviar un mensaje al número conectado.

El asistente responderá automáticamente.
