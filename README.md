# BOE GPT 🇪🇸🤖

Asistente inteligente para el Boletín Oficial del Estado (BOE). Este proyecto utiliza la potencia de la IA para hacer que la información oficial sea más accesible, comprensible y útil para todos los ciudadanos.

## 🚀 Presentación
BOE GPT es una herramienta diseñada para interactuar con los datos abiertos del BOE en lenguaje natural. Permite resumir disposiciones, explicar términos jurídicos complejos y realizar búsquedas inteligentes, democratizando el acceso a la normativa vigente.

## 🤝 ¡Contribuye al Proyecto!
¡Este proyecto es de todos! Si quieres ayudar a mejorar las capacidades del asistente, optimizar las consultas o añadir nuevas funcionalidades, eres más que bienvenido.

**¿Cómo participar?**
- Haz un **Fork** del repositorio.
- Implementa tus mejoras o correcciones.
- Envía un **Pull Request** explicando tus cambios.

Valoramos enormemente cualquier aportación, desde pequeñas correcciones en la documentación hasta nuevas integraciones técnicas. ¡Hagamos juntos que el BOE sea más fácil de entender!

## 📄 Documentación y Privacidad
Toda la documentación técnica y las políticas de privacidad necesarias para el GPT Store se encuentran en la carpeta `docs/`.

### Hosting en GitHub Pages
Para publicar la política de privacidad y que sea accesible desde el asistente:
1. Ve a **Settings** > **Pages**.
2. Selecciona **Source**: "Deploy from a branch".
3. Elige la rama principal y la carpeta `/docs`.
4. Haz clic en **Save**.

La URL resultante será la que debas configurar en el panel de GPTs de OpenAI.

## 🛠️ Requisitos y Arquitectura
- **API de Datos Abiertos del BOE**.
- **Especificación OpenAPI** (`openapi.yaml`): Define las acciones que el GPT puede ejecutar de forma autónoma.
- **Base de Conocimiento** (Knowledge Base): El asistente incluye documentos técnicos y legales cargados internamente (en la carpeta `knowledge/`) para enriquecer sus respuestas sin depender siempre de llamadas externas a la API. Esta base incluye:
  - Documentación técnica de las APIs del BOE (Consolidada, Sumario BOE, Sumario BORME).
  - Leyes y normativas fundamentales consolidadas en formato PDF (ej. Constitución Española de 1978, Código Civil, Estatuto de los Trabajadores, etc.) para servir como referencia base rápida y segura.

## 📚 Recursos Externos
- [BOE GPT en OpenAI](https://chatgpt.com/g/g-6998dfaca4d48191b89c53a4ba0233d4-boe-espana) - Enlace oficial del chat.
- [API de Datos Abiertos del BOE](https://www.boe.es/datosabiertos/api/api.php) - Documentación oficial y endpoints.

