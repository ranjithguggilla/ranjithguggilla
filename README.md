## Ranjith Guggilla

**Research Data Engineer** · Harte Research Institute, Texas A&M University–Corpus Christi

Building tools for oceanographic data curation, metadata compliance, and FAIR data publication.

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![xarray](https://img.shields.io/badge/xarray-NetCDF-orange)](https://xarray.dev/)
[![CF-1.8](https://img.shields.io/badge/CF--1.8-compliant-blue)](https://cfconventions.org/)
[![ISO 19115](https://img.shields.io/badge/ISO_19115--2-metadata-green)](https://www.iso.org/standard/67039.html)

---

### Oceanographic Data Engineering Portfolio

<table>
<tr>
<td width="50%">

#### [glider-data-curation](https://github.com/ranjithguggilla/glider-data-curation)
Slocum glider mission archive pipeline. Ingests IOOS Glider DAC segments, merges into CF-1.8 trajectory NetCDF, computes TEOS-10 derived variables, applies QARTOD QC, and produces archive packages with interactive maps, reports, and DataCite DOI metadata.

![CF-1.8](https://img.shields.io/badge/CF--1.8-trajectory-blue)
![TEOS-10](https://img.shields.io/badge/TEOS--10-GSW-teal)
![QARTOD](https://img.shields.io/badge/IOOS-QARTOD-orange)
![DataCite 4.4](https://img.shields.io/badge/DataCite-4.4-purple)
![CI](https://github.com/ranjithguggilla/glider-data-curation/actions/workflows/ci.yml/badge.svg)

</td>
<td width="50%">

#### [iso19115-validator](https://github.com/ranjithguggilla/iso19115-validator)
ISO 19115-2 metadata compliance engine. XSD structure checks, Schematron policy rules, CF-1.8 and ACDD-1.3 attribute validation, YAML rules DSL for custom policies, FAIR self-scoring, and a FastAPI web dashboard.

![ISO 19115-2](https://img.shields.io/badge/ISO_19115--2-XSD-green)
![ACDD-1.3](https://img.shields.io/badge/ACDD--1.3-checked-blue)
![FAIR](https://img.shields.io/badge/FAIR-scoring-orange)
![FastAPI](https://img.shields.io/badge/FastAPI-dashboard-009688)
![CI](https://github.com/ranjithguggilla/iso19115-validator/actions/workflows/ci.yml/badge.svg)

</td>
</tr>
<tr>
<td width="50%">

#### [ctd-cast-processor](https://github.com/ranjithguggilla/ctd-cast-processor)
CTD cast processing pipeline. Reads Sea-Bird CNV files, applies TEOS-10 conversions via GSW, flags outliers, bins to standard depths, and exports CF-compliant NetCDF with full provenance.

![TEOS-10](https://img.shields.io/badge/TEOS--10-GSW-teal)
![Sea-Bird](https://img.shields.io/badge/Sea--Bird-CNV-blue)
![CF-1.8](https://img.shields.io/badge/CF--1.8-profile-blue)
![CI](https://github.com/ranjithguggilla/ctd-cast-processor/actions/workflows/ci.yml/badge.svg)

</td>
<td width="50%">

#### [gulf-buoy-etl](https://github.com/ranjithguggilla/gulf-buoy-etl)
NDBC buoy observation ETL pipeline. Extracts Gulf of Mexico station data, transforms with unit normalization and QC flagging, loads into partitioned Parquet with DuckDB analytics.

![NDBC](https://img.shields.io/badge/NDBC-buoy_data-blue)
![DuckDB](https://img.shields.io/badge/DuckDB-analytics-yellow)
![Parquet](https://img.shields.io/badge/Parquet-columnar-orange)
![CI](https://github.com/ranjithguggilla/gulf-buoy-etl/actions/workflows/ci.yml/badge.svg)

</td>
</tr>
<tr>
<td colspan="2">

#### [ocean-curation-pipeline-toolkit](https://github.com/ranjithguggilla/ocean-curation-pipeline-toolkit)
Reusable framework for building oceanographic data curation pipelines. Provides base classes for ingest, transform, validate, and publish stages with plugin architecture, checksum verification, and structured logging.

![Pipeline](https://img.shields.io/badge/pipeline-framework-blue)
![SHA-256](https://img.shields.io/badge/SHA--256-checksums-green)
![CI](https://github.com/ranjithguggilla/ocean-curation-pipeline-toolkit/actions/workflows/ci.yml/badge.svg)

</td>
</tr>
</table>

---

### Tech Stack

| Category | Tools |
|----------|-------|
| **Languages** | Python, Bash, SQL |
| **Ocean Data** | xarray, netCDF4, GSW (TEOS-10), CF-conventions, ERDDAP |
| **Standards** | ISO 19115-2, ACDD-1.3, IOOS QARTOD, DataCite 4.4, FAIR |
| **Data** | Pandas, NumPy, DuckDB, Parquet |
| **Web** | FastAPI, Jinja2, Folium |
| **Quality** | pytest, ruff, GitHub Actions CI |
| **XML/Schema** | lxml, XSD, Schematron, XPath |

---

### Contact

[![Email](https://img.shields.io/badge/Email-ranjithguggilla668%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:ranjithguggilla668@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-ranjithguggilla-181717?logo=github)](https://github.com/ranjithguggilla)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ranjithguggilla-0A66C2?logo=linkedin)](https://www.linkedin.com/in/ranjithguggilla/)
