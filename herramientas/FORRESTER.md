# Forrester — Diagrama causal y modelo de dinámica de sistemas

## Descripción del sistema

El problema de la despoblación rural es un **sistema complejo adaptativo (SCA)** con bucles de retroalimentación no lineales. El modelo de dinámica de sistemas (Forrester/Meadows) permite identificar las palancas de intervención reales y anticipar los efectos secundarios de cada acción.

---

## Stakeholders del sistema

| Actor | Rol | Tipo |
|-------|-----|------|
| **Ayuntamiento de Santacara** | Propietario de activos, promotor del modelo, gestor | Interno |
| **Gobierno de Navarra** | Estrategia de Vivienda Rural, ayudas rehabilitación, marco normativo | Externo institucional |
| **NASUVINSA** | Cofinanciación técnica, gestión de programas forales de vivienda rural | Externo institucional |
| **Cooperativa / Koobizitza** | Organización del proyecto, adjudicación de usos, gestión comunitaria | Externo privado-social |
| **Constructora local** | Ejecución de obra → multiplicador económico local | Externo privado |
| **Nuevos residentes** | Teletrabajadores, trabajadores GKN/Rockwool/polígonos, familias | Beneficiarios |
| **Residentes actuales** | Sostenimiento de servicios, identidad territorial | Internos |
| **Proveedores y comercio local** | Receptores del gasto de nuevos vecinos → multiplicador R2 | Internos |

---

## Modelo de cesión de uso (Koobizitza)

La cooperativa conserva la titularidad del edificio y los socios adquieren un **derecho de uso**:

- Evita la especulación — la vivienda no puede revenderse con beneficio
- Cuotas más estables — el objetivo es vivir, no invertir
- Mantiene la vivienda vinculada al interés público a largo plazo
- Especialmente útil para vivienda senior, proyectos intergeneracionales y rehabilitación de patrimonio

Proyectos de referencia en Navarra: **Arterra Bizimodu**, **Etxekonak Bat** (Pamplona, 20 viviendas senior).

---

## Cómo se financia en la práctica

Combinación de instrumentos — ningún actor soporta el coste completo:

| Actor | Qué aporta |
|-------|-----------|
| **Ayuntamiento** | Suelo o edificio municipal, cofinanciación propia (ingresos central + Bardenas) |
| **Gobierno de Navarra** | Estrategia de Vivienda Rural, ayudas rehabilitación forales |
| **NASUVINSA** | Cofinanciación técnica y económica, gestión del programa |
| **Fondos europeos** | NextGenerationEU para eficiencia energética |
| **Cooperativa** | Organización, adjudicación de usos, gestión comunitaria |
| **Socios** | Aportación económica inicial según modelo elegido |

Marco normativo: **Ley Foral de cooperativas en cesión de uso** en desarrollo para esta legislatura. Hasta su aprobación, proyectos via convenios y ayudas existentes.

---

## Stocks del modelo

| Stock | Descripción | Unidad | Valor actual Santacara |
|-------|-------------|--------|----------------------|
| `POB` Población residente | Habitantes empadronados | hab. | 858 (2024, tendencia ↓) |
| `VIV` Viviendas disponibles | Unidades habitables en oferta | uds. | Sin inventariar — cuello de botella |
| `ACT` Activos municipales | Viviendas, solares, edificios del ayuntamiento | uds./€ | Existentes, sin activar |
| `CAP` Capital municipal | Presupuesto disponible para inversión | € | Alto relativo (central + Bardenas) |
| `SER` Servicios activos | Servicios públicos y privados operativos | índice | Por encima de la media para su tamaño |
| `ATR` Atractivo municipal | Percepción externa de calidad de vida | índice | Alto objetivamente, bajo en percepción externa |

---

## Flujos del modelo

| Flujo | Stock afectado | Tipo | Descripción |
|-------|---------------|------|-------------|
| Nacimientos | POB ↑ | Entrada | Crecimiento vegetativo positivo |
| Defunciones | POB ↓ | Salida | -9 sobre nacimientos en 2023 |
| Inmigración | POB ↑ | Entrada | Nuevos residentes atraídos |
| Emigración | POB ↓ | Salida | Salida de residentes existentes |
| Rehabilitación propia | VIV ↑ | Entrada | Activación directa de activos municipales |
| Cesión de uso (Koobizitza) | VIV ↑ | Entrada | Modelo cooperativo con NASUVINSA |
| Plusvalías / cuotas | CAP ↑ | Entrada | Retorno reinvertible de la operación |
| Inversión en obra | CAP ↓ | Salida | Gasto en rehabilitación |

---

## Bucles de retroalimentación

### B1 — Despoblación (equilibrio negativo, destructivo)

```
Población baja (POB ↓)
  → Demanda de servicios cae
    → Servicios se reducen o retiran (SER ↓) [umbral ~600-700 hab.]
      → Atractivo del municipio cae (ATR ↓)
        → Emigración sube / inmigración cae
          → Población baja ← cierre del bucle B1
```

**Estado actual en Santacara**: activo pero pre-umbral. Con -5 hab./año y crecimiento vegetativo negativo, el umbral crítico se alcanzaría en ~10-15 años sin intervención.

---

### R1 — Vivienda activa (refuerzo positivo)

```
Activos municipales activados (ACT →)
  → Rehabilitación / cesión de uso (con NASUVINSA/Koobizitza)
    → Vivienda disponible aumenta (VIV ↑)
      → Demanda latente se convierte en residencia
        → Nuevos residentes llegan (POB ↑)
          → Servicios se mantienen o mejoran (SER ↑)
            → Atractivo municipal sube (ATR ↑)
              → Más demanda de vivienda ← cierre del bucle R1
```

