# Modelo de Dinámica de Sistemas: Promoción de Vivienda Municipal

Este proyecto modela el sistema de gestión de vivienda de un Ayuntamiento rural, enfocado en la **economía circular local** y la **fijación de población**.

## 🏘️ El Sistema
El modelo se basa en la recuperación de activos municipales y privados (ruinas, impagos, casas de maestros) para su reforma y puesta en el mercado (venta o alquiler).

### Objetivos Clave:
* **Fijación de Población:** Atraer nuevos vecinos y retener a los jóvenes.
* **Economía Local:** Prioridad absoluta a proveedores y negocios del municipio.
* **Autosuficiencia:** Viviendas energéticamente eficientes (FV) para reducir costes.
* **Reinversión:** El flujo de capital de las ventas se reinvierte en nuevas promociones.

## 📊 Mapa Causal (Forrester)
Este diagrama muestra cómo interactúan los actores y los recursos:

```mermaid
graph TD
    subgraph Activos
        Suelo[Suelo Urbanizable] -->|Conversión| Obra[Proyectos de Reforma]
        Casas[Casas Cura/Médico/Maestros] -->|Conversión| Obra
        Ruina[Requisas por Ruina/Impagos] -->|Conversión| Obra
    end

    subgraph Economia_Local
        Obra -->|Concurso Prioridad Local| Prov[Proveedores Locales]
        Prov -->|Multiplicador| Empleo[Empleo y Renta Local]
        Empleo -->|Impulso| Comercio[Farmacia, Súper, Bares]
        Comercio -->|Sostenibilidad| Servicios[Servicios Públicos/Escuela]
    end

    subgraph Modelo_Negocio
        FV[Eficiencia FV] -->|Atractivo| Valor[Valor de Vivienda]
        Obra -->|Plusvalía| Valor
        Valor -->|Venta/Alquiler| Cash[Retorno de Capital]
        Cash -->|Reinversión| Presupuesto[Presupuesto Promoción]
        Presupuesto -->|Compra Vivienda Privada| Obra
    end

    Servicios -->|Retención| Vecinos[Nuevos Vecinos / Jóvenes]
    Vecinos -->|Demanda| Obra
