# Fase 2 — Fenomenología y análisis de la complejidad

## 2.1 Clasificación del sistema

El problema de la despoblación rural no es un problema simple con solución algorítmica conocida. Es un **sistema complejo adaptativo (SCA)** en el sentido de Meadows/Holland:

- Sus agentes (vecinos, ayuntamiento, empresas, administración autonómica) **cambian sus reglas** en función del entorno
- Presenta **emergencia**: el comportamiento del sistema (despoblación acelerada) no se explica por la suma de las decisiones individuales
- Tiene **bucles de retroalimentación no lineales** que pueden ser de refuerzo (positivos) o de equilibrio (negativos)
- Es **irreversible a partir de un umbral**: cuando la población cae por debajo del mínimo de sostenibilidad de servicios, el bucle se acelera de forma difícil de revertir

No es, por tanto, un problema que se resuelva con una sola intervención puntual. Requiere **gestión sistémica continuada**.

---

## 2.2 El bucle central de despoblación

El sistema presenta un bucle de equilibrio negativo (B) que se autorefuerza:

```
Población
    ↓ (si baja)
Servicios disponibles
    ↓ (si se reducen)
Atractivo del municipio
    ↓ (si baja)
Llegada de nuevos residentes
    ↓ (si cae)
Población  ← cierre del bucle
```

Este bucle es un **sistema complejo físico con comportamiento adaptativo**: una vez que los agentes (familias, jóvenes) perciben que los servicios bajan, su comportamiento cambia (se van antes de que bajen más), acelerando el proceso.

### Umbral de no retorno

Existe un punto de inflexión estimado entre 600-700 habitantes para municipios con servicios básicos públicos en España, por debajo del cual:
- La administración autonómica retira o fusiona el centro de salud
- La escuela pasa a ser unitaria o se cierra
- El transporte público se reduce o elimina
- El comercio local cierra por falta de masa crítica de clientes

Una vez retirados los servicios, recuperarlos requiere un esfuerzo político y económico muy superior al de haberlos mantenido.

### Datos demográficos reales de Santacara (INE 2024)

La gravedad del problema queda confirmada por los datos del padrón:

| Indicador | Valor | Interpretación |
|-----------|-------|----------------|
| Población 2024 | 858 hab. | −199 hab. desde 2002 (−9/año de media histórica) |
| Ritmo reciente (2019-2024) | −5 hab./año | Desaceleración respecto al pico, pero tendencia negativa |
| Media de edad | 49,48 años | +1,10 años respecto a hace un lustro — envejecimiento activo |
| Población >65 años | 231 hab. (26,9%) | Casi 1 de cada 3 habitantes |
| Población <18 años | 103 hab. (12,0%) | Base de reemplazo generacional muy estrecha |
| Crecimiento vegetativo 2023 | −9 (4 nacimientos, 13 defunciones) | Sin inmigración, la pérdida sería el doble |
| Población 18-65 años | 525 hab. (61,1%) | Masa crítica laboral aún presente, pero decreciente |

El municipio ha perdido el 34% de su población desde 1986 (1.147 hab.) hasta 2024 (858 hab.). Sin intervención, el umbral crítico de 600-700 habitantes se alcanzaría en 8-13 años al ritmo actual.

---

## 2.3 Bucles de refuerzo positivo (palancas de intervención)

El mismo sistema tiene bucles de refuerzo (R) que pueden activarse con la intervención correcta:

```
Vivienda disponible y asequible
    ↓ (activa)
Llegada de nuevos residentes
    ↓
Aumento de población
    ↓
Más demanda de servicios
    ↓
Mantenimiento o mejora de servicios
    ↓
Mayor atractivo del municipio
    ↓
Más demanda de vivienda  ← cierre del bucle R
```

Y el bucle económico local:

```
Inversión en rehabilitación
    ↓
Empleo local en obra
    ↓
Gasto local (comercio, hostelería)
    ↓
Ingresos para negocios locales
    ↓
Viabilidad del tejido económico
    ↓
Mayor atractivo como lugar de residencia
    ↓
Más vecinos → más ingresos municipales → más inversión  ← cierre del bucle R
```

---

## 2.4 Clasificación del problema según la escala de complejidad

| Dimensión | Nivel | Justificación |
|-----------|-------|---------------|
| Número de variables | Alto | Demografía, economía, normativa, percepción, mercado inmobiliario... |
| Interacción entre variables | No lineal | Los bucles generan comportamientos emergentes no predecibles por suma |
| Dinamismo | Alto | Las condiciones cambian con cada elección política, ciclo económico, crisis |
| Opacidad | Alta | El estado real del parque de vivienda municipal rara vez está inventariado |
| Reversibilidad | Parcial | Reversible antes del umbral crítico; muy difícil después |

