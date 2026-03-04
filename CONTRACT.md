# SOFTWARE DEVELOPMENT AGREEMENT
## Proyecto: MetricDash UACM

**Identificador del Producto:** mx.edu.uacm.is.slt.ms.metricdash
**Versión del Contrato:** 1.0
**Fecha de Entrada en Vigor:** Marzo 2026

---

## 1. PARTES

Este Acuerdo de Desarrollo de Software se celebra entre:

**Cliente:** Profesor responsable de la asignatura Métricas de Software.
**Proveedor:** Equipo de Desarrollo MetricDash UACM.

Ambas partes acuerdan lo siguiente:

---

## 2. OBJETO DEL CONTRATO

El presente contrato tiene por objeto el diseño, desarrollo, implementación y entrega de un sistema de software denominado
**MetricDash UACM**, consistente en un Panel de Instrumentos (Dashboard) para el registro, procesamiento y visualización de
métricas de software.

El sistema deberá cumplir con los requerimientos académicos establecidos en el programa oficial de la asignatura.

---

## 3. ALCANCE DEL PROYECTO

### 3.1 Funcionalidades Incluidas

El sistema deberá:

- Permitir el registro manual de medidas de software.
- Procesar al menos tres métricas cuantitativas.
- Generar indicadores derivados automáticamente.
- Mostrar visualmente los indicadores en formato Dashboard.
- Proporcionar retroalimentación inmediata.
- Resaltar estados de riesgo mediante semáforos (Verde, Amarillo, Rojo).
- Persistir información en almacenamiento local.

---

### 3.2 Métricas Mínimas a Implementar

- Tamaño del producto (KLOC)
- Número de defectos
- Esfuerzo (Horas Hombre)

---

### 3.3 Indicadores Derivados

- Densidad de Defectos
- Productividad
- Tasa de Defectos por Esfuerzo

Cada indicador deberá contar con:

- Fórmula matemática formal
- Umbrales definidos
- Interpretación ejecutiva documentada

---

## 4. MARCO METODOLÓGICO

El proceso de medición se alineará con el estándar:

- ISO/IEC/IEEE 15939:2017

El diseño de métricas seguirá el enfoque:

- Goal Question Metric (GQM)

El modelo organizacional considerará principios del:

- Capability Maturity Model Integration (CMMI)

---

## 5. TECNOLOGÍAS A UTILIZAR

### 5.1 Plataforma
- Java SE 25.0.2

### 5.2 Interfaz Gráfica
- JavaFX

### 5.3 Persistencia
- H2 Database en archivo local

### 5.4 Control de Versiones
- Git
- GitHub Education

### 5.5 Documentación
- Google Drive institucional
- Repositorio GitHub

---

## 6. ENTREGABLES

El Proveedor entregará:

- Código fuente completo.
- Historial de versiones verificable.
- Ejecutable JAR funcional.
- Documento técnico formal.
- Diseño centrado en métricas.
- Diagramas UML.
- Evidencia de organización y roles.
- Presentación ejecutiva.

---

## 7. METODOLOGÍA DE TRABAJO

El proyecto se ejecutará bajo un modelo híbrido Ágil–Guiado por Plan que incluye:

- Planeación inicial estructurada.
- Iteraciones incrementales.
- Revisión semanal interna.
- Control de versiones obligatorio.
- Validación cruzada de métricas.

---

## 8. CRITERIOS DE ACEPTACIÓN

El sistema será considerado aceptado cuando:

- Los cálculos matemáticos sean correctos.
- El Dashboard refleje los valores en tiempo real.
- Los estados de riesgo cambien según los umbrales definidos.
- No existan fallas críticas de ejecución.
- Se entregue la documentación completa.

---

## 9. GESTIÓN DE RIESGOS

El equipo implementará mecanismos preventivos para mitigar:

- Retrasos en cronograma.
- Errores en fórmulas matemáticas.
- Fallas de integración entre módulos.
- Inconsistencias documentales.

---

## 10. CONTROL DE CAMBIOS

Toda modificación al alcance deberá:

- Documentarse formalmente.
- Ser aprobada por ambos líderes de proyecto.
- Reflejarse mediante incremento de versión en el repositorio.
