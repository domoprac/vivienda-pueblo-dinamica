# Fase 1 — Metodología CPS

## 1.1 Definición del problema

> Un municipio español pierde población de forma sostenida porque no dispone de vivienda disponible y asequible para acoger a nuevos residentes, a pesar de tener activos municipales infrautilizados, servicios funcionales y una calidad de vida objetivamente alta respecto a su coste.

La clave del CPS en esta fase es no confundir el síntoma (despoblación) con el problema real. El problema no es que la gente no quiera vivir en pueblos — la demanda existe. El problema es que **no hay vivienda donde alojarlos**.

## 1.2 Tipología del problema

| Dimensión | Evaluación |
|-----------|------------|
| Estructuración | Mal estructurado — múltiples actores, objetivos difusos, soluciones no evidentes |
| Dinamismo | Altamente dinámico — demográfico, económico, normativo, social |
| Tipo CPS | Problema de política pública (policy problem) |
| Reversibilidad | Parcialmente reversible — el bucle puede romperse con intervención temprana |

## 1.3 Características de dificultad (según CPS)

- **Alta complejidad**: interactúan ayuntamiento, propietarios, nuevos residentes, administración autonómica, proveedores locales, mercado laboral cercano
- **Durabilidad**: el proceso de despoblación lleva décadas instalado en muchos municipios
- **Conectividad**: vivienda → población → servicios → atractivo → vivienda (bucle causal cerrado)
- **Imprevisibilidad**: variables exógenas (migración urbana, normativa, subvenciones, mercado inmobiliario)
- **Opacidad**: el estado real del parque de vivienda municipal raramente está inventariado
- **Temporalidad**: existe un umbral crítico de población (~600-700 hab.) por debajo del cual la retirada de servicios se vuelve irreversible a corto plazo

## 1.4 Declaración formal del problema (ES / NO ES)

| | ES | NO ES |
|--|-----|-------|
| El problema | Falta de vivienda disponible y asequible para nuevos residentes | Falta de demanda de residencia rural |
| El alcance | Gestión activa del parque de vivienda municipal | Política urbanística regional o nacional |
| El agente | Ayuntamiento con activos propios y capacidad de acción | Mercado inmobiliario privado |
| La solución buscada | Modelo replicable de economía circular municipal | Proyecto puntual de un municipio concreto |

## 1.5 Actores y stakeholders (análisis CATWOE)

| Rol | Quiénes |
|-----|---------|
| **C** Customers (beneficiarios) | Familias y trabajadores que buscan residencia rural asequible |
| **A** Actors (ejecutores) | Ayuntamiento, empresa constructora local, gestores municipales |
| **T** Transformation (cambio) | Viviendas vacías/ruinas → hogares ocupados → nuevos vecinos → más servicios |
| **W** Worldview (supuesto) | La vivienda municipal gestionada activamente es el motor de la economía circular local |
| **O** Owner (propietario del sistema) | Ayuntamiento |
| **E** Environment (restricciones) | Normativa urbanística, presupuesto municipal, normativa de ruina y expropiación, FEDER/LEADER |

## 1.6 Valores prioritarios del proyecto

1. **Sostenibilidad financiera** — el modelo debe autofinanciarse a medio plazo (plusvalías reinvertidas)
2. **Replicabilidad** — válido para cualquier municipio español, no solo para el caso piloto
3. **Acción municipal autónoma** — el ayuntamiento puede actuar sin depender de terceros
4. **Transparencia** — todos los datos, modelos y herramientas son abiertos (open source)

## 1.7 Herramientas de diagnóstico aplicadas

| Herramienta | Estado | Archivos |
|-------------|--------|---------|
| DAFO | ✅ Completo | [Template](herramientas/DAFO_TEMPLATE.md) · [Santacara](herramientas/DAFO_SANTACARA.md) |
| Ishikawa (causa-raíz) | ✅ Completo | [Template](herramientas/ISHIKAWA_TEMPLATE.md) · [Santacara](herramientas/ISHIKAWA_SANTACARA.md) · [SVG](herramientas/graficos/ISHIKAWA.svg) · [Metodología](herramientas/ISHIKAWA.md) |
| Forrester (dinámica de sistemas) | ✅ Completo | [Template](herramientas/FORRESTER_TEMPLATE.md) · [Santacara](herramientas/FORRESTER_SANTACARA.md) · [SVG](herramientas/graficos/FORRESTER.svg) · [Metodología](herramientas/FORRESTER.md) |
| Stakeholders (mapa de actores) | ✅ Completo | [Template](herramientas/STAKEHOLDERS_TEMPLATE.md) · [Santacara](herramientas/STAKEHOLDERS_SANTACARA.md) |

