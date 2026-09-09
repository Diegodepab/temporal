# 1. Basic Information (Información Básica)

### DOI
* **Do you already have a DOI for this upload?**
  * no. Zenodo asignará un DOI automáticamente al publicar o reservar.

---

### Resource type
* **Resource type:** `Dataset`

---

### Title (Título)
* Mediterranean Forest Tree Type Database: Major Pure Balanced LC

---

### Additional titles (Títulos adicionales)

#### Título adicional 1 (Español)
* **Title:** `Tipos de árboles de bosques mediterráneos: estratos puros principales balanceados`
* **Type:** `Translated title`
* **Language:** `Spanish`

#### Título adicional 2 (Inglés alternativo)
* **Title:** `Mediterranean Forest Tree Type To Model Nomfemix Major Pure Balanced Lc`
* **Type:** `Alternative title`
* **Language:** `English`

---

### Publication date (Fecha de publicación)

* 2026-09-09

---

### Creators / Authors (Autores)

---

# 2. Description (Campo Principal)

> En Zenodo: Pegar en la caja principal de **Description**.

### [Opción Inglés - Recomendada]
## Mediterranean Forest Tree Type Database (Major Pure Balanced LC)

The **Mediterranean Forest Tree Type Database: Major Pure Balanced LC** is a harmonized, multi-source tabular dataset designed to support machine learning classification, species distribution modeling (SDM), and geospatial analysis of forest ecosystems across the Mediterranean basin.

This dataset aggregates and standardizes vegetation inventory records and cartographic observations from diverse national forest inventories, regional databases, and European initiatives (including the Spanish Forest Map MFE50, European Vegetation Archive EVA, CircumMed Pine FOR database, Turkish and Moroccan forest inventories, Lebanese LULC, and Tunisian forestry surveys). The collection focuses on major pure forest tree types and balanced land cover categories, specifically excluding mixed strata (`noMFEmix`) to provide high-fidelity training and evaluation benchmarks for ecological models and remote sensing classification.

The dataset comprises **52,819 records and 10 attributes**, covering spatial coordinates, hierarchical land cover and forest type classifications, taxonomic subcategories, and source provenance identifiers.

### Key Features
- **Geographic Coverage:** Multi-country Mediterranean coverage (Spain, France, Italy, Greece, Turkey, Lebanon, Tunisia, Morocco, and Balkan region).
- **Thematic Scope:** Major pure forest types (broadleaved evergreen, deciduous, coniferous) alongside balanced complementary land-cover classes (cropland, shrubland, grassland, bare soil, wetland, water).
- **Standardization:** Fully harmonized into a uniform 10-variable tabular schema with 100% data completeness (0% missing values across key fields).


### [Opción Español]
## Base de Datos de Tipos de Árboles de Bosques Mediterráneos (Major Pure Balanced LC)

La **Base de Datos de Tipos de Árboles de Bosques Mediterráneos: Major Pure Balanced LC** es un conjunto de datos tabular armonizado y multifuente diseñado para dar soporte a la clasificación mediante aprendizaje automático, el modelado de distribución de especies (SDM) y el análisis geoespacial de ecosistemas forestales en la cuenca mediterránea.

Este conjunto de datos recopila y estandariza registros de inventarios de vegetación y observaciones cartográficas procedentes de diversos inventarios forestales nacionales, bases de datos regionales e iniciativas europeas (incluyendo el Mapa Forestal de España MFE50, el European Vegetation Archive EVA, la base de datos CircumMed Pine FOR, inventarios de Turquía y Marruecos, el LULC del Líbano y muestreos forestales de Túnez). La colección se centra en los principales tipos de árboles forestales puros y categorías balanceadas de cobertura del suelo, excluyendo expresamente los estratos mixtos (`noMFEmix`) con el fin de proporcionar patrones de referencia de alta fidelidad para modelos ecológicos y clasificación mediante teledetección.

El dataset contiene **52.819 registros y 10 variables**, cubriendo coordenadas espaciales, clasificaciones jerárquicas de cobertura del suelo y tipos forestales, subcategorías taxonómicas e identificadores de procedencia de los datos.

