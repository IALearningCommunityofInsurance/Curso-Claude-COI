# Glosario · Curso Claude COI

Términos clave usados a lo largo del curso, ordenados por orden de aparición.

---

## Conceptos de IA / Claude

**Modelo de lenguaje (LLM)**  
Sistema de inteligencia artificial entrenado para generar texto prediciendo la siguiente palabra más probable en una secuencia. Claude es un LLM desarrollado por Anthropic. No razona como un humano, no busca en Internet (salvo con búsqueda web activada) y no tiene memoria entre conversaciones por defecto.

**Ventana de contexto**  
La cantidad máxima de texto que Claude puede "ver" en una conversación. Todo lo que está fuera de la ventana es invisible para el modelo. Gestionarla bien (S02) es una de las habilidades centrales del curso.

**Alucinación**  
Cuando Claude genera información plausible pero falsa con aparente seguridad. El riesgo más crítico para el trabajo editorial. El Protocolo Anti-Alucinación (P03) es la respuesta del curso.

**Prompt**  
La instrucción o mensaje que se envía a Claude. La calidad del output depende en gran medida de la calidad del prompt. Este curso enseña a construir prompts de nivel profesional.

**Temperatura**  
Parámetro que controla la creatividad vs. precisión de las respuestas. Alta temperatura = más variedad y creatividad. Baja temperatura = respuestas más predecibles y precisas. En Claude.ai no se controla directamente, pero se puede influenciar con las instrucciones.

**Token**  
La unidad mínima de procesamiento de Claude. Aproximadamente 1 token ≈ 0,75 palabras en español. La ventana de contexto se mide en tokens.

---

## Técnicas de prompting

**RTCFR**  
Framework central del curso: Rol, Tarea, Contexto, Formato, Restricción. La arquitectura de cinco componentes para construir prompts de calidad editorial. Ver `docs/framework-rtcfr.md`.

**Chain of Thought (CoT)**  
Técnica para hacer que Claude razone paso a paso antes de dar la respuesta final. Se activa con instrucciones como "Razona primero" o "Piensa en voz alta antes de responder". Especialmente útil para análisis complejos (S06).

**Few-Shot Prompting**  
Enseñar a Claude con ejemplos en lugar de instrucciones abstractas. Se proporcionan 2-3 ejemplos del tipo de output que se desea, y Claude aprende el patrón. La herramienta más potente para capturar la voz editorial de Insur·Insights (S07).

**Zero-Shot Prompting**  
Dar una instrucción sin ejemplos. Funciona bien para tareas estándar; los few-shots son necesarios cuando el estilo o formato es específico.

**Prompt encadenado (Chained Prompt)**  
Técnica en la que la salida de un prompt es la entrada del siguiente. Permite construir flujos de trabajo complejos con Claude (S16). Los cuatro patrones: Amplificación, Destilación, Transformación, Refinamiento.

**Meta-prompt**  
Un prompt cuya función es generar el prompt correcto para una tarea nueva. El marco de tres preguntas de la S19: ¿Qué quiero conseguir? ¿Qué necesita saber Claude? ¿Cómo quiero la salida?

---

## Herramientas y funciones de Claude

**Claude Projects**  
Función de Claude.ai que permite crear un espacio de trabajo con instrucciones permanentes, documentos de referencia y conversaciones relacionadas. Una vez configurado el Proyecto COI (S08), no hay que repetir instrucciones en cada conversación.

**Artefactos**  
En Claude, los artefactos son bloques de contenido estructurado (documentos, código, tablas) que se generan en el panel lateral de Claude.ai, separados de la conversación. Permiten iterar sin perder el historial (S09).

**Búsqueda web integrada**  
Función que permite a Claude acceder a Internet para obtener datos actuales. Requiere activación explícita. S12 cubre cuándo usarla y cómo verificar antes de publicar.

**Memoria de Claude**  
Por defecto, Claude no recuerda conversaciones anteriores. Cada conversación empieza desde cero. Los Claude Projects mitigan esto para el contexto institucional. La gestión del conocimiento (S18) es la respuesta sistémica.

---

## Conceptos editoriales COI

**Biblioteca de Prompts COI**  
El activo principal que se construye a lo largo del curso: 20 plantillas numeradas (P01–P20) que cubren todas las tareas editoriales y analíticas recurrentes de COI.

**Sistema Personal COI V1.0**  
El entregable final del curso (S20): la integración de las 20 plantillas en un flujo de trabajo operativo documentado. El punto de partida del Nivel 2.

**Flujo editorial 6 fases**  
El proceso de producción de contenido COI con Claude, desarrollado en S13:  
1. Brief → 2. Investigación → 3. Estructura → 4. Borrador → 5. Revisión → 6. Formato final

**Protocolo anti-alucinación**  
El conjunto de técnicas de S03 para reducir el riesgo de que Claude genere datos falsos. Componentes: pedir fuentes, instruir sobre incertidumbre, verificar datos numéricos externamente, no preguntar sobre datos muy específicos sin contexto.

**Voz editorial COI**  
El registro de Insur·Insights: analítico pero accesible, con tesis editorial propia (no neutro), sin jerga anglosajona innecesaria, con datos verificados y perspectiva iberoamericana. Se captura y replica con Few-Shot (S07).