## 1.8 Hipótesis de trabajo — estado de validación

| # | Hipótesis | Estado | Evidencia (Fase 3) |
|---|-----------|--------|-------------------|
| 1 | El municipio tiene activos de vivienda infrautilizados cuyo valor de rehabilitación es inferior al precio de venta o alquiler de mercado | ✅ Validada | Casa médico + casa cura ya en rehabilitación; precio venta mercado 650-750 €/m² vs. coste rehabilitación 800 €/m² cubierto al 75% por Plan Rural Navarra |
| 2 | Existe demanda real de residencia rural en el radio de influencia del municipio | ✅ Parcialmente validada | 30 interesados confirmados (residentes actuales); demanda externa latente estimada 35-105 personas pendiente de verificación con empleadores del entorno (GKN, Rockwool, polígonos) |
| 3 | Las subvenciones autonómicas disponibles reducen significativamente el coste neto de rehabilitación | ✅ Validada | Plan Rehabilitación Rural Navarra/NASUVINSA: 75% del coste de obra, máx. 60.000 €/vivienda — coste neto municipal ~40.000 € para 2 viviendas |
| 4 | El multiplicador económico local compensa con creces la inversión inicial en un horizonte de 5-10 años | ✅ Validada (modelo) | Retorno sobre inversión neta: 27-33%/año; período de retorno 3-4 años; a 10 años el parque genera +84.000 € sobre la inversión inicial — ver Fase 3, sección 3.5 |

> ⚠️ **Hipótesis pendiente de validación externa**: la demanda de nuevos residentes externos (H2) está estimada pero no verificada. El paso crítico es abrir la lista de espera antes del lanzamiento y contactar con los departamentos de RRHH de los empleadores del entorno. Ver Fase 3, sección 3.6.

## 1.9 Soluciones intentadas que mantienen el problema (Nardone)

Uno de los pilares del **Problem Solving Estratégico de Giorgio Nardone** es que, antes de diseñar cualquier intervención, hay que identificar con precisión qué soluciones se han intentado hasta ahora y por qué no solo no han funcionado, sino que con frecuencia **han contribuido a mantener o agravar el problema**.

> *"Son las soluciones las que explican los problemas, no al revés."*
> — Giorgio Nardone, *Problem Solving Estratégico*

Esta lógica contraintuitiva es especialmente potente en la despoblación rural, donde décadas de intervenciones bienintencionadas han producido resultados decepcionantes. Identificar el patrón de fracaso es el primer paso para romperlo.

### Soluciones intentadas históricamente en municipios españoles en despoblación

| Solución intentada | Lógica implícita | Por qué mantiene el problema |
|--------------------|-----------------|------------------------------|
| **Campañas de imagen y marketing territorial** | "Si la gente supiera lo bien que se vive aquí, vendría" | Sin vivienda disponible, el interés generado no se convierte en residencia. El embudo se bloquea siempre en el mismo punto. |
| **Subvenciones directas a particulares para reformar vivienda propia** | "Si bajamos el coste, el propietario reformará y alquilará" | El propietario privado sin intención de residir no tiene incentivo suficiente. La subvención se usa para mejorar el patrimonio, no para generar oferta de alquiler. |
| **Planes de empleo local** | "Si hay trabajo aquí, la gente no se irá" | Sin vivienda, los trabajadores se desplazan desde otros municipios. El empleo no ancla población si no hay dónde vivir. |
| **Construcción de VPO nueva** | "Si construimos vivienda nueva y barata, vendrá gente" | Coste inicial muy alto, plazo de 4-6 años, sin modelo de retorno. Agota el presupuesto municipal en una sola operación y depende de demanda que no está verificada. |
| **Ayudas al empadronamiento** (bonificaciones fiscales, cheques bebé) | "Si bajamos el coste de vivir aquí, la gente se quedará" | Sin vivienda disponible donde empadronarse, el incentivo fiscal no puede activarse. Es una solución al síntoma, no al cuello de botella. |
| **Planes de desarrollo rural (LEADER, FEDER)** | "Con inversión en infraestructuras y tejido productivo, el municipio se dinamizará" | Generan infraestructura y actividad económica, pero no resuelven el problema de acceso a vivienda. Los trabajadores de los nuevos proyectos viven en otros municipios. |
| **Fusiones municipales** | "Unidos tendremos más recursos para sostener servicios" | No aborda la causa raíz (falta de vivienda). Reduce la identidad local sin aumentar la oferta residencial. Suele generar rechazo político y social. |

