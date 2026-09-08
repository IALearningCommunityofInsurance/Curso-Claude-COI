# Sesion 18 - Gestion del conocimiento COI: notas, sintesis y memoria institucional

**Fecha:** Jueves 28 agosto 2025  
**Semana:** 4 - Automatizacion  
**Plantilla resultante:** P18 - Gestion COI  
**Duracion:** 60 minutos

---

## Concepto central (15 minutos)

El conocimiento que no se captura se pierde. COI genera conocimiento valioso continuamente:
reuniones, entrevistas, lecturas, conversaciones, eventos.

Claude puede actuar como procesador de conocimiento institucional:

1. SINTESIS DE REUNIONES:
   - Notas brutas -> puntos acordados, pendientes, decisiones
   - Distingue entre lo que se dijo y lo que se decidió

2. SINTESIS DE LECTURAS:
   - Artículo/informe -> lo que importa para COI específicamente
   - No un resumen genérico: filtrado por relevancia editorial

3. IDENTIFICACION DE PATRONES:
   - Un mes de contenidos -> tendencias editoriales detectadas
   - Qué temas se están agotando, cuáles emergen

4. BASE DE CONOCIMIENTO:
   - Prompts para construir un repositorio de insights reutilizables
   - La memoria institucional que no depende de la memoria humana

La diferencia con los informes (S14): los informes son para publicar.
La gestión del conocimiento es para operar internamente.

---

## Practica (30 minutos)

Ejercicio: Los tres usos principales

SINTESIS DE REUNION:
"Aqui tienes mis notas brutas de una reunión [tipo].
Estructura la síntesis en:
1. Decisiones tomadas (solo lo que quedó firmado)
2. Temas pendientes con responsable y fecha si se mencionó
3. Ideas que surgieron pero no se decidieron (para seguimiento)
4. Mi valoración: lo más importante de esta reunión en una frase

[NOTAS BRUTAS]"

SINTESIS DE LECTURA:
"He leído [articulo/informe]. Dame:
1. La tesis central (una frase)
2. Los dos o tres datos que son nuevos o sorprendentes
3. Lo que implica específicamente para COI / Insur-Insights
4. Si hay algo que contradiga nuestra visión editorial actual, señálalo
5. Rating de relevancia editorial: Alta / Media / Baja y por qué"

PATRON MENSUAL:
"Aquí tienes los títulos y resúmenes de los [N] artículos que publicamos 
en Insur-Insights este mes:
[LISTA]
Analiza:
- Temas dominantes este mes
- Temas ausentes que deberían estar
- Si hay coherencia de perspectiva editorial o mensajes contradictorios
- Una recomendación para el mes siguiente"


---

## Reflexion (10 minutos)

Antes de guardar la plantilla, responde:
- Que parte de esta sesion cambio como usas Claude?
- En que tarea real de COI aplicaras esto esta semana?
- Que variante del prompt quieres probar en la proxima sesion?

---

## Plantilla P18 - Gestion COI

```
GESTION DEL CONOCIMIENTO COI (P18)

SINTESIS DE REUNION:
"Notas brutas de reunion [tipo/fecha]:
[NOTAS]
Estructura: Decisiones tomadas / Pendientes (responsable + fecha) / Ideas sin decidir / Una frase clave"

SINTESIS DE LECTURA:
"Lectura: [titulo/fuente]. 
Dame: tesis central / datos nuevos o sorprendentes / implicacion para COI / rating de relevancia editorial (Alta/Media/Baja)"

PATRON EDITORIAL MENSUAL:
"Titulos y resumenes de [N] articulos del mes:
[LISTA]
Analiza: temas dominantes / ausentes / coherencia editorial / recomendacion siguiente mes"

REPOSITORIO DE INSIGHT:
"De todo lo que hemos procesado esta semana, formula los tres insights reutilizables 
que debería guardar en la base de conocimiento COI. Formato: titulo del insight + 
descripcion (2 frases) + cuando aplicarlo."

```

Guarda esta plantilla en: prompts/biblioteca/p18-gestion-coi.md

---

*<- Sesion anterior (../S17/README.md) · Volver al indice (../../README.md) · Sesion siguiente (../S19/README.md) ->*
