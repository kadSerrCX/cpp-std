# Plan para un agente de contenido AI

## Objetivo
Crear un agente de contenido AI que genere, revise y adapte texto en español para materiales de marketing, documentación técnica y publicaciones en redes sociales. El agente debe ser capaz de:

- Crear contenido alineado con una voz de marca definida.
- Revisar y mejorar contenido existente.
- Adaptar mensajes a diferentes públicos y canales.
- Generar ideas de temas y títulos.

## Componentes

1. Definición de voz y estilo
   - Tono: profesional, cercano y directo.
   - Audiencia: desarrolladores, equipos técnicos y patrocinadores.
   - Formato: claro, conciso y con llamados a la acción cuando proceda.

2. Funcionalidades principales
   - Generación de contenido original:
     - Publicaciones para blog o README.
     - Descripciones de proyectos y casos de uso.
     - Textos para redes sociales.
   - Revisión y edición:
     - Corrección de gramática y estilo.
     - Simplificación de textos complejos.
     - Ajuste de longitud según canal.
   - Localización / adaptación:
     - Generar versiones en español e inglés.
     - Ajustar el mensaje para público técnico vs. general.
   - Brainstorming de ideas:
     - Sugerir titulares.
     - Proponer temas relacionados.

3. Flujo de interacción del agente
   - Entrada: prompt del usuario con contexto y objetivo.
   - Procesamiento:
     - Detectar tipo de contenido deseado.
     - Aplicar plantilla de voz y estructura.
     - Generar una salida con variantes si es necesario.
   - Salida:
     - Texto principal.
     - Opciones alternativas.
     - Resumen breve del enfoque.

## Ejemplo de prompts para el agente

- "Genera un párrafo de presentación para un proyecto de C++ orientado a compilación cruzada y contenedores." 
- "Revisa y mejora este texto técnico para que sea más claro y amigable." 
- "Crea tres ideas de publicaciones para redes sociales sobre soporte de CMake y LLVM en Linux." 

## Implementación sugerida

1. Crear un archivo de configuración o plantilla de agente:
   - `AI-content-agent-plan.md` (plan inicial)
   - `ai-content-agent-instructions.md` (si se integra con un sistema de agentes)
2. Integrar con el servicio AI elegido:
   - ChatGPT API, OpenAI, o cualquier servicio compatible.
3. Construir una interfaz simple:
   - Línea de comandos o script Python/Node.js que genere el contenido.
4. Agregar validación manual:
   - Un paso para revisar y ajustar antes de publicar.

## Próximos pasos

1. Definir formalmente la voz, audiencia y formatos usados en el proyecto.
2. Elegir la plataforma AI y crear prompts base.
3. Implementar un primer prototipo de agente de contenido.
4. Probar con ejemplos reales y refinar el comportamiento.
