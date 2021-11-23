# Median-House-Value-Prediction
Group project for UCSD ECE-143

## Installation

Some main third part packages used
- pandas
- sklearn
- seaborn
- folium
- geopy

Clone the repository
```
git clone https://github.com/udayvarikuti/Median-House-Value-Prediction.git
```

Setup the environment using the environment.yaml file
```
conda env create -f environment.yaml
```

## Visualization

Visualizations from the EDA can be seen in the [GenerateVisualizations.ipynb](https://github.com/udayvarikuti/Median-House-Value-Prediction/blob/main/GenerateVisualizations.ipynb) notebook. Folium maps can be generated by executing the code in the 'Map Visualization' section.

The Visualization of maps uses the files
<li>exampleMap.py</li>
<li>severityMaps.py</li>
<li>bedroomCountMaps.py</li>
<li>eda.py</li>
<br>
The map_tool.py generates the map. The files exampleMap.py, bedroomCountMaps.py and severityMaps.py call the map_tool.py file internally to generate the folium map.
<br>

Requires outside libraries:
<ul>
    <li>General</li>
    <ul>
        <li>Pandas</li>
        <li>Numpy</li>
    </ul>
    <li>Visualizations</li>
        <ul>
            <li>Folium</li>
            <li>Geopy</li>
            <li>pickle</li>
            <li>Seaborn</li>
            <li>sklearn</li>
        </ul>
    <li>Model</li>
    <ul>
        <li>matplotlib</li>
        <li>scipy</li>
        <li>sklearn</li>
        <li>pickle</li>
        <li>joblib</li>
        <li>sklearn</li>
        <li>statsmodels</li>
    </ul>
    
</ul>

Must have the following data saved in the current directory
<ul>
    <li>"./data/zillowHousing/clean_data_2016.csv"</li>
        <ul>
            <li>Zillow data used for most map visualizations</li>
        </ul>
    <li>"./datastories_table.csv"</li>
        <ul>
            <li>Contains model infered data by zipcode</li>
        </ul>
    <li>"./zipcode_mapping.pickle"</li>
        <ul>
            <li>Used to map zillow internal fake zipcodes to real life zipcodes. Genreated via geopy</li>
        </ul>
</ul>
