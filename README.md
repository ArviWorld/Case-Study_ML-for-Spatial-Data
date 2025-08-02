# Predicting the Invasive Species 'Gorse (Ulex europaeus)' on Banks Peninsula, New Zealand 

**Land Cover Classification with Machine Learning Models in R**

This project applies advanced machine learning techniques to classify land cover and predict the spread of the invasive plant species *Gorse (Ulex europaeus)* on Banks Peninsula, New Zealand. The models are trained on satellite imagery and geospatial datasets using R. A short statement and executive summary is given below. 

---
## Project Structure

- `data/` – Raw and pre-processed datasets (e.g., Sentinel imagery, land cover maps)
- `report.Rmd` – RMarkdown file containing the full analysis
- `report.html` – Rendered HTML report
- `README.md` – Project description and documentation

---

> See the full report: [`Report.html`](./Report.html)

---
# Statements

**Acknowledgement**\
I am sincerely thank the OpenGeoHub Foundation for their work in making open source geospatial models for everyone. The videos posted in their website on tutorials to learn remote sensing concepts and understand the workflow structures in working with geospatial data analysis. Particular mention to the tutorial *"Machine Learning for Spatial Data"* by Dr. Hanna Meyer which helped me to work on this project.

Furthermore, I thank the professional certification courses relevant to understanding programming, machine learning, remote sensing concepts which helped me to work on this project.

**Use of generative artificial intelligence**\
Generative artificial intelligence (GenAI) was mainly used for creating charts and adjusting visualization parameters in R. GenAI was also used for code debugging. However, the responses provided by GenAI were critically judged before being implemented.

---
# Executive Summary 

**Problem Statement**\
**Gorse (*Ulex europaeus*)** plant was brought to New Zealand during the European settlement as a hedge plant and spreads into farmlands which is associated with negative consequences for the quality of the grassland. Each year millions of dollars are spent for its control and field sampling are expensive for developing management strategies. It's of high importance to map the distribution of such invasive plants using remote sensing methods.

**Project Aim and Focus**\
The project aim and focus is on using Machine Learning models to predict the invasive species **gorse (*Ulex europaeus*)** on the Banks Peninsula of New Zealand.

**Raw data used**\
Sentinel satellite data and plotted land cover class of a section of the Banks Peninsula of New Zealand.

**Methodology**\
The following methodology was undertaken for this project,\
- Raw data and land cover classes are visualized and merged to a single data set to build the Machine Learning models (`Random Forest`, `XGBoost` and `Support Vector Machine`).\
- The merged data set is split into 30% training and 70% test data which is used to train and predict using the models.\
- Various analysis such as confusion matrix, scoring metrics, predictive & entropy maps, and uncertainty diagnostics were performed to analyse the models performance in land cover classification and predicting the invasive plant species.

**Results**\
Out of the three models, `RF` and `XGBoost` model performs very well and `SVM` model is not up to par in classifying the land cover class using the satellite images. Based on the various analysis, `Random Forest` with the highest accuracy of 99.33%, Model outperforms `XGBoost` in predicting the invasive species **gorse (*Ulex europaeus*)**, using Sentinel satellite data, on the Banks Peninsula of NewZealand.
