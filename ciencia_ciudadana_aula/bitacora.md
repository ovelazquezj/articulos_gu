# Bitácora de Sesión — Artículo: Ciencia Ciudadana en el Aula

**Proyecto:** Ciencia Ciudadana en el Aula: Del Estado del Arte a la Acción
**Autor:** Omar Francisco Velázquez Juárez
**Fecha de sesión:** 2026-03-26
**Colaboración asistida por IA:** Claude (Anthropic)

---

## Resumen de la sesión

Sesión de trabajo enfocada en la revisión del SRS, verificación de insumos y redacción del artículo de divulgación. Se completaron las Fases 1 y 2 del plan de implementación, con revisión editorial activa de las secciones 1 y 2 del artículo.

---

## Registro cronológico

### 1. Análisis del SRS01

- Se leyó y analizó el documento `SRS01_ciencia_cuidadana_en_aula.md` (v1.0, 2026-03-26).
- Se identificó el estado de los entregables: SRS aprobado, estructura definida, referencias referenciadas pero sin verificar, artículo final inexistente.
- Se elaboró un plan de implementación en 4 fases:
  - **Fase 1:** Verificación de insumos
  - **Fase 2:** Redacción del artículo
  - **Fase 3:** Control de calidad
  - **Fase 4:** Entrega

---

### 2. Fase 1 — Verificación de insumos

**Acción:** Lectura de `bibliografia.bib` y revisión del directorio `/outputs/`.

**Hallazgos:**
- 10 referencias confirmadas, rango 2020-2025 ✅
- 3 referencias con cobertura directa México/Latam (López, Sanabria-Z, UNESCO) ✅
- El directorio `/outputs/` no existía — sin borrador previo
- Se detectó una referencia con inconsistencias: `CitizenScienceGoesToSchool` (Bonney et al., 2022) presentaba un DOI incongruente con el año y los autores

**Corrección bibliográfica — decisión del autor:**

El autor proporcionó la referencia correcta para reemplazar la entrada inconsistente:

| Campo | Entrada errónea | Entrada corregida |
|-------|----------------|-------------------|
| Clave BibTeX | `CitizenScienceGoesToSchool` | `masson2025citizen` |
| Autores | Bonney, Phillips, Enck | Masson, Siebert, Köhler, Fritsche, Zabel |
| Año | 2022 | 2025 |
| Volumen/Número | 54(8) | 57(5-6) |
| Páginas | 1031–1059 | 359–398 |
| DOI | Inconsistente (eliminado) | — |

**Archivo modificado:** `bibliografia.bib`

---

### 3. Fase 2 — Redacción del artículo

**Acción:** Se generó el artículo completo en `/outputs/articulo_ciencia_ciudadana_aula.md`.

**Métricas del primer borrador:**
- Extensión: 2,041 palabras ✅ (rango SRS: 1800–2200)
- Secciones: 5 completas ✅
- Referencias citadas: 10 ✅
- Formato citas: APA 7ma edición ✅
- Licencia CC BY 4.0: incluida ✅

---

### 4. Revisión editorial — Sección 1 (Introducción)

**Problema identificado por el autor:** La introducción original resultaba "demasiado cuadrada" — tono formal y pregunta retórica convencional sin engagement narrativo.

**Decisión editorial:** Reescribir la introducción siguiendo el siguiente tren de ideas propuesto por el autor:
- Referencia a la costumbre personal de pensar en seis improbabilidades (tomada de la Reina Blanca en *Alicia en el País de las Maravillas* de Lewis Carroll)
- Una de esas improbabilidades recurrentes: *¿puede la ciencia surgir de sus propios consumidores?*
- Ese hilo conduce al descubrimiento/recuerdo de la ciencia ciudadana como respuesta

**Tono buscado:** Personal, narrativo, con referencia literaria que ancle la reflexión sin resultar forzada.

**Resultado:** Introducción reescrita y aprobada por el autor. Aplicada al artículo.

---

### 5. Revisión editorial — Sección 2 (Marco teórico)

**Problema identificado por el autor:** La sección resultaba "acartonada" — lenguaje académico estándar que no conecta emocionalmente con la audiencia.

**Decisión editorial:** Reescribir en estilo tipo Feynman — explicación clara, directa, que parte de una preocupación real y compartida por los lectores.

**Ancla narrativa propuesta por el autor:** La conversación recurrente sobre la **fuga de cerebros** y la falta de desarrollo científico en la región. Esto traslada la relevancia de la ciencia ciudadana de un concepto abstracto a una necesidad concreta que los docentes e investigadores ya sienten.

