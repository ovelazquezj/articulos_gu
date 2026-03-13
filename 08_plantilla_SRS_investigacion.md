# SRS: Especificación de Requerimientos para Investigación

## Propósito

Adaptar el documento de Especificación de Requerimientos de Software (SRS) al contexto de investigación académica. Un experimento o instrumento de investigación se trata como un "sistema" que debe cumplir requerimientos específicos, tener criterios de aceptación claros, y ser verificable.

---

## Plantilla SRS para Experimento

```markdown
# SRS: [Nombre del Experimento/Instrumento]

**Versión:** [X.Y]
**Fecha:** [YYYY-MM-DD]
**Autor:** [Nombre]
**Estado:** [Borrador / En revisión / Aprobado / En ejecución / Completado]

---

## 1. Introducción

### 1.1 Propósito
[¿Qué busca lograr este experimento? ¿Qué pregunta de investigación responde?]

### 1.2 Alcance
[¿Qué incluye y qué NO incluye este experimento?]

### 1.3 Definiciones y acrónimos

| Término | Definición |
|---------|------------|
| [Término 1] | [Definición] |
| [Término 2] | [Definición] |

### 1.4 Referencias
- [Documento 1: ej. Marco teórico, sección X]
- [Documento 2: ej. Paper de referencia metodológica]
- [Documento 3: ej. SRS de experimento previo relacionado]

---

## 2. Descripción General

### 2.1 Contexto
[¿Dónde se ubica este experimento en el proyecto de investigación general?
¿Qué lo precede? ¿Qué depende de sus resultados?]

### 2.2 Hipótesis
[Hipótesis específica que este experimento busca probar o refutar]

**H0 (nula):** [Formulación]
**H1 (alternativa):** [Formulación]

### 2.3 Variables

| Variable | Tipo | Descripción | Medición |
|----------|------|-------------|----------|
| [Var 1] | Independiente | [Descripción] | [Cómo se mide/manipula] |
| [Var 2] | Dependiente | [Descripción] | [Cómo se mide] |
| [Var 3] | Control | [Descripción] | [Cómo se controla] |

### 2.4 Supuestos
1. [Supuesto 1: condición que asumimos verdadera]
2. [Supuesto 2]
3. [Supuesto 3]

### 2.5 Restricciones
1. [Restricción 1: ej. tiempo disponible]
2. [Restricción 2: ej. recursos computacionales]
3. [Restricción 3: ej. acceso a datos]

---

## 3. Requerimientos Específicos

### 3.1 Requerimientos de Datos

#### REQ-DAT-001: [Nombre]
- **Descripción:** [Qué datos se necesitan]
- **Fuente:** [De dónde provienen]
- **Formato:** [Estructura esperada]
- **Volumen:** [Cantidad aproximada]
- **Calidad:** [Criterios de calidad mínima]
- **Prioridad:** [Alta / Media / Baja]

#### REQ-DAT-002: [Nombre]
[...]

### 3.2 Requerimientos de Procesamiento

#### REQ-PROC-001: [Nombre]
- **Descripción:** [Qué procesamiento se requiere]
- **Entrada:** [Qué recibe]
- **Salida:** [Qué produce]
- **Método:** [Algoritmo, técnica o herramienta]
- **Prioridad:** [Alta / Media / Baja]

#### REQ-PROC-002: [Nombre]
[...]

### 3.3 Requerimientos de Análisis

#### REQ-ANA-001: [Nombre]
- **Descripción:** [Qué análisis se debe realizar]
- **Técnica estadística:** [Prueba o método]
- **Justificación:** [Por qué esta técnica]
- **Herramienta:** [Software/librería]
- **Prioridad:** [Alta / Media / Baja]

#### REQ-ANA-002: [Nombre]
[...]

### 3.4 Requerimientos de Documentación

#### REQ-DOC-001: Registro de proceso
- **Descripción:** Documentar cada paso del experimento en bitácora
- **Formato:** Entrada de bitácora por sesión
- **Prioridad:** Alta

#### REQ-DOC-002: Reproducibilidad
- **Descripción:** Todo código y datos deben permitir replicación
- **Formato:** Scripts versionados + datos accesibles
- **Prioridad:** Alta

---

## 4. Criterios de Aceptación

### 4.1 Criterios de éxito del experimento

| ID | Criterio | Métrica | Umbral |
|----|----------|---------|--------|
| CA-001 | [Descripción] | [Cómo se mide] | [Valor mínimo aceptable] |
| CA-002 | [Descripción] | [Cómo se mide] | [Valor mínimo aceptable] |
| CA-003 | [Descripción] | [Cómo se mide] | [Valor mínimo aceptable] |

### 4.2 Criterios de validez

| ID | Criterio | Verificación |
|----|----------|--------------|
| CV-001 | Validez interna: [aspecto] | [Cómo se verifica] |
| CV-002 | Validez externa: [aspecto] | [Cómo se verifica] |
| CV-003 | Confiabilidad: [aspecto] | [Cómo se verifica] |

### 4.3 Condiciones de falla

El experimento se considera fallido si:
1. [Condición 1: ej. datos insuficientes]
2. [Condición 2: ej. resultados no interpretables]
3. [Condición 3: ej. violación de supuestos críticos]

**Protocolo ante falla:** [Qué hacer si el experimento falla]

---

## 5. Diseño del Experimento

### 5.1 Tipo de diseño
[Experimental / Cuasi-experimental / Observacional / etc.]

[Justificación de por qué este diseño]

### 5.2 Procedimiento

```
Paso 1: [Descripción]
   └── Entregable: [Qué produce este paso]
   └── Verificación: [Cómo sé que está bien]

