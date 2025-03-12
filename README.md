# Python-program-to-fetch-research-papers-based-on-a-user-specified-query

To write a Python program to fetch research papers based on a user-specified query. The program must identify papers with at least one author affiliated with a pharmaceutical or biotech company and return the results as a CSV file

PubMed Research Paper Fetcher

Overview

This Python script fetches research papers from PubMed based on user queries, extracts relevant metadata, and outputs the results in a CSV file. It also identifies papers authored by researchers affiliated with pharmaceutical or biotech companies.

Features

Search for research papers using keywords.

Extract and display metadata including title, authors, affiliations, and publication year.

Filter papers by pharmaceutical and biotech affiliations.

Save results to a CSV file.

Enable debug mode for detailed logs.

Prerequisites

Python 3.8+

Poetry: for dependency management

PubMed API access (no API key required for basic queries)

Installation

Clone the repository:

https://github.com/Amal047/Python-program-to-fetch-research-papers-based-on-a-user-specified-query.git

Install dependencies using Poetry:

poetry install

Usage

Run the script with a search query:

python pyCode.py "cancer research"

Save Results to a File

python pyCode.py "cancer research" -f results.csv

Enable Debug Mode

python pyCode.py "cancer research" -d

Command-Line Arguments

Argument

Description

query

Search term for PubMed

-f, --file

Output file name (CSV)

-d, --debug

Enable debug logs

Example Output

Title: Cancer Research Study
Authors: John Doe, Jane Smith
Affiliations: ABC Pharma Inc., XYZ Biotech Co.
Year: 2023

Development

Run Tests

pytest tests/

Format Code

black .

License

MIT License

Author

Amal047 - GitHub Profile
