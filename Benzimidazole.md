
# 🧪 Dataset: **Benzimidazole Antibiotics – Chemical Structures and Antimicrobial Activity**

---

## 🔷 **Core RAI Fields**

---

### `rai:dataCollection`

Data was automatically extracted from scientific articles using a specialized prompt designed to retrieve information on benzimidazole derivatives. Extracted elements include SMILES structures, MIC/pMIC values, and related metadata. Both text and images in the articles served as sources.  
☑️ Confirmed in *Extraction Prompt* and *Dataset Description*

---

### `rai:dataBiases`

Possible biases:
- Data is limited to only two bacterial species: *S. aureus* and *E. coli*;  
- Selectivity toward compounds based on the benzimidazole scaffold;  
- Limited availability of MIC/pMIC values depending on whether the information was present in the original publications.

🟡 **[No information provided on efforts to address these biases]**

---

### `rai:personalSensitiveInformation`

The dataset contains only experimental chemico-biological data extracted from published scientific papers. No personal or sensitive information is included.  
☑️ Confirmed based on dataset composition

---

### `rai:dataLimitations`

- Some structures in the dataset are incomplete or underspecified (e.g., scaffold + residue);  
- MIC/pMIC values may vary based on measurement methods, and normalization of conditions is not described;  
- Only covers *S. aureus* and *E. coli*, excluding other pathogens;  
- Some fields are marked as “NOT_DETECTED” — reflecting incomplete source data.

☑️ Clarified in *Notes* and *Dataset Description*

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**  
No data regarding annotators’ specialization, country, age, language, or other demographics.

---

### `rai:dataSocialImpact`

**Positive impact**:
- Supports the discovery of new antimicrobial agents;  
- Facilitates development of QSAR models and analysis of structure–activity relationships;  
- Simplifies access to structured data on antibiotics.

🟡 **[No information provided about risks or potential misuse]**

---

## ➕ **Additional Metadata**

---

### `keywords`

benzimidazole, antibiotics, MIC, SMILES, structure–activity, antimicrobial activity, QSAR, pMIC  
☑️ Confirmed from the dataset description and schema

---

### `creator`

🟡 **[Information not provided]**  
No author or organization specified

---

### `citation`

🟡 **[Information not provided]**  
No citation format or publication reference included

---

### `semanticTypes`

☑️ Based on the description and objectives:
- Molecular structure representation (SMILES)  
- Compound properties (inhibition threshold)  
- Information extraction from articles  
- Antibacterial studies of small molecules  
- QSAR modeling

---

### `preProcessing`

☑️ A total of 77 corrections were made: 63 template-based, 14 unique  
- Key fields: `smiles`, `target_value`, `compound_id`  
- Typical issues: incomplete SMILES, identifier mismatches

🟡 Formatting normalization, tokenization, and similar procedures are not detailed → **[Partially provided]**

---

### `purpose`

The dataset is intended for:
- QSAR modeling  
- Analysis of structure–activity relationships  
- Chemical information extraction from academic literature  
- Studying the efficacy of antibacterial agents

☑️ Stated in *Dataset Description*

🟡 No non-recommended usage stated → **[Partially provided]**

---

## 🧩 **Annotation (RAI) Fields**

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**

No details about individuals involved in annotation or validation

---

### `rai:dataAnnotationAnalysis`

☑️ 77 corrections made, including 63 template-based and 14 isolated issues  
Errors in fields: `smiles`, `target_value`, `compound_id`  
🟡 No information on annotation agreement or quality checks → **[Partially provided]**

---

### `rai:dataAnnotationPlatform`

🟡 **[Information not provided]**

No annotation tool or environment mentioned

---

### `rai:dataAnnotationProtocol`

☑️ A specialized system with strict extraction rules was used, with `NOT_DETECTED` as a standard marker  
🟡 Details about manual validation, task distribution, or guidelines are missing → **[Partially provided]**

---

### `rai:machineAnnotationTools`

☑️ Mentioned that a **specialized extraction prompt** was used, focused on:
- benzimidazole-based antibiotics  
- *S. aureus* and *E. coli*  
🟡 Specific names of tools or models are not disclosed → **[Partially provided]**

---

## ⚙ **Fields Related to Data Collection and Processing**

---

### `rai:dataCollectionMissingData`

☑️ Missing values are marked as `NOT_DETECTED` and present across various fields  
🟡 No description of how missing data was handled (e.g., removed, imputed)

---

### `rai:dataCollectionRawData`

🟡 **[Information not provided]**  
No mention of access to raw data (PDFs, original tables)

---

### `rai:dataCollectionType`

☑️ Combined method: automatic extraction of information from scientific publications

---

### `rai:dataDataManipulationProtocol`

☑️ Corrections were made to:
- SMILES structures  
- MIC numeric values  
- Compound identifiers  
🟡 Additional data handling procedures are not described (e.g., filtering, normalization)

---

### `rai:dataImputationProtocol`

🟡 **[Information not provided]**  
No information on imputed or substituted missing values, aside from the `NOT_DETECTED` flag

---

### `rai:dataPreprocessingProtocol`

☑️ Entries were structured based on a pattern; standardized string formats are present (e.g., unit fields, relation symbols)  
🟡 Technical steps (lowercasing, tokenization, etc.) are not mentioned

---

### `rai:dataReleaseMaintenancePlan`

🟡 **[Information not provided]**

No information regarding dataset updates or maintenance responsibility

---

### `rai:dataUseCases`

☑️ Designed for:
- Modeling antimicrobial activity  
- Extraction and normalization of chemical properties  
- In silico model validation

🟡 Usage limitations (e.g., avoid use without expert interpretation) are not stated → **[Partially provided]**

---
