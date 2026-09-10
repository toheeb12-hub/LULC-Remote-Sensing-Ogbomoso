````markdown
#  Land Use/Land Cover Classification — Ogbomoso North

<p align="center">

<img src="https://img.shields.io/badge/Remote%20Sensing-Earth%20Observation-0e75b6?style=for-the-badge">

<img src="https://img.shields.io/badge/GIS-Spatial%20Analysis-27ae60?style=for-the-badge">

<img src="https://img.shields.io/badge/LULC-Classification-8e44ad?style=for-the-badge">

<img src="https://img.shields.io/badge/Year-2025-2c3e50?style=for-the-badge">

</p>

---

##  Project Overview

This project focused on the **Land Use/Land Cover (LULC) classification of Ogbomoso North, Oyo State, Nigeria**, using remote sensing and Geographic Information System (GIS) techniques.

The project demonstrates how Earth observation data can be transformed into structured spatial information for understanding the distribution of land-cover types across a landscape.

Two classification approaches were explored:

- **Unsupervised Classification**
- **Supervised Classification**

The resulting 2025 LULC maps represent five major land-cover classes:

-  Water Bodies
-  Vegetation
-  Built-up Areas
-  Agriculture
-  Bare/Range Land

The project combines **remote sensing, image classification, spatial analysis and cartographic visualization** to produce a detailed representation of the landscape.

---

#  Project Objectives

The main objectives of the project were to:

- Classify the major land-cover types within Ogbomoso North.
- Apply an unsupervised classification approach to remotely sensed data.
- Apply a supervised classification approach using predefined land-cover information.
- Compare the spatial representation produced by the two approaches.
- Generate a thematic LULC map for 2025.
- Visualize the spatial distribution of major land-cover classes.
- Demonstrate the application of remote sensing and GIS to land management and planning.

---

# Study Area

The study area is **Ogbomoso North, Oyo State, Nigeria**.

Ogbomoso North contains a mixture of developed areas, vegetation, agricultural land, exposed surfaces and water features, making it suitable for demonstrating the application of remote sensing-based land-cover classification.

The resulting map provides a spatial representation of the landscape and the distribution of the identified LULC classes.

---

#  Land Cover Classes

The classification identified five principal land-cover categories.

| Class | Description |
|---|---|
|  Water Bodies | Rivers, ponds and other surface-water features |
|  Vegetation | Areas dominated by vegetation and natural plant cover |
|  Built-up | Residential, commercial, institutional and other developed surfaces |
|  Agriculture | Agricultural and cultivated areas |
|  Bare/Range Land | Exposed surfaces and areas with limited vegetation cover |

---

# 🔬 Classification Approaches

## 01 — Unsupervised Classification

The unsupervised approach was used to identify naturally occurring spectral groupings within the remotely sensed data.

The classification process initially generated spectral clusters without assigning them directly to predefined land-cover categories.

The resulting clusters were subsequently interpreted and associated with meaningful LULC classes.

### Workflow

```text
Remote Sensing Data
        ↓
Data Preparation
        ↓
Spectral Information
        ↓
Unsupervised Classification
        ↓
Spectral Clusters
        ↓
Cluster Interpretation
        ↓
LULC Class Assignment
        ↓
Thematic Map
````

---

# 02 — Supervised Classification

The supervised classification approach used predefined land-cover information to guide the classification of the remotely sensed data.

Training information was used to distinguish the major land-cover categories and produce a thematic representation of the study area.

### Workflow

```text
Remote Sensing Data
        ↓
Data Preparation
        ↓
Training Information
        ↓
Classification
        ↓
Land-Cover Prediction
        ↓
Class Assignment
        ↓
Thematic LULC Map
```

---

#  Complete Geospatial Workflow

The overall project workflow can be represented as:

```text
                    STUDY AREA
                        │
                        ↓
               REMOTE SENSING DATA
                        │
                        ↓
                 DATA PREPARATION
                        │
                        ↓
              IMAGE / SPECTRAL DATA
                        │
             ┌──────────┴──────────┐
             ↓                     ↓
      UNSUPERVISED             SUPERVISED
      CLASSIFICATION           CLASSIFICATION
             ↓                     ↓
     Spectral Clusters       Training Information
             ↓                     ↓
       Interpretation          Classification
             ↓                     ↓
             └──────────┬──────────┘
                        ↓
                 LULC CLASS MAP
                        │
                        ↓
              SPATIAL INTERPRETATION
                        │
                        ↓
                CARTOGRAPHIC OUTPUT
                        │
                        ↓
             GEOSPATIAL DECISION SUPPORT