→ El problema es un **SCA de complejidad alta** que requiere herramientas de dinámica de sistemas para modelarlo correctamente.

---

## 2.5 Elementos del modelo Forrester aplicado

Siguiendo la notación de Meadows (*Thinking in Systems*, 2008):

### Stocks principales

| Stock | Descripción |
|-------|-------------|
| Población residente | Número de habitantes empadronados |
| Viviendas disponibles | Unidades de vivienda habitables en oferta (alquiler o cesión de uso) |
| Activos municipales | Viviendas, solares y edificios propiedad del ayuntamiento |
| Capital municipal | Presupuesto disponible para inversión en vivienda |
| Servicios activos | Número y calidad de servicios públicos y privados disponibles |

### Flujos principales

| Flujo | Tipo | Descripción |
|-------|------|-------------|
| Nacimientos | Entrada a Población | Crecimiento vegetativo positivo |
| Defunciones | Salida de Población | Crecimiento vegetativo negativo |
| Inmigración | Entrada a Población | Llegada de nuevos residentes |
| Emigración | Salida de Población | Salida de residentes existentes |
| Rehabilitación | Entrada a Viviendas disponibles | Activación de activos municipales |
| Cesión/alquiler | Salida de Activos municipales | Traspaso de uso a nuevos residentes |
| Plusvalías | Entrada a Capital municipal | Retorno de la inversión en vivienda |

### Bucles de retroalimentación

| Bucle | Tipo | Descripción |
|-------|------|-------------|
| B1 — Despoblación | Equilibrio negativo | Menos población → menos servicios → menos atractivo → más emigración |
| R1 — Vivienda activa | Refuerzo positivo | Más vivienda disponible → más inmigración → más población → más servicios |
| R2 — Economía circular | Refuerzo positivo | Inversión municipal → empleo local → gasto local → viabilidad económica → más atractivo |
| R3 — Alianza pública | Refuerzo positivo | Colaboración ayuntamiento + Navarra + NASUVINSA → menor coste inicial → más operaciones posibles |

→ Ver diagrama completo: [FORRESTER_SANTACARA.md](herramientas/FORRESTER_SANTACARA.md) · [diagrama SVG](herramientas/graficos/FORRESTER.svg)

---

## 2.6 ¿Por qué fallan las soluciones habituales?

Aplicando el concepto de **definición incorrecta del problema** (PDF Fase 2, Tema 2):

| Solución habitual | Por qué no funciona |
|-------------------|---------------------|
| Campañas de marketing territorial | Atrae interés pero sin vivienda disponible, el interés no se convierte en residencia |
| Subvenciones directas a particulares para reformar | El propietario privado no tiene incentivos si no va a vivir allí |
| Creación de empleo local | Sin vivienda, los trabajadores se desplazan desde otros municipios |
| Construcción de vivienda nueva de obra | Coste muy alto para presupuestos municipales pequeños sin modelo de retorno |

La solución correcta ataca el problema en su raíz: **crear oferta de vivienda desde los activos que el propio ayuntamiento ya posee**, con un modelo de reinversión que hace el proceso autosostenible.

---

## 2.7 Stakeholders del sistema

Un SCA no puede analizarse sin identificar los agentes que lo componen y sus valores en juego. Para este proyecto se distinguen tres niveles:

### Stakeholders internos (municipio)

| Actor | Rol en el sistema | Valor prioritario | Posición esperada |
|-------|-------------------|-------------------|-------------------|
| Alcaldía / equipo de gobierno | Decisor principal, propietario de activos | Continuidad del municipio, legado | Favorable si ve viabilidad |
| Vecinos actuales | Usuarios de servicios, comunidad | Calidad de vida, identidad local | Mixta — miedo al cambio vs. esperanza |
| Propietarios de vivienda vacía | Posibles socios o resistencias | Valor patrimonial, privacidad | Resistente si perciben competencia |
| Asociaciones locales | Tejido social, comunicación | Cohesión comunitaria | Favorable si se les incluye |

### Stakeholders externos directos

| Actor | Rol en el sistema | Valor prioritario | Posición esperada |
|-------|-------------------|-------------------|-------------------|
| Gobierno de Navarra (Dpto. Vivienda) | Financiación, marco normativo | Estrategia regional, justificación presupuestaria | Favorable — alineado con Estrategia Vivienda Rural |
| NASUVINSA | Cofinanciación técnica, aval | Viabilidad financiera del modelo | Condicionada a datos del proyecto |
| Koobizitza / cooperativas de cesión de uso | Modelo de gestión alternativo | Acceso a vivienda sin especulación | Muy favorable |
| Empresas del entorno (GKN, Rockwool, etc.) | Fuente de empleo para nuevos residentes | Disponibilidad de mano de obra | Indirectamente favorable |

