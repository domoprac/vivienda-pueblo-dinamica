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
| Viviendas disponibles | Unidades de vivienda habitables en oferta (alquiler o venta) |
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
| Venta/alquiler | Salida de Activos municipales | Traspaso a nuevos residentes |
| Plusvalías | Entrada a Capital municipal | Retorno de la inversión en vivienda |

### Bucles de retroalimentación

| Bucle | Tipo | Descripción |
|-------|------|-------------|
| B1 — Despoblación | Equilibrio negativo | Menos población → menos servicios → menos atractivo → más emigración |
| R1 — Vivienda activa | Refuerzo positivo | Más vivienda disponible → más inmigración → más población → más servicios |
| R2 — Economía circular | Refuerzo positivo | Inversión municipal → empleo local → gasto local → viabilidad económica → más atractivo |

→ Ver diagrama completo en construcción: [FORRESTER.md](herramientas/FORRESTER.md)

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

*Fase anterior: [Fase 1 — Metodología CPS](FASE_1_METODOLOGIA.md)*
*Siguiente fase: [Fase 3 — Análisis de la realidad](FASE_3_ANALISIS_REALIDAD.md)*
