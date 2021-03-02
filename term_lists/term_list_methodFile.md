|Metadata_Element|methodID|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|identifier for the method used|
|**format**|only alphanumeric characters and dash  "-" and underscore  "_" allowed|
|**additional_instructions**|must be unique within the dataset &#124; recommended to maintain a consistent set of methodIDs within a team or project|
|**examples**|ANION_T_AN_000 &#124; FRZ_80C &#124; H2Odilutionx2|

|Metadata_Element|methodType|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|the type of method |
|**format**|text &#124; camelCase preferred|
|**additional_instructions**|use recommended vocabulary if possible &#124; include definitions for used terminology in dataDictionary|
|**examples**|analysisMethod &#124; storageMethod &#124; preparationMethod &#124; dataProcessingMethod|

|Metadata_Element|methodDescription|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|method description detailed enough to pass peer review in a scientific publication|
|**format**|text|
|**additional_instructions**|may refer to publication of method including any deviations and modifications applied|
|**examples**|EPA 353.2 Rev 2 &#124; Vials were stored at -80 degC until prepared for analysis &#124; Dissolved organic C was analyzed by the non-purgeable organic C (NPOC) method on a Shimadzu TOC-L analyzer with in-line acidification (phosphoric acid) of samples to volatilize inorganic C|

|Metadata_Element|methodInstrument|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|instrument specifications: type &#124; model &#124; manufacturer &#124; manufacturing location |
|**format**|text|
|**additional_instructions**|use N/A for methods that did not involve a specific instrument|
|**examples**|WestCo SmartChem 200 Discrete Analyzer &#124; ICP-MS XSERIES 2 - 135 Thermo Scientific - Cambridge - U.K.|

|Metadata_Element|methodLab|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|name of the laboratory where the method was performed|
|**format**|text|
|**additional_instructions**|as specific as possible &#124; may be more than one laboratory if appropriate but must be clarified what was done where in that case|
|**examples**|EMSL-PNNL &#124; UC Davis Analytical Lab|

|Metadata_Element|methodLabContact|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|contact details for the laboratory where the method was performed|
|**format**|text|
|**additional_instructions**|include all relevant contact information; website &#124; email address &#124; postal address &#124; phone number&#124; name of contact person|
|**examples**|UC Davis Analytical Lab; University of California Davis; CA-95616-5270; (530) 752-0147; anlab@ucdavis.edu|

|Metadata_Element|methodTemp|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|temperature at which method was carried out|
|**format**|text | degrees celsius preferred|
|**additional_instructions**|recommended format is temperature in degrees celsius (e.g. 20C, 2C, -80C), but can also be "ambient", "unknown", "iced", "heated' etc that provides relevant information even if the exact temperature is not known|
|**examples**| 2C &#124; -80C &#124; frozen &#124; room temperature|

|Metadata_Element|methodLight|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|light conditions for the method|
|**format**|text | camelCase preferred|
|**additional_instructions**|report if light conditions are relevant for sample integrity|
|**examples**|ambient light &#124; dark &#124; unknown|

|Metadata_Element|methodAtmosphere|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|atmosphere for the method|
|**format**|text &#124; alphanumerical preferred|
|**additional_instructions**|report if atmosphere is relevant for sample integrity or method specificity |
|**examples**|anoxic &#124; 95to5-N2toH2&#124; vaccuum &#124; He |

|Metadata_Element|methodMoisture|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|moisture conditions of sample exposed to method|
|**format**|text|
|**additional_instructions**|only relevant for solid samples|
|**examples**|dry &#124; field moist &#124; 30 percent water holding capacity &#124; field capacity |

|Metadata_Element|methodMedium|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|medium used for the method|
|**format**|text|
|**additional_instructions**|report for methods involving manipulations of the initial sample medium: extractions&#124; dilutions &#124; nutrient media for incubations. Must include concentrations and specific composition in method description field.|
|**examples**||

|Metadata_Element|methodTime|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|time span for method|
|**format**|number and unit|
|**additional_instructions**|report if relevant for the method: incubation time &#124; storage time &#124; extraction time etc|
|**examples**|2 hours &#124; 30 days &#124; 20 minutes|

|Metadata_Element|methodReference|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|citation or link to published method description|
|**format**|text|
|**additional_instructions**|if possible provide the citation if the method has been published or a link to method description website|
|**examples**|https://www.epa.gov/sites/production/files/2015-08/documents/method_353-2_1993.pdf|
