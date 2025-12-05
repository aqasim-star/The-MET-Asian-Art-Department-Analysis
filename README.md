# The-MET-Asian-Art-Department-Analysis
This project retrieves, analyzes, and visualizes artworks from The Metropolitan Museum of Art’s public API, focusing specifically on the Asian Art. It collects metadata such as object IDs, object names, country, geographic origins, and culture, and organizes this information into a structured dataset for further exploration.

## Rationale Statement 
The purpose of this project is to investigate patterns of representation within The Met’s Asian Art collection. By gathering and analyzing data programmatically, the project aims to provide insights into cultural diversity, geographic distribution, and medium-based categorization within the collection. This work supports broader conversations about digital access and cultural visibility in museum collections.

## Workflow
Libraries Used:
* requests — to make API calls
* pandas — to store, clean, filter, and analyze tabular data
* json — for handling API responses
* matplotlib — for data visualization 

Main Steps in the Code:
* Construct API Query
* Retrieve Object IDs
* Loop Through IDs & Get Full Metadata
* Store Data in Lists or Dictionaries
* Convert to DataFrame
* Export to CSV
* Visualization / Analysis

## Further Uses
* Compare Asian Art with another department (e.g., Islamic Art).
* Integrate multiple museum APIs (e.g., Freer/Sackler, British Museum).
* Expand the dataset by including images or provenance data.
* Conduct comparative cultural analyses across institutions.

## Files List
* Main Jupyter Notebook containing all code, API calls, data cleaning, and analysis.
* met_asian_art.csv — Exported dataset of the Asian Art collection retrieved from The Met API.
* README.md — Project summary, documentation, and usage instructions.

