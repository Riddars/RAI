

# 🧪 Dataset: **Oxazolidinone Antibiotics – Chemical Structures and Antimicrobial Activity**

---

## 🔷 **Core RAI Fields**

---

### `rai:dataCollection`

The data was extracted from scientific publications. For each compound, structural information (either SMILES or scaffold + residues) is included, along with the bacterial species it was tested against and corresponding MIC/pMIC values. Additionally, the dataset records the exact page numbers, tables, figures, and sections of the publications where the relevant data was found.  
☑️ Confirmed in *Dataset Description*, *Data Scheme*, *Note*

---

### `rai:dataBiases`

Potential biases in the data:
- The focus on oxazolidinones excludes other classes of antibiotics;  
- Limited spectrum of bacteria (exact list not provided, but focus is only on MIC/pMIC measurements);  
- Only data that could be extracted from publications is included (studies with negative or zero findings may be missing).

🟡 **[No information provided regarding mitigation of these biases]**

---

### `rai:personalSensitiveInformation`

The dataset only includes chemical structures, MIC/pMIC values, and their documented sources from scientific articles. No personal or sensitive information is present.  
☑️ Confirmed through the dataset structure.

---

### `rai:dataLimitations`

- The data was obtained through different channels within each article (tables, figures, text), but experimental conditions (e.g., pH, temperature) are not standardized;  
- Limited control over how MIC/pMIC values were measured in respective studies;  
- Only MIC/pMIC values and structures are included without broader biological or pharmacological context;  
- Scaffold/residue mismatches may lead to incomplete structure representations.

☑️ Confirmed in descriptions and schema

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**  
No details are available on the individuals who performed data extraction or validation (number, gender, qualifications, etc.)

---

### `rai:dataSocialImpact`

**Positive impact**:
- Enables easier development of QSAR models;  
- Lowers barriers to accessing organized biological activity data on compounds;  
- Supports systematic review and analysis of scientific literature on antibiotics.

🟡 **[Risks and usage limitations are not described]**

---

## ➕ **Additional Metadata**

---

### `keywords`

oxazolidinones, antibiotics, MIC, QSAR, SMILES, pMIC, structure–activity, biological activity  
☑️ Clearly reflected in the description

---

### `creator`

🟡 **[Information not provided]**  
No details about authorship, labs, or affiliated teams

---

### `citation`

🟡 **[Information not provided]**  
No official citation format is given

---

### `semanticTypes`

☑️ Based on dataset contents:
- Small molecule structures (SMILES, scaffold/residue)  
- Biological activity (MIC, pMIC)  
- Scientific information extraction  
- Antibacterial modeling  
- Standardization of experimental data

---

### `preProcessing`

☑️ A total of 69 template-based corrections were made in the fields `smiles`, `compound_id`, and `target_type`.  
No unique or manually unresolvable issues were observed.

🟡 Other preprocessing steps (lemmatization, text cleaning, syntax standardization) not described → **[Partially provided]**

---

### `purpose`

Designed for:
- Developing QSAR models for antibiotics;  
- Analyzing structure–activity correlations;  
- Structuring scientific data for downstream ML applications.

☑️ Clearly stated in the description

🟡 Non-recommended use cases are not listed → **[Partially provided]**

---

## 🧩 **RAI Annotation Fields**

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**  
No data on annotators or dataset curators

---

### `rai:dataAnnotationAnalysis`

☑️ 69 template-based corrections were conducted, with no isolated or unique cases.  
Errors addressed: `smiles`, `compound_id`, `target_type`.

🟡 No information about annotator agreement or resolution of discrepancies → **[Partially provided]**

---

### `rai:dataAnnotationPlatform`

🟡 **[Information not provided]**  
No platform or annotation tool described (e.g., Label Studio, Excel, custom system)

---

### `rai:dataAnnotationProtocol`

🟡 **[Information not provided]**  
No protocol, guidelines, task distribution, or team size is documented

---

### `rai:machineAnnotationTools`

🟡 **[Information not provided]**  
No mention of LLMs, OCR, or other automated tools used in data extraction

---

## ⚙ **Data Collection and Processing**

---

### `rai:dataCollectionMissingData`

☑️ Missing values are noted in scaffold/residue formats, unit fields, and specialized columns  
🟡 Method of handling missing values (e.g., filling, deletion) is not described → **[Partially provided]**

---

### `rai:dataCollectionRawData`

🟡 **[Information not provided]**  
No details about access to original PDFs or external documentation beyond the `pdf` field

---

### `rai:dataCollectionType`

☑️ Automatic extraction of structures and values from scientific publications, with targeting of specific fields (structure, MIC/pMIC, citation location)

---

### `rai:dataDataManipulationProtocol`

☑️ Corrections and normalizations performed on fields such as:
- `smiles`  
- `compound_id`  
- `target_type`

🟡 Additional transformations (e.g., filtering, normalization) not described

---

### `rai:dataImputationProtocol`

🟡 **[Information not provided]**  
No information provided on whether missing fields were filled, ignored, or calculated

---

### `rai:dataPreprocessingProtocol`

🟡 **[Information not provided]**  
No description of preprocessing steps like text formatting, lowercasing, or tokenization

---

### `rai:dataReleaseMaintenancePlan`

🟡 **[Information not provided]**  
No indication of ongoing maintenance, responsible parties, or dataset versioning

---

### `rai:dataUseCases`

☑️ Suitable for:
- ML models involving biochemical structures  
- Antibiotic activity modeling and prediction  
- Automated extraction from scientific literature

🟡 Non-permitted or discouraged uses are unspecified → **[Partially provided]**

---
