# Carousel Brief

- Fecha: 2026-09-20
- Tema: WhatsApp Business Tools MCP de Meta
- Slug: whatsapp-business-tools-mcp
- Marca: @jaime_cabadas
- Potencia: 9/10
- Riesgo de repetición: MEDIO; WhatsApp apareció por precios y Meta por Meta One, pero este ángulo nuevo trata onboarding técnico, herramientas MCP y pruebas, no tarifas ni suscripciones.

## Fuentes primarias

- Anuncio oficial de Meta for Developers, 15/09/2026: https://developers.facebook.com/blog/post/2026/09/15/whatsapp-business-messaging-mcp-ai-agent/
- Documentación y referencia oficial: https://developers.facebook.com/documentation/mcp/whatsapp-business-tools-mcp
- Endpoint oficial documentado: https://mcp.facebook.com/whatsapp_business_tools

## Fuentes secundarias

- TechCrunch: https://techcrunch.com/2026/09/15/meta-now-lets-ai-agents-handle-the-boring-parts-of-whatsapp-business-setup/

## Objetivo

Explicar que Meta ha convertido la configuración y prueba de WhatsApp Business Platform en un flujo conversacional para agentes de IA. Evitar el error de presentarlo como un agente que ya atiende autónomamente a clientes o sustituye una integración de producción.

## Ángulo central

Meta deja que una IA configure WhatsApp Business mediante 18 herramientas oficiales, pero configurar no significa operar conversaciones en producción.

## Audiencia

Negocios que usan WhatsApp Business Platform, agencias, integradores, desarrolladores y equipos de automatización que trabajan con Cloud API, plantillas y webhooks.

## Hechos verificados

- Servidor MCP remoto oficial de Meta, en beta y con despliegue gradual.
- Compatible/documentado para Claude, Codex y ChatGPT; el anuncio también menciona Cursor.
- La documentación enumera 18 herramientas con prefijo `whatsapp_biz_`.
- Permite descubrir empresas/cuentas/números, incorporar y verificar teléfonos, registrar Cloud API, administrar plantillas, enviar mensajes de prueba o plantillas aprobadas, configurar webhooks, revisar pagos/verificación y obtener enlace para token de usuario del sistema.
- Usa OAuth de Meta con `business_management`, `whatsapp_business_management` y `whatsapp_business_messaging`.
- Meta comprueba administración de la app, negocio asociado y aceptación de términos; registra invocaciones y exige una persona autenticada para cambios de estado.
- Meta dice expresamente que esta versión es para desarrollo y pruebas, no para envíos de producción a escala.
- No sustituye Cloud API, la aprobación de plantillas, la ventana de 24 horas, la política ni el precio de los mensajes.
- El catálogo documentado no incluye lectura completa de bandeja, resumen de conversaciones ni respuesta autónoma a clientes.

## Dirección visual

- Formato 3:4, crema cálido, tipografía casi negra, terracota y verde WhatsApp como acento protagonista.
- Usar logo oficial de WhatsApp Business/WhatsApp y Meta.
- Usar frames reales del vídeo oficial de Meta: cuatro consolas, listado de herramientas, OAuth/alcance y creación de plantilla.
- Usar logos verificados de OpenAI y Anthropic donde corresponda; Codex se presenta mediante tarjeta de nombre limpia porque no hay un icono oficial fiable en los recursos locales.
- No inventar un logo para WhatsApp Business Tools MCP: usar su nombre oficial.
- Jaime aparece solo en portada y cierre, con poses diferentes y su referencia real.

## Plan de 8 slides

1. Hook: `META ACABA DE DEJAR QUE UNA IA CONFIGURE TU WHATSAPP BUSINESS`. Subtítulo: `Pero configurar no es operar tus conversaciones.`
2. Qué es: `NO ES UN CHATBOT PARA TUS CLIENTES`. Flujo: `TÚ DESCRIBES → LA IA LLAMA HERRAMIENTAS → META EJECUTA`.
3. Antes/después: `DE 4 PANTALLAS A UNA CONVERSACIÓN`. Developer Console, Business Manager, documentación y editor frente a un prompt.
4. Capacidades: `18 HERRAMIENTAS PARA QUITARTE LA BUROCRACIA`. Números, OTP, Cloud API, plantillas, pruebas, webhooks, pagos y verificación.
5. Seguridad: `EL AGENTE NO ENTRA CON LLAVE MAESTRA`. OAuth, permisos, admin, términos, registro y persona autenticada.
6. Límites: `CONFIGURAR WHATSAPP NO ES OPERAR WHATSAPP`. Sin lectura total de bandeja, respuesta autónoma ni producción a escala; no evita reglas y costes.
7. Encaje: `¿QUIÉN LE SACA PARTIDO?`. Agencias, integradores, Cloud API, desarrolladores y equipos de pruebas; beta gradual.
8. Ruta segura: `PROMPT → REVISIÓN → PRUEBA → PRODUCCIÓN`. CTA `COMENTA MCP` para recibir la checklist.

## Mapa de variedad visual

1. Portada con Jaime y gran núcleo WhatsApp/MCP.
2. Puente de tres etapas con logos reales.
3. Comparativa de cuatro consolas frente a conversación, basada en frame oficial.
4. Panel de 18 herramientas y seis categorías, basado en frame oficial.
5. Escudo OAuth y tarjetas de alcance, basado en frame oficial.
6. Barrera visual entre sandbox y producción.
7. Mapa de perfiles y clientes compatibles.
8. Pipeline seguro de cuatro etapas con Jaime señalando la aprobación humana.

## Recurso práctico

`Checklist segura para conectar WhatsApp Business Tools MCP`: requisitos, permisos, prompts de lectura, secuencia de cambios, pruebas de número/plantilla/webhook, límites de producción, revocación y plan de vuelta atrás.

## CTA

`COMENTA MCP`
