# DAFO — Herramienta de autodiagnóstico municipal

Herramienta de diagnóstico aplicable a cualquier municipio español. Responde cada pregunta y clasifica el resultado en la matriz DAFO correspondiente.

**Instrucciones**: Para cada pregunta, marca la respuesta que mejor describe la situación actual de tu municipio. La columna "Resultado" indica en qué cuadrante del DAFO se clasifica cada respuesta.

---

## Bloque 1 — Demografía

| # | Pregunta diagnóstica | Sí → | Parcial → | No → |
|---|---------------------|------|-----------|------|
| 1 | ¿La población ha crecido o se ha mantenido estable en los últimos 5 años? | F | D | D |
| 2 | ¿Hay población de origen externo que haya llegado a vivir al municipio? | F | O | D |
| 3 | ¿La tasa de paro municipal es igual o inferior a la media regional? | F | D | D |

**Interpretación**:
- Mayoría F → demografía como fortaleza, municipio con inercia positiva
- Mayoría D → municipio en riesgo demográfico, intervención urgente
- Mix → municipio con potencial pero sin estrategia de atracción activa

---

## Bloque 2 — Finanzas municipales

| # | Pregunta diagnóstica | Sí → | Parcial → | No → |
|---|---------------------|------|-----------|------|
| 4 | ¿El municipio tiene ingresos propios estables más allá del IBI? (arrendamientos, activos productivos, contratos…) | F | D | D |
| 5 | ¿Las tasas municipales (IBI, vehículos, basuras…) son bajas comparadas con municipios similares? | F | — | D |
| 6 | ¿El ayuntamiento puede invertir en vivienda sin depender exclusivamente de subvenciones? | F | D | D |

**Interpretación**:
- Municipio con ingresos propios diversificados + tasas bajas = ventaja competitiva real para atraer residentes
- Dependencia total de transferencias = fragilidad ante cambios normativos

---

## Bloque 3 — Servicios y conectividad

| # | Pregunta diagnóstica | Sí → | Parcial → | No → |
|---|---------------------|------|-----------|------|
| 7 | ¿El municipio tiene acceso a internet de alta velocidad (fibra ≥100 Mbps)? | F | D | D |
| 8 | ¿Hay centro de salud o consulta médica a menos de 15 minutos? | F | D | D |
| 9 | ¿Existe oferta educativa (colegio o IES) accesible en 20 minutos? | F | D | D |

**Interpretación**:
- Fibra + sanidad + educación = municipio viable para familias → fortaleza combinada
- Ausencia de cualquiera de los tres = barrera estructural para nuevos residentes

---

## Bloque 4 — Empleo y economía local

| # | Pregunta diagnóstica | Sí → | Parcial → | No → |
|---|---------------------|------|-----------|------|
| 10 | ¿Hay polígonos industriales o grandes empleadores a menos de 30 minutos? | F | O | A |
| 11 | ¿Existe actividad económica local activa (comercio, cooperativas, turismo…)? | F | D | D |
| 12 | ¿El municipio cuenta con suelo industrial o terciario disponible? | O | — | D |

**Interpretación**:
- Empleo externo próximo + economía local activa = municipio autosuficiente
- Sin empleo a 30 min = el modelo depende de teletrabajadores o jubilados activos

---

## Bloque 5 — Vivienda

| # | Pregunta diagnóstica | Sí → | Parcial → | No → |
|---|---------------------|------|-----------|------|
| 13 | ¿El ayuntamiento es propietario de viviendas, solares o edificios recuperables? | F | D | D |
| 14 | ¿Existe oferta de vivienda asequible disponible en el mercado local? | F | D | D |
| 15 | ¿Hay viviendas vacías o en ruina con potencial de rehabilitación identificadas? | O | O | A |

**Interpretación**:
- Activos municipales + viviendas vacías = oportunidad de intervención directa de bajo coste
- Sin oferta de vivienda de ningún tipo = principal barrera de entrada → prioridad máxima

---

## Bloque 6 — Entorno externo y normativo

| # | Pregunta diagnóstica | Sí → | Parcial → | No → |
|---|---------------------|------|-----------|------|
| 16 | ¿Existen subvenciones autonómicas o europeas activas para rehabilitación o despoblación? | O | O | A |
| 17 | ¿Hay tendencia de teletrabajo o éxodo urbano que pueda beneficiar al municipio? | O | — | A |
| 18 | ¿El municipio tiene imagen o identidad positiva reconocida externamente? | F | O | D |

---

## Bloque 7 — Riesgo sistémico

| # | Pregunta diagnóstica | Sí → | Parcial → | No → |
|---|---------------------|------|-----------|------|
| 19 | ¿La población está por encima del umbral de sostenibilidad de servicios (~600-700 hab.)? | F | A | A |
| 20 | ¿Existe competencia de municipios mayores cercanos con más servicios? | A | A | F |

**Interpretación**:
- Por debajo del umbral crítico = intervención urgente antes de que el bucle sea irreversible
- Competencia cercana = el municipio necesita diferenciarse activamente (coste, calidad de vida, identidad)

---

## Matriz de resultados

Una vez completadas las 20 preguntas, agrega los resultados:

| Cuadrante | Nº de ítems | Ítems identificados |
|-----------|-------------|---------------------|
| **F** Fortalezas | | |
| **D** Debilidades | | |
| **O** Oportunidades | | |
| **A** Amenazas | | |

### Lectura estratégica

| Perfil | Descripción | Estrategia recomendada |
|--------|-------------|----------------------|
| F>D, O>A | Municipio con base sólida y entorno favorable | Acelerar: lanzar el modelo ahora |
| F>D, A>O | Municipio fuerte internamente pero entorno adverso | Consolidar fortalezas antes de escalar |
| D>F, O>A | Municipio débil pero con oportunidades externas | Aprovechar subvenciones para corregir debilidades |
| D>F, A>O | Municipio en riesgo estructural | Intervención de emergencia + alianzas supramunicipales |

---

*Ver instancia completa con datos reales: [DAFO_SANTACARA.md](DAFO_SANTACARA.md)*

