
# MLRP Mapping Toolkit – Basin Datasets

This repository contains the spatial datasets used in the **MLRP Mapping Toolkit**, a web-based decision-support tool developed to support California’s **Multibenefit Land Repurposing Program (MLRP)**.

---

## Study Areas

The datasets include Public Land Survey (PLS) section polygons for two critically overdrafted groundwater subbasins in California’s San Joaquin Valley:

- **Kaweah Subbasin**
- **Tule Subbasin**

Each basin folder contains Public Land Survey (PLS) section polygons with both input and processed suitability data.

**Web Applications:**  
* Kaweah Tool: 169.236.229.50:3838/Kaweah_OpenApp/
* Tule Tool: 169.236.229.50:3838/Tule_OpenApp/

---

## Repository Structure

```
Kaweah/
├── Kaweah_PLS_sections.shp
├── Kaweah_PLS_sections.dbf
├── Kaweah_PLS_sections.shx
├── Kaweah_PLS_sections.prj
└── Kaweah_DataDictionary.xlsx

Tule/
├── Tule_PLS_sections.shp
├── Tule_PLS_sections.dbf
├── Tule_PLS_sections.shx
├── Tule_PLS_sections.prj
└── Tule_DataDictionary.xlsx
```

---

## Spatial Information

- **Geometry:** Polygon (PLS Sections)
- **Resolution:** 1-mile sections
- **Projection:** *NAD83 / California Albers – EPSG:3310*

Each polygon represents the common spatial unit used to calculate suitability scores.

---

## Dataset Contents

Each shapefile includes:

### Input Variables
- Hydrologic and recharge data  
- Agricultural characteristics  
- Renewable energy potential  
- Habitat and conservation metrics  
- Flood risk indicators  
- Environmental health variables
  
### Processed Outputs
- Normalized variables  
- Fuzzy logic transformations  
- Suitability index scores  

---

## Data Dictionary

Each basin folder includes an Excel file containing:

- Variable names  
- Descriptions
- Units
- Processing notes  

Please consult the data dictionary before conducting analysis.

---

## Disclaimer

Suitability scores are relative indicators intended for screening and prioritization purposes. They are not designed for parcel-level decisions.

---
## Citation

If using these datasets, please cite:

Nuñez-Bolaño, Y., Flores-Landeros, H., Rodríguez-Flores, J. M., Fernandez-Bou, A. S., Medellín-Azuara, J., & Harmon, T. C. (2025). A participatory approach for developing a geospatial toolkit for mapping the suitability of California’s Multibenefit Land Repurposing Program (MLRP) in support of groundwater sustainability. Frontiers in Water, 7, 1539834.[https://doi.org/10.3389/frwa.2025.1539834].

## Contact

**Yelenka Nunez-Bolano**  
University of California, Merced
ynunezbolano@ucmerced.edu

