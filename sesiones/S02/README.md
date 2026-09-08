# Sesión 02 · La ventana de contexto: qué es, cuánto dura, cómo aprovecharlo

> **La limitación más importante de Claude, convertida en herramienta. Pre-resumen de intención.**

**Fecha:** Martes 5 agosto 2025  
**Semana:** 1 — Fundamentos  
**Plantilla resultante:** P02 · Pre-intención  
**Duración:** 60 minutos

---

## Concepto central (15 minutos)

La **ventana de contexto** es todo el texto que Claude puede "ver" en una conversación: tus mensajes, sus respuestas, los documentos que pegas. Todo ocupa espacio en esa ventana.

**Lo que tienes que entender:**
- Claude solo puede trabajar con lo que está dentro de la ventana
- Cuando la ventana se llena, el modelo "olvida" el principio de la conversación
- Cuanto antes en la conversación establezcas las instrucciones clave, más sólido el resultado

**La técnica del Pre-resumen de intención:**  
Antes de pegar un documento largo o empezar una tarea compleja, dile a Claude qué va a hacer con esa información. Así activa el filtro correcto desde el principio.

Sin pre-resumen:
> [Pegar documento de 20 páginas] → Claude lo lee "neutralmente"

Con pre-resumen:
> "Voy a pegarte un informe de Swiss Re de 20 páginas sobre el mercado asegurador europeo. Tu tarea será identificar las 3 tendencias más relevantes para las corredurías medianas españolas. Aquí está el documento: [...]"

## Práctica (30 minutos)

### Ejercicio 1 · El pre-resumen en acción
Elige un PDF de mercado que tengas (o usa el texto de cualquier informe):

**Sin pre-resumen:**
```
[Pega 500 palabras de un informe de mercado]
¿Qué conclusiones sacas?
```

**Con pre-resumen:**
```
Voy a compartir contigo un fragmento de [informe]. 
Tu tarea: extraer solo las implicaciones para corredurías 
independientes españolas con volumen menor de 5 MM€. 
Ignora todo lo que no sea directamente relevante para ese perfil.

[Pega el mismo fragmento]
```

Compara la utilidad de las dos respuestas.

### Ejercicio 2 · Gestionar una conversación larga
Cuando una conversación se alarga, usa este recurso:

```
Antes de continuar: resume en tres puntos lo que hemos decidido 
hasta ahora sobre [tema]. Luego seguimos desde ahí.
```

Esto "recarga" el contexto activo sin perder el hilo.

---

## Plantilla P02 · Pre-intención

```
INSTRUCCIÓN INICIAL:
Voy a compartir contigo [tipo de documento / cantidad de texto] sobre [tema].

Tu tarea en esta conversación será:
1. [Tarea principal]
2. [Tarea secundaria si la hay]

El resultado final debe ser [formato] de [extensión aproximada].

Destinatario: [perfil del lector]
Publicación: [medio o uso]

Restricciones desde el inicio:
- Solo usa información del documento adjunto
- Si hay datos numéricos que no estén en el documento, indícalo como "dato no disponible en la fuente"
- [Restricción específica del caso]

¿Entendido? Confirma y espera a que te comparta el documento.
```

**Por qué funciona:** Establece el filtro de atención antes de que Claude lea el documento, no después. Es la diferencia entre un lector que sabe para qué lee y uno que lee sin objetivo.

---

*← [Sesión anterior](../S01/README.md) · [Volver al índice](../../README.md) · [Sesión siguiente](../S03/README.md) →*