### Características Clave
- **Cobertura Geográfica:** Cobertura multipaís en el Mediterráneo (España, Francia, Italia, Grecia, Turquía, Líbano, Túnez, Marruecos y región balcánica).
- **Ámbito Temático:** Tipos forestales puros principales (perennifolios de hoja ancha, caducifolios, coníferas) junto a clases complementarias balanceadas de cobertura del suelo (cultivos, matorral, pastizal, suelo desnudo, humedal, agua).
- **Estandarización:** Totalmente armonizado en un esquema tabular uniforme de 10 variables con 100% de completitud (0% de valores nulos).


---

# 3. Additional Descriptions

> **+ Add another description** 

---

## 3.1. Additional Description &rarr; Type: `Abstract`

### [Inglés]
* **Type:** `Abstract`
* **Language:** `English`

### Abstract
**What it is:** A structured, multi-country tabular dataset comprising 52,819 georeferenced observations of Mediterranean forest tree types and associated land-cover categories across Southern Europe, North Africa, and the Eastern Mediterranean.

**Dataset Profile:**
- **Total Records:** 52,819 observations
- **Variables:** 10 harmonized columns (ID, provenance, geographic coordinates, hierarchical forest & land cover classification, dataset source, observational comments)
- **Data Integrity:** 100% completeness (zero missing values across all columns)
- **Format & Encoding:** CSV, UTF-8-SIG, semicolon (`;`) delimited, 4.81 MB

**Intended Applications:**
- Species and forest-type distribution modeling (SDM) in Mediterranean biomes.
- Training and benchmarking remote sensing classification algorithms (e.g., Copernicus Sentinel-2 land cover mapping).
- Biodiversity monitoring, macroecological pattern analysis, and forest conservation planning under climate change scenarios.


### [Español]
* **Type:** `Abstract`
* **Language:** `Spanish`

### Resumen
**¿Qué es?:** Un conjunto de datos tabular estructurado y multipaís compuesto por 52.819 observaciones georreferenciadas de tipos de árboles de bosques mediterráneos y categorías asociadas de cobertura del suelo en el sur de Europa, norte de África y Mediterráneo oriental.

**Perfil del Dataset:**
- **Total de Registros:** 52.819 observaciones
- **Variables:** 10 columnas armonizadas (identificador, procedencia, coordenadas geográficas, clasificación jerárquica de cobertura y tipo forestal, fuente del dataset, comentarios de observación)
- **Integridad de Datos:** 100% de completitud (cero valores nulos en todas las columnas)
- **Formato y Codificación:** CSV, UTF-8-SIG, delimitado por punto y coma (`;`), 4,81 MB

**Aplicaciones Previstas:**
- Modelado de distribución de especies y tipos forestales (SDM) en biomas mediterráneos.
- Entrenamiento y evaluación de algoritmos de clasificación en teledetección (p. ej., cartografía de cobertura del suelo con Copernicus Sentinel-2).
- Monitorización de biodiversidad, análisis de patrones macroecológicos y planificación para la conservación de bosques ante escenarios de cambio climático.


---

## 3.2. Additional Description &rarr; Type: `Methods`

### [Inglés]
* **Type:** `Methods`
* **Language:** `English`

### Methodology & Data Harmonization

The dataset was constructed through an integration and quality-control workflow aimed at synthesizing disparate forestry inventories into a machine-learning-ready resource:

1. **Source Aggregation:** Primary records were harvested from authoritative national inventories and community repositories (Spanish Forest Map MFE50, European Vegetation Archive EVA, CircumMed Pine FOR database, regional inventories across Greece, Turkey, Morocco, Tunisia, Lebanon, and Copernicus/Sentinel tile chips).
2. **Filtering & Strata Selection (`noMFEmix`):** Mixed-species forest polygons and ambiguous forest transitions were excluded to isolate pure, dominant forest stands and reduce spectral and taxonomic confusion in downstream classification models.
3. **Class Balancing (`MAJOR_pure_balanced_LC`):** Sample instances across major forest types and surrounding land-cover categories (shrubland, cropland, grassland, bare soil, built) were balanced to mitigate severe class imbalance.
4. **Coordinate Standardization:** Geographic coordinates were extracted and formatted in decimal degrees (longitude/latitude).



