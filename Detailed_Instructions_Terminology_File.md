# Detailed Instructions for Terminiology File(s)

The terminology file template is structured to allow for collecting all terms used by one project/team etc. into one master terminology library. Note that the terminology file is different from the data dictionary (\_dd.csv) that is required for all csv files, but it is completely fine to include row/column headers (i.e. the fields required to list in the data dictionary) in the terminology file as well. Depending on how you prefer to structure your data and how consistent the units etc. are between data files, it may be helpful to include the required fields from the data dictionary template in the terminology file, and then pull out the relevant ones for each \_dd.csv file. Note that the header for the “Term” column should be “Column_or_Row_Name” in the \_dd.csv files.

Figure 1 shows an example of terms listed in a terminology file, without including the column names  that are part of the \_dd.csv files. Figure 2 shows an example of a terminology file that is structured like the \_dd.csv template, but with the additional column stating the type of term in order to allow for a single master file collection of all terminology used within a dataset/project/team etc. Note that the Units column is required in \_dd.csv files.

![Diagram showing an example termininology file with only required fields.](https://github.com/ess-dive-community/essdive-water-soil-sed-chem/blob/main/.gitbook/assests/Terminology_File_Figure_1.png)

**Figure 1.** Example of terminology file with only required metadata.

![Diagram showing an example terminology file with terms used by a project. This diagram includes terms, their definitions, and other important information about the terms. This template includes both required and optional fields.](https://github.com/ess-dive-community/essdive-water-soil-sed-chem/blob/main/.gitbook/assests/Terminology_File_Figure_2.png)

**Figure 2.** Example of a terminology file that is structured to include all terms used by a project (i.e. including headers etc that are required in the \_dd.csv files) - i.e., serving as a complete dictionary. Note that the shaded fields are the only ones required for a terminology file included as part of a water-soil-sed-chem dataset, and the unshaded (appearing white) fields are added because they are required in the \_dd.csv files. If you prefer to keep the data dictionaries and the other terminology files separate, then disregard columns B and D above for the terminology file and remove column E (Term_Type) for the data dictionary files.
