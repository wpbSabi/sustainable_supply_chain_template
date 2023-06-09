# Sustainable Supply Chain Model 
To read more about this sustainable supply chain template with geospatial calculations in python, see the supporting article on 
Towards Data Science for more background information.
https://medium.com/towards-data-science/a-sustainable-supply-chain-template-with-geospatial-calculations-in-python-f99a20a43df4

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

Three Distribution Centers (DCs) versus one DC reduced the transportation emissions by more than 50% compared. But the total emissions increased by 40% due to the additional DCs.

Under certain conditions, more DCs and shorter shipping distances can lead to less greenhouse gas emissions. But this limited example demonstrates that shorter final-shipping destinations may not always be indicative of a supply chain network with a lower carbon footprint.

In order to design a sustainable supply chain, the considerations of both transportation and facility impacts should be considered, along with other factors.

## Geospatial Illustrations

3 DCs
![3 DCs](https://github.com/wpbSabi/sustainable_supply_chain_template/blob/main/images/folium_ThreeDCs.png)

Seattle DC
![Seattle DC](https://github.com/wpbSabi/sustainable_supply_chain_template/blob/main/images/folium_Seattle.png)

Memphis DC
![Memphis DC](https://github.com/wpbSabi/sustainable_supply_chain_template/blob/main/images/folium_Memphis.png)

St. Louis DC
![St. Louis DC](https://github.com/wpbSabi/sustainable_supply_chain_template/blob/main/images/folium_StLouis.png)