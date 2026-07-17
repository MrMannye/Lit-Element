# Building AI Agents for Software Engineers — Lit & Cells

Material del curso **"Building AI Agents for Software Engineers"**, enfocado en ingenieros de Frontend de BBVA que trabajan con **Lit** y la arquitectura **Cells**. El curso enseña a diseñar, construir e integrar agentes de IA capaces de generar, revisar, refactorizar, probar y documentar componentes Lit de forma automática.

**Portal en vivo:** [lit-cells-agents.vercel.app](https://lit-cells-agents.vercel.app/)

---

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `index.html` | Portal interactivo de práctica: checklist de los 18 laboratorios (Módulos 1-17 + Proyecto Final), prompts reutilizables copiables y un **Prompt Playground** que llama en vivo a la API de Claude. |
| `Modulo_1_Introduccion_AI_Agents.pdf` | Material del facilitador — Módulo 1: Introducción a los AI Agents. |
| `Modulos_2_a_17_y_Proyecto_Final.pdf` | Material del facilitador — Módulos 2 al 17 y el Proyecto Final (AI Cells Software Engineer). |

---

## Sobre el portal (`index.html`)

El portal está construido con **Web Components nativos siguiendo el patrón de LitElement** (Shadow DOM, propiedades reactivas, `render()`, Custom Events entre componentes) — el mismo estilo de arquitectura que enseña el curso — sin dependencias externas ni build step. Es un único archivo HTML autocontenido.

Incluye:

- **Checklist de aceptación** por módulo, con progreso guardado automáticamente.
- **Prompts de referencia** listos para copiar (Módulos 4, 5, 6, 7, 8, 11 y 17).
- **Prompt Playground**: escribe un system prompt + user prompt y ejecútalo contra Claude en vivo, con un modo opcional de *Function Calling* para ver cómo el modelo decide invocar una herramienta (conecta directamente con el Módulo 2 — Arquitectura de un AI Agent).

### Correrlo localmente

No requiere instalación ni dependencias:

```bash
# Opción 1: abrirlo directo
open index.html

# Opción 2: servirlo (recomendado para evitar restricciones de file://)
npx serve .
```

---

## Estructura del curso

1. Introducción a los AI Agents
2. Arquitectura de un AI Agent
3. Lit + Cells Architecture
4. Prompt Engineering para Lit
5. Construcción del primer AI Agent
6. AI Agent para generar componentes Lit
7. Agente para generar componentes Cells
8. AI Agent para Code Review
9. Agente para Refactoring
10. Agente para generar pruebas
11. Agente para documentación
12. AI Agent para Storybook
13. Multi-Agent System
14. Agente conectado a GitHub
15. Agente conectado a Azure DevOps
16. AI Agent con MCP
17. Agente con memoria
18. **Proyecto Final** — AI Cells Software Engineer

---

## Uso

Material de uso interno para el programa de formación de BBVA. Los PDF están pensados como guía del facilitador; el portal es de uso individual para que cada participante practique y lleve su propio progreso durante el curso.
