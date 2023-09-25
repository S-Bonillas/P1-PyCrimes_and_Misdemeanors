# P1-PyCrimes_and_Misdemeanors

**Team #2 Members:**
- Steve Bonillas
- Laura Hickman
- Kento Nakajima
- Michelle Anne Verger
- Christian Cornoa

**Project Abstract:**
- Tracking the rate of non-violent crimes in the US from 2010 to 2020.
- Sources are the FBI Crime Data Explorer and the US Census Bureau.
- Data Analysis is analyzed in both total numbers and per capita.
- Visualizations are in Line, Bar, and Scatter Graphs.
- HvPlot maps are also provided.

.gitignore hides the utilized API keys.

Final project files are housed within the PyCrimes_Final folder.
Project members workbooks are saved in separate folders.

**PyCrimes_Final Contains:**
- PyCrimes_Final.ipynb (Jupyter Notebook file of the requested analysis and visualizations)
- PyCrimes_Presentation.pptx (PowerPoint presentation for the project)
- PyCrimes_Presentation.pdf (PDF handout for the class)
- Resources Folder (The notebook references the Resources folder, output files are also housed there)

**PyCrimes_Final > Resources contains:**
- census_data.csv (Cleaned data from the US Census Bureau)
- combined_cleaned.csv (FBI data cleaned and extrapolated, exported from a dataframe)
- FBI_Data_Raw_2010_2020.json (Raw FBI API data showing arrest data from 2010 to 2020, saved to a JSON)
- fbi-crime-data-normalized.csv (Crime data adjusted for population)
- gz_2010_us040_00_500k.json (GeoJson data for map visualizations. Source: https://eric.clst.org/tech/usgeojson/)
- law_enforcement_employees.json (Raw FBI API data showing # of law enforcement employees, saved to a JSON, saved from a dataframe)
- LE_Data_Raw_2010_2020.json (Raw FBI API data showing # of law enforcement employees, saved to a JSON, saved from an API pull)
- state_avg.csv (Average total arrests per state, calculated in a dataframe and saved to a CSV)
- state_id.csv (Key for translating state abbreviations to full state names via Python)

