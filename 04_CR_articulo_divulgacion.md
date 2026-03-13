# Control de Cambios: Artículo "Del Prompt al Pipeline"

**Documento:** CR_articulo_divulgacion.md  
**Última actualización:** 2025-03-12

---

## Resumen de Cambios

| CR-ID | Fecha | Tipo | Descripción | Estado |
|-------|-------|------|-------------|--------|
| CR-001 | 2025-03-12 | Mayor | Clarificación conceptual IA/mercadotecnia | Implementado |
| CR-002 | 2025-03-12 | Mayor | Reestructuración del pipeline (Git transversal) | Implementado |
| CR-003 | 2025-03-12 | Mayor | Reescritura sección 4 (tono presuntuoso) | Implementado |
| CR-004 | 2025-03-12 | Mayor | Reescritura sección 5 (cierre memorable) | Implementado |
| CR-005 | 2025-03-12 | Menor | Cambio de formato de entrega (.docx → .md) | Implementado |

---

## CR-001: Clarificación Conceptual IA/Mercadotecnia

**Fecha:** 2025-03-12  
**Tipo:** Mayor  
**Estado:** Implementado

### Situación anterior

El borrador inicial de la sección 1 afirmaba:

> "El término 'inteligencia artificial' es, en esencia, mercadotecnia."

Esta formulación era ambigua y podía interpretarse como que todo el campo de IA es mercadotecnia.

### Cambio realizado

Se reformuló para distinguir entre:
- El campo de IA: legítimo, con historia desde 1956
- El término "inteligencia": atribución mercadotécnica de capacidades humanas a los modelos

Nueva formulación:

> "El campo de la inteligencia artificial es legítimo y tiene historia. Nació formalmente en 1956, en la conferencia de Dartmouth, y desde entonces investigadores de todo el mundo han contribuido a su desarrollo. Lo que sí es mercadotecnia es el término 'inteligencia'. Estos modelos no piensan."

### Justificación

- Precisión conceptual importante para audiencia académica
- Evita parecer que se descalifica un campo de estudio completo
- Mantiene la crítica al antropomorfismo sin perder rigor

### Impacto

| Área | Nivel | Detalle |
|------|-------|---------|
| Contenido | Alto | Cambio sustancial en argumento inicial |
| Tono | Medio | Más matizado y preciso |
| Referencias | Ninguno | No requirió nuevas fuentes |

---

## CR-002: Reestructuración del Pipeline (Git Transversal)

**Fecha:** 2025-03-12  
**Tipo:** Mayor  
**Estado:** Implementado

### Situación anterior

El borrador presentaba las 8 etapas como secuencia lineal:

1. Perplexity
2. Google Scholar
3. Zotero
4. Git (para bibliografía)
5. Le Chat
6. Bitácora
7. Claude Code
8. NotebookLM

Git aparecía como etapa aislada para versionado de bibliografía.

### Cambio realizado

Se reorganizó en tres fases, con Git como infraestructura transversal de las etapas 4-7:

**Fase de recolección (etapas 1-3)**
- Perplexity, Google Scholar, Zotero

**Fase Documentation as Code (etapas 4-7)**
- Todo vive en Git: bibliografía, prompts, bitácora, artefactos SRS/CR
- Etapa 4: Diseño de prompts (versionados)
- Etapa 5: Bitácora (markdown en repo)
- Etapa 6: Claude Code con SRS/CR
- Etapa 7: Integración y consolidación

**Fase de producción (etapa 8)**
- NotebookLM

### Justificación

- Refleja cómo funciona realmente el pipeline
- Git no es "un paso" sino la infraestructura donde viven todos los artefactos
- Documentation as Code es el principio unificador, no una herramienta

### Impacto

| Área | Nivel | Detalle |
|------|-------|---------|
| Estructura | Alto | Reorganización completa de sección 3 |
| Claridad | Alto | Mejor representación del flujo real |
| Extensión | Medio | Sección 3 creció ~30% |

---

## CR-003: Reescritura Sección 4 (Tono Presuntuoso)

**Fecha:** 2025-03-12  
**Tipo:** Mayor  
**Estado:** Implementado

### Situación anterior

La sección 4 original tenía estructura:

1. "Este pipeline no es solo para investigadores..."
2. Mis 3 criterios de evaluación
3. Breve mención de beneficios

