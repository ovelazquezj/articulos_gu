# CR: Control de Cambios para Investigación

## Propósito

Documentar la evolución de la investigación de manera sistemática: qué cambió, por qué cambió, quién lo aprobó, y cuál es el impacto. El Control de Cambios (CR) complementa el SRS y la bitácora, proporcionando un registro formal de modificaciones al alcance, metodología o criterios del proyecto.

---

## Cuándo Usar el CR

| Situación | ¿Requiere CR? | Tipo |
|-----------|---------------|------|
| Cambio en pregunta de investigación | Sí | Mayor |
| Cambio en hipótesis | Sí | Mayor |
| Cambio en metodología | Sí | Mayor |
| Cambio en criterios de aceptación | Sí | Mayor |
| Cambio en cronograma (>1 semana) | Sí | Menor |
| Agregar/quitar variable | Sí | Menor |
| Cambio en herramienta de análisis | Depende | Menor |
| Corrección de errores en documentos | No | N/A |
| Actualización de referencias | No | N/A |

---

## Plantilla: Registro de Control de Cambios

```markdown
# Control de Cambios: [Nombre del Proyecto]

**Documento:** CR_[nombre_proyecto].md
**Última actualización:** [YYYY-MM-DD]

---

## Resumen de Cambios

| CR-ID | Fecha | Tipo | Descripción breve | Estado |
|-------|-------|------|-------------------|--------|
| CR-001 | 2025-03-10 | Mayor | Cambio de metodología de evaluación | Aprobado |
| CR-002 | 2025-03-15 | Menor | Extensión de cronograma fase 2 | Aprobado |
| CR-003 | 2025-03-18 | Mayor | Nueva variable dependiente | Pendiente |

---

## Detalle de Cambios

### CR-001: [Título del Cambio]

**Fecha de solicitud:** [YYYY-MM-DD]
**Solicitante:** [Nombre]
**Tipo:** [Mayor / Menor]
**Estado:** [Pendiente / En revisión / Aprobado / Rechazado / Implementado]

#### Descripción del cambio

**Situación actual:**
[Cómo está definido actualmente en el SRS o plan de investigación]

**Cambio propuesto:**
[Qué se propone modificar]

**Justificación:**
[Por qué es necesario este cambio. Incluir evidencia si aplica:
resultados preliminares, feedback del asesor, limitaciones encontradas]

#### Análisis de impacto

| Área | Impacto | Descripción |
|------|---------|-------------|
| Alcance | [Alto/Medio/Bajo/Ninguno] | [Detalle] |
| Cronograma | [Alto/Medio/Bajo/Ninguno] | [Detalle] |
| Recursos | [Alto/Medio/Bajo/Ninguno] | [Detalle] |
| Calidad | [Alto/Medio/Bajo/Ninguno] | [Detalle] |
| Riesgos | [Alto/Medio/Bajo/Ninguno] | [Detalle] |

**Documentos afectados:**
- [ ] SRS_[nombre].md - Sección [X]
- [ ] Bitácora - Actualizar con decisión
- [ ] Cronograma - Ajustar fechas
- [ ] [Otro documento]

#### Alternativas consideradas

| Alternativa | Ventajas | Desventajas | Razón de descarte |
|-------------|----------|-------------|-------------------|
| [Alt 1] | [Lista] | [Lista] | [Por qué no] |
| [Alt 2] | [Lista] | [Lista] | [Por qué no] |

#### Decisión

**Aprobado por:** [Nombre y rol]
**Fecha de aprobación:** [YYYY-MM-DD]
**Condiciones:** [Si aplica, condiciones para la aprobación]

**Rechazado por:** [Si aplica]
**Razón de rechazo:** [Si aplica]

#### Implementación

**Fecha de implementación:** [YYYY-MM-DD]
**Responsable:** [Nombre]
**Verificación:** [Cómo se verificó que el cambio se implementó correctamente]

**Commits relacionados:**
- [hash] - [mensaje del commit]
- [hash] - [mensaje del commit]

---

### CR-002: [Título del Cambio]

[Misma estructura...]

---
```

---

## Plantilla: Solicitud de Cambio Individual

Para cambios mayores, usar este formato antes de agregar al CR consolidado:

