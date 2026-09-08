# Sesión 03 · Alucinaciones: por qué Claude inventa y cómo evitarlo

> **El riesgo más crítico para el trabajo editorial. Protocolo anti-alucinación para datos del mercado asegurador.**

**Fecha:** Miércoles 6 agosto 2025  
**Semana:** 1 — Fundamentos  
**Plantilla resultante:** P03 · Anti-alucinación  
**Duración:** 60 minutos

---

## Concepto central (15 minutos)

**Alucinación:** Claude genera información plausible, bien redactada y con aspecto de veracidad, que es falsa.

Ocurre especialmente con:
- Datos numéricos específicos (cuotas de mercado, primas, ratios)
- Nombres de personas (cargos, declaraciones)
- Fechas y estadísticas
- Referencias a estudios o informes ("según el informe X de 2024...")
- Normativa específica (artículos de ley, circulares)

**Por qué ocurre:** Claude predice el siguiente token más probable. Un dato inventado "suena" igual de bien que un dato real.

**La buena noticia:** Es completamente gestionable con el protocolo correcto.

## El Protocolo Anti-Alucinación COI

### Regla 1: No preguntes por datos específicos sin fuente
❌ `"¿Cuál fue el crecimiento de primas del ramo de vida en España en 2024?"`  
✅ `"Según este informe de ICEA [texto adjunto], ¿qué crecimiento de primas registró el ramo de vida?"`

### Regla 2: Instruye sobre la incertidumbre
Añade siempre a tus prompts:
```
Si no tienes certeza sobre un dato, escríbelo como "[estimación]" 
o "[verificar en fuente]", nunca lo presentes como hecho confirmado.
```

### Regla 3: Pide verificabilidad explícita
```
Para cada dato numérico que incluyas, indica la fuente de la que proviene
o marca como "sin fuente verificable" si no puedes atribuirlo.
```

### Regla 4: Nunca uses Claude para "buscar" datos que no tienes
Claude no es una base de datos. Trae los datos tú; Claude los analiza.

### Regla 5: Revisa siempre los datos antes de publicar
Especialmente: cifras de mercado, cuotas, crecimientos, nombres propios y cargos.

## Práctica (30 minutos)

### Ejercicio 1 · Detectar el riesgo
Envía este prompt (sin añadir ningún documento):
```
Dame las cinco principales corredurías de seguros de España por volumen 
de primas intermediadas en 2024, con sus cifras exactas.
```
Observa la respuesta. ¿Es verificable? ¿Ha inventado datos?

### Ejercicio 2 · El protocolo en acción
Ahora envía:
```
No tengo datos de corredurías españolas 2024 disponibles ahora mismo.
Necesito que me ayudes a estructurar un artículo sobre el sector de 
distribución en España que sea analíticamente sólido sin depender de 
datos específicos que no puedo verificar. 

Estructura: análisis de tendencias cualitativas + indicadores de 
dirección (sin cifras exactas) + conclusión editorial.
```
Compara la utilidad y la seguridad de las dos respuestas.

---

## Plantilla P03 · Anti-alucinación

```
INSTRUCCIÓN DE VERIFICACIÓN (añadir a cualquier prompt con datos):

Restricciones de verificación:
- Solo incluye datos que estén explícitamente en el material que te adjunto
- Si mencionas una cifra, indica entre paréntesis la fuente exacta: (Fuente: ICEA 2024, p.12)
- Si un dato no está en el material, escribe: [sin fuente en el material]
- Nunca estimes o aproximes datos numéricos sin marcarlo como [estimación]
- Los nombres de personas y sus cargos deben estar en el material; si no, omítelos

Esta instrucción tiene prioridad sobre cualquier otra indicación de completitud.
```

**Variante para artículos de análisis sin documento adjunto:**
```
Este artículo es de análisis y perspectiva, no de datos. 
No incluyas cifras específicas de mercado a menos que sean 
ampliamente conocidas y verificables (ej: el mercado asegurador 
español supera los 60.000 M€ en primas). 
Para el resto, usa lenguaje de tendencia: "crece", "se consolida", 
"pierde cuota", etc. sin porcentajes inventados.
```

---

*← [Sesión anterior](../S02/README.md) · [Volver al índice](../../README.md) · [Sesión siguiente](../S04/README.md) →*