El tono era percibido como presuntuoso: "miren lo que yo hago" sin desarrollar la propuesta para que el lector la adopte.

### Cambio realizado

Reescritura completa con nueva estructura:

1. **Apertura con problema reconocible:** El alumno que entrega proyecto funcional pero no sabe explicarlo
2. **Contexto estadístico:** 86% de estudiantes usan IA sin estructura
3. **Análisis de respuestas fallidas:** Prohibir vs. permitir sin criterio
4. **Propuesta:** Hacer del proceso el objeto de evaluación
5. **Desarrollo concreto:** Qué significa que el alumno entregue un repositorio
6. **Beneficio para el profesor:** Reutilización, memoria institucional
7. **Conexión con principios más amplios:** Reproducibilidad como hábito mental

### Justificación

- La sección original no desarrollaba la propuesta, solo la enunciaba
- El tono presuntuoso alienaba al lector en lugar de invitarlo
- Faltaba el "cómo" concreto para que un profesor o alumno pudiera adoptar el enfoque

### Impacto

| Área | Nivel | Detalle |
|------|-------|---------|
| Contenido | Alto | Reescritura ~90% del texto |
| Tono | Alto | De presuntuoso a propositivo |
| Utilidad | Alto | Ahora incluye orientación práctica |

---

## CR-004: Reescritura Sección 5 (Cierre Memorable)

**Fecha:** 2025-03-12  
**Tipo:** Mayor  
**Estado:** Implementado

### Situación anterior

La sección 5 original era una lista de frases sueltas:

> "La IA no es una herramienta; es un conjunto de herramientas..."
> "Estamos en la era de la generación de conocimiento..."
> "Parafraseando el lema de nuestra universidad..."

Sin desarrollo, sin arco narrativo, sin cierre memorable.

### Cambio realizado

Reescritura completa con arco narrativo:

1. **Perspectiva histórica:** De fichas bibliográficas a Google a IA
2. **Reconocimiento del punto de inflexión:** Necesidad de nueva alfabetización
3. **Distinción crítica:** Consumir IA vs. trabajar con IA
4. **Analogías profesionales:** Cirujano, ingeniero
5. **Implicaciones para profesores:** Qué enseñar, cómo evaluar
6. **Implicaciones para alumnos:** Competencia profesional demandada
7. **Reflexión sobre el momento:** Velocidad sin estructura = ruido
8. **Cierre con el lema universitario:** Disrupción genuina
9. **Invitación final:** El repositorio puede empezar hoy

### Justificación

- Un cierre memorable requiere desarrollo, no bullets
- El lector necesita sentir que el artículo llega a algún lado
- La invitación final da agencia al lector

### Impacto

| Área | Nivel | Detalle |
|------|-------|---------|
| Contenido | Alto | Reescritura 100% |
| Extensión | Alto | De ~100 palabras a ~500 |
| Efecto | Alto | De anticlimático a memorable |

---

## CR-005: Cambio de Formato de Entrega

**Fecha:** 2025-03-12  
**Tipo:** Menor  
**Estado:** Implementado

### Situación anterior

Primer entregable generado en formato .docx (Word).

### Cambio realizado

Entregable final en formato .md (Markdown).

### Justificación

- Publicación será en web, Markdown es más apropiado
- Markdown es versionable en Git (consistente con pipeline propuesto)
- Más portable entre plataformas

### Impacto

| Área | Nivel | Detalle |
|------|-------|---------|
| Formato | Bajo | Cambio de extensión |
| Compatibilidad | Positivo | Mejor para publicación web |

---

## Lecciones Aprendidas

1. **Clarificar conceptos antes de redactar:** El malentendido sobre IA/mercadotecnia se hubiera evitado con mejor input inicial.

2. **Describir estructura real, no idealizada:** Git es infraestructura transversal, no etapa secuencial.

3. **Feedback específico > feedback vago:** "Suena presuntuoso" es más útil que "no me gusta".

4. **Los cierres requieren desarrollo:** Una lista de ideas no es un cierre. Necesita arco narrativo.

5. **El formato importa:** Elegir el formato de salida desde el inicio ahorra retrabajo.

---

## Licencia

Este documento está licenciado bajo Creative Commons Atribución 4.0 Internacional (CC BY 4.0).
