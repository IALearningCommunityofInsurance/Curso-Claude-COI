# Sesion 19 - Personalizacion avanzada: adaptar Claude a cualquier tarea nueva

**Fecha:** Viernes 29 agosto 2025  
**Semana:** 4 - Automatizacion  
**Plantilla resultante:** P19 - Meta-prompt  
**Duracion:** 60 minutos

---

## Concepto central (15 minutos)

El meta-prompt es la habilidad de usar Claude para generar el prompt correcto
para una tarea nueva. En lugar de construir el RTCFR desde cero cada vez,
le preguntas a Claude cómo preguntarle a Claude.

El marco de tres preguntas para cualquier tarea nueva:
1. ¿Qué quiero conseguir exactamente?
2. ¿Qué necesita saber Claude para hacerlo bien?
3. ¿Cómo quiero que estructure la salida?

Estas tres preguntas son el núcleo del framework RTCFR expresado de forma simple.

Cinco casos de uso nuevos para COI donde aplicar el meta-prompt:
1. Análisis de competencia editorial (¿qué publican otros medios del sector?)
2. Evaluación de propuestas de colaboración
3. Preparación de entrevistas con directivos
4. Análisis de feedback de lectores
5. Planificación de la agenda editorial trimestral

La meta-habilidad: una vez que sabes construir un prompt RTCFR para cualquier tarea,
has desbloqueado el uso real de Claude. No necesitas más plantillas: puedes generar las tuyas.

---

## Practica (30 minutos)

Ejercicio: El meta-prompt en acción

PASO 1 - PIDE A CLAUDE QUE DISEÑE EL PROMPT:
"Necesito hacer lo siguiente con Claude: [describe la tarea nueva en lenguaje natural].
No lo hagas aún. Primero diseña el prompt RTCFR óptimo para esta tarea.
El prompt debe incluir: rol apropiado, tarea clara, contexto necesario,
formato del output y las 2-3 restricciones más importantes."

PASO 2 - REVISA Y AJUSTA:
"El prompt propuesto es bueno en general, pero quiero que ajustes:
- El rol: más específico en [aspecto]
- La restricción 2: añade también [restricción adicional]
- El formato: añade una tabla comparativa al final"

PASO 3 - EJECUTA CON EL PROMPT DISEÑADO:
"Bien, ahora aplica ese prompt para realizar la tarea con esta información: [datos]"

PASO 4 - META-APRENDIZAJE:
"¿Qué hizo este prompt que lo hace más efectivo que uno básico para esta tarea?
Identifica los dos o tres elementos que más impacto tuvieron en el resultado."


---

## Reflexion (10 minutos)

Antes de guardar la plantilla, responde:
- Que parte de esta sesion cambio como usas Claude?
- En que tarea real de COI aplicaras esto esta semana?
- Que variante del prompt quieres probar en la proxima sesion?

---

## Plantilla P19 - Meta-prompt

```
META-PROMPT COI (P19)

PARA CUALQUIER TAREA NUEVA:

PASO 1 - DISEÑO DEL PROMPT:
"Necesito realizar la siguiente tarea: [descripcion en lenguaje natural].
Diseña el prompt RTCFR óptimo. No ejecutes la tarea aún.
El prompt debe incluir: rol / tarea clara / contexto necesario / formato de output / 2-3 restricciones."

PASO 2 - AJUSTE:
"Ajusta el prompt: [lista de modificaciones específicas]"

PASO 3 - EJECUCION:
"Ahora aplica el prompt diseñado con esta información: [datos/material]"

EL MARCO DE 3 PREGUNTAS (antes de cualquier prompt):
1. ¿Qué quiero conseguir exactamente? -> Tarea
2. ¿Qué necesita saber Claude para hacerlo bien? -> Rol + Contexto
3. ¿Cómo quiero que estructure la salida? -> Formato + Restricciones
```

Guarda esta plantilla en: prompts/biblioteca/p19-meta-prompt.md

---

*<- Sesion anterior (../S18/README.md) · Volver al indice (../../README.md) · Sesion siguiente (../S20/README.md) ->*