**Palanca principal**: activar VIV desde activos municipales existentes. Es la intervención de mayor impacto y menor coste relativo.

---

### R2 — Economía circular local (refuerzo positivo)

```
Inversión en rehabilitación (CAP ↓)
  → Empleo local en construcción y proveedores
    → Gasto en comercio, hostelería y servicios locales
      → Viabilidad del tejido económico local
        → Mayor atractivo municipal (ATR ↑)
          → Más residentes → más ingresos municipales (CAP ↑)
            → Mayor capacidad de nueva inversión ← cierre del bucle R2
```

**Palanca**: cada euro invertido en obra local tiene un multiplicador interno. El Centro Sociocultural 2026 es un precedente directo de este mecanismo.

---

### R3 — Alianza pública (refuerzo positivo)

```
Ayuntamiento cede suelo o activos
  → Cooperativa (Koobizitza) organiza el proyecto
    → NASUVINSA cofinancia técnica y económicamente
      → Gobierno de Navarra activa Estrategia de Vivienda Rural
        → Coste neto para el municipio se reduce
          → Más vivienda disponible (VIV ↑)
            → Más vecinos → más ingresos municipales (CAP ↑)
              → Mayor capacidad de nuevas cesiones ← cierre del bucle R3
```

**Palanca**: la cooperación público-cooperativa reduce el riesgo inicial y hace viable la primera operación sin que el ayuntamiento asuma el coste completo.

---

## Diagrama causal simplificado

```
[Gobierno Navarra / Estrategia Vivienda Rural]
    ──R3──→ [Financiación combinada]
[NASUVINSA]
    ──R3──→ [Financiación combinada]
[Cooperativa Koobizitza]
    ──R3──→ [Rehabilitación / cesión de uso]
[Activos municipales] (central + Bardenas → CAP alto)
    ──R1──→ [Rehabilitación / cesión de uso]
[Financiación combinada]
    ──→ [Rehabilitación / cesión de uso]
[Rehabilitación / cesión de uso]
    ──→ [Vivienda disponible] ← CUELLO DE BOTELLA ACTUAL
[Demanda latente] (teletrabajadores + trabajadores GKN/Rockwool/Tafalla)
    ──→ [Vivienda disponible]
[Vivienda disponible]
    ──R1──→ [Nuevos residentes]
[Nuevos residentes]
    ──→ [Servicios activos] (escuela, médico, comercio)
[Nuevos residentes]
    ──R2──→ [Ingresos municipales]
[Rehabilitación]
    ──R2──→ [Empleo local] (constructora + proveedores)
[Empleo local]
    ──R2──→ [Ingresos municipales]
[Ingresos municipales]
    ──R2──→ [Activos municipales] ← cierre R2
[Servicios activos]
    ──→ [Atractivo municipal]
[Atractivo municipal]
    ──R1──→ [Demanda latente] ← cierre R1
[Atractivo municipal] (si cae)
    ──B1──→ [Umbral crítico ~600-700 hab.]
[Umbral crítico]
    ──B1──→ [Servicios activos] (los reduce) ← cierre B1
```

---

## Aplicación a Santacara — Estado actual y palancas

| Variable | Estado actual | Palanca disponible |
|----------|-------------|-------------------|
| POB (858 hab.) | Tendencia negativa, pre-umbral | R1: activar VIV para atraer residentes |
| VIV disponibles | Sin inventariar — cuello de botella | Inventariar + rehabilitar activos municipales |
| ACT municipales | Existentes, sin activar | Activar con modelo Koobizitza/NASUVINSA |
| CAP municipal | Alto relativo (central + Bardenas) | Cofinanciar primera operación sin depender solo de subvenciones |
| SER | Por encima de la media — escuela local, médico, fibra 1 Gbps | Comunicar externamente (ATR gap) |
| ATR | Alto objetivamente, bajo en percepción externa | mapa-calidad-vida + campaña de atracción |
| Empleo próximo | GKN, Rockwool, Tafalla, Olite (15-20 min) | Incluir en propuesta de valor del municipio |

**Diagnóstico**: todos los bucles de refuerzo (R1, R2, R3) están disponibles para activarse. El bucle B1 aún no ha alcanzado el umbral crítico. La ventana de oportunidad está abierta pero se estrecha ~5 hab./año.

---

## Por qué fallan las soluciones habituales

| Solución habitual | Por qué no funciona |
|-------------------|-------------------|
| Campañas de marketing territorial | Sin vivienda disponible, el interés no se convierte en residencia |
| Subvenciones directas a particulares para reformar | El propietario privado no tiene incentivos si no va a vivir allí |
| Creación de empleo local | Sin vivienda, los trabajadores se desplazan desde otros municipios |
| Construcción de vivienda nueva de obra | Coste muy alto sin modelo de retorno de la inversión |

**La solución correcta** ataca el cuello de botella real: crear oferta de vivienda desde los activos que el propio ayuntamiento ya posee, con un modelo de reinversión que hace el proceso autosostenible.

---

*Ver causas raíz: [ISHIKAWA.md](ISHIKAWA.md)*
*Ver DAFO: [DAFO_SANTACARA.md](DAFO_SANTACARA.md)*
*Fase metodológica: [Fase 2 — Fenomenología](../FASE_2_FENOMENOLOGIA.md)*
