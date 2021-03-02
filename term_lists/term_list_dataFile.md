|Metadata_Element|headerRows|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|number of header rows used|
|**format**|integer|
|**additional_instructions**|to enable flexibility in providing metadata in separate header rows instead of columns if that is suitable for the datafile|
|**examples**| 1 &#124; 2 &#124; 10 |

|Metadata_Element|sampleID|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|globally unique and persistent identifier for the sample.|
|**format**|alphanumeric characters|
|**additional_instructions**|must be a sampleID already or simultaneously filed according to the ESS-DIVE sample ID metadata reporting format|
|**examples**|IEWER7214 &#124; IERVTL15V|

|Metadata_Element|sampleName|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|project-specific unique sample name|
|**format**|free text &#124; unique|
|**additional_instructions**|must be the same as registered with the sampleID|
|**examples**|001-ER18-FO &#124; Ani_PTT1-76in_20190603|

|Metadata_Element|material|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|material that the sample consists of|
|**format**|SESAR controlled list|
|**additional_instructions**|must be the same as registered with the sampleID|
|**examples**|soil &#124; sediment &#124; surface water &#124; groundwater|

|Metadata_Element|variableName|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|variable name and specification - variable &#124; element &#124; chemical species etc|
|**format**|text &#124; camelCase preferred|
|**additional_instructions**|use the recommended vocabulary if possible &#124; if other terms are used - ensure there is no ambiguity in terms of speciation|
|**examples**|nitrateN &#124; sulfate &#124; organicCarbon &#124; arsenic|

|Metadata_Element | unit|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|unit for reported data &#124; SI units strongly recommended|
|**format**|text &#124; camelCase preferred|
|**additional_instructions**|use recommended vocabulary if possible or search http://unit.lternet.edu/unitregistry/ for another standardized unit &#124; minimum requirement is to specify unit in a completely unambiguous way |
|**examples**|milligramsPerLiter &#124; milliMolar &#124; percent &#124; micromolPerKilogram|

|Metadata_Element|unitBasis|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|basis for the unit |
|**format**|text &#124; camelCase preferred|
|**additional_instructions**|specify the unit basis so there is no ambiguity |
|**examples**|asNitrogen &#124; asSulfate &#124; dryWeight|

|Metadata_Element|analysisMethodID|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|identifier for the analytical method used|
|**format**|only alphanumeric characters and hyphen  "-" and underscore  "_" allowed|
|**additional_instructions**|must be unique within the dataset &#124; recommended to maintain a consistent set of methodIDs within a team or project|
|**examples**|DA-NO3-SFA &#124; ANION_T_AN_000 &#124; EA_OC &#124; HNO3-EXT-ICPMS|

|Metadata_Element|analysisDetectionLimit|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|detection limit for the analysis|
|**format**|numeric or methodID |
|**additional_instructions**|must be in same unit as data values unless a methodID is used &#124; if a methodID is used it must be listed in a methodFile or dataDictionary included with the dataset &#124; may be reported for each sample or for a set of samples|
|**examples**|0.4 &#124; TN_T_AN_000|

|Metadata_Element|analysisPrecision|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|precision of the data values|
|**format**|numeric or methodID |
|**additional_instructions**|must be in same unit as data values unless a methodID is used &#124; if a methodID is used it must be listed in a methodFile or dataDictionary included with the dataset &#124; may be reported for each sample or for a set of samples|
|**examples**|0.1 &#124; TN_T_DP_000|

|Metadata_Element|dataStatus|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|processing status of the data|
|**format**|text|
|**additional_instructions**|can be a methodID listed in a methodFile or dataDictionary included with the dataset|
|**examples**|raw &#124; adjusted for dilutions &#124; average of triplicate measurements &#124; QAQC_001|

|Metadata_Element|preservationMethodID|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|identifier for the preservation method used|
|**format**|only alphanumeric characters and hyphen  "-" and underscore  "_" allowed|
|**additional_instructions**|must be unique within the dataset &#124; recommended to maintain a consistent set of methodIDs within a team or project|
|**examples**|ICP_T_PRES_000 &#124; FRZDRY_3day &#124; ANOX-RT-DRY|

|Metadata_Element|storageMethodID|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|identifier for the storage method used|
|**format**|only alphanumeric characters and hyphen  "-" and underscore  "_" allowed|
|**additional_instructions**|must be unique within the dataset &#124; recommended to maintain a consistent set of methodIDs within a team or project|
|**examples**|FRZ_80C &#124; ANOX-RT-DRK &#124; 2C_ANOX_DARK|

|Metadata_Element|preparationMethodID|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|identifier for the preparation method used|
|**format**|only alphanumeric characters and hyphen  "-" and underscore  "_" allowed|
|**additional_instructions**|must be unique within the dataset &#124; recommended to maintain a consistent set of methodIDs within a team or project|
|**examples**|H2ODil2x &#124; HNO3_2percent &#124; HClextr_1-5|

|Metadata_Element|dataProcessingMethodID|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|identifier for the analytical method used|
|**format**|only alphanumeric characters and hyphen  "-" and underscore  "_" allowed|
|**additional_instructions**|must be unique within the dataset &#124; recommended to maintain a consistent set of methodIDs within a team or project|
|**examples**|avg3 &#124; Geochem_QA_000 &#124; outliers_10percentSTD_excluded|

|Metadata_Element|timeStampUTC|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|time of analysis in UTC format with up to 12 digits to appropriate level of precision&#124; may be in Local Standard Time if  offset is added after UTC in header or  UTC in header is replaced with timezone acronym|
|**format**|YYYYMMDDhhmmss|
|**additional_instructions**|may be reported per sample or per variable &#124; if reported per variable the variable name must be included in the header e.g. "timeStameUTC_nitrateN" |
|**examples**|20190715141235 &#124; 201810091045 &#124; 20210103|

|Metadata_Element|dataFlags|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|optional|
|**definition**|code or identifier for notifying a data quality issue or deviation from the methodology used etc|
|**format**|text &#124; alphanumeric characters and hyphen - and underscore _ format preferred|
|**additional_instructions**|may be reported per sample or per variable &#124; if reported per variable the variable name must be included in the header e.g. "dataFlags_nitrateN" &#124; may include several flags in the same field if separated by a vertical bar "&#124;" |
|**examples**||

|Metadata_Element|notes|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|optional|
|**definition**|additional notes or explanations about the data|
|**format**|text|
|**additional_instructions**|may be reported per sample or per variable &#124; if reported per variable the variable name must be included in the header e.g. "notes_nitrateN"|
|**examples**|leaked after measuring anions &#124; single measurement only &#124; concentration outside calibration curve &#124; no dilution for this sample set|
