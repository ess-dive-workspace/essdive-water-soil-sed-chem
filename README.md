ESS-DIVE Reporting Format for Water-Soil-Sediment Chemistry Data

This reporting format has been developed to use for data from chemical concentration measurements of water, soil, and sediment samples. The goal of the reporting format is to ensure that data and metadata files are machine-readable, and that enough metadata is included with the data to make it FAIR (findable, accessible, interoperable, and re-useable) such that data meta-data analyses, modelling, and other ‘data uses’ are enabled. However, the primary purpose is to provide guidelines and templates that facilitate the process of archiving water/soil/sediment chemistry data in a meaningful way for the data producers/collectors and ensure that appropriate credit is received for collecting the data. 

**The reporting format assumes that all files will be uploaded to ESS-DIVE as CSV files**, even if the excel-based templates are used (i.e. they should be converted to CSV files in the end). It builds on and follows the ESS-DIVE requirements for package level, [file level](https://github.com/ess-dive-community/essdive-file-level-metadata), [sample ID](https://github.com/ess-dive-community/essdive-sample-id-metadata), and [CSV file](https://github.com/ess-dive-community/essdive-csv-structure) metadata, terminology, and structure, such that compliance with this reporting format will automatically ensure compliance with those upstream requirements. 

There are three required parts to this reporting format, in order to comply with ESS-DIVE recommendations: the actual data, the associated methods, and the explanation/definition of used terminology and codes/flags. The recommendation is to keep these in three separate csv-files that are packaged together and that unique codes/IDs are used to link between metadata and data files (e.g., a method code (ID) used in a data file is listed in a method file along with enough detail about the method to enable an outside viewer to judge the integrity of the sample and the quality of the associated data for a specific purpose). It is strongly recommended to use the templates (dataFile, methodFile, and terminologyFile *links coming soon*) and recommended vocabularies *links coming soon* for this reporting format to the extent possible, as they have been designed to facilitate adherence to the requirements. Thus, as long as all samples have been registered in accordance with the [ESS-DIVE sample metadata reporting format](https://github.com/ess-dive-community/essdive-sample-id-metadata), using the templates will make this the ‘one-shop-stop’ for assembling and archiving laboratory analyses of water/soil/sediment chemistry data within ESS-DIVE.

However, other ways of structuring the data and metadata are permissible as long as all the required information is 1) included, 2) unambiguously linked to the data, and 3) the organization of this information is clearly explained in a readMe (or similar) file. In addition, 4) all file formats should follow upstream ESS-DIVE reporting formats (package level, [file level](https://github.com/ess-dive-community/essdive-file-level-metadata), [sample ID](https://github.com/ess-dive-community/essdive-sample-id-metadata), and [CSV file](https://github.com/ess-dive-community/essdive-csv-structure))  and instructions. 

## Getting started

## How to contribute

This reporting format is evolving and adapting to meet the needs of the community. Feedback and new contributions are welcome. If you would like to suggest a change, please submit a GitHub issue using one of the templates we provide. We recognize that, although our intent is to provide a reporting format that will enable data producers to gain wider spread recognition for their data and data users to gain more streamlined options for automized download and synthesis of datasets, the result is a reporting format that will please nobody and that leaves a lot to be desired from everybody. 

If you have any questions about this reporting format, you can also email ESS-DIVE support at ess-dive-support *at* lbl.gov.


## Copyright information

This repository content is license for use under the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/)

## Funding and acknowledgements

Funding for the development of ESS-DIVE's generic water/soil/sediment sample data and metadata reporting format was provided by the U.S. Department of Energy, Office of Science, Office of Biological and Environmental Research, Climate and Environmental Science Division, Data Management program under contract number DE-AC02-05CH11231.

## Related References

## References

Our reporting format and templates were loosely based on those used by the EPA and USGS through the [Water Quality Portal (WQP)](https://www.waterqualitydata.us/), but were also inspired from other standards, best practices, and recommendations within the water quality, soil science, and geological survey communities. Most importantly the reporting format and templates were developed to fit with needs, recommendations, and advice from the DOE-BER-ESS community including both data producers and data users – a summary of the community member feedback and list of consulted members can be found here.
