# Framework RTCFR · El método de prompt central del curso

> El framework que unifica todas las sesiones del curso. Aplicarlo convierte cualquier interacción con Claude de conversación casual a operación profesional.

---

## ¿Qué es RTCFR?

Una arquitectura de cinco componentes para construir prompts que producen resultados de calidad editorial publicable. Desarrollada y aplicada en todas las sesiones del curso con casos reales de COI / Insur·Insights / CICA.

```
R  →  ROL          ¿Quién es Claude en esta tarea?
T  →  TAREA        ¿Qué tiene que hacer exactamente?
C  →  CONTEXTO     ¿Qué información de fondo necesita?
F  →  FORMATO      ¿Cómo debe estructurarse la salida?
R  →  RESTRICCIÓN  ¿Qué no debe hacer o qué límites existen?
```

---

## Los cinco componentes explicados

### R — Rol
Define la identidad y especialización de Claude para esta tarea concreta.  
No es decorativo: el rol activa el registro, el tono y el nivel de conocimiento con que Claude responde.

**Ejemplos COI:**
- `"Eres analista editorial senior especializado en el mercado asegurador iberoamericano."`
- `"Actúa como consultor de estrategia digital para corredurías de seguros."`
- `"Eres el editor de Insur·Insights con doce años de experiencia en análisis sectorial."`

**Lo que cambia con el rol:**
- Sin rol → respuesta genérica, tono neutro, nivel medio
- Con rol → terminología sectorial, profundidad analítica, voz editorial específica

---

### T — Tarea
La instrucción de acción. Concreta, medible, sin ambigüedad.

**Fórmula base:** `[Verbo de acción] + [objeto] + [alcance]`

**Ejemplos COI:**
- `"Redacta un artículo de análisis de 800 palabras sobre la concentración del mercado asegurador español."`
- `"Elabora un resumen ejecutivo de tres párrafos de este informe de Swiss Re."`
- `"Identifica las cinco principales tendencias en el texto adjunto y ordénalas por impacto potencial."`

---

### C — Contexto
La información de fondo que Claude necesita para calibrar su respuesta.  
Incluye: quién es el lector, qué sabe ya, en qué publicación aparecerá, qué propósito tiene el texto.

**Ejemplos COI:**
```
"El lector es directivo de correduría española con más de diez años de experiencia.  
El artículo se publica en Insur·Insights, newsletter especializado con 3.000 suscriptores  
en España y Latinoamérica. El tono es analítico pero accesible, sin jerga innecesaria."
```

**Regla práctica:** Si tienes que elegir entre más tarea o más contexto, prioriza el contexto.  
Claude puede inferir la tarea; no puede inventarse el contexto correcto.

---

### F — Formato
La estructura de la salida esperada. Cuánto más preciso, mejor resultado.

**Opciones de formato frecuentes en COI:**

| Tipo de entrega | Especificación de formato |
|----------------|--------------------------|
| Artículo Insur·Insights | Titular (12 palabras máx) + subtítulo + 3 secciones con intertítulos + conclusión operativa |
| Resumen ejecutivo | 3 párrafos: situación / análisis / implicación |
| Informe de mercado | Portada conceptual + 3 secciones analíticas + tabla de datos + conclusiones |
| Newsletter breve | 250 palabras · párrafo de apertura + 3 puntos destacados + llamada a la acción |
| Tabla comparativa | Cabecera + filas por criterio + columna de valoración 1-5 |

---

### R — Restricción
Los límites que definen qué NO debe hacer Claude. Tan importante como la tarea.

**Tipos de restricciones:**

1. **De verificación:** `"Solo usa datos que puedas confirmar. Si hay incertidumbre, indícalo explícitamente."`
2. **De estilo:** `"No uses anglicismos directos. 'Property' → 'seguros de daños'. 'Casualty' → 'seguros de RC'."`
3. **De extensión:** `"Máximo 600 palabras. No rellenes con ejemplos innecesarios."`
4. **De fuente:** `"Basa el análisis solo en los datos del documento adjunto. No añadas información externa."`
5. **De tono:** `"Evita el tono académico. El artículo debe poder leerse en 3 minutos y dejar una conclusión clara."`

