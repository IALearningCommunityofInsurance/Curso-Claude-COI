# Sesión 04 · Las fortalezas nativas de Claude aplicadas a COI

> **Qué hace Claude mejor que cualquier otra herramienta. Mapa de casos de uso reales para Insur·Insights.**

**Fecha:** Jueves 7 agosto 2025  
**Semana:** 1 — Fundamentos  
**Plantilla resultante:** P04 · Revisión editorial  
**Duración:** 60 minutos

---

## Concepto central (15 minutos)

Claude no es bueno en todo por igual. Conocer sus fortalezas reales permite usarlo donde multiplica el valor y no depender de él donde puede fallar.

### Las 6 fortalezas nativas de Claude relevantes para COI

**1. Síntesis de texto largo con criterio**  
Leer y resumir un informe de 80 páginas en 10 minutos, extrayendo solo lo relevante para un perfil específico. No cualquier resumen: uno con perspectiva editorial.

**2. Revisión y mejora de texto propio**  
Tomar un borrador y mejorarlo en precisión, claridad, tono y estructura sin perder la voz del autor. Es el asistente editorial más rápido que existe.

**3. Generación de variantes**  
Producir 5 titulares, 3 aperturas, 4 conclusiones para elegir la mejor. La creatividad por variación, no por inspiración.

**4. Reformateado y adaptación de contenido**  
Transformar un artículo en un hilo de LinkedIn, un resumen ejecutivo en una presentación, un dato en un párrafo de análisis. Un contenido, múltiples formatos.

**5. Razonamiento sobre información compleja**  
Dado un conjunto de datos (que tú proporcionas), identificar patrones, contradicciones, implicaciones. El análisis que llevaría horas, en minutos.

**6. Escritura con voz específica**  
Una vez que le muestras ejemplos de cómo escribes (S07), reproduce ese estilo con notable precisión.

## Práctica (30 minutos)

### Ejercicio · El mapa de uso COI

Completa esta tabla para tu caso real:

| Tarea recurrente de COI | ¿Claude la hace bien? | ¿Cómo la usaría? |
|------------------------|----------------------|-----------------|
| Redactar editorial Insur·Insights | ✅ | Borrador + revisión |
| Buscar datos de mercado actuales | ❌ | No; solo analizarlos |
| Sintetizar informe Swiss Re | ✅ | Paste + prompt de síntesis |
| Preparar ponencia APECOSE | ✅ | Estructura + guion |
| Verificar normativa DGS 2025 | ⚠️ | Solo si tenemos el texto |
| Traducir contenido al inglés | ✅ | Con revisión humana |
| Generar ideas para artículos | ✅ | Lluvia de ideas estructurada |

### Prueba en tiempo real

Toma el último artículo que hayas escrito para Insur·Insights y pásale este prompt:

```
Aquí tienes un artículo mío. Analiza:
1. ¿Cuál es la tesis editorial? (en una frase)
2. ¿Qué párrafo es el más fuerte?
3. ¿Qué párrafo es el más débil y por qué?
4. ¿El titular está a la altura del contenido?
5. ¿Qué cambiarías en la conclusión?

[ARTÍCULO]
```

---

## Plantilla P04 · Revisión editorial

```
ROL:
Eres un editor senior con experiencia en medios especializados en sectores financieros 
y aseguradores. Tu criterio editorial es exigente pero constructivo.

TAREA:
Revisa el siguiente texto de Insur·Insights y proporciona un análisis editorial en 
cinco dimensiones.

DIMENSIONES DE ANÁLISIS:
1. TESIS: ¿Cuál es el argumento central? ¿Está claro desde el primer párrafo?
2. ESTRUCTURA: ¿El texto fluye con lógica? ¿Hay párrafos que sobren o falten?
3. TITULAR Y APERTURA: ¿Enganchan? ¿Prometen lo que el texto cumple?
4. DATOS Y ARGUMENTACIÓN: ¿Los datos apoyan la tesis? ¿Hay afirmaciones sin sustento?
5. CONCLUSIÓN: ¿Deja al lector con algo accionable o una perspectiva clara?

FORMATO DE RESPUESTA:
- Para cada dimensión: una valoración (Fuerte / Mejorable / Débil) + una frase de diagnóstico
- Al final: tres cambios concretos y prioritarios
- No reescribas el texto; solo diagnostica

RESTRICCIÓN:
Mantén la voz del autor. No estés de acuerdo con el contenido; evalúa la construcción editorial.

[TEXTO A REVISAR]
```

---

*← [Sesión anterior](../S03/README.md) · [Volver al índice](../../README.md) · [Sesión siguiente](../S05/README.md) →*