### Patrón común de fracaso

Todas las soluciones anteriores comparten una lógica errónea: **actúan sobre síntomas o consecuencias** (imagen, empleo, costes fiscales, infraestructura) sin atacar el **cuello de botella estructural**: la inexistencia de vivienda disponible y asequible para nuevos residentes.

En términos de Nardone, estas soluciones son **"tentativas de solución que mantienen el problema"**: cada vez que se aplica una de ellas sin resultado, se refuerza la creencia de que el problema es irresoluble, lo que reduce la voluntad política de intentar algo distinto.

### La ruptura del patrón en Santacara

La intervención propuesta rompe el patrón porque actúa directamente sobre el cuello de botella — la vivienda disponible — usando activos que el ayuntamiento ya posee, con financiación ya existente (Plan Rural Navarra / NASUVINSA), y con un modelo de retorno que hace la solución autosostenible. No depende de que ocurra nada externo: el ayuntamiento puede ejecutarla de forma autónoma.

## 1.10 Análisis de sesgos del proyecto

Todo proceso de diagnóstico y diseño de soluciones está expuesto a sesgos cognitivos que distorsionan la percepción del problema, la interpretación de los datos y las decisiones que se toman. Identificarlos explícitamente es una práctica de rigor metodológico — no una autocrítica, sino una herramienta para tomar mejores decisiones.

> *"El mayor obstáculo para resolver un problema no es la ignorancia, sino la ilusión del conocimiento."*
> — Atribuido a Daniel Kahneman, *Thinking, Fast and Slow*

En este proyecto se han identificado los siguientes sesgos relevantes:

---

### Sesgo 1 — Sesgo de confirmación por implicación personal del decisor

**Descripción del sesgo**: el sesgo de confirmación lleva a buscar, interpretar y recordar la información de forma que confirme las creencias o hipótesis previas, ignorando o minimizando la evidencia contradictoria.

**Manifestación concreta en este proyecto**: el alcalde de Santacara es menor de 35 años y no tiene vivienda propia. Esto significa que el principal decisor político del proyecto **vive el problema en primera persona** — conoce desde dentro la dificultad de acceder a vivienda asequible en un municipio rural y tiene una motivación genuina y directa para resolverlo.

Esta circunstancia es un activo real del proyecto (mayor compromiso, mayor velocidad de decisión, mayor empatía con el perfil de los potenciales nuevos residentes), pero también genera un riesgo específico de sesgo:

| Riesgo | Manifestación probable | Corrección |
|--------|----------------------|------------|
| Sobreestimar la demanda externa | "Si yo lo necesito, muchos otros también" — extrapolar la experiencia propia a una demanda masiva no verificada | Validar la demanda con datos externos antes de escalar (lista de espera real, encuesta en empleadores) |
| Infraestimar las resistencias internas | Los vecinos con vivienda propia pueden tener intereses distintos a los del alcalde — no ven el problema de la misma manera | Incluir en el proceso a vecinos con perfil distinto; ver STAKEHOLDERS_SANTACARA.md sección propietarios |
| Urgencia que acelera decisiones sin datos | La implicación personal puede llevar a actuar antes de tener el inventario real validado o el modelo financiero confirmado | Separar el ritmo político del ritmo técnico; cada hito requiere datos, no solo voluntad |
| Sesgo de solución prematura | El modelo Koobizitza / cesión de uso puede estar sobredimensionado porque responde al perfil del decisor (joven sin propiedad) más que a la demanda real del municipio | Contrastar con el perfil real de los interesados antes de elegir el modelo de tenencia definitivo |