**Estructura resultante de la sección:**
- Subsección *¿Qué es y por qué importa?*: parte del diagnóstico de la fuga de cerebros → pregunta sobre el tipo de relación con la ciencia que construye el aula → introduce la ciencia ciudadana como ruptura de esa dinámica → respaldo con Zhang et al. (2023) y Johns et al. (2021)
- Subsección *El contexto latinoamericano*: potencial sin explotar de la región → fragmentación del ecosistema (UNESCO, 2024; Sanabria-Z et al., 2023) → caso Chiapas como ejemplo de apropiación comunitaria (López, 2020) → cierre: la brecha es de imaginación institucional, no de recursos

**Resultado:** Sección reescrita y aprobada por el autor. Aplicada al artículo.

---

### 6. Revisión editorial — Sección 3 (Propuestas)

**Problema identificado por el autor:** El formato de "Contexto / Herramientas / Pasos" resultaba demasiado instructivo y frío — no transmitía el carácter innovador de las propuestas.

**Decisión editorial:** Reescribir la sección presentando las propuestas como rutas ya recorridas por investigadores, con tono de innovación y reto. Cada propuesta narra el camino que llevó a esos investigadores a sus hallazgos actuales.

**Incidencia durante la revisión:** Se detectó que la referencia Carrier et al. (2024) correspondía a un estudio de educación primaria (*elementary*), inconsistente con la audiencia universitaria del artículo. El autor decidió sustituirla por Zhang et al. (2023), cuyo alcance multinivel es más pertinente.

**Resultado:** Sección reescrita con nuevo título (*"Propuestas que están funcionando: rutas abiertas por otros"*), tres subsecciones narrativas y referencia corregida. Aprobada y aplicada.

---

### 7. Revisión editorial — Sección 5 (Llamado a la acción)

**Decisión editorial:** Anclar el llamado a la acción en el caso concreto del autor en Global University, eliminando los ejemplos genéricos del borrador original.

**Elementos incorporados por el autor:**
- Lema institucional de Global University: *"hasta que el conocimiento genere disrupción"*
- Línea de investigación personal: Interacción Humano-Máquina
- Proyecto en curso: instrumento de evaluación de perfiles de lenguaje usando IA
- Participantes: alumnos de noveno semestre del curso
- Resultado tangible: 4 estudiantes desarrollando propuestas de tesis derivadas del proyecto

**Tono resultante:** Testimonio en primera persona que cierra el ciclo del artículo — de la improbabilidad de la introducción a la evidencia concreta de que ya está ocurriendo.

**Resultado:** Sección reescrita, aprobada y aplicada.

---

## Estado del artículo al cierre de sesión

| Sección | Estado |
|---------|--------|
| 1. Introducción | ✅ Revisada y aprobada |
| 2. Marco teórico | ✅ Revisada y aprobada |
| 3. Propuestas | ✅ Revisada y aprobada |
| 4. Lecciones aprendidas | Pendiente de revisión |
| 5. Llamado a la acción | ✅ Revisada y aprobada |
| Referencias | ✅ 10 referencias, APA 7ma |
| Licencia CC BY 4.0 | ✅ Incluida |

---

## Archivos modificados en esta sesión

| Archivo | Acción |
|---------|--------|
| `bibliografia.bib` | Corrección de referencia `CitizenScienceGoesToSchool` → `masson2025citizen` |
| `bitacora_sesion_01.md` | Renombrado a `bitacora.md` |
| `outputs/articulo_ciencia_ciudadana_aula.md` | Creado (borrador completo) |
| `outputs/articulo_ciencia_ciudadana_aula.md` | Sección 1 reescrita |
| `outputs/articulo_ciencia_ciudadana_aula.md` | Sección 2 reescrita |
| `outputs/articulo_ciencia_ciudadana_aula.md` | Sección 3 reescrita (+ corrección de referencia Carrier → Zhang) |
| `outputs/articulo_ciencia_ciudadana_aula.md` | Sección 5 reescrita |
| `.gitignore` | Creado — carpeta `outputs/` excluida del repositorio |

---

## Decisiones de estilo vigentes

1. **Tono general:** Reflexivo, inspirador, accesible — nunca acartonado ni autopromocional.
2. **Introducción:** Narrativa personal con referencia literaria (*Alicia en el País de las Maravillas*).
3. **Marco teórico:** Estilo Feynman — partir de preocupaciones reales del lector (fuga de cerebros, desarrollo científico regional) antes de introducir conceptos.
4. **Propuestas:** Narrativa de ruta recorrida — innovación y reto, no manual de instrucciones.
5. **Llamado a la acción:** Testimonio concreto del autor en Global University, anclado en proyecto real.
6. **Criterio de revisión:** El autor evalúa cada sección propuesta antes de aplicar cambios al archivo.

---

*Bitácora actualizada al cierre de la sesión de trabajo del 2026-03-26.*
