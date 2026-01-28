#-- BUILDING A PREDICTIVE MODEL FOR POWER THEFT HOTSPOTS USING GIS AND MACHINE LEARNING IN KISAUNI SUB COUNTY MOMBASA


# 1. Introduction

Electricity theft presents a significant challenge to power utilities in developing countries, resulting in revenue losses, operational inefficiencies, and reduced service reliability. Conventional electricity theft detection methods are largely reactive, relying on manual inspections and rule-based auditing, which are often costly and spatially inefficient.

Advances in Geographic Information Systems (GIS), Earth Observation data, and Machine Learning (ML) techniques provide an opportunity to enhance electricity theft detection through spatially informed, data-driven approaches. Integrating spatial infrastructure data with billing and anomaly records enables the identification of high-risk areas and supports proactive decision-making.

This project develops a spatially explicit machine learning framework for analysing and predicting electricity theft hotspots within Kisauni Sub-County, Kenya.

---

# 2. Research Objectives

The main objective of this study is to develop and evaluate a machine learning–based spatial model for predicting electricity theft hotspots.

The specific objectives are to:

1. Analyse the spatial and temporal distribution of electricity theft incidents.
2. Integrate geospatial infrastructure and billing data to derive predictive features.
3. Develop and train machine learning models for electricity theft prediction.
4. Visualize predicted theft hotspots using GIS-based mapping techniques.

---

# 3. Research Gaps

Despite increasing application of machine learning in utility management, existing approaches exhibit several limitations:

- Limited integration of spatial context in electricity theft detection models.
- Minimal use of GIS-based proximity and density analyses.
- Lack of spatial decision-support outputs for operational planning.

This study addresses these gaps by combining spatial analysis, machine learning, and geovisualization within a unified analytical framework.

---

# 4. Study Area

The study area is Kisauni Sub-County, located in Mombasa County, Kenya. The area is characterized by high population density, mixed land use, and extensive low-voltage electricity infrastructure, making it susceptible to electricity theft activities.

---

# 5. Data Used

The analysis utilizes multiple spatial and non-spatial datasets, including:

- Electricity infrastructure data (meter boxes, low-voltage lines, and secondary substations)
- Monthly billing and anomaly records
- Administrative boundaries and road networks
- Derived spatial features such as density and proximity metrics

All datasets were harmonized to a common coordinate reference system and preprocessed for spatial consistency.

---

# 6. Methodology Adopted

The methodological workflow comprises the following stages:

### 6.1 Data Preprocessing
- Cleaning and validation of billing and anomaly records
- Spatial data projection and alignment
- Feature engineering and aggregation

### 6.2 Spatial Analysis
- Density analysis to identify clustering patterns
- Proximity analysis to assess infrastructure influence
- Grid-based spatial aggregation

### 6.3 Machine Learning Modelling
- Feature selection and normalization
- Model training and tuning
- Performance evaluation and validation

### 6.4 Visualization
- Mapping observed and predicted theft hotspots
- GIS-based spatial interpretation of results

---

# 7. Results

The results indicate clear spatial clustering of electricity theft incidents. Proximity to electricity infrastructure significantly influences theft likelihood, and machine learning models demonstrate improved predictive capability when spatial features are incorporated. Predicted hotspots provide actionable insights for targeted inspection and enforcement.

---

# 8. Conclusions

This study demonstrates the effectiveness of integrating GIS and machine learning techniques for electricity theft analysis. The proposed framework enhances spatial understanding of theft patterns and supports proactive, data-driven utility management. The methodology can be adapted to other regions facing similar challenges.

---

## 9. Repository Structure

