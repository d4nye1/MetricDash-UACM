# MetricDash UACM

**Identificador del Producto:** mx.edu.uacm.is.slt.ms.metricdash  
**Versión Actual:** 1.0  
**Tipo de Proyecto:** Dashboard de Métricas de Software  
**Institución:** UACM  
---

## Descripción General

MetricDash UACM es un sistema de software desarrollado en Java que permite el **registro, procesamiento y visualización de métricas de software** mediante un tablero de instrumentos (Dashboard).

El objetivo del sistema es facilitar la interpretación de datos cuantitativos del proyecto y convertirlos en **indicadores visuales que apoyen la toma de decisiones**.

El sistema transforma medidas básicas (errores, tamaño, esfuerzo) en indicadores ejecutivos utilizando semáforos de riesgo (Verde, Amarillo, Rojo).

---

## Objetivo del Proyecto

Desarrollar una herramienta funcional que:

- Permita registrar medidas de software manualmente.
- Calcule automáticamente indicadores derivados.
- Muestre estados de riesgo en tiempo real.
- Refuerce el aprendizaje práctico de métricas en Ingeniería de Software.

---

## Métricas Implementadas

El sistema procesa al menos las siguientes métricas:

- Tamaño del Producto (KLOC)
- Número de Defectos
- Esfuerzo (Horas Hombre)
---

## Tecnologías Utilizadas

### Plataforma
- Java SE 25.0.2

### Interfaz Gráfica
- JavaFX

### Persistencia
- H2 Database (Base de datos en archivo local)

### Control de Versiones
- Git
- GitHub

### Documentación
- Google Drive
- Repositorio GitHub

---

## Marco Metodológico

El diseño del sistema se basa en:

- ISO/IEC/IEEE 15939 (Proceso de Medición)
- Enfoque Goal Question Metric (GQM)
- Principios de CMMI Nivel 2 (Gestión basada en medición)

---

## Equipo de Desarrollo

- Líder de Proyecto A / Arquitecto
- Líder de Proyecto B / Ingeniero de Información
- Especialista en Métricas
- Gestor de Calidad y Documentación

---
### Reglas Obligatorias de Integración

- No se permite realizar commits directos a `main`.
- Toda funcionalidad deberá desarrollarse en una rama `feature/*`.
- La integración a `develop` o `main` deberá realizarse mediante Pull Request.
- Todo Pull Request deberá ser revisado por al menos un integrante.
- El código debe compilar correctamente antes de integrarse.
- El código debe cumplir con los estándares de codificación Java establecidos.
- No se permite integrar código con errores críticos o advertencias graves.
