# Water-Soil-Sediment Chemistry Data Reporting Format Instructions  
To create a data package containing chemical concentration data for water/soil/sediment samples follow these steps:  

1. Decide how you want to organize your data – for example: one or more data files?, samples in rows or columns?, one or more variables in one data file – if more than one, in rows or columns?, method metadata details in same or separate file? **We strongly recommend using separate files for the data and the detailed method metadata, as it will simplify reuse of your method metadata across data packages.** It also makes the data table easier to overview.  

2. Make sure all of your samples have a unique identifier and assemble the [sample metadata table](https://github.com/ess-dive-community/essdive-sample-id-metadata/blob/master/sampleTemplate.xls), following the instructions for [sample metadata](https://ess-dive.gitbook.io/sample-id-and-metadata/).  

3. Assemble the data table(s), making sure that all of the required fields are included and formatted correctly. **NO empty rows or cells are allowed, must use “-9999” for missing values in numerical fields and “N/A” in text fields.** Use the recommended vocabularies for variable names, units, and method types to the extent possible. Using the dataFile template is strongly recommended. Note that header rows can be turned into columns if that is more suitable for your data. Units may be reported as part of the header name, instead of as a separate header row, if that is preferred.  

4. Assemble the method file (template), making sure all of the required fields are included and formatted correctly. All method descriptions must be detailed enough for someone else to repeat the procedure. It is recommended to separate out details that are of relevance for making quick assessments about sample integrity, method applicability, and data quality (e.g. temperature, light conditions). 

5. List all terms (column headers and row labels) in a data dictionary table(s) ([template](https://github.com/ess-dive-community/essdive-file-level-metadata/tree/master/csv_dd_instructions)), providing the required metadata. Note that if units are included in the variable name, it is still required to specify the unit in the data dictionary. This is needed to make translation and combination of data from various projects and packages possible for others. 

6. If you are using data flags or other codes (that are not methodIDs or sampleIDs) you must provide explanations for those in a separate terminology file (template). 

7. Save all files in csv format with the appropriate extension (i.e. &#95;dataFile; &#95;methodmetadataFile; &#95;csv&#95;dd). Filenames should be unique and be as descriptive as possible about the file contents. Use only letters (e.g. CamelCase), numbers, and underscores "&#95;". Do not include spaces. Hyphens are allowed but not preferred.

8. Create a [file level metadata (FLMD) table](https://github.com/ess-dive-community/essdive-file-level-metadata/blob/master/documents/flmd_quick_guide.md) ([template](https://github.com/ess-dive-community/essdive-file-level-metadata/blob/3acd84067cf980484b4b86e95dbdcace42db3796/flmd_template.xlsx)). If the same metadata applies to multiple files in the same package use the "&ast;" wildcard. For example – if the same FLMD applies to all data files in this data package, enter "&#95;dataFile&ast;.csv" in the file name column of the FLMD.