### [Español]
* **Type:** `Methods`
* **Language:** `Spanish`

### Metodología y Armonización de Datos

El conjunto de datos se construyó mediante un flujo de trabajo de integración y control de calidad con el objetivo de sintetizar diversos inventarios forestales en un recurso listo para aprendizaje automático:

1. **Recopilación de Fuentes:** Los registros originales se obtuvieron de inventarios nacionales oficiales y repositorios de la comunidad científica (Mapa Forestal de España MFE50, European Vegetation Archive EVA, base de datos CircumMed Pine FOR, inventarios regionales de Grecia, Turquía, Marruecos, Túnez, Líbano y cuadrículas de satélite Copernicus/Sentinel).
2. **Filtrado y Selección de Estratos (`noMFEmix`):** Se excluyeron los polígonos forestales mixtos y las transiciones forestales ambiguas para aislar masas forestales puras dominantes y reducir la confusión espectral y taxonómica en los modelos de clasificación posteriores.
3. **Balanceo de Clases (`MAJOR_pure_balanced_LC`):** Se balancearon las muestras de los principales tipos forestales y de las categorías circundantes de cobertura del suelo (matorral, cultivo, pastizal, suelo desnudo, edificado) para evitar desequilibrios severos en las clases.
4. **Estandarización de Coordenadas:** Las coordenadas geográficas fueron extraídas y estructuradas en grados decimales (longitud/latitud).

---

## 3.3. Additional Description &rarr; Type: `Technical info`

### [Inglés]
* **Type:** `Technical info`
* **Language:** `English`

### Technical Specifications & Data Dictionary

#### 1. File Specifications
- **Filename:** `MEDITERRANEAN_FOREST_TREE_TYPE_DB_to_model_noMFEmix_MAJOR_pure_balanced_LC.csv`
- **File Size:** ~4.59 MB (4,811,148 bytes)
- **Format / MIME Type:** CSV (`text/csv`)
- **Character Encoding:** UTF-8 with Byte Order Mark (`UTF-8-SIG`)
- **Field Delimiter:** Semicolon (`;`)
- **Checksum (SHA-256):** `11f6a081b519777ef8f6fa6195cf8577fcbbd32d077e984c8c7b25685331abbb`

#### 2. Data Quality Metrics
- **Total Records:** 52,819
- **Total Attributes:** 10
- **Completeness:** 100% (0% null or missing values across all columns)
- **Consistency:** 100%
- **Uniqueness:** 100% distinct records

#### 3. Column Data Dictionary
| Column Name | Data Type | Null % | Description / Semantic Concept |
| :--- | :--- | :--- | :--- |
| `ID` | Integer | 0% | Unique sequential identifier assigned to each record (1 to 52,819). |
| `Database_origin` | String | 0% | Source database or national repository. E.g., Spanish FOR Map, EVA, Greece_FOR_map, Morocco_FOR_inventory, Turkiye_FOR_inventory, Lebanon_LULC2017, NFI_Tunisia. |
| `ID_original` | String | 0% | Original identifier from the primary source inventory (enables lineage and traceability). |
| `longitude` | Decimal / String | 0% | Geographic longitude in decimal degrees (comma `,` decimal separator). |
| `latitude` | Decimal / String | 0% | Geographic latitude in decimal degrees (comma `,` decimal separator). |
| `category` | String | 0% | Broad land cover class: `FOR` (Forest), `SHRUBLAND`, `GRASS`, `CROPLAND`, `BUILT`, `BARE SOIL`, `WETLAND`, `WATER`, `OPF`. |
| `FOR_type` | String | 0% | Forest structural type: `Broadleaved evergreen`, `Broadleaved deciduous`, `Coniferous`, or non-forest category labels. |
| `subcategory` | String | 0% | Specific taxonomic or dominant tree species unit (e.g., `F-Quercus coccifera`, `Pinus halepensis`, `Quercus ilex`). |
| `Dataset` | String | 0% | Specific sub-collection or survey name (e.g., CircumMed Pine FOR database, VegItaly, SOPHY France, AMS-VegBank, Albanian Vegetation Database). |
| `Comments` | String | 0% | Observation notes or remarks (hyphen `-` where no remarks are present). |

