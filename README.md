# Adi Ultimate — proyecto base completo

Este paquete separa Adi en frontend + backend seguro.

## Qué ya está hecho
- UI móvil de Adi
- voz de entrada mediante Web Speech cuando Android/Chrome la ofrece
- voz de salida del dispositivo como fallback
- memoria local con autorización explícita
- modos General, Profesor, Manager, Gaming y Finanzas
- conexión configurable a un backend
- backend Node/Express preparado para OpenAI Responses API
- API key SOLO en backend, nunca en GitHub Pages
- endpoint /health para comprobar el servidor

## Lo que falta configurar
1. Crear/configurar una cuenta de API.
2. Colocar la clave en el backend como variable de entorno.
3. Desplegar el backend en un hosting HTTPS.
4. Poner esa URL en la configuración de Adi.
5. Para voz neuronal en lugar de la voz del teléfono, añadir el endpoint TTS/Realtime y reproducir el audio desde la app.
6. Para "Hey, Adi" en segundo plano y acciones Android, convertir el frontend en app nativa y añadir componentes Android apropiados.

## Importante
NO pongas OPENAI_API_KEY dentro del repositorio público ni dentro de index.html.

La API de Assistants fue retirada el 26 de agosto de 2026; este proyecto usa Responses API para la integración nueva.
