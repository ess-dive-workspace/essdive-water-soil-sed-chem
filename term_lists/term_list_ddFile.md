|Metadata_Element|Column_Name|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|column or row header as used in data, method or any other file for which this dataDictionary applies|
|**format**|only alphanumeric characters and hyphen  "-" and underscore  "\_" allowed | camelCase preferred|
|**additional_instructions**|must list all column headers even if using templates for dataFile and methodFile|
|**examples**|sampleID |; NO3-N |; dataFlags|

|Metadata_Element|Unit|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|unit for the column &#124; report "N/A" for any column where units are not applicable|
|**format**|text|
|**additional_instructions**|SI units strongly recommended &#124; must be defined clearly and completely unambiguous|
|**examples**| milligram_Nitrate_As_Nitrogen_Per_Liter \| percent_Organic_Carbon_By_Dry_Weight|

|Metadata_Element|Definition|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|explanation of term|
|**format**|text|
|**additional_instructions**|may be a direct translation to a recommended term if applicable|
|**examples**|N/A|

|Metadata_Element|Term_Type|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|required|
|**definition**|specification of the type of term|
|**format**|text|
|**additional_instructions**|must use column_header and row_header for terms that serve as column and row headers respectively|
|**examples**|column_header \| row_header \| dataFlag \| method_type \| data_status|

|Metadata_Element|Column_or_Row_Long_Name|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|reccomended|
|**definition**|human readable name of column or row|
|**format**|text|
|**additional_instructions**|may be equivalent to column name|
|**examples**|nitrate_N \| data_Quality_Comments|

|Metadata_Element|Data_Type|
|:----------------------------------------------------|:----------------------------------------------------|
|**requirement_level**|reccommended|
|**definition**|definition of the data format|
|**format**|text|
|**additional_instructions**|ensure all data in the corresponding csv fields (columns or rows) comply with this format|
|**examples**|numeric \| text \| date \| logical \| integer|
