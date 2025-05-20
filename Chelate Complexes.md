

# 🧪 Dataset: **Chelate Complexes – Thermodynamic Stability of Metal–Ligand Complexes**

---

## 🔷 **Core Responsible AI (RAI) Fields**

---

### `rai:dataCollection`

The data was manually extracted from scientific publications. Extracted elements include ligand structures in canonical SMILES format, metal type, and thermodynamic stability values (lgK). Each value is linked to a specific source and page within the publication. All structures were standardized using RDKit.  
☑️ Confirmed in *Original Data*, *Dataset Description*, *Key Notes*

---

### `rai:dataBiases`

Potential sources of bias:
- Only 4 metal types are represented: Ga, Gd, Tc, Lu;  
- Polymers, biomolecules, nonstandard radicals, and undefined structures were excluded;  
- Only publications that fully matched the selection criteria were used.

🟡 **[No information provided on bias mitigation efforts]**

---

### `rai:personalSensitiveInformation`

The dataset contains no personal or sensitive information. All data consists of depersonalized chemical and experimental parameters extracted from published scientific sources.  
☑️ Confirmed based on field content and data structure

---

### `rai:dataLimitations`

- Limited to four metals: Ga, Gd, Tc, Lu;  
- Stereochemistry was removed;  
- No inclusion of biomolecular interactions, arbitrary radicals, or structural precursors;  
- Intended solely for **in vitro / theoretical analysis**, with no biological or pharmacokinetic data.

☑️ Confirmed in *Key Notes* and *Restrictions*

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**  
No information is available regarding who performed annotation (gender, age, country, experience, etc.)

---

### `rai:dataSocialImpact`

**Potential benefits**:
- Supports development of MRI contrast agents;  
- Enables the creation of benchmark datasets for coordination chemistry research;  
- Improves accuracy of automated data extraction systems.

🟡 Potential risks (e.g., misuse in medical decision-making without sufficient validation) **not addressed** → **[Partially provided]**

---

## ➕ **Additional Metadata**

---

### `keywords`

chelate complexes, stability, lgK, organometallic chemistry, SMILES, ligand, contrast agents, Gd, Ga, Tc, Lu  
☑️ Derived from dataset description

---

### `creator`

🟡 **[Information not provided]**  
No information about the data extraction team or authors

---

### `citation`

🟡 **[Information not provided]**  
No guidance on how to cite usage of the dataset

---

### `semanticTypes`

☑️ Based on domain scope:
- Coordination compounds  
- Thermodynamics  
- Property prediction  
- Structural chemistry  
- Machine learning in chemistry

---

### `preProcessing`

☑️ Molecules were converted into **canonical SMILES format**  
☑️ **Stereochemistry was manually removed**  
☑️ Structural filtering rules were applied (e.g., incomplete ligands, polyamides, amino acids excluded)  
☑️ 212 corrections in total: 190 template-based and 22 manual/focused

🟡 No detailed description of NLP- or table-based preprocessing → **[Partially provided]**

---

### `purpose`

- Modeling stability of nuclear and MRI-relevant complexes  
- Studying interactions between metals and macrocyclic/polydentate ligands  
- Testing methods for automated data extraction in coordination chemistry

☑️ Clearly stated in *Dataset Description*

🟡 No information on non-recommended use cases → **[Partially provided]**

---

## 🧩 **Responsible AI Annotation Fields**

---

### `rai:annotatorDemographics`

🟡 **[Information not provided]**  
No details on annotator qualifications, team composition, or affiliations

---

### `rai:dataAnnotationAnalysis`

☑️ A total of 212 corrections were made:  
- 190 template-based (e.g., bracket notation, SMILES formatting);  
- 22 custom cases such as mismatches between compound numbers and figure references.  
☑️ Most frequent errors occurred in `compound_id`, `compound_name`, and `SMILES`.

🟡 No data on agreement protocols or multilayer annotation review → **[Partially provided]**

---

### `rai:dataAnnotationPlatform`

🟡 **[Information not provided]**  
No mention of tools or platforms used for annotation (e.g., Google Sheets, Prodigy, others)

---

### `rai:dataAnnotationProtocol`

☑️ It is stated that only complete and well-defined structures were extracted  
☑️ Strict filtering was applied: short structures, radicals, and precursors excluded  
🟡 No details on annotation steps, number of contributors, or documentation of annotation rules → **[Partially provided]**

---

### `rai:machineAnnotationTools`

🟡 **[Information not provided]**  
No indication whether automated tools were used (e.g., RDKit, NLP models)

---

## ⚙ **Data Collection and Processing**

---

### `rai:dataCollectionMissingData`

☑️ Some values may be missing (e.g., structure, page ID)  
☑️ Missing entries were either filtered out or excluded prior to final dataset assembly

🟡 The method of handling missing values is not described separately → **[Partially provided]**

---

### `rai:dataCollectionRawData`

🟡 **[Information not provided]**  
PDFs are referenced, but it is unclear whether source files are accessible to users

---

### `rai:dataCollectionType`

☑️ Manual extraction from scientific articles and supplementary materials, followed by validation and filtering

---

### `rai:dataDataManipulationProtocol`

☑️ Data cleaning and filtering procedures included:  
- Removal of incomplete or ambiguous structures  
- Filtering out short compounds  
- Resolving inconsistencies between compound identifiers and figure references  

☑️ Implemented through 212 corrections

---

### `rai:dataImputationProtocol`

🟡 **[Information not provided]**  
No indication of whether imputation or value-filling techniques were used

---

### `rai:dataPreprocessingProtocol`

☑️ Stereochemistry was removed  
☑️ Structures normalized to canonical SMILES  
🟡 No information on NLP preprocessing, segmentation, or text normalization → **[Partially provided]**

---

### `rai:dataReleaseMaintenancePlan`

🟡 **[Information not provided]**  
No information provided regarding dataset updates or maintenance responsibilities

---

### `rai:dataUseCases`

☑️ Recommended for:
- Modeling thermodynamic stability of chelate complexes  
- Research related to MRI contrast agents  
- Evaluation of chemical data extraction algorithms

🟡 No information on use cases where the dataset should **not** be applied → **[Partially provided]**

---
