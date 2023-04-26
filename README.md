# Sustainable Supply Chain Model 
To read more about this sustainable supply chain template with geospatial calculations in python, see the supporting article on ![Towards Data Science](https://medium.com/towards-data-science/a-sustainable-supply-chain-template-with-geospatial-calculations-in-python-f99a20a43df4) for more background information.
(Link coming soon)

## To Run
The python notebook `sustainable_supply_chain_template.ipynb` can be run in a jupyter notebook.  
Data is located in the data folder.

This notebook serves as a template with sample data, to demonstrate that both transportation and facility greenhouse gas emissions should be included in a supply chain carbon evaluation.

## Scenario example
For example, here are the results of four scenarios and the accompanying maps

| Scenario     | Transportation Emissions | Transportation and DC Emissions Total |
|--------------|--------------------------|---------------------------------------|
| 3 DCs        | 11 kg CO2e               | 779 kg CO2e                           |
| Seattle DC   | 51 kg CO2e               | 494 kg CO2e                           |
| Memphis DC   | 23 kg CO2e               | 466 kg CO2e                           |
| St. Louis DC | 24 kg CO2e               | 467 kg CO2e                           |


3 DCs
![3 DCs](https://github.com/wpbSabi/sustainable_supply_chain_template/blob/main/images/folium_ThreeDCs.png)

Seattle DC
![Seattle DC](https://github.com/wpbSabi/sustainable_supply_chain_template/blob/main/images/folium_Seattle.png)

Memphis DC
![Memphis DC](https://github.com/wpbSabi/sustainable_supply_chain_template/blob/main/images/folium_Memphis.png)

St. Louis DC
![St. Louis DC](https://github.com/wpbSabi/sustainable_supply_chain_template/blob/main/images/folium_StLouis.png)