### Stakeholders externos indirectos

| Actor | Rol en el sistema | Valor prioritario | Posición esperada |
|-------|-------------------|-------------------|-------------------|
| Potenciales nuevos residentes | Demanda latente | Calidad de vida + coste razonable + empleo accesible | Muy favorable si hay oferta real |
| Medios de comunicación regional | Amplificación, presión política | Interés periodístico | Neutral / oportunidad |
| Otros municipios | Adopción del modelo replicable | Solución a su propio problema | Receptivos una vez validado |

→ Ver análisis detallado: [STAKEHOLDERS_SANTACARA.md](herramientas/STAKEHOLDERS_SANTACARA.md)

---

## 2.8 Entornos VUCA aplicados al proyecto

El concepto VUCA (Volatility, Uncertainty, Complexity, Ambiguity) permite evaluar el entorno en el que opera el sistema y calibrar la estrategia de intervención:

| Dimensión | Nivel | Manifestación concreta | Respuesta estratégica |
|-----------|-------|------------------------|----------------------|
| **Volatilidad** | Medio | Cambios en financiación europea (NextGenEU), ciclos electorales municipales, fluctuaciones del mercado de la construcción | Diversificar fuentes de financiación; no depender de un solo programa |
| **Incertidumbre** | Alto | Demanda real no verificada, inventario de activos municipales sin datos precisos, posición real del Gobierno de Navarra | Validar hipótesis con datos antes de escalar; piloto en Santacara antes de replicar |
| **Complejidad** | Alto | Múltiples bucles de retroalimentación, muchos stakeholders con intereses distintos, marco normativo en evolución (ley cooperativas) | Usar dinámica de sistemas (Forrester) para visualizar interacciones; gestión por fases |
| **Ambigüedad** | Medio | "Vivienda disponible" significa cosas distintas para cada actor; "éxito" del proyecto no tiene definición única | Establecer métricas claras (población, viviendas activadas, retorno económico) desde el inicio |

### Implicación para la metodología CPS

Un entorno VUCA alto exige **iterar rápido con datos reales** en lugar de planificar exhaustivamente sin acción. La estructura de fases CPS es adecuada precisamente porque permite revisar el diagnóstico conforme aparecen nuevos datos (Fase 3) sin invalidar el trabajo conceptual ya realizado.

---

## 2.9 Herramientas utilizadas en esta fase

| Herramienta | Función | Archivo |
|-------------|---------|---------|
| Diagrama de Ishikawa | Identificación de causas raíz de la despoblación | [ISHIKAWA_SANTACARA.md](herramientas/ISHIKAWA_SANTACARA.md) · [SVG](herramientas/graficos/ISHIKAWA.svg) |
| Modelo Forrester | Dinámica de stocks, flujos y bucles de retroalimentación | [FORRESTER_SANTACARA.md](herramientas/FORRESTER_SANTACARA.md) · [SVG](herramientas/graficos/FORRESTER.svg) |
| Análisis DAFO | Diagnóstico estratégico del municipio | [DAFO_SANTACARA.md](herramientas/DAFO_SANTACARA.md) |
| Mapa de stakeholders | Identificación y posicionamiento de actores clave | [STAKEHOLDERS_SANTACARA.md](herramientas/STAKEHOLDERS_SANTACARA.md) |
| Análisis VUCA | Evaluación del entorno de intervención | Sección 2.8 de este documento |

---

## 2.10 Referencias metodológicas

- **Holland, J.H.** (1995). *Hidden Order: How Adaptation Builds Complexity*. Addison-Wesley. — Base conceptual de los sistemas complejos adaptativos (SCA).
- **Meadows, D.H.** (2008). *Thinking in Systems: A Primer*. Chelsea Green Publishing. — Notación de stocks, flujos y bucles; concepto de puntos de apalancamiento.
- **Damas, S.** (coord.) (2024). *Materiales de la asignatura Fase 2: Fenomenología y análisis de la complejidad*. Máster en Problem Solving, UNIR. — Marco metodológico del proyecto.
- **Arterra Bizimodu** — Cooperativa de cesión de uso en Navarra. Referencia de modelo Koobizitza aplicado. [https://arterrabizimodu.eus](https://arterrabizimodu.eus)
- **NASUVINSA** — Navarra de Suelo y Vivienda S.A. Marco de cofinanciación técnica para proyectos de vivienda municipal. [https://www.nasuvinsa.es](https://www.nasuvinsa.es)

---

*Fase anterior: [Fase 1 — Metodología CPS](FASE_1_METODOLOGIA.md)*
*Siguiente fase: [Fase 3 — Análisis de la realidad](FASE_3_ANALISIS_REALIDAD.md)*
