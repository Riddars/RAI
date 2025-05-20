

# 🧪 Dataset: **Synergy – Toxicity of Drug, Nanoparticle, and Their Synergistic Effect on Bacterial Strains**

---

## 🔷 **Core RAI Fields**

---

### `rai:dataCollection`

The data was collected from scientific publications in PDF format. Extraction was performed using automated tools and was further manually validated. Automatic validation is mentioned.  
☑️ Confirmed in *Original Data*, *Metadata*, *Note*, *Dataset Description*

---

### `rai:dataBiases`

Potential biases:
- Uneven distribution of nanoparticles and antibiotics;  
- Predominance of certain bacterial strains;  
- Publication bias (data sourced from already published studies);  
- Missing values in several columns (e.g., MIC, zeta potential, coating, etc.).

🟡 **[No information provided regarding bias mitigation efforts]**

---

### `rai:personalSensitiveInformation`

The dataset consists solely of in vitro experimental data. No personal or sensitive information is present.  
☑️ Confirmed based on the data table structure and nature of sources.

---

### `rai:dataLimitations`

- Data obtained under in vitro laboratory conditions;  
- Does not reflect in vivo effects or behavior;  
- Some values are missing (e.g., MIC, coating, zeta potential);  
- Possible methodological variations between publications.

☑️ Confirmed in *Dataset Description* and *Notes*

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**  
No request for or description of annotators (number, age, gender, country, native language, specialization, etc.)

---

### `rai:dataSocialImpact`

**Potential positive impacts**:
- Support for research combating antibiotic-resistant bacteria;  
- Development of combination nano-based agents with synergistic effects.

🟡 **[Potential risks/limitations regarding social use not described]**

---

## ➕ **Additional Metadata**

---

### `keywords`

nanomedicine, antibiotics, synergy, microbiology, MIC, FIC, bacterial strains, resistance, combination therapy  
☑️ Justified based on data description and structure

---

### `creator`

🟡 **[Information not provided]**

No mention of the team, institute, or lab is present.

---

### `citation`

🟡 **[Information not provided]**

No publication or citation format is provided.

---

### `semanticTypes`

☑️ Based on dataset content:
- Synergy analysis  
- Antimicrobial activity  
- Drug efficacy prediction  
- Multimodal biomedical data  
- Information extraction

---

### `preProcessing`

☑️ Automatic validation was performed.  
🟡 Corrections/transformations (normalization, error handling, workarounds) **are not described**  
🟡 Lemmatization, tokenization, and other NLP procedures **are not specified**

---

### `purpose`

- Research into synergistic antimicrobial effects of NPs and antibiotics  
- Modeling interactions in drug + nanoparticle systems  
- Testing algorithms for synergy detection  
☑️ Confirmed in *Dataset Description*

🟡 No list of non-recommended applications provided → **[Partially provided information]**

---

## 🧩 **Annotation Fields**

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**

No details regarding platform, experience, number of annotators, etc.

---

### `rai:dataAnnotationAnalysis`

🟡 **[Information not provided]**

No mention of errors, annotation conflicts, agreement levels, or resolution strategies.

---

### `rai:dataAnnotationPlatform`

🟡 **[Information not provided]**

The environment/platform used for annotation is not mentioned (e.g., Google Sheets, Excel, Label Studio, etc.)

---

### `rai:dataAnnotationProtocol`

🟡 **[Information not provided]**

No step-by-step protocol, guidelines, number of annotators per item, or verification process is described.

---

### `rai:machineAnnotationTools`

🟡 **[Information not provided]**

No tools/models used for OCR, LLM, or NER (if any) are specified.

---

## ⚙ **Fields Related to Data Quality and Processing**

---

### `rai:dataCollectionMissingData`

☑️ It is mentioned that some columns have missing values (e.g., drug, zeta_potential, peptide_MIC).  
Missing data appears as empty cells.

🟡 It is not specified how missing values were handled (e.g., deletion, imputation)

---

### `rai:dataCollectionRawData`

☑️ A `pdf` field is included indicating the source articles.  
🟡 However, it is not specified where the raw data is stored, whether it is accessible or published → **[Information not provided]**

---

### `rai:dataCollectionType`

☑️ Stated: data were collected from articles (PDF), with automatic verification and manual review.  
Collection type — **hybrid extraction with verification**

---

### `rai:dataDataManipulationProtocol`

🟡 **[Information not provided]**

No details on normalization, unit conversion, duplicate handling, or other data transformations.

---

### `rai:dataImputationProtocol`

🟡 **[Information not provided]**

No indication of whether imputation was performed or whether missing values were handled using specific strategies.

---

### `rai:dataPreprocessingProtocol`

🟡 **[Information not provided]**

No description of preprocessing steps prior to usage (format standardization, tokenization, etc.)

---

### `rai:dataReleaseMaintenancePlan`

🟡 **[Information not provided]**

No maintenance, versioning, or update mechanism is mentioned.

---

### `rai:dataUseCases`

☑️ Designed for:
- Analysis of antimicrobial effectiveness of drug-nanomaterial combinations  
- Identifying synergy and building predictive models

🟡 No mention of where use is **not recommended** → **[Partially provided]**

---
