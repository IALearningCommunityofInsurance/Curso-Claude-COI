# Sesion 11 - Analisis de documentos largos: PDFs, informes y el arte de preguntar bien

**Fecha:** Martes 19 agosto 2025  
**Semana:** 3 - Produccion real  
**Plantilla resultante:** ```
PROTOCOLO ANALISIS DOCUMENTAL COI (P11)

INSTRUCCION INICIAL:
Voy a compartir contigo [tipo de informe] de [fuente] ([año]).

Tu tarea especifica en esta conversacion:
- Perspectiva: [perfil del lector / proposito editorial]
- Extraccion prioritaria: [que tipo de informacion importa mas]
- Restriccion: solo usa datos del documento; si estimas, marcalo como [estimacion]
- Alerta de contradiccion: si detectas inconsistencias internas en el informe, señalalas

[DOCUMENTO]

PRIMER PASO:
Antes de cualquier analisis, dame:
1. El argumento central del informe (una frase)
2. La metodologia y sus limitaciones
3. Los tres datos mas relevantes para [proposito COI]
4. Una señal de alerta si algo parece cuestionable

Luego espera mis preguntas especificas.
```  
**Duracion:** 60 minutos

---

## Concepto central (15 minutos)

La ventana de contexto de Claude permite cargar documentos de hasta ~200.000 tokens.
Eso equivale a cientos de paginas. Pero mas texto no significa mejor analisis.
La clave esta en como preguntas, no en cuanto pones.

**Las 5 estrategias de analisis documental:**

1. **Extraction selectiva:** No pidas "resume el documento". Pide "extrae los datos sobre [X especifico]"
2. **Perspectiva definida:** "Analiza este informe desde la perspectiva de una correduria mediana española"
3. **Contraste dirigido:** "Compara la seccion 3 de este informe con lo que decia el informe de 2023"
4. **Interrogatorio de datos:** "Encuentra las tres afirmaciones mas sorprendentes y evalua si estan bien sustentadas"
5. **Accionabilidad:** "De todo este informe, que implica concretamente para Insur-Insights esta semana"

**Fuentes habituales en COI:**
- Swiss Re Sigma (macrotendencias globales)
- MAPFRE Economics (mercados iberoamericanos)
- ICEA (estadisticas mercado español)
- Informes anuales de compañias cotizadas
- Resoluciones DGS / CNMV

---

## Practica (30 minutos)

**Ejercicio: El protocolo de 5 pasos**

Toma cualquier informe de mercado que tengas (Swiss Re, ICEA, MAPFRE Economics).
Aplica este protocolo en 5 prompts consecutivos:

```
PASO 1 - ORIENTACION:
"Voy a compartir contigo el informe [nombre]. 
Tu tarea en esta conversacion:
- Extraer implicaciones para correduria mediana española
- Identificar los 3 datos mas relevantes para Insur-Insights
- Señalar cualquier contradiccion interna

Aqui esta el documento: [PEGAR DOCUMENTO]"

PASO 2 - TESIS:
"Con base en este informe, formula la tesis editorial principal 
que defenderia un articulo de analisis. En una sola frase."

PASO 3 - DATOS CLAVE:
"Lista los 5 datos especificos del informe que apoyarian esa tesis.
Indica pagina o seccion de origen para cada uno."

PASO 4 - CONTRAARGUMENTO:
"Ahora juega al abogado del diablo: que datos del mismo informe
podrian contradecir o matizar esa tesis?"

PASO 5 - ARTICULO:
"Con la tesis, los datos y el contraargumento, escribe el articulo 
de 700 palabras para Insur-Insights. Usa el formato P05-RTCFR."
```

---

## Plantilla ```
PROTOCOLO ANALISIS DOCUMENTAL COI (P11)

INSTRUCCION INICIAL:
Voy a compartir contigo [tipo de informe] de [fuente] ([año]).

Tu tarea especifica en esta conversacion:
- Perspectiva: [perfil del lector / proposito editorial]
- Extraccion prioritaria: [que tipo de informacion importa mas]
- Restriccion: solo usa datos del documento; si estimas, marcalo como [estimacion]
- Alerta de contradiccion: si detectas inconsistencias internas en el informe, señalalas

[DOCUMENTO]

PRIMER PASO:
Antes de cualquier analisis, dame:
1. El argumento central del informe (una frase)
2. La metodologia y sus limitaciones
3. Los tres datos mas relevantes para [proposito COI]
4. Una señal de alerta si algo parece cuestionable

Luego espera mis preguntas especificas.
```

```
PROTOCOLO ANALISIS DOCUMENTAL COI (P11)

INSTRUCCION INICIAL:
Voy a compartir contigo [tipo de informe] de [fuente] ([año]).

Tu tarea especifica en esta conversacion:
- Perspectiva: [perfil del lector / proposito editorial]
- Extraccion prioritaria: [que tipo de informacion importa mas]
- Restriccion: solo usa datos del documento; si estimas, marcalo como [estimacion]
- Alerta de contradiccion: si detectas inconsistencias internas en el informe, señalalas

[DOCUMENTO]

PRIMER PASO:
Antes de cualquier analisis, dame:
1. El argumento central del informe (una frase)
2. La metodologia y sus limitaciones
3. Los tres datos mas relevantes para [proposito COI]
4. Una señal de alerta si algo parece cuestionable

Luego espera mis preguntas especificas.
```

---

*<- Sesion anterior (../S10/README.md) · Volver al indice (../../README.md) · Sesion siguiente (../S12/README.md) ->*
