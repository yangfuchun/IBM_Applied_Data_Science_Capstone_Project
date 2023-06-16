### Overview
This project aims to predict the success of the Falcon 9 first stage landing, which can ultimately determine the cost of a launch. By analyzing this information, it can be used to aid other companies in bidding against SpaceX for a rocket launch. This is significant because SpaceX is able to offer launches at a much lower cost due to their ability to reuse the first stage.
##### The project is divided into six phases as follows:
1. Data Collection through API
2. Web-Scraping
3. Data Wrangling and Cleaning
4. Exploratory Data Analysis (EDA) and Data Visualization
5. Machine Learning Prediction
6. Dashboards to Show Results
### Description of files
- dataset_part_1: Comprises the query sent to the [SpaceX API](https://api.spacexdata.com/v4/) and the processed data.
- spacex_web_scraped: Web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled [List of Falcon 9 and Falcon Heavy launches](https://en.wikipedia.org/wiki/List_of_Falcon\_9\_and_Falcon_Heavy_launches)
- dataset_part_2: Contains the dataset that has been performed some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models
- dataset_part_3: Contains the dataset that has been performed Exploratory Data Analysis and Feature Engineering
- space_launch_geo: Contains augmented dataset with latitude and longitude added for each site
### List of Python libraries used
`pandas` `matplotlib` `numpy` `seaborn` `sklearn` `folium` `wget` 
### Snapshots
<img width="898" alt="image" src="https://user-images.githubusercontent.com/100629848/230683776-9cdfbe66-9504-48e4-b0b9-62b969c18d5e.png">
<img width="899" alt="image" src="https://user-images.githubusercontent.com/100629848/230683829-fd6b6b33-bfa6-4e3e-be24-17a53b6b11c9.png">
