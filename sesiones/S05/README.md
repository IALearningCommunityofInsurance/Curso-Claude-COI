# Sesión 05 · El framework RTCFR: Rol, Tarea, Contexto, Formato, Restricción

> **La arquitectura de prompt que lo cambia todo. Aplicación inmediata a cinco tareas reales de COI.**

**Fecha:** Viernes 8 agosto 2025 · CIERRE SEMANA 1  
**Semana:** 1 — Fundamentos  
**Plantilla resultante:** P05 · RTCFR  
**Duración:** 60 minutos

---

## Concepto central (15 minutos)

El framework RTCFR es la síntesis de todo lo aprendido en la Semana 1. Cinco componentes que, juntos, producen prompts de calidad editorial publicable.

```
R → ROL          ¿Quién es Claude en esta tarea?
T → TAREA        ¿Qué tiene que hacer exactamente?
C → CONTEXTO     ¿Qué información de fondo necesita?
F → FORMATO      ¿Cómo debe estructurarse la salida?
R → RESTRICCIÓN  ¿Qué no debe hacer o qué límites existen?
```

**Ver el documento completo:** `docs/framework-rtcfr.md`

## Práctica (30 minutos) · Cinco prompts RTCFR para COI

### Prompt RTCFR #1 · Artículo de análisis

```
ROL: Eres analista editorial senior de COI especializado en distribución de seguros.

TAREA: Redacta un artículo de análisis de 700 palabras sobre el futuro de las 
corredurías medianas en España ante la consolidación del sector.

CONTEXTO: Lectores de Insur·Insights: directivos con 10+ años de experiencia. 
El artículo debe aportar perspectiva, no noticias.

FORMATO: Titular (12 palabras máx) + subtítulo + 3 secciones con intertítulos + 
conclusión con pregunta abierta al sector.

RESTRICCIÓN: Sin anglicismos. Sin datos numéricos que no puedas verificar. 
Tono analítico, no alarmista.
```

### Prompt RTCFR #2 · Resumen ejecutivo

```
ROL: Eres sintetizador editorial de informes de mercado asegurador.

TAREA: Resume el documento adjunto en un resumen ejecutivo de tres párrafos.

CONTEXTO: El lector es un CEO de correduría que tiene 3 minutos.

FORMATO: Párrafo 1 (situación) + Párrafo 2 (análisis) + Párrafo 3 (implicación práctica). 
Máximo 200 palabras totales.

RESTRICCIÓN: Solo datos que estén en el documento. Sin opinión propia. Sin jerga técnica innecesaria.

[DOCUMENTO]
```

### Prompt RTCFR #3 · LinkedIn

```
ROL: Eres editor de contenido digital especializado en LinkedIn B2B para el sector asegurador.

TAREA: Transforma el artículo adjunto en un post de LinkedIn de 250 palabras.

CONTEXTO: Audiencia de LinkedIn COI: profesionales del sector asegurador. 
El post debe generar conversación, no solo informar.

FORMATO: Hook de apertura (1-2 líneas impactantes) + desarrollo (3-4 párrafos cortos) + 
cierre con pregunta + 3 hashtags relevantes.

RESTRICCIÓN: El enlace al artículo completo va en los comentarios, no en el cuerpo del post. 
Sin bullet points: prosa fluida.
```

## Entregable de cierre Semana 1

**Tu Biblioteca P01–P05 está completa.** Cinco plantillas operativas que cubren:
- P01: Contexto institucional COI
- P02: Pre-intención para documentos
- P03: Anti-alucinación para datos
- P04: Revisión editorial estructurada
- P05: Framework RTCFR en cinco variantes COI

Guarda las cinco plantillas en `prompts/biblioteca/`.

---

## Plantilla P05 · RTCFR maestro para COI

```
[USAR COMO PLANTILLA BASE — rellenar los corchetes]

ROL:
Eres [cargo/especialidad] con experiencia en [dominio específico].

TAREA:
[Verbo de acción] + [objeto] + [extensión/cantidad] sobre [tema específico].

CONTEXTO:
- Publicación/uso: [Insur·Insights / COI Magazine / informe interno / presentación]
- Lector objetivo: [perfil exacto del lector]
- Propósito del texto: [para qué sirve exactamente]
- Información disponible: [adjunta / en el mensaje / de tu conocimiento]

FORMATO:
[Estructura específica, componente por componente]

RESTRICCIONES:
- [Restricción 1 — la más importante]
- [Restricción 2]
- [Restricción 3 si es necesaria]
```

**Cómo adaptar P05 a cualquier tarea nueva:**

Antes de escribir un prompt, hazte estas cinco preguntas:
1. ¿Qué perfil de Claude necesita esta tarea?
2. ¿Qué quiero exactamente que produzca?
3. ¿Qué contexto necesita para calibrar bien?
4. ¿Cómo quiero que estructure la salida?
5. ¿Qué podría salir mal que debo prevenir?

Las respuestas son tus cinco componentes RTCFR.

---

*← [Sesión anterior](../S04/README.md) · [Volver al índice](../../README.md) · [Sesión siguiente](../S06/README.md) →*
