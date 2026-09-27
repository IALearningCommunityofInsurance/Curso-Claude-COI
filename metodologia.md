# Metodología del curso · Método Progresivo COI

---

## Principios de diseño

Este curso está construido sobre tres principios que lo diferencian de la formación genérica en IA:

### 1. Entregables reales, no ejercicios hipotéticos
Cada semana termina con algo publicable o directamente utilizable en la operativa de COI. No hay "ejercicios de práctica" desvinculados del trabajo real.

### 2. Progresión acumulativa
Cada sesión se apoya en las anteriores. Las técnicas no son módulos independientes: se integran. Al final del curso, el Prompt Maestro COI incorpora todo lo aprendido.

### 3. Especialización sectorial
Los ejemplos, casos y materiales de práctica son del mercado asegurador iberoamericano. Los prompts hablan de Swiss Re, MAPFRE Economics, ICEA, corredurías, DIC, property, RC. No hay que traducir desde ejemplos de tecnología o marketing.

---

## Estructura de cada sesión (60 minutos)

```
┌─────────────────────────────────────────────────────┐
│  15'  CONCEPTO                                      │
│       Qué es, cómo funciona, por qué importa        │
│       → Explicación sin tecnicismos innecesarios    │
├─────────────────────────────────────────────────────┤
│  30'  PRÁCTICA REAL                                 │
│       Ejercicio con material real de COI            │
│       → El resultado es usable directamente         │
├─────────────────────────────────────────────────────┤
│  10'  REFLEXIÓN Y TÉCNICA AVANZADA                  │
│       Qué has aprendido · variaciones · errores     │
│       → La meta-comprensión de la técnica           │
├─────────────────────────────────────────────────────┤
│   5'  PLANTILLA PARA LA BIBLIOTECA COI              │
│       El prompt de la sesión, guardado y nombrado   │
│       → Tu activo permanente                        │
└─────────────────────────────────────────────────────┘
```

---

## Los 4 entregables del curso

| Entregable | Qué es | Sesión de cierre |
|-----------|--------|-----------------|
| **E1 · Biblioteca P01–P05** | Las cinco primeras plantillas operativas documentadas | S05 |
| **E2 · Flujo editorial + Proyecto COI** | Manual de operaciones COI con Claude + Proyecto configurado | S10 |
| **E3 · Informe de mercado COI** | Informe de tres secciones publicable bajo marca COI | S15 |
| **E4 · Sistema Personal COI V1.0** | Las 20 plantillas + sistema documentado + manifiesto de cierre | S20 |

---

## Progresión de dificultad

```
Semana 1 — FUNDAMENTOS
   ↓ Cómo funciona Claude · por qué no es Google · primeras técnicas
   ↓ Framework RTCFR

Semana 2 — TÉCNICAS PROFESIONALES  
   ↓ Chain of Thought · Few-Shot · Proyectos · Formatos · Integración
   ↓ Flujo editorial documentado

Semana 3 — PRODUCCIÓN REAL
   ↓ PDFs · Búsqueda web · Flujo 6 fases · Informes estructurados
   ↓ Informe de mercado publicable

Semana 4 — AUTOMATIZACIÓN Y SISTEMA
   ↓ Prompts encadenados · Ponencias · Gestión del conocimiento
   ↓ Meta-prompt · Sistema personal V1.0
```

---

## Técnicas cubierta por semana

### Semana 1 — Fundamentos
- **Modelo mental correcto:** Claude no es un buscador ni una base de datos
- **Ventana de contexto:** cómo funciona y cómo gestionarla
- **Protocolo anti-alucinación:** la técnica más crítica para el trabajo editorial
- **Mapa de fortalezas:** qué hace Claude mejor que cualquier otra herramienta
- **Framework RTCFR:** la arquitectura central de todo el curso

### Semana 2 — Técnicas avanzadas
- **Chain of Thought (CoT):** hacer que Claude razone antes de responder
- **Few-Shot Prompting:** enseñar con ejemplos en lugar de instrucciones
- **Claude Projects:** contexto persistente, sin repetir instrucciones
- **Gestión de formatos:** tabla / texto / resumen / código según la tarea
- **Integración:** RTCFR + CoT + Few-Shot en un prompt maestro único

### Semana 3 — Producción
- **Análisis documental:** protocolo de 5 pasos para informes PDF
- **Búsqueda web:** cuándo activarla, cómo verificar, límites editoriales
- **Flujo editorial 6 fases:** de dato bruto a artículo publicable en 60 minutos
- **Arquitectura de informes:** técnica de los dos prompts (estructura primero, desarrollo después)
- **Entregable publicable:** informe de mercado con sello COI

### Semana 4 — Automatización
- **4 patrones de encadenamiento:** Amplificación / Destilación / Transformación / Refinamiento
- **Flujo de ponencias:** 5 fases de preparación de cualquier presentación
- **Gestión del conocimiento:** notas, síntesis, memoria institucional
- **Meta-prompt:** el marco de 3 preguntas para adaptar Claude a cualquier tarea nueva
- **Sistema personal:** integración de los 20 prompts en un flujo de trabajo operativo

---

## Cómo preparar cada sesión

### Antes
1. Lee el `README.md` de la sesión (5 minutos)
2. Ten abierto Claude (claude.ai) en otra ventana
3. Prepara el material de práctica indicado (PDF, texto, etc.)

### Durante
1. **Concepto** (15'): Lee la explicación, no copies los prompts todavía
2. **Práctica** (30'): Ejecuta los ejercicios en orden. Ajusta, no copies exacto
3. **Reflexión** (10'): Anota qué funcionó y qué no
4. **Plantilla** (5'): Copia el prompt final a tu `prompts/biblioteca/`

### Después
- Guarda el resultado de la práctica (el texto generado, el análisis, etc.)
- Anota una variación del prompt que quieras probar en otra sesión
- Actualiza el entregable de semana si corresponde

---

## Nota terminológica

Este curso usa terminología aseguradora en español iberoamericano estándar:

| Término anglosajón | Término COI |
|-------------------|-------------|
| Property insurance | Seguros de daños |
| Casualty insurance | Seguros de RC (responsabilidad civil) |
| P&C | Ramos no vida |
| Life insurance | Seguros de vida |
| InsurTech | Tecnología aseguradora / sector insurtech |
| Claims | Siniestros |
| Underwriting | Suscripción |
| Broker | Corredor de seguros |

Esta distinción es relevante al trabajar con Claude: los prompts de este curso incluyen la corrección terminológica como restricción estándar.