**Corrección sistémica**: incluir en el equipo nuclear (ver Fase 5, sección 5.2) al menos un perfil con perspectiva distinta — vecino con vivienda propia, propietario de inmueble vacío, o técnico externo sin vinculación emocional al proyecto.

---

### Sesgo 2 — Confusión entre demanda interna y demanda de captación

**Descripción del sesgo**: el sesgo de disponibilidad lleva a sobreponderar la información más accesible y cercana. Cuando los primeros interesados en el proyecto son personas del entorno inmediato, se corre el riesgo de confundir esa señal con validación de la hipótesis central.

**Manifestación concreta en este proyecto**: existen aproximadamente **30 personas interesadas en el proyecto que ya residen en Santacara**. Este dato es relevante y positivo, pero requiere una interpretación cuidadosa:

| Dimensión | Interpretación incorrecta | Interpretación correcta |
|-----------|--------------------------|------------------------|
| ¿Qué valida? | "Hay 30 interesados — la demanda está confirmada" | Valida que hay necesidad de mejora habitacional interna, no que lleguen nuevos residentes |
| ¿Qué impacto tiene en población? | "30 interesados = 30 potenciales nuevos vecinos" | **Impacto en población = 0** a corto plazo — son personas ya empadronadas |
| ¿Qué impacto tiene en el modelo financiero? | Ninguno — el retorno por alquiler funciona igual con residentes actuales que con nuevos | ✅ El modelo financiero es válido independientemente del origen del inquilino |
| ¿Qué impacto tiene en los indicadores? | Si se mide éxito solo por variación de padrón, el piloto parecerá fallido | Redefinir indicadores de corto plazo (ver tabla siguiente) |

### Redefinición de indicadores para el corto plazo

La existencia de demanda interna obliga a **separar dos horizontes temporales** con indicadores distintos:

| Horizonte | Indicador principal | Meta realista |
|-----------|---------------------|---------------|
| **Corto plazo (año 1-2)** | Viviendas ocupadas + calidad habitacional mejorada | 2 viviendas ocupadas (residentes actuales o nuevos) |
| **Corto plazo (año 1-2)** | Lista de espera externa verificada | ≥5 familias externas en lista antes del lanzamiento |
| **Medio plazo (año 2-4)** | Nuevos empadronamientos netos | +4 a +8 personas nuevas en padrón |
| **Largo plazo (año 4+)** | Tendencia del padrón revertida | De −5/año a 0 o positivo |

**Consecuencia operativa clave**: las 2 viviendas del piloto (casa médico + casa cura) deberían reservarse **prioritariamente para nuevos residentes externos**, incluso si hay demanda interna. Si se asignan a residentes actuales, el modelo mejora la calidad de vida pero no activa el bucle R1 (vivienda → nueva población → más servicios). Esto requiere una decisión política explícita y comunicada con transparencia a los vecinos.

---

### Mapa de sesgos del proyecto (resumen)

| Sesgo | Origen | Riesgo principal | Corrección aplicada |
|-------|--------|-----------------|---------------------|
| Confirmación por implicación personal | Alcalde <35, sin vivienda propia | Sobreestimar demanda; infraestimar resistencias | Equipo nuclear diverso; validación externa de demanda |
| Disponibilidad de demanda interna | 30 interesados ya residentes | Confundir mejora habitacional con captación de población | Separar indicadores por horizonte; reserva para externos |
| Sesgo de solución única | Todo el proyecto apunta a un modelo (Koobizitza / Plan Rural) | Descuidar alternativas si el modelo elegido encuentra obstáculos | Cartera de soluciones alternativas documentada en Fase 4 |
| Optimismo de planificación | Subvenciones al 75%, retorno en 3 años | Subestimar retrasos, obstáculos burocráticos o cambios normativos | Escenario pesimista documentado en Fase 3 (55% subvención, retorno 6,7 años) |
| Sesgo de anclaje | El primer dato concreto (858 hab.) ancla todas las proyecciones | Proyecciones de población demasiado conservadoras o demasiado optimistas | Usar rango (escenario base + pesimista + optimista) en todos los modelos |

---

*Siguiente fase: [Fase 2 — Fenomenología y análisis de la complejidad](FASE_2_FENOMENOLOGIA.md)*
