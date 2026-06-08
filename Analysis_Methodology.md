# Analysis Methodology

## Project Overview

This project analyzes the Tamil Nadu Assembly Election 2026 and compares it with the 2021 election results to identify regional shifts, constituency-level changes, reserved-seat patterns, and changes in electoral competitiveness.

The analysis was conducted using Power BI, Power Query, and DAX.

---

## Data Sources

The project uses:

* Tamil Nadu Assembly Election 2021 Results
* Tamil Nadu Assembly Election 2026 Results
* Constituency Master Data
* Reserved Category Information (SC/ST/General)

Additional constituency-level information was validated using publicly available election data sources where required.

---

## Data Preparation

### Data Cleaning

The following steps were performed in Power Query:

* Standardized column names
* Removed unnecessary columns
* Verified constituency identifiers
* Checked for duplicate records
* Corrected data types
* Created year identifiers for comparative analysis

### Data Transformation

* Appended 2021 and 2026 datasets for comparison
* Created winner tables for both election years
* Calculated constituency-level seat counts
* Categorized constituencies into six regions:

  * Chennai Metro
  * North
  * Central
  * Kongu
  * Delta
  * South
* Classified constituencies into:

  * SC Reserved
  * ST Reserved
  * General

---

## Analytical Approach

### 1. Geographic Story

Objective:
Analyze how seat distribution changed across Tamil Nadu's six regions.

Method:

* Calculated seats won by party in each region.
* Compared regional performance between 2021 and 2026.
* Measured seat gains and losses by major parties.

Key Finding:

TVK emerged as a major statewide force while DMK experienced seat losses across all regions.

---

### 2. Flip Story

Objective:
Identify constituencies that changed their winning party.

Method:

* Compared winning parties in each constituency between 2021 and 2026.
* Created a constituency transition matrix.
* Measured party-to-party seat transfers.

Key Finding:

A large number of constituencies changed their winning party, with TVK being the largest beneficiary.

---

### 3. Reserved Seat Story

Objective:
Determine whether reserved constituencies behaved differently from general constituencies.

Method:

* Segmented constituencies into SC, ST, and General categories.
* Compared party performance between 2021 and 2026.
* Evaluated seat changes by reservation category.

Key Finding:

TVK performed strongly in both reserved and general constituencies.

---

### 4. Margin of Victory Story

Objective:
Assess electoral competitiveness.

Method:

* Identified winners and runners-up for each constituency.
* Calculated victory margins.
* Compared average victory margins across election years.

Key Finding:

Average victory margins declined from approximately 23K votes in 2021 to 17K votes in 2026, indicating more competitive elections.

---

## Dashboard Development

The dashboard was developed in Power BI using:

* Interactive filters and slicers
* KPI cards
* Matrix visualizations
* Regional comparisons
* Party performance analysis
* Constituency transition analysis

---

## Limitations

* Some constituency-level turnout information was not directly available in the provided datasets.
* Analysis is based on officially available election result data and derived calculations.
* Findings should be interpreted within the context of the available data sources.

---

## Tools Used

* Power BI
* Power Query
* DAX
* Microsoft PowerPoint
* GitHub

---

## Author

Veena Chandra

Data Analytics | Power BI | Business Intelligence