Paso 2: [Descripción]
   └── Entregable: [...]
   └── Verificación: [...]

Paso 3: [Descripción]
   └── Entregable: [...]
   └── Verificación: [...]

[...]
```

### 5.3 Cronograma

| Fase | Actividad | Inicio | Fin | Dependencias |
|------|-----------|--------|-----|--------------|
| 1 | [Preparación de datos] | [Fecha] | [Fecha] | - |
| 2 | [Ejecución] | [Fecha] | [Fecha] | Fase 1 |
| 3 | [Análisis] | [Fecha] | [Fecha] | Fase 2 |
| 4 | [Documentación] | [Fecha] | [Fecha] | Fase 3 |

---

## 6. Recursos Requeridos

### 6.1 Hardware
| Recurso | Especificación | Disponibilidad |
|---------|----------------|----------------|
| [Recurso 1] | [Specs] | [Sí/No/Parcial] |

### 6.2 Software
| Herramienta | Versión | Licencia | Propósito |
|-------------|---------|----------|-----------|
| [Software 1] | [X.Y.Z] | [Tipo] | [Para qué] |

### 6.3 Datos
| Dataset | Fuente | Acceso | Estado |
|---------|--------|--------|--------|
| [Dataset 1] | [URL/Ref] | [Público/Restringido] | [Obtenido/Pendiente] |

### 6.4 Humanos
| Rol | Responsabilidad | Persona |
|-----|-----------------|---------|
| Investigador principal | [Responsabilidades] | [Nombre] |
| Asesor | [Responsabilidades] | [Nombre] |

---

## 7. Riesgos

| ID | Riesgo | Probabilidad | Impacto | Mitigación |
|----|--------|--------------|---------|------------|
| R-001 | [Descripción] | [Alta/Media/Baja] | [Alto/Medio/Bajo] | [Estrategia] |
| R-002 | [Descripción] | [...] | [...] | [...] |

---

## 8. Entregables

| ID | Entregable | Formato | Ubicación | Fecha |
|----|------------|---------|-----------|-------|
| E-001 | Datos procesados | [CSV/JSON/etc.] | [Ruta en repo] | [Fecha] |
| E-002 | Scripts de análisis | [.py/.R/etc.] | [Ruta en repo] | [Fecha] |
| E-003 | Resultados | [Formato] | [Ruta en repo] | [Fecha] |
| E-004 | Informe final | [.md/.pdf] | [Ruta en repo] | [Fecha] |

---

## 9. Aprobaciones

| Rol | Nombre | Firma/Confirmación | Fecha |
|-----|--------|-------------------|-------|
| Investigador | [Nombre] | [ ] | [Fecha] |
| Director/Asesor | [Nombre] | [ ] | [Fecha] |
| Co-asesor | [Nombre] | [ ] | [Fecha] |

---

## 10. Historial de Versiones

| Versión | Fecha | Autor | Cambios |
|---------|-------|-------|---------|
| 1.0 | [Fecha] | [Nombre] | Versión inicial |
| 1.1 | [Fecha] | [Nombre] | [Descripción de cambios] |
```

---

## Ejemplo: SRS para Experimento de Evaluación de Modelo

```markdown
# SRS: Evaluación de Precisión del Modelo TinyBERT en NER Español

**Versión:** 1.0
**Fecha:** 2025-03-12
**Autor:** Omar Francisco Velázquez Juárez
**Estado:** Aprobado

---

## 1. Introducción

### 1.1 Propósito
Evaluar la precisión del modelo TinyBERT adaptado para Named Entity Recognition 
(NER) en español, comparando su desempeño con el baseline de BERT-base-spanish.

### 1.2 Alcance
**Incluye:**
- Evaluación en dataset WikiANN español
- Métricas: Precision, Recall, F1-score por entidad
- Comparación con baseline

**No incluye:**
- Evaluación en otros idiomas
- Fine-tuning adicional
- Evaluación de latencia (cubierto en experimento 02)

[...]
```

---

## Licencia

Este instrumento está licenciado bajo Creative Commons Atribución 4.0 Internacional (CC BY 4.0).
