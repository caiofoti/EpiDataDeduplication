# EpiDataDeduplication
This repository contains code developed during my internship at the State Center for Health Surveillance. The main purpose of this code is to automate the deduplication of epidemiological data on Viral Hepatitis in Rio Grande do Sul. It uses fuzzy similarity logic to ensure the correct identification of patients and proper cleaning of the database, which is essential for maintaining accurate and reliable health data records.

Overview
This project addresses the challenge of deduplicating epidemiological data using fuzzy matching techniques. By applying string matching and similarity computations, the code effectively identifies and merges duplicate records in the dataset.

Features
Fuzzy String Matching: Utilizes advanced fuzzy matching algorithms to identify similar records.
Automated Data Cleaning: Automatically processes and cleans the dataset to remove duplicates.
User Input for Column Names: Allows users to specify the relevant columns for names and birthdates.
Date Handling: Special handling of date formats, especially for the SIM database.
Municipality Mapping: Provides a dictionary for mapping municipality codes to names.
