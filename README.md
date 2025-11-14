# RemoteOK Job Scraper

This Python project scrapes job listings and details from [RemoteOK](https://remoteok.com) for Python/Remote developer jobs and exports them into an Excel file.

## Features
- Scrapes job title, company, location, and job URL.
- Visits each job page to extract:
  - Experience required
  - Skills required
  - Salary (if listed)
  - Job description summary
- Saves all data into `RemoteOK_Jobs_Full.xlsx`.
- Handles missing data gracefully.

## Requirements
- Python 3.x
- Libraries:
  - requests
  - beautifulsoup4
  - pandas
  - openpyxl

## Usage
1. Install dependencies:
```bash
pip install requests beautifulsoup4 pandas openpyxl