```markdown
# Solicitud de Cambio: CR-[XXX]

## Información General

| Campo | Valor |
|-------|-------|
| ID | CR-[XXX] |
| Fecha | [YYYY-MM-DD] |
| Solicitante | [Nombre] |
| Proyecto | [Nombre del proyecto] |
| Tipo | [Mayor / Menor] |
| Urgencia | [Alta / Media / Baja] |

---

## 1. Descripción del Cambio

### Estado actual
[Descripción detallada de cómo está definido actualmente]

### Cambio propuesto
[Descripción detallada de qué se quiere cambiar]

### Diferencia
```diff
- [Lo que se elimina o modifica]
+ [Lo que se agrega o cómo queda]
```

---

## 2. Justificación

### Razón del cambio
[¿Por qué es necesario?]

### Evidencia de soporte
- [Resultado de experimento que motivó el cambio]
- [Feedback de asesor]
- [Referencia bibliográfica que justifica]
- [Limitación técnica encontrada]

### Consecuencias de NO hacer el cambio
[¿Qué pasa si seguimos como está?]

---

## 3. Análisis de Impacto

### Impacto en el proyecto

| Dimensión | Nivel | Descripción |
|-----------|-------|-------------|
| Alcance | [ ] Ninguno [ ] Bajo [ ] Medio [ ] Alto | [Detalle] |
| Tiempo | [ ] Ninguno [ ] Bajo [ ] Medio [ ] Alto | [Detalle] |
| Costo/Recursos | [ ] Ninguno [ ] Bajo [ ] Medio [ ] Alto | [Detalle] |
| Calidad | [ ] Ninguno [ ] Bajo [ ] Medio [ ] Alto | [Detalle] |

### Documentos que requieren actualización
- [ ] SRS: [Cuáles secciones]
- [ ] Bitácora: [Agregar decisión]
- [ ] Prompts: [Cuáles]
- [ ] Cronograma: [Qué ajustes]
- [ ] Otro: [Especificar]

### Dependencias
[¿Este cambio afecta o depende de otros elementos del proyecto?]

---

## 4. Alternativas Evaluadas

### Alternativa A: [Nombre]
- **Descripción:** [Qué implica]
- **Pros:** [Lista]
- **Contras:** [Lista]
- **Viabilidad:** [Alta/Media/Baja]

### Alternativa B: [Nombre]
- **Descripción:** [Qué implica]
- **Pros:** [Lista]
- **Contras:** [Lista]
- **Viabilidad:** [Alta/Media/Baja]

### Justificación de la alternativa elegida
[Por qué el cambio propuesto es mejor que las alternativas]

---

## 5. Plan de Implementación

### Pasos
1. [Paso 1]
2. [Paso 2]
3. [Paso 3]

### Cronograma de implementación
| Actividad | Fecha inicio | Fecha fin | Responsable |
|-----------|--------------|-----------|-------------|
| [Actividad 1] | [Fecha] | [Fecha] | [Nombre] |
| [Actividad 2] | [Fecha] | [Fecha] | [Nombre] |

### Verificación
[Cómo se confirmará que el cambio se implementó correctamente]

---

## 6. Riesgos del Cambio

| Riesgo | Probabilidad | Impacto | Mitigación |
|--------|--------------|---------|------------|
| [Riesgo 1] | [A/M/B] | [A/M/B] | [Estrategia] |
| [Riesgo 2] | [A/M/B] | [A/M/B] | [Estrategia] |

---

## 7. Aprobación

### Revisores requeridos
- [ ] Director de tesis / Asesor principal
- [ ] Co-asesor (si aplica)
- [ ] [Otro rol]

### Firmas

| Rol | Nombre | Decisión | Fecha | Comentarios |
|-----|--------|----------|-------|-------------|
| Investigador | [Nombre] | Solicita | [Fecha] | |
| Asesor | [Nombre] | [ ] Aprueba [ ] Rechaza | [Fecha] | [Comentarios] |
| Co-asesor | [Nombre] | [ ] Aprueba [ ] Rechaza | [Fecha] | [Comentarios] |

---

## 8. Post-Implementación

**Fecha de cierre:** [YYYY-MM-DD]
**Implementado por:** [Nombre]
**Verificado por:** [Nombre]

### Lecciones aprendidas
[¿Qué aprendimos de este cambio que pueda aplicarse en el futuro?]
```

---

## Flujo de Trabajo para Cambios

```
┌─────────────────┐
│ Identificar     │
│ necesidad de    │
│ cambio          │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Documentar en   │
│ bitácora        │
│ (entrada diaria)│
└────────┬────────┘
         │
         ▼
┌─────────────────┐     ┌─────────────────┐
│ ¿Es cambio      │ No  │ Implementar     │
│ mayor o menor?  ├────►│ directamente    │
└────────┬────────┘     │ + commit        │
         │ Sí           └─────────────────┘
         ▼
┌─────────────────┐
│ Crear solicitud │
│ de cambio (CR)  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Revisar con     │
│ asesor(es)      │
└────────┬────────┘
         │
    ┌────┴────┐
    ▼         ▼
┌───────┐ ┌───────┐
│Aprobado│ │Rechazado│
└───┬───┘ └───┬───┘
    │         │
    ▼         ▼
┌─────────┐ ┌─────────────┐
│Implementar│ │Documentar   │
│+ actualizar│ │razón y      │
│documentos │ │alternativas │
└─────────┘ └─────────────┘
```

---

## Integración con Git

Cada cambio aprobado debe reflejarse en commits atómicos:

```bash
# Commit del cambio en documentación
git commit -m "cr: CR-001 actualizar SRS con nueva metodología"

# Commit de implementación
git commit -m "cr: CR-001 implementar nuevo pipeline de evaluación"

# Tag para versiones importantes
git tag -a v2.0-post-CR001 -m "Versión con metodología actualizada"
```

---

## Licencia

Este instrumento está licenciado bajo Creative Commons Atribución 4.0 Internacional (CC BY 4.0).
