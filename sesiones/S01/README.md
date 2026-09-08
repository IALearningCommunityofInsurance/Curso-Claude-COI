# Sesión 01 · Qué es Claude y en qué se diferencia de un buscador

> **El modelo de lenguaje explicado sin tecnicismos. Por qué no es Google y por qué importa saberlo.**

**Fecha:** Lunes 4 agosto 2025  
**Semana:** 1 — Fundamentos  
**Plantilla resultante:** P01 · Contexto COI  
**Duración:** 60 minutos

---

## Concepto central (15 minutos)

Claude es un modelo de lenguaje (LLM) desarrollado por Anthropic. **No es un buscador.** Esta distinción es fundamental:

| Google / Buscadores | Claude |
|--------------------|--------------------|
| Indexa páginas web existentes | Genera texto nuevo en tiempo real |
| Devuelve enlaces a fuentes | Elabora respuestas directas |
| Actualización constante | Conocimiento hasta fecha de entrenamiento |
| Busca información que existe | Razona sobre información que le proporcionas |
| Óptimo para "dónde encontrar X" | Óptimo para "ayúdame a pensar / escribir / analizar X" |

**El punto clave para COI:** Claude no va a buscar el último dato de primas del mercado español. Para eso están Swiss Re, ICEA, MAPFRE Economics. Claude sirve para razonar sobre esos datos una vez que los tienes.

## Conceptos que debes entender antes de seguir

1. **Claude genera texto estadísticamente probable** — no "piensa" como un humano  
2. **No tiene acceso a Internet por defecto** — solo sabe lo que está en su entrenamiento (o lo que tú le das)  
3. **No recuerda conversaciones anteriores** — cada conversación empieza desde cero  
4. **Puede equivocarse** — especialmente con datos numéricos específicos (ver S03)

## Práctica (30 minutos)

### Ejercicio 1 · El experimento de la comparación
Abre Claude.ai y un buscador en paralelo. Haz la misma pregunta a los dos:

> *"¿Cuáles son las tendencias más importantes en la distribución de seguros en España en 2025?"*

Observa:
- ¿Qué devuelve el buscador? (enlaces, fragmentos)
- ¿Qué devuelve Claude? (análisis, razonamiento)
- ¿Cuál es más útil para escribir un artículo de Insur·Insights?

### Ejercicio 2 · Darle contexto vs. no darlo
Prueba estas dos versiones:

**Sin contexto:**
```
¿Qué es una correduría de seguros?
```

**Con contexto:**
```
Soy editor de Insur·Insights, newsletter especializado en seguros iberoamericanos.  
Necesito explicar a un directivo de compañía aseguradora qué diferencia a una  
correduría independiente de un agente vinculado, en tres párrafos directos.
```

Compara los resultados. Esto anticipa el framework RTCFR de la S05.

## Reflexión (10 minutos)

**La pregunta clave:** ¿En qué casos de mi trabajo diario en COI sería Claude claramente mejor que un buscador? ¿En cuáles no lo sustituye?

**Mapa inicial de uso COI:**
- ✅ Redactar artículos de análisis a partir de datos que ya tienes
- ✅ Revisar y mejorar textos existentes
- ✅ Sintetizar informes largos que le pegas en la conversación
- ✅ Preparar guiones de ponencias
- ❌ Buscar el último dato de siniestralidad de 2025
- ❌ Verificar si una compañía ha cambiado sus tarifas esta semana

---

## Plantilla P01 · Contexto COI

La primera plantilla de la Biblioteca. Su función: dar contexto institucional a Claude al inicio de cualquier conversación importante.

```
ROL:
Eres un analista editorial senior especializado en el mercado asegurador 
iberoamericano, con profundo conocimiento de España y América Latina.

CONTEXTO INSTITUCIONAL:
Trabajas con Community of Insurance (COI), fundada en 2011 por Carlos Biurrun 
Murillo. COI publica Insur·Insights, newsletter semanal de referencia en el 
sector asegurador de España y Latinoamérica. Los lectores son directivos de 
corredurías, compañías aseguradoras y organismos supervisores.

ESTILO EDITORIAL COI:
- Analítico y con tesis editorial propia (no neutral)
- Accesible para directivos senior (no académico)
- Sin anglicismos directos: "property" → "seguros de daños", "casualty" → "RC"
- Con datos verificados o explícitamente estimados
- Perspectiva iberoamericana, no solo española

Confirma que has entendido este contexto y estás listo para trabajar.
```

**Cuándo usar P01:**
- Al iniciar una conversación nueva en Claude (fuera del Proyecto COI)
- Cuando necesitas que Claude sepa exactamente para qué publicación escribe
- Como primera instrucción antes de cualquier tarea editorial importante

---

*← [Sesión anterior](../S00/README.md) · [Volver al índice](../../README.md) · [Sesión siguiente](../S02/README.md) →*
