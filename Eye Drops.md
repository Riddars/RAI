
# 🧪 Dataset: **Eye Drops – Corneal Permeability of Small Molecules**

---

## 🔷 **Core Responsible AI (RAI) Fields**

---

### `rai:dataCollection`

Data was extracted from scientific publications. Molecular structures (`SMILES`) were manually drawn based on compound names and tables provided in the articles. Corneal permeability values (`perm`) and their logarithmic counterparts (`logP`) were either directly extracted or calculated based on available parameters. Additional metadata was collected to trace sources (DOI, PMID, page numbers, tables).  
☑️ Confirmed in *Dataset Description* and *Key Notes*

---

### `rai:dataBiases`

Potential sources of bias:
- Only published compounds with known permeability values were used (positive result bias);  
- SMILES were manually created — potential subjective interpretation of structures;  
- Only molecules with known pharmaceutical applications were included (limited chemical class coverage).

🟡 **[No information provided on efforts to reduce or address these biases]**

---

### `rai:personalSensitiveInformation`

The dataset contains no personal or sensitive data. It includes only chemical structures, numerical values, and bibliographic source information.  
☑️ Fully confirmed by the dataset fields.

---

### `rai:dataLimitations`

- SMILES structures were not automatically extracted — they were drawn manually from compound names, which may lead to inaccuracies;  
- Some `perm` and `logP` values were computed rather than directly extracted — may contain calculation errors;  
- The compound list is limited to 163 entries and focused exclusively on ophthalmic use cases.

☑️ Stated in *Dataset Description* and *Key Notes*

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**  
No data on who manually created SMILES or performed value validation/calculations.

---

### `rai:dataSocialImpact`

**Potential benefits**:
- Supports the development of ophthalmic drugs;  
- Helps build predictive models for corneal permeability;  
- Useful in testing extraction methods for chemical structures and properties.

🟡 **[No information on potential risks or unintended uses is provided]**

---

## ➕ **Additional Metadata**

---

### `keywords`

ophthalmology, corneal permeability, SMILES, logP, pharmaceutical molecules, eye drops, molecular properties  
☑️ Clearly based on dataset description

---

### `creator`

🟡 **[Information not provided]**

No information available regarding the creators or team behind the project

---

### `citation`

🟡 **[Information not provided]**

No reference or formal citation format provided

---

### `semanticTypes`

☑️ Based on dataset structure:
- Chemical compound structures (SMILES format)  
- Molecular properties (permeability, logP)  
- Tabular data  
- Pharmaceutical modeling  
- Manual curation of molecules  

---

### `preProcessing`

☑️ Manual sketching and verification of structures were performed based on compound names in the articles  
☑️ 23 errors were corrected: 20 template-based and 3 unique  
☑️ Primary fields affected: `perm (cm/s)`, `name`, `smiles`

🟡 **[Details of other preprocessing steps (e.g., tokenization, case normalization) are not provided]**

---

### `purpose`

Designed for:
- Building models to assess compound permeability through the cornea;  
- Use in ophthalmic research and formulation;  
- Mapping structure–property relationships to predict biological availability.

☑️ Confirmed in *Dataset Description*

🟡 **[No mention of scenarios where use is not recommended]**

---

## 🧩 **RAI Annotation Fields**

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**

No details about individuals who drew the SMILES or verified values

---

### `rai:dataAnnotationAnalysis`

☑️ 23 corrections were made; most (20) were recurring template issues.  
Errors were found in SMILES strings, compound names, and permeability values.

🟡 No notes on annotator disagreements or agreement procedures → **[Partially provided]**

---

### `rai:dataAnnotationPlatform`

🟡 **[Information not provided]**

No mention of the tool or environment used for structure creation or annotation (e.g., ChemDraw, Google Sheets)

---

### `rai:dataAnnotationProtocol`

☑️ SMILES were manually drawn based on compound names from publications  
☑️ `perm` and `logP` values were either extracted or calculated  
🟡 No info on number of annotators, instructions, or data verification workflow

---

### `rai:machineAnnotationTools`

🟡 **[Information not provided]**

No references to use of RDKit, LLMs, or other automated extraction tools

---

## ⚙ **Fields Related to Data Quality and Processing**

---

### `rai:dataCollectionMissingData`

☑️ Some records only include one value (`perm` or `logP`) — the other was calculated  
☑️ Missing values were manually tracked and handled

---

### `rai:dataCollectionRawData`

🟡 **[Information not provided]**

No details on access to original publications or document pages

---

### `rai:dataCollectionType`

☑️ Manual data extraction from published sources  
☑️ Manual drawing of structures based on compound names

---

### `rai:dataDataManipulationProtocol`

☑️ Manual corrections included:  
- Discrepancies between compound name and SMILES structure  
- Errors in permeability values

🟡 No information on further transformations (e.g., unit normalization, filtering)

---

### `rai:dataImputationProtocol`

🟡 **[Information not provided]**

No explanation of how calculated values were treated or validated

---

### `rai:dataPreprocessingProtocol`

☑️ Manual standardization of structures and calculation of some properties was performed  
🟡 **[No automated or NLP preprocessing techniques are discussed]**

---

### `rai:dataReleaseMaintenancePlan`

🟡 **[Information not provided]**

No plan mentioned for versioning, maintenance, or future updates

---

### `rai:dataUseCases`

☑️ Suitable for:
- Predictive modeling of corneal permeability  
- QSAR analysis in ophthalmology  
- Structure–property relationship model testing

🟡 Non-recommended use cases are not listed → **[Partially provided]**

---
