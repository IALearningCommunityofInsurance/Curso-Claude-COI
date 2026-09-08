# Sesion 16 - Prompts encadenados: flujos de trabajo que se ejecutan solos

**Fecha:** Martes 26 agosto 2025  
**Semana:** 4 - Automatizacion  
**Plantilla resultante:** P16 - Flujo amplificacion  
**Duracion:** 60 minutos

---

## Concepto central (15 minutos)

Los prompts encadenados son flujos donde la salida de cada paso es la entrada del siguiente.
Permiten construir procesos de trabajo complejos que antes requerían múltiples herramientas o personas.

Los cuatro patrones de encadenamiento para COI:

PATRON 1 - AMPLIFICACION:
Dato bruto -> Analisis -> Articulo -> Adaptaciones
(un dato se convierte en múltiples piezas de contenido)

PATRON 2 - DESTILACION:
Documento largo -> Sección relevante -> Dato clave -> Frase editorial
(lo mucho se convierte en lo esencial)

PATRON 3 - TRANSFORMACION:
Articulo -> Newsletter -> Post LinkedIn -> Hilo Twitter
(un contenido, múltiples formatos)

PATRON 4 - REFINAMIENTO:
Borrador 1 -> Critica -> Borrador 2 -> Pulido final
(mejora iterativa estructurada)

La clave tecnica: al inicio de cada prompt posterior, incluye el output del anterior.

---

## Practica (30 minutos)

Ejercicio: El patron de amplificacion completo

Un dato de mercado -> cuatro piezas de contenido COI

PROMPT 1:
"Dato: [pega un dato de mercado real]
Analiza este dato en profundidad:
- Contexto que lo hace significativo
- Lo que cambia respecto al período anterior
- Las implicaciones para [tipo de actor del mercado]
- La pregunta que abre este dato (no la responde, la formula)"

PROMPT 2:
"Con el análisis anterior como base, escribe un artículo de 700 palabras
para Insur-Insights sobre [el dato]. Aplica el formato RTCFR estándar COI.
El análisis que generaste es tu material base; el artículo debe tener
perspectiva editorial propia, no solo describir el análisis."

PROMPT 3:
"Transforma el artículo en tres formatos adicionales:
A) Resumen ejecutivo (150 palabras)
B) Post LinkedIn (250 palabras, con hook y pregunta de cierre)
C) Punto de agenda para el próximo newsletter semanal (80 palabras)"

PROMPT 4:
"Revisa los cuatro outputs (análisis + artículo + resumen + LinkedIn + newsletter).
¿Hay coherencia de mensajes? ¿Alguno contradice al otro?
¿La tesis es consistente en todos los formatos?
Lista los ajustes necesarios para que el conjunto funcione como campaña coherente."


---

## Reflexion (10 minutos)

Antes de guardar la plantilla, responde:
- Que parte de esta sesion cambio como usas Claude?
- En que tarea real de COI aplicaras esto esta semana?
- Que variante del prompt quieres probar en la proxima sesion?

---

## Plantilla P16 - Flujo amplificacion

```
FLUJO DE AMPLIFICACION COI (P16)

PASO 1 - ANALISIS:
"Dato: [X]. Analiza: contexto / cambio respecto a anterior / implicaciones para [actor] / pregunta que abre"

PASO 2 - ARTICULO:
"Con el análisis anterior como base, articulo de [N] palabras para [publicacion] con estilo COI.
El análisis es material base; el artículo tiene perspectiva editorial propia."

PASO 3 - MULTIFORMATO:
"Transforma en: resumen ejecutivo ([N] palabras) + post LinkedIn ([N] palabras) + nota newsletter ([N] palabras)"

PASO 4 - COHERENCIA:
"Revisa los [N] outputs. ¿Coherencia de tesis? ¿Contradicciones? Lista ajustes necesarios."

Tiempo estimado total: 40-50 minutos
```

Guarda esta plantilla en: prompts/biblioteca/p16-flujo-amplificacion.md

---

*<- Sesion anterior (../S15/README.md) · Volver al indice (../../README.md) · Sesion siguiente (../S17/README.md) ->*
