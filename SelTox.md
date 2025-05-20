

# 🧪 Dataset: **SelTox – Toxicity of Inorganic Nanoparticles on Bacteria**

---

## 🔷 Core RAI Fields

---

### `rai:dataCollection`

The data was extracted from scientific publications in PDF format. Both main articles and supplementary materials were used. Automatic extraction was followed by manual verification. Automatic record validation is indicated.  
☑️ Confirmed in the *Original Data*, *Metadata*, and *Validation Results* sections.

---

### `rai:dataBiases`

Potential biases are associated with:
- Skew toward certain types of nanoparticles (e.g., popular or commonly studied compounds);  
- Uneven coverage of various bacterial strains;  
- A predominance of positive results, since the source is published articles;  
- Missing information for certain parameters (e.g., zeta potential).

🟡 [No information provided on actions taken to mitigate biases]

---

### `rai:personalSensitiveInformation`

The dataset contains no personal data. It presents anonymized experimental results from in vitro studies on the effects of nanoparticles on bacterial cultures.  
☑️ Confirmed by the nature of the content and the absence of human-centered data.

---

### `rai:dataLimitations`

- The data relates only to in vitro analysis and does not reflect in vivo effects;  
- Not all possible bacterial strains are covered;  
- Methods from different publications may be partially inconsistent;  
- Some values are missing (e.g., zeta potential or strain information).

☑️ Confirmed in the *Dataset Description* and *Key Notes*

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**

No information is available on who conducted validation and annotation (experience, gender, country, native language, etc.)

---

### `rai:dataSocialImpact`

**Positive impacts**:
- Supporting research into the causes and nature of bacterial resistance to inorganic nanomaterials;  
- Potential contribution to the development of antimicrobial solutions against drug-resistant strains.

**Risks**:
- Potential use outside of a scientific or clinically validated context;  
- Application of models trained on this data without considering real-world medical scenarios.

☑️ Confirmed in the *Dataset Description*

---

## ➕ Additional Metadata

---

### `keywords`

nanomaterials, antimicrobial activity, antibiotic resistance, in vitro, multidrug-resistant bacteria, MIC, ZOI, toxicity

☑️ Derived from the dataset description and content

---

### `creator`

🟡 **[Information not provided]**

The name of the team or organization is not explicitly mentioned in the provided information.

---

### `citation`

🟡 **[Information not provided]**

Citation format is not indicated. No mention of a publication.

---

### `semanticTypes`

☑️ Based on the intended use of the dataset:
- Extraction of chemical-biological entities  
- Antimicrobial activity prediction  
- Processing and analysis of tabular data  
- Nanotoxicology  
- Information extraction from scientific publications

---

### `preProcessing`

☑️ Stated:  
- 51 corrections, including 48 template-based;  
- Main fields with errors: `np_synthesis`, `strain`, `bacteria`  
Rule-based approaches were used for correcting terminological inconsistencies.

🟡 [No information about other preprocessing steps — lemmatization, lowercasing, etc.]

---

### `purpose`

The dataset is intended for:  
- Studying the relationship between properties of nanoparticles and their antimicrobial activity  
- Building models to predict activity against MDR bacteria  
- Structured information extraction tasks from publications

☑️ Confirmed in the *Dataset Description*

---

## 📦 Fields Related to Annotation

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**  
No information on annotators (who they are, experience, gender, country, etc.)

---

### `rai:dataAnnotationAnalysis`

☑️ 51 corrections were made, 48 of them template-based and 3 unique cases.  
Mistakes included errors in method names, strains, and nanoparticle names.

☑️ Problems were resolved using rule-based updates.  
🟡 [No information on disagreements between annotators or annotation alignment procedures]

---

### `rai:dataAnnotationPlatform`

🟡 **[Information not provided]**  
No mention of annotation platforms or tools (e.g., Excel, Prodigy, internal platform, etc.)

---

### `rai:dataAnnotationProtocol`

☑️ It is stated that data were checked against the original PDF articles.  
🟡 [No information on number of annotators, guidelines, tasks involved, or verification process]

---

### `rai:machineAnnotationTools`

🟡 **[Information not provided]**  
No mention of automated tools used (e.g., NER models, OCR, etc.)

---

## ⚙ Fields Related to Collection and Processing

---

### `rai:dataCollectionMissingData`

☑️ It is stated that fields like `strain`, `zeta_potential`, and `hydrodynamic_diameter` may remain blank if not reported in the article  
🟡 [No description of how missing data was handled]

---

### `rai:dataCollectionRawData`

☑️ A `pdf` column exists, pointing to the original article files  
🟡 [No information on whether raw data is stored or accessible]

---

### `rai:dataCollectionType`

☑️ Data was collected from PDF articles and their supplements  
Can be described as:  
**Manual verification following automatic extraction** (including automatic validation)

---

### `rai:dataDataManipulationProtocol`

☑️ Partially confirmed:  
- Template-based corrections in several columns like `np_synthesis`, `strain`, `bacteria`  
🟡 [Additional transformations not described]

---

### `rai:dataImputationProtocol`

🟡 **[Information not provided]**

No information on whether imputation (filling of missing values) was applied or if they were left blank.

---

### `rai:dataPreprocessingProtocol`

☑️ Terminology normalization and template corrections at the column level are mentioned.  
🟡 [Other steps (lemmatization, tokenization, text normalization) are not described]

---

### `rai:dataReleaseMaintenancePlan`

🟡 **[Information not provided]**  
No information on whether the dataset is maintained or planned to be updated

---

### `rai:dataUseCases`

☑️ Suitable for:
- Research on antimicrobial activity of nanoparticles  
- Machine learning tasks on in vitro data  
- Comparative analysis of effectiveness against MDR bacteria

🟡 Not recommended for:
- Clinical applications or inferences of in vivo effects

---



---