```

---

#  Classification Results

## Unsupervised Classification

The unsupervised classification produced a spatially continuous representation of the major spectral patterns within Ogbomoso North.

The classified output was interpreted into the five principal land-cover categories:

`Water Bodies` • `Vegetation` • `Built-up` • `Agriculture` • `Bare/Range Land`

---

## Supervised Classification

The supervised classification produced a more explicitly labelled representation of the identified land-cover categories.

The resulting map provides a spatial basis for examining the distribution of developed areas, vegetation, agricultural land, exposed surfaces and water bodies across Ogbomoso North.

---

#  Supervised vs Unsupervised Classification

One of the key aspects of this project was the comparison of two different classification strategies.

### Unsupervised Classification

```text
No predefined class labels
          ↓
Spectral clustering
          ↓
Cluster interpretation
          ↓
LULC classes
```

### Supervised Classification

```text
Predefined training information
          ↓
Classification model
          ↓
Predicted land-cover classes
          ↓
LULC map
```

This comparison demonstrates an important principle in remote sensing:

> **The quality and structure of classification results depend not only on the imagery, but also on the classification strategy and the information used to define land-cover classes.**

---

#  Spatial Interpretation

The resulting maps show a heterogeneous landscape across Ogbomoso North.

Built-up areas are particularly visible around the more developed portions of the study area, while vegetation and agricultural land occur extensively across the surrounding landscape.

The classification also identifies smaller and spatially localized water bodies and areas of bare or sparsely covered land.

The spatial pattern demonstrates the usefulness of remotely sensed data for rapidly characterizing land-cover conditions over a relatively large area.

---

#  Applications

The resulting LULC information can support a range of environmental and planning applications.

###  Urban Planning

Monitoring the spatial distribution and expansion of built-up areas.

###  Environmental Monitoring

Assessing vegetation distribution and changes in natural land cover.

###  Agricultural Management

Identifying and monitoring agricultural areas.

###  Land Management

Providing spatial information for land-use planning and resource management.

###  Sustainable Development

Supporting evidence-based spatial planning and environmental decision-making.

###  Earth Observation

Demonstrating how satellite-derived information can be converted into useful geospatial intelligence.

---

#  Tools & Technologies

### Remote Sensing

`Satellite Imagery`

`Earth Observation`

`Image Classification`

`LULC Mapping`

### GIS

`QGIS`

`ArcGIS Pro`

`Spatial Analysis`

`Cartography`

### Classification

`Unsupervised Classification`

`Supervised Classification`

---

#  Project Outputs

## Unsupervised Classification — 2025

<p align="center">
<img src="maps/ogbomoso_north_unsupervised_2025.png" width="90%">
</p>

---

## Supervised Classification — 2025

<p align="center">
<img src="maps/ogbomoso_north_supervised_2025.png" width="90%">
</p>

---

#  Skills Demonstrated

```text
Remote Sensing
Earth Observation
LULC Classification
Supervised Classification
Unsupervised Classification
GIS
Spatial Analysis
Satellite Image Interpretation
Cartographic Visualization
Land-Cover Mapping
Geospatial Data Processing
```

---

#  Technical Significance

This project demonstrates the transition from **raw Earth observation data to interpretable geospatial information**.

The workflow illustrates how remote sensing and GIS can be integrated to:

```text
OBSERVE
   ↓
CLASSIFY
   ↓
MAP
   ↓
INTERPRET
   ↓
SUPPORT DECISIONS
```

Rather than treating the LULC map as a standalone cartographic product, the project positions land-cover classification as a **spatial analytical framework for understanding the interaction between built environments, vegetation, agriculture and other landscape components**.

---

#  Future Development

Future extensions of this project could include:

* Multi-temporal LULC analysis
* LULC change detection across multiple years
* Classification accuracy assessment
* Confusion matrix generation
* Overall accuracy calculation
* Producer's and user's accuracy
* Kappa or alternative agreement statistics
* Machine-learning-based classification
* Integration of Sentinel-1 and Sentinel-2 datasets
* Automated classification workflows
* LULC transition analysis
* Urban expansion modelling

---

#  Project Status

```text
🟢 Classification completed
🟢 Unsupervised classification completed
🟢 Supervised classification completed
🟢 LULC maps produced
🟡 Further accuracy assessment / temporal analysis can be added
```

---

#  Author

## Toheeb Adeyemo

**Surveying & Geoinformatics | Geospatial Analyst**

Nigeria

### Areas of Interest

`GIS` • `Remote Sensing` • `Earth Observation` • `Spatial Data Science` • `Environmental Mapping` • `Urban Analytics` • `UAV Mapping` • `Surveying`

---

#  Project Philosophy

> **Observe the landscape. Classify the patterns. Understand the change.**

This project represents my interest in applying **remote sensing, GIS and Earth observation technologies to transform spatial data into meaningful information for environmental monitoring, urban planning and sustainable land management.**

---

<p align="center">

###  From Satellite Data → Spatial Information → Geospatial Intelligence

</p>
```

