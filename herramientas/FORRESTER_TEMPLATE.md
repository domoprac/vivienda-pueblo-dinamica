# Forrester — Modelo de dinámica de sistemas (genérico)

Aplicable a cualquier municipio. Rellena los valores actuales en la tabla de stocks.

## Stocks del modelo

| Stock | Descripción | Valor actual |
|-------|-------------|-------------|
| `POB` Población residente | Habitantes empadronados | |
| `VIV` Viviendas disponibles | Unidades habitables en oferta | |
| `ACT` Activos municipales | Viviendas, solares, edificios del ayuntamiento | |
| `CAP` Capital municipal | Presupuesto disponible para inversión | |
| `SER` Servicios activos | Servicios públicos y privados operativos | |
| `ATR` Atractivo municipal | Percepción externa de calidad de vida | |

---

## Flujos del modelo

| Flujo | Stock afectado | Tipo |
|-------|---------------|------|
| Nacimientos | POB ↑ | Entrada |
| Defunciones | POB ↓ | Salida |
| Inmigración | POB ↑ | Entrada |
| Emigración | POB ↓ | Salida |
| Rehabilitación propia | VIV ↑ | Entrada |
| Modelo colaborativo (cooperativa) | VIV ↑ | Entrada |
| Plusvalías / cuotas | CAP ↑ | Entrada |
| Inversión en obra | CAP ↓ | Salida |

---

## Bucles de retroalimentación

### B1 — Despoblación (equilibrio negativo)

```
Población baja (POB ↓)
  → Servicios se reducen (SER ↓) [umbral ~600-700 hab.]
    → Atractivo cae (ATR ↓)
      → Emigración sube / inmigración cae
        → Población baja ← cierre B1
```

**Señal de alerta**: crecimiento vegetativo negativo + pérdida neta de habitantes.

---

### R1 — Vivienda activa (refuerzo positivo)

```
Activos municipales activados (ACT →)
  → Rehabilitación / modelo colaborativo
    → Vivienda disponible (VIV ↑) ← CUELLO DE BOTELLA HABITUAL
      → Nuevos residentes (POB ↑)
        → Servicios se mantienen (SER ↑)
          → Atractivo sube (ATR ↑)
            → Más demanda de vivienda ← cierre R1
```

**Palanca principal**: activar VIV desde activos que el ayuntamiento ya posee.

---

### R2 — Economía circular local (refuerzo positivo)

```
Inversión en rehabilitación (CAP ↓)
  → Empleo local (construcción + proveedores)
    → Gasto en comercio y servicios locales
      → Viabilidad del tejido económico
        → Atractivo (ATR ↑)
          → Más residentes → más ingresos municipales (CAP ↑)
            → Mayor capacidad de nueva inversión ← cierre R2
```

**Palanca**: cada euro invertido localmente tiene efecto multiplicador interno.

---

### R3 — Alianza pública (refuerzo positivo)

```
Ayuntamiento cede suelo o activos
  → Entidad gestora (cooperativa u organismo público) organiza
    → Administración autonómica cofinancia
      → Coste neto para el municipio se reduce
        → Más vivienda disponible (VIV ↑)
          → Más ingresos municipales (CAP ↑)
            → Mayor capacidad de nuevas cesiones ← cierre R3
```

**Palanca**: la cooperación público-social reduce el riesgo inicial de la primera operación.

---

## Diagnóstico por perfil de municipio

| Perfil | Situación | Estrategia |
|--------|-----------|------------|
| POB > umbral, CAP alto | Ventana abierta, recursos disponibles | Activar R1 y R3 ahora |
| POB > umbral, CAP bajo | Ventana abierta, recursos limitados | Priorizar R3 (alianza pública) |
| POB cerca del umbral | Urgente | Intervención inmediata + comunicación |
| POB < umbral | Crítico | Alianzas supramunicipales + plan de emergencia |

---

## Por qué fallan las soluciones habituales

| Solución habitual | Por qué no funciona |
|-------------------|-------------------|
| Campañas de marketing | Sin vivienda disponible, el interés no se convierte en residencia |
| Subvenciones a particulares | El propietario privado no tiene incentivos si no va a vivir allí |
| Creación de empleo local | Sin vivienda, los trabajadores se desplazan desde fuera |
| Obra nueva sin modelo de retorno | Coste muy alto sin mecanismo de reinversión |

---

*Ver instancia concreta: [FORRESTER_SANTACARA.md](FORRESTER_SANTACARA.md)*
*Ver herramienta de diagnóstico: [ISHIKAWA_TEMPLATE.md](ISHIKAWA_TEMPLATE.md)*
