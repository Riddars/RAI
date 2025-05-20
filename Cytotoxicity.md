

# ✅ Corrected RAI Fields and Metadata for the **Cytotoxicity** Dataset

---

## 🔷 Core RAI Fields

---

### `rai:dataCollection`

The data was collected from full-text articles in PDF format and supplementary materials. Both the articles and their appendices were used. Extraction was done using a combination of automated tools (LLM, OCR) and manual expert correction. Automatic validation is indicated.  
☑️ Confirmed in the *Original Data* and *Dataset Description* sections.

---

### `rai:dataBiases`

Potential biases may arise due to:
- Uneven representation of different types of nanoparticles;
- Possible predominance of widely studied cell lines;
- Missing data where no measurements were reported.

☑️ Partially confirmed in tables and descriptions.  
🟡 [No indication of specific steps taken to mitigate biases]

---

### `rai:personalSensitiveInformation`

There is no personal or sensitive information in the dataset. Only depersonalized experimental data from scientific publications is used, including data on cell lines.  
☑️ Explicitly confirmed by the nature of the sources.

---

### `rai:dataLimitations`

- Data is limited to **in vitro** studies only.  
- Not applicable for predicting **in vivo** effects or for clinical use.  
- Missing values are possible (e.g., zeta potential).  
- Minor formatting and terminology differences across publications may affect model quality.

☑️ Confirmed by the dataset description and column schema.

---

### `rai:annotatorDemographics`

🟡 Information not provided.  
Your descriptions do not specify who performed the annotation, their profession, country, age, native language, or count.  
🔸 Clarification: only mentioned that annotation was performed by **experts** and included **manual validation**.

---

### `rai:dataSocialImpact`

Possible **positive impacts**:
- Accelerating research in nanotoxicology;
- Increasing representativeness and accessibility of data.

Possible **risks**:
- Misuse of data outside laboratory settings;
- Unfounded conclusions drawn without sufficient expertise.

☑️ Confirmed in the *Dataset Description* and *Project Motivation* sections.

---

## ➕ Additional Metadata

---

### `keywords`

nanotoxicology, in vitro, nanomaterials, cytotoxicity, cell lines, information extraction, machine learning  
☑️ Derived from the task description and dataset structure.

---

### `creator`

☑️ Stated: ChemX project team  
🟡 [Specific names or institutions not provided]

---

### `citation`

🟡 Citation not provided.  
⚠️ It is noted that the article is *under review*, a link will be added later.

---

### `semanticTypes`

☑️ Named Entity Recognition (NER);  
☑️ Relation Extraction;  
☑️ Tabular Data;  
☑️ Toxicity Prediction;  
☑️ Scientific Texts; Document Analysis

All types derived from the dataset objective and methodology.

---

### `preProcessing`

☑️ Stated:  
- Terminology correction (cell_type, test) — 1351 corrections;  
- Template errors identified and corrected.  
🟡 No information on tokenization, lowercasing, lemmatization → marked as: [Information not provided]

---

### `purpose`

☑️ Suitable for:
- Training chemical information extraction models  
- Testing multimodal analysis tools  
- Studying dependencies between nanoparticle features and cytotoxicity

🟡 Not recommended for:
- Clinical or regulatory decisions  
- Deriving in vivo characteristics

---

## 📦 Fields Related to Annotation

---

### `rai:annotatorDemographics`
🟡 Information not provided.

---

### `rai:dataAnnotationAnalysis`

☑️ Described: 1351 corrections were made, 1350 of which were template errors.  
Key issues: **inconsistent cell line and test naming**.  
Corrections were applied manually based on recurring patterns.

---

### `rai:dataAnnotationPlatform`

☑️ Not explicitly stated. However,  
🟡 [Annotation platform not mentioned: e.g., Excel, Prodigy, Google Sheets — not indicated]

---

### `rai:dataAnnotationProtocol`

☑️ Manual validation and correction of evident errors is mentioned.  
🟡 [No details on number of annotators, annotation guidelines, conflict resolution, etc.]

---

### `rai:machineAnnotationTools`

🟡 The dataset does **not specify** which tools were used (e.g., ChemBERTa, GPT-4o, etc.)

---

## ⚙ Fields Related to Collection and Preprocessing

---

### `rai:dataCollectionMissingData`

☑️ Stated that missing values (e.g., zeta potential) are present.  
They were left blank — **not imputed** or **corrected**.

---

### `rai:dataCollectionRawData`

☑️ PDF archive is denoted as `pdf` in the table.  
🟡 [No information on accessibility or preservation of unstructured data → marked as: access unknown]

---

### `rai:dataCollectionType`

☑️ Stated: data was extracted from articles (PDF), including tables, text, and figures.  
The method is unstructured but can be classified as: "automatic extraction and manual validation"

---

### `rai:dataDataManipulationProtocol`

☑️ Confirmed:  
- correction of template errors (1351 instances),  
- terminology normalization  
- harmonization of field names and values  
- formatting/cleaning

---

### `rai:dataImputationProtocol`

☑️ Missing values were not processed, left as is.

---

### `rai:dataPreprocessingProtocol`

☑️ Stylistic and terminology errors were corrected.  
🟡 [No info on tokenization, lemmatization, lowercasing, etc.]

---

### `rai:dataReleaseMaintenancePlan`

🟡 Not provided.  
[No details on responsibility for dataset maintenance and versioning]

---

### `rai:dataUseCases`

☑️ Used for:
- training chemical AI models  
- information extraction tasks  
- toxicity analysis

🟡 Not recommended for:
- clinical conclusions  
- conclusions about humans or living organisms

---
