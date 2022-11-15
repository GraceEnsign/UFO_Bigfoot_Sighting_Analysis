## UFO and Bigfoot Sighting Analysis

![Map](https://user-images.githubusercontent.com/105288631/201795512-9fb99167-65f9-49ef-9d51-085863bd8204.jpeg)

[Link to Interactive Tableau Dashboard](https://public.tableau.com/views/UFO_Bigfoot_Sighting_Map/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)

### Project Description
Geographic comparison of UFO and bigfoot sighting reports in the United States. Data of bigfoot sighting reports and locations were aquired and merged to form one cohesive dataframe. UFO data was geocoded to obtain the longitude and latitude of each sighting location. Cleaned reports were then connected to a Tableau dashboard, in which the user is able to see on a map of the United States where each sighting was reported. Map is interactive, and the user is able to select individual map markers to read the report and date of the sighting. Analysis created to aid in the question: Where, in the United States, are UFOs and bigfoot mostly spotted? Do UFOs make more appearances in the northeast? Does bigfoot prefer warmer climates, like Texas or Florida? Let's find out!

### Instructions to Run Project/Install Virtual Environment
<ol><li>Clone the repository by typing the following: <blockquote> git clone https://github.com/GraceEnsign/UFO_Bigfoot_Sighting_Analysis.git</blockquote> </li>
<li>Run the following to install virtual environment (if not already installed): <blockquote> pip install virtualenv</blockquote> </li>
<li>Create virtual environment by typing the following: <blockquote> virtualenv environment</blockquote></li>
<li>To enter the virtual environment: <blockquote> source environment/bin/activate </blockquote></li>
<li>Open the Analysis.ipynb once in the main directory with Jupyter Notebook, or open with editor.</li></ol>

### Relevant Packages
Python 3.10.4 <br>
Jupyter Notebook <br>
Pandas 1.4.2 <br>
NumPy 1.23.3 <br>
Geocoder 1.38.1 <br>

### Data Description
Three dataframes were initially acquired. Bigfoot sighting locations dataframe was a csv file and the reports dataframe was a json file. UFO dataframe was a json file. Due to the size of each dataframe, a SQL query was created to obtain a URL of each dataframe, and then read in as a csv. 

### Dataframe Sources
[UFO Data](https://data.world/timothyrenner/ufo-sightings)
[Both Bigfoot Datframes](https://data.world/timothyrenner/bfro-sightings-data)

### Features Included 
1. Loading data- Read in three data files (Cells 2-4)
2. Clean and operate the data while combining them- Performed Pandas merge on the two bigfoot dataframes (Cell 6) after cleaning column names to assist with the merge (Cell 5). Used Pandas and NumPy to split, rename, reformat, drop, and filter columns (Cells 7-22, 27). Used geocoding to acquire longitude and latitude for UFO dataframe (Cells 23-24). Exported cleaned dataframes into Excel worksheets (Cell 28).
3. Visualize/Present your data- Created interactive Tableau dashboard, which can be viewed [here](https://public.tableau.com/views/UFO_Bigfoot_Sighting_Map/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link).
4. Best practices- Utilized a virtual environment and included instructions in README. 
5. Interpretation of your data- Added markdown cells in Jupyter Notebook (found between cells through notebook). Further analysis found in section below.

### Analysis
