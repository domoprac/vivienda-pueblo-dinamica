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

## 1.11 El Factor X — Factor humano en la selección de inquilinos

### ¿Qué es el Factor X en CPS?

El **Factor X** es el componente humano que ningún modelo técnico o financiero puede eliminar: las personas no tomamos decisiones puramente racionales. Nos movemos por incentivos, percepciones, emociones, identidad social y presión del grupo. En este proyecto, el Factor X determina quién ocupa las viviendas del piloto — y esa decisión tiene consecuencias sistémicas directas sobre si el bucle R1 se activa o no.

> El modelo financiero es robusto. El modelo de selección de inquilinos es el punto más frágil del proyecto desde el punto de vista humano.

---

### El sistema de adjudicación de NASUVINSA — lo que ya existe

Antes de diseñar una regla propia, es fundamental entender qué sistema de selección tiene ya NASUVINSA, porque si las viviendas del piloto se gestionan a través de su Bolsa de Alquiler, ese sistema se aplica automáticamente.

**NASUVINSA adjudica las viviendas de su parque mediante un baremo aplicado al Censo de Solicitantes de Vivienda Protegida**, con atención personalizada y gestión de contratos y renovaciones.

Las viviendas se adjudican en riguroso orden de puntuación según el baremo establecido, entre personas inscritas en el censo que cumplan requisitos de ingresos y no dispongan de vivienda en propiedad. El proceso se celebra cada tres meses.

La selección de inquilinos de la Bolsa de Alquiler se realiza entre personas inscritas en el Censo de Solicitantes, con subvenciones al alquiler de entre el 25% y el 90% según ingresos.

#### Características clave del sistema NASUVINSA relevantes para Santacara

| Característica | Descripción | Implicación para Santacara |
|----------------|-------------|---------------------------|
| **Baremo por puntuación** | Se adjudica por orden de puntos: necesidad de vivienda, ingresos, situación familiar | El sistema es objetivo y blindado legalmente — reduce el riesgo político para el alcalde |
| **Censo de Solicitantes** | Solo pueden acceder personas inscritas en el censo navarro | Activa automáticamente la demanda externa latente — los 30 interesados internos que ya tienen vivienda propia no puntúan |
| **Sin vivienda en propiedad** | Requisito de acceso | Filtra directamente a los 30 interesados internos si son propietarios — resuelve el dilema operativo de Fase 1 sección 1.10 |
| **Precio regulado** | 5,55 €/m²/mes en zona rural (<5.000 hab.) | Para 90 m²: ~500 €/mes — asequible y dentro de las hipótesis del modelo financiero |
| **Contrato 7 años y medio** | Plazo largo de cesión | Garantiza ingresos recurrentes y arraigo real del inquilino |
| **Gestión delegada** | NASUVINSA busca inquilinos, gestiona contrato y mantenimiento | El ayuntamiento no tiene que gestionar la relación con el inquilino — reduce carga política y operativa |

**Conclusión**: si el piloto se gestiona vía NASUVINSA, el sistema de selección ya existe, es legal, objetivo y resuelve automáticamente la tensión entre demanda interna y demanda externa.

---

### El Factor X — por qué el sistema técnico no es suficiente

Incluso con un baremo objetivo, el Factor X actúa en al menos cuatro momentos críticos del proceso:

#### Momento 1 — ¿Quién se inscribe en el Censo?

El baremo solo actúa sobre quien está inscrito. La demanda latente externa (trabajadores de GKN, teletrabajadores) **no se inscribe sola** — necesita saber que existe la opción.

| Sesgo en juego | Descripción | Efecto en Santacara |
|----------------|-------------|---------------------|
| **Sesgo de disponibilidad** | Las personas solo consideran opciones que conocen | Si los trabajadores de GKN no saben que hay vivienda en Santacara, no se inscriben en el Censo |
| **Inercia de status quo** | Tendencia a no cambiar la situación actual aunque sea subóptima | "Ya me he acostumbrado a vivir en Tudela aunque sea caro" — el cambio requiere un empujón activo |
| **Coste de transacción percibido** | Inscribirse en el Censo parece complicado o burocrático | Reducir la fricción: acompañar el proceso de inscripción desde la campaña de captación |

**Corrección**: la campaña activa en empleadores (Fase 4, sección C1) no es solo marketing — es reducción de fricción cognitiva. Hay que llevar el proceso de inscripción al trabajador, no esperar que el trabajador lo encuentre solo.

#### Momento 2 — ¿Quién renuncia una vez adjudicado?

La exclusión del Censo por renuncia a una vivienda adjudicada supone una penalización de 2-3 años sin poder optar de nuevo. Esto desincentiva la renuncia especulativa, pero no elimina las renuncias por razones emocionales o sociales.

| Causa de renuncia probable | Mecanismo psicológico | Corrección |
|---------------------------|----------------------|------------|
| "No conozco a nadie en Santacara" | Miedo a la soledad y al desarraigo | Protocolo de acogida activo antes de la firma (D1 en Fase 4) |
| "Mi familia dice que es mala idea" | Presión social del entorno cercano | Testimonios de residentes actuales satisfechos; visita al municipio antes de decidir |
| "El pueblo me parece demasiado pequeño" | Efecto de contraste con ciudad | Mostrar la realidad con datos: servicios, conectividad, calidad de vida — no solo la estética rural |
| "Tengo miedo de quedarme atrapado si no funciona" | Aversión a la pérdida (Kahneman) | Claridad sobre las condiciones de salida del contrato; no presentarlo como decisión irreversible |

