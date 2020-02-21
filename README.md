# SOUPS20GovVsCompanies

This repository contains the data for the following paper:

Comparing Privacy Policies of Government Agencies and Companies: a Study Using Privacy Policy Analysis Tools

We make our data, including links to all the privacy policies, their downloaded text used in the experiments, and the results of running the tools on them, publicly available.

# Repository structure 
The Corpora folder includes five text files, each containing the URLs of privacy policies of one corpus: EU, US, APP, STOCK, and WEB. This folder also includes five folders, each containing the downloaded html files of privacy policies of each corpus.

The Results folder has a spreadsheet named statsPolisis.xlsx that contains the number of times each Polisis assessment was reported for each of the five corpora (EU, US, APP, STOCK, and WEB). It also calculates the percentage of occurrence in each corpus and lists short names for Polisis assessments. Finally, in the folder named statsPrivacyCheck, there are five spreadsheets named {CORPUS}_PrivacyCheck.xlsx listing what PrivacyCheck returned for each of its ten privacy factors per URL. A sample table shows how we calculated the distribution of PrivacyCheck risk levels for the paper.
