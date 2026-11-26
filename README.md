# Nobel Prize API and Nested JSON Analysis

**R · REST API · Pagination · Relational data transformation**

## Overview
Explore Nobel recognition across categories and decades, representation, age at award and birth versus affiliation countries.

## Analytical workflow
Retrieve paginated laureate JSON with retries, flatten into laureate, award and affiliation tables, validate identifiers, handle missing fields and summarize results.

## Project files
- [Data 607 Assigment 10B Code Base.qmd](Data%20607%20Assigment%2010B%20Code%20Base.qmd) — analysis source.
- See the repository for accompanying rendered reports and any included source data.

## Reproduce
Render the Quarto source with R and internet access; the setup installs missing packages. No API key is required.

## Limitations
Live API records may change; a laureate–prize row is not necessarily a distinct prize event.

*Academic project — DATA 607, CUNY School of Professional Studies.*