---

### [Español]
* **Type:** `Technical info`
* **Language:** `Spanish`

### Especificaciones Técnicas y Diccionario de Datos

#### 1. Especificaciones del Archivo
- **Nombre del archivo:** `MEDITERRANEAN_FOREST_TREE_TYPE_DB_to_model_noMFEmix_MAJOR_pure_balanced_LC.csv`
- **Tamaño del archivo:** ~4,59 MB (4.811.148 bytes)
- **Formato / Tipo MIME:** CSV (`text/csv`)
- **Codificación:** UTF-8 con marca de orden de bytes (`UTF-8-SIG`)
- **Delimitador de campos:** Punto y coma (`;`)
- **Checksum (SHA-256):** `11f6a081b519777ef8f6fa6195cf8577fcbbd32d077e984c8c7b25685331abbb`

#### 2. Métricas de Calidad de Datos
- **Filas Totales:** 52.819
- **Columnas Totales:** 10
- **Completitud:** 100% (0% de valores nulos o faltantes en todas las columnas)
- **Consistencia:** 100%
- **Unicidad:** 100% de registros únicos

#### 3. Diccionario de Datos de Columnas
| Columna | Tipo de Dato | % Nulos | Descripción / Concepto Semántico |
| :--- | :--- | :--- | :--- |
| `ID` | Entero | 0% | Identificador secuencial único asignado a cada registro (1 a 52.819). |
| `Database_origin` | Cadena | 0% | Base de datos o repositorio de origen. Ej.: Spanish FOR Map, EVA, Greece_FOR_map, Morocco_FOR_inventory, Turkiye_FOR_inventory, Lebanon_LULC2017, NFI_Tunisia. |
| `ID_original` | Cadena | 0% | Identificador original en el inventario primario (garantiza trazabilidad de linaje). |
| `longitude` | Decimal / Cadena | 0% | Longitud geográfica en grados decimales (separador decimal con coma `,`). |
| `latitude` | Decimal / Cadena | 0% | Latitud geográfica en grados decimales (separador decimal con coma `,`). |
| `category` | Cadena | 0% | Clase principal de cobertura del suelo: `FOR` (Bosque), `SHRUBLAND` (Matorral), `GRASS` (Pastizal), `CROPLAND` (Cultivo), `BUILT` (Edificado), `BARE SOIL` (Suelo desnudo), `WETLAND` (Humedal), `WATER` (Agua), `OPF` (Bosque abierto). |
| `FOR_type` | Cadena | 0% | Tipo estructural de bosque: `Broadleaved evergreen`, `Broadleaved deciduous`, `Coniferous`, o etiqueta de clase no forestal. |
| `subcategory` | Cadena | 0% | Unidad taxonómica o especie forestal dominante (ej.: `F-Quercus coccifera`, `Pinus halepensis`, `Quercus ilex`). |
| `Dataset` | Cadena | 0% | Subcolección o campaña de muestreo específica (ej.: CircumMed Pine FOR database, VegItaly, SOPHY France, AMS-VegBank, Albanian Vegetation Database). |
| `Comments` | Cadena | 0% | Notas u observaciones contextuales (guion `-` cuando no hay comentarios). |


---

# 4. License (Licencia)

* **License:** `Creative Commons Attribution 4.0 International` (`CC BY 4.0`)

---

# 5. Keywords (Palabras clave)

> Copiar y pegar en el campo de **Keywords** (puedes añadirlas una a una o separadas por coma según el campo):


```text
Mediterranean, Mediterranean forests, forest cover, tree species, tree types, forest biodiversity, biodiversity, ecology, species distribution modeling, geospatial data, remote sensing, provenance, Mediterranean region
```

- Mediterranean
- Mediterranean forests
- forest cover
- tree species
- tree types
- forest biodiversity
- biodiversity
- ecology
- species distribution modeling
- geospatial data
- remote sensing
- provenance
- Mediterranean region




---

# 6. Languages & Version (Idiomas y Versión)

* **Language:** `English` (idioma principal de los datos tabulares)
* **Version:** `1.0.0`

--- 
# 7. Software

* **Programming language:** CSV
