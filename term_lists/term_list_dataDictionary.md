|Metadata_Element|Column_Name|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|column header as used in dataFile or methodFile or any other file for which this dataDictionary applies|
|**format**|only alphanumeric characters and hyphen  "-" and underscore  "_" allowed &#124; camelCase preferred|
|**additional_instructions**|must list all column headers even if using templates for dataFile and methodFile|
|**examples**|sampleID &#124; NO3-N &#124; dataFlags |

|Metadata_Element|Unit|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|unit for the column &#124; report "N/A" for any column where units are not applicable|
|**format**|text &#124; camelCase preferred|
|**additional_instructions**|SI units strongly recommended &#124; must be defined clearly and completely unambiguous|
|**examples**|milligramNitrateAsNitrogenPerLiter &#124; percentOrganicCarbonByDryWeight|

|Metadata_Element|Definition|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|explanation of term |
|**format**|text|
|**additional_instructions**|may be a direct translation to a recommended term if applicable|
|**examples**||

|Metadata_Element|Column_Long_Name|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|human readable name of column|
|**format**|text|
|**additional_instructions**|may be equivalent to column name|
|**examples**|nitrateN &#124; dataQualityComments|

|Metadata_Element|Data_Type|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|recommended|
|**definition**|definition of the data format|
|**format**|text|
|**additional_instructions**|ensure all data in the corresponding csv fields (columns or rows) comply with this format|
|**examples**|numeric &#124; text &#124; date &#124; logical &#124; integer|