---

## Plantilla maestra RTCFR

```
ROL:
Eres [especialidad/cargo/perfil] con experiencia en [dominio].

TAREA:
[Verbo] [objeto] de [extensión/formato] sobre [tema].

CONTEXTO:
- Publicación: [medio/plataforma]
- Lector objetivo: [perfil del lector]
- Propósito: [para qué sirve este texto]
- Información de base: [adjunto / datos inline]

FORMATO:
[Estructura específica de la salida esperada]

RESTRICCIONES:
- [Restricción 1]
- [Restricción 2]
- [Restricción 3]
```

---

## Ejemplo completo aplicado a COI

```
ROL:
Eres analista editorial senior de Community of Insurance, especializado en 
transformación digital del sector asegurador iberoamericano.

TAREA:
Redacta un artículo de análisis de 700 palabras sobre el impacto de la 
inteligencia artificial en la distribución de seguros en España en 2025.

CONTEXTO:
- Publicación: Insur·Insights, newsletter semanal de COI
- Lector objetivo: directivos de corredurías y compañías aseguradoras 
  con más de 10 años de experiencia; nivel de conocimiento: avanzado
- Propósito: análisis que aporte perspectiva propia, no resumen de noticias
- Información base: usa el informe adjunto de ICEA 2025 como fuente principal

FORMATO:
- Titular impactante (máx 12 palabras)
- Subtítulo que complete la idea (máx 20 palabras)
- Párrafo de apertura: dato o afirmación que enganche (80 palabras)
- Sección 1: "La situación" — qué está pasando (200 palabras)
- Sección 2: "Lo que cambia" — implicaciones concretas (200 palabras)
- Sección 3: "La pregunta que nadie hace" — perspectiva editorial propia (150 palabras)
- Conclusión operativa: una sola idea accionable (70 palabras)

RESTRICCIONES:
- No uses anglicismos sin traducción: "InsurTech" → "tecnología aseguradora"
- Evita el tono académico; el artículo debe poder leerse en 3 minutos
- No afirmes datos que no estén en el informe adjunto; si estimas, indícalo
- Sin clichés corporativos: nada de "disrupción", "ecosistema", "hoja de ruta"
```

---

## Evolución del framework en el curso

El framework RTCFR se introduce en la Sesión 05 y se enriquece a lo largo del curso:

| Sesión | Añade al framework |
|--------|-------------------|
| S05 | RTCFR base — los cinco componentes |
| S06 | + Chain of Thought en el componente Tarea |
| S07 | + Few-Shot examples en el componente Contexto |
| S08 | + Proyecto Claude como contenedor permanente del framework |
| S10 | RTCFR + CoT + Few-Shot integrados en prompt maestro |
| S16 | RTCFR encadenado — la salida de un prompt es el Contexto del siguiente |
| S19 | Meta-prompt — generar el propio framework RTCFR para tareas nuevas |

---

## Anti-patrones frecuentes

❌ **Sin rol:** `"Escribe sobre la IA en seguros"` → respuesta genérica  
✅ **Con rol:** `"Eres analista de COI. Escribe..."`

❌ **Tarea vaga:** `"Ayúdame con un informe"` → Claude no sabe qué hacer  
✅ **Tarea concreta:** `"Elabora un informe de tres secciones de 1.500 palabras sobre..."`

❌ **Sin formato:** → Claude elige la estructura que prefiere  
✅ **Con formato:** → La estructura es exactamente la que necesitas publicar

❌ **Sin restricción:** → Claude puede alucinar datos o usar anglicismos  
✅ **Con restricción:** → Los límites protegen la calidad editorial
