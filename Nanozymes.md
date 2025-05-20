
# 🧪 Dataset: **Nanozymes – Catalytic Properties of Nanozyme Materials**

---

## 🔷 **Core RAI Fields**

---

### `rai:dataCollection`

The data was manually extracted from scientific articles (PDF). Each row in the table corresponds to a **separate experiment**, not just a publication. Extracted parameters include structural characteristics, catalytic activity, functional coatings, and reaction conditions.  
☑️ Confirmed in: *Original Data*, *Dataset Description*, *Notes*

---

### `rai:dataBiases`

Possible biases:
- Repetitive articles with similar experiments may dominate over less represented cases;  
- Not all types of catalytic activity are evenly covered;  
- Some reaction conditions (e.g., surface coatings) are undocumented for certain records;  
- Missing values may distort representativeness.

🟡 **[No information provided on steps taken to mitigate these biases]**

---

### `rai:personalSensitiveInformation`

The dataset contains no personal data. Information was derived from experiments involving synthetic nanomaterials.  
☑️ Clearly confirmed in the context of in vitro use and the nature of publications.

---

### `rai:dataLimitations`

- Data is limited to in vitro laboratory experiments only;  
- Does not include biological or clinical application scenarios;  
- Some values were calculated or interpreted by the annotation team, rather than directly taken from the article text (e.g., `syngony`);  
- Missing data may occur for coatings, parameters, and concentrations.

☑️ Confirmed in *Validation Results*, *Notes*

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**

No data is available on who performed the extraction or validation (number, gender, experience, country, etc.)

---

### `rai:dataSocialImpact`

**Potential positive applications**:
- Acceleration of development and optimization of new nanocatalysts (nanozymes);  
- Support in computational modeling tasks related to structure and activity;  
- Facilitates access to catalytic activity parameters.

🟡 Potential risks or limitations of use are not described → **[Partially provided]**

---

## ➕ **Additional Metadata**

---

### `keywords`

nanozymes, catalytic activity, Michaelis–Menten, Vmax, Km, nanomaterials, biosensors, catalytic properties  
☑️ Clearly reflected in the dataset description and structure

---

### `creator`

🟡 **[Information not provided]**

No name of the team, organization, or laboratory is included.

---

### `citation`

🟡 **[Information not provided]**

No publication details, author names, or citation format available.

---

### `semanticTypes`

☑️ Derived from the dataset contents:
- Chemical analysis  
- Catalytic activity  
- Extraction of experimental parameters  
- Scientific tables  
- Structure-function modeling

---

### `preProcessing`

☑️ According to *Validation Results*, 439 corrections were implemented:
- 398 template-based (formulas, temperature, crystal symmetry);  
- 41 case-specific corrections.

🟡 No information on further NLP/ML preprocessing (tokenization, lowercasing, lemmatization, etc.) → **[Partially provided]**

---

### `purpose`

The dataset is intended for:
- Benchmarking catalytic properties;  
- Discovering structure–activity dependencies (structure–function);  
- Validating ML models in chemistry;  
- Developing predictive approaches for catalytic efficiency.

☑️ Clearly stated in *Dataset Description*

---

## 🧩 **RAI Fields Related to Annotation**

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**

No indication of who performed the annotation.

---

### `rai:dataAnnotationAnalysis`

☑️ 439 corrections were reported:  
- Errors in formula fields, symmetry, temperature;  
- Some values were partially derived or interpreted;  
- Repetitive error patterns across articles were used to apply fixes.

🟡 Conflicts between annotators, evaluation method, or agreement procedures are not mentioned.

---

### `rai:dataAnnotationPlatform`

🟡 **[Information not provided]**

No mention of which tool was used for annotation.

---

### `rai:dataAnnotationProtocol`

☑️ It is mentioned that data were manually extracted from scientific publications.  
🟡 Step-by-step procedure, annotator count, instructions, or validation methods are not described → **[Partially provided]**

---

### `rai:machineAnnotationTools`

🟡 **[Information not provided]**

No mention of LLMs, OCR, NLP, or other tools being used.

---

## ⚙ **Fields Related to Data Processing and Quality**

---

### `rai:dataCollectionMissingData`

☑️ It is stated that missing values occur when information was not mentioned in the article (e.g., coating, Km values, etc.)

🟡 Treatment of missing data (removal, imputation, etc.) is not described → **[Partially provided]**

---

### `rai:dataCollectionRawData`

🟡 **[Information not provided]**

No indication whether original PDFs are available, beyond the `pdf` field in the table.

---

### `rai:dataCollectionType`

☑️ It is explicitly stated that data were manually extracted from publications.  
Type: **manual collection from open sources**

---

### `rai:dataDataManipulationProtocol`

☑️ The following were performed:
- Manual correction of both template and case-specific errors;  
- Fixes applied to symmetry, formulas, and units.

🟡 Other possible steps (e.g., duplicate merging, filtering) are not described.

---

### `rai:dataImputationProtocol`

🟡 **[Information not provided]**

No information on how missing values were handled.

---

### `rai:dataPreprocessingProtocol`

☑️ Included correction of inconsistent values using error pattern templates.

🟡 No details on text formatting, lowercasing, tokenization, etc.

---

### `rai:dataReleaseMaintenancePlan`

🟡 **[Information not provided]**

No mention of who maintains or updates the dataset.

---

### `rai:dataUseCases`

☑️ Suitable for:
- Structure–activity relationship (SAR) research;  
- Machine learning in catalysis;  
- Performance benchmarking for nanozymes.

🟡 No mention of where use is **not recommended** (e.g., clinical settings) → **[Partially provided]**

---
