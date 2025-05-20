

# 🧲 Dataset: **Magnetic Nanomaterials – Structure and Magnetic Properties of Core–Shell Nanoparticles**

---

## 🔷 **Core RAI Fields**

---

### `rai:dataCollection`  
The data was extracted from scientific publications and includes structural, magnetic, and crystallographic information on nanoparticles, core and shell composition, magnetic parameters (e.g., remanent magnetization, hysteresis loop shift), as well as specific properties related to MRI and hyperthermia. The dataset aggregates information from three distinct scientific sources: two related to biomedical applications and one focused on physical effects (exchange bias).  
☑️ Confirmed in *Dataset Description*, *Notes*, *Original Data*

---

### `rai:dataBiases`  
Potential biases:  
- The dataset includes only publications where magnetic measurements are available — possible skew toward interesting/successful results;  
- Focus on core–shell systems may not be representative of other types of nanomaterials;  
- Emphasis on medical applications (MRI, hyperthermia) may exclude data relevant to industrial materials.

🟡 **[No information provided on attempts to mitigate these biases]**

---

### `rai:personalSensitiveInformation`  
The dataset contains no personal or sensitive data. All information pertains to the physical and chemical properties of materials.  
☑️ Confirmed based on structure and content

---

### `rai:dataLimitations`  
- Combines data from various sources with heterogeneous measurement methodologies;  
- Not all entries were manually verified (explicitly indicated in the `verification required` field);  
- Metadata may contain errors or gaps (documented via the fields `has_mistake_in_metadata`, `comment`);  
- No information is provided on the biological, toxicological, or in vivo performance of the nanoparticles.

☑️ Stated in the structure and validator fields

---

### `rai:annotatorDemographics`  
🟡 **[Information not provided]**  
No information is available about who performed the manual validation and review: qualifications, nationality, age, number of specialists, etc.

---

### `rai:dataSocialImpact`  
**Potential benefits**:  
- Supporting new developments in MRI diagnostics and hyperthermia;  
- Usable for training models to predict magnetic properties;  
- Data standardization for evaluating nanomaterials in medicine and materials science.

🟡 **[Potential risks or misuses are not described]**

---

## ➕ **Additional Metadata**

---

### `keywords`  
magnetic nanoparticles, magnetization, MRI, hyperthermia, core–shell structure, exchange bias, materials, nanotechnology  
☑️ Based on the intended use of the dataset

---

### `creator`  
🟡 **[Information not provided]**  
No team or project authors are mentioned.

---

### `citation`  
🟡 **[Information not provided]**  
No citation or referencing instructions are provided.

---

### `semanticTypes`  
☑️ Based on the dataset structure and application domains:
- Physical properties (magnetism)  
- Molecular nanomaterials  
- Biomedical applications (MRI, hyperthermia)  
- Composite materials and crystallography  
- Machine learning for nanomaterials

---

### `preProcessing`  
☑️ Basic validation is implemented (both automatic and manual):  
- Fields like `verified_by`, `verification_required`, and `comment` are used for marking records evaluated for correctness  
🟡 **[Text/data normalization methods are not described]**

---

### `purpose`  
Dataset objectives include:
- Analysis of magnetic properties of nanomaterials in the context of materials science and biomedical engineering;  
- Machine learning for structure-based prediction in core–shell architectures;  
- Cross-method comparison of physical measurements (SQUID, XRD, EM).

☑️ Clearly stated in *Dataset Description*

🟡 **[Unintended / non-recommended use cases are not described]**

---

## 🧩 **RAI Annotation Fields**

---

### `rai:annotatorDemographics`  
🟡 **[Information not provided]**  
No information about curators/validators, although the `verified_by` field exists.

---

### `rai:dataAnnotationAnalysis`  
☑️ Manual verification is indicated using fields like `verification_required` and `comment`.  
☑️ The field `has_mistake_in_metadata` tracks metadata issues.  
🟡 **[No information about overlapping annotation, agreement levels, or annotation volume]** → **[Partially provided]**

---

### `rai:dataAnnotationPlatform`  
🟡 **[Information not provided]**  
The annotation tools or interface used are not specified.

---

### `rai:dataAnnotationProtocol`  
🟡 **[Information not provided]**  
No detailed description of protocols, task distribution, workflow steps, or QA procedures.

---

### `rai:machineAnnotationTools`  
🟡 **[Information not provided]**  
No mention of whether automated tools (e.g., LLMs, OCR, scripts) were used in data extraction.

---

## ⚙ **Collection, Gaps, and Processing**

---

### `rai:dataCollectionMissingData`  
☑️ Fields like `verified_by`, `comment`, and `has_mistake_in_metadata` indicate the presence, tracking, and review of errors or missing metadata.  
🟡 **[No data on frequency or automatic handling of missing values]** → **[Partially provided]**

---

### `rai:dataCollectionRawData`  
🟡 **[Information not provided]**  
The `pdf` column is present, but access to source publications or supplementary materials is unclear.

---

### `rai:dataCollectionType`  
☑️ The data was compiled from three scientific sources on magnetic nanoparticles.  
☑️ Multi-layered structure: includes measurement data, material descriptions, and structure information.

---

### `rai:dataDataManipulationProtocol`  
☑️ Manual validation, correction/substitution of inaccurate metadata was performed.  
🟡 **[Further normalization and detailed processing steps not specified]**

---

### `rai:dataImputationProtocol`  
🟡 **[Information not provided]**  
No mention of imputation strategies or whether missing values were filled using empirical models.

---

### `rai:dataPreprocessingProtocol`  
☑️ Validation of errors, use of verification markers, and annotations in comments were implemented.  
🟡 **[No info on standardization, tokenization, text cleaning, etc.]**

---

### `rai:dataReleaseMaintenancePlan`  
🟡 **[Information not provided]**  
No statements regarding updates, maintainers, or current dataset versioning.

---

### `rai:dataUseCases`  
☑️ Recommended use cases:
- Development and evaluation of MRI contrast agents;  
- Training prediction models for magnetic properties;  
- Analysis of physical/mechanical properties of core–shell systems.

🟡 **[No limitations or explicitly discouraged applications provided]**

---
