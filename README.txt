This is the repository for the exam project of the course Information Science, part of the MA Digital Text Analysis of the University of Antwerp.

This repository contains the code (VandyckCarolineInformationScience.ipynb) for data reconciliation between a sample of the Anet SQLite export file and the CERL Thesaurus SRU/CQL service. For the code to work, the notebook and the sample need to be located in the same directory.

The purpose of the code is to retrieve the tags/identifiers (one from Anet, one from the CERL Thesaurus) that correspond for the same person. The program will query CERL on the basis of the surname obtained from Anet and will select the first 50 records. For those 50 (or less) records, it will be checked whether the first name and year of birth match. In the end, every record obtained from CERL will be returned with a statement on which metadata it matches Anet. It only uses Python's standard library.

At the end of the notebook, some observations and possible improvements are listed. However, most of these 'possible improvements' boil down to personal choices/preferences (relating to what you find important and how you want to standardize names). There are always many options to choose from and choices to make. I attempted to make the optimal ones and explained why, yet opinions can differ.