#### Momento 3 — ¿Quién se queda después de los primeros meses?

El arraigo no es automático. Los primeros 6-12 meses son críticos: si el nuevo residente no construye vínculos sociales reales, la probabilidad de abandono se dispara.

| Factor de abandono | Mecanismo | Corrección |
|-------------------|-----------|------------|
| Aislamiento social | Sin red de relaciones, el municipio "no tiene vida" | Padrino/madrina local; integración en actividades del pueblo |
| Disonancia cognitiva post-decisión | "Tomé la decisión equivocada" — se buscan confirmaciones del error | Seguimiento activo durante el primer año; resolver problemas antes de que cristalicen en narrative de fracaso |
| Cambio de empleo o situación laboral | El trabajo en GKN/Rockwool era el ancla; si cambia, el motivo de vivir aquí desaparece | Diversificar el perfil de inquilinos: no solo trabajadores de una empresa, también teletrabajadores |

#### Momento 4 — ¿Qué perciben los vecinos actuales?

El Factor X no actúa solo sobre los nuevos residentes — también sobre los vecinos actuales. Su reacción determina si el entorno es acogedor o hostil para los recién llegados.

| Percepción de vecinos | Mecanismo psicológico | Riesgo | Corrección |
|----------------------|----------------------|--------|------------|
| "Les están dando lo mejor a los de fuera" | Sesgo de equidad — injusticia percibida | Resistencia pública; sabotaje sutil de la acogida | Comunicación previa sobre el proceso de selección objetivo (baremo NASUVINSA) |
| "Van a cambiar el pueblo" | Amenaza a la identidad local | Rechazo social a los nuevos vecinos | Participación de vecinos actuales en el protocolo de acogida — los convierte en protagonistas |
| "El alcalde favorece a sus amigos" | Desconfianza institucional, especialmente en municipios pequeños | Pérdida de legitimidad del proyecto | El baremo objetivo de NASUVINSA como escudo: "No es el alcalde quien elige, es un sistema regulado por el Gobierno de Navarra" |

---

### Regla robusta de selección — propuesta integrada

Integrando el sistema NASUVINSA con las correcciones del Factor X, la regla de selección recomendada para el piloto de Santacara es:

```
REGLA DE SELECCIÓN DE INQUILINOS — PILOTO SANTACARA

1. CANAL: Gestión vía Bolsa de Alquiler NASUVINSA
   → Baremo objetivo, legal, blindado políticamente

2. FILTRO DE ELEGIBILIDAD (requisitos NASUVINSA):
   → Inscrito en Censo de Solicitantes de Vivienda Protegida de Navarra
   → Sin vivienda en propiedad (filtra demanda interna de propietarios)
   → Ingresos dentro de los tramos establecidos

3. CRITERIO DE PRIORIDAD MUNICIPAL (propuesto como preferencia en el Censo):
   → Prioridad 1: nueva residencia + empleo en radio 30 min de Santacara
   → Prioridad 2: nueva residencia + teletrabajo
   → Prioridad 3: residente actual sin vivienda propia (mejora habitacional)

4. REDUCCIÓN DE FRICCIÓN (antes de la inscripción):
   → Campaña activa en RRHH de GKN, Rockwool, polígonos
   → Acompañamiento en el proceso de inscripción al Censo
   → Visita al municipio antes de la firma del contrato

5. PROTOCOLO DE ARRAIGO (después de la firma):
   → Padrino/madrina local asignado antes de la llegada
   → Seguimiento activo durante los primeros 12 meses
   → Revisión de satisfacción a los 6 y 12 meses
```

---

### Análisis desde la sociología, psicología y antropología

| Disciplina | Concepto aplicado | Aplicación a Santacara |
|------------|------------------|----------------------|
| **Psicología conductual** (Kahneman, Thaler) | *Nudge* — arquitectura de decisiones que facilita la elección correcta sin prohibir las otras | El baremo NASUVINSA es el nudge institucional: no obliga, pero hace que la opción más alineada con el objetivo público sea también la más fácil de acceder |
| **Sociología del arraigo** (Granovetter) | Los vínculos débiles (conocidos, no amigos íntimos) son más importantes que los vínculos fuertes para integrarse en una nueva comunidad | El padrino/madrina no tiene que ser el mejor amigo del nuevo vecino — basta con que sea un puente hacia la red social del pueblo |
| **Antropología de la comunidad rural** | Las comunidades pequeñas tienen alta memoria social y baja tolerancia a la percepción de injusticia | La transparencia del proceso de selección no es un lujo — es una condición de supervivencia política del proyecto |
| **Economía conductual** (Ariely) | La aversión a la pérdida pesa el doble que la ganancia equivalente | Presentar la vivienda en Santacara como "recuperar calidad de vida que estás perdiendo pagando caro en Tudela" es más efectivo que "gana dinero viviendo aquí" |
| **Psicología social** (Cialdini) | El principio de prueba social: las personas imitan las decisiones de otros similares a ellos | Los primeros 2 inquilinos son críticos: si están satisfechos y lo cuentan, la lista de espera crece sola. Si no lo están, el proyecto muere antes de escalar |

---

*Siguiente fase: [Fase 2 — Fenomenología y análisis de la complejidad](FASE_2_FENOMENOLOGIA.md)*
