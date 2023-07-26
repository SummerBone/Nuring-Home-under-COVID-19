READ ME
The CODE folder contains the code for preparing the dataset, the code for modeling, the code for visualization and the datasets. This readme contains three parts accordingly.

1. The code and datasets for preparing the dataset (Merge COVID-19 Nursing Home Data.ipynb, COVID-19_Nursing_Home_Dataset.csv, Provider_Info.csv).
Description: this code is for merging the original datasets to the dataset we used in our experiment. 
Installation: download the code and the input datasets, make sure the code and input datasets are under the same path. 
Execution: run the code on the Jupyter Notebook. 

2. The code and dataset for modeling (ML_modeling.ipynb, select_feature_quantile.csv).
Description: this code is for our modeling. 
Installation: download the code and the input dataset, make sure the code and input dataset are under the same path. 
Execution: run the code on the Jupyter Notebook. 

3. The code for visualization (Project_visualization.html).
Description: This file is for our interactive visualization where there are three dashboards. 
             1.The first dashboard shows the Nursing Homes� rating score that is based on our new rating system, at state level and county level. It also lists each Nursing Home�s information, such as address, ownership, and provider type. 
             2.The second dashboard presents the rating score changes in the choropleth map when adjusting the key features� values.
             3.The last dashboard shows feature comparison between two different Nursing Homes that the user selects.
Installation: Please install FireFox or Chrome, download the file and open the file with FireFox or Chrome.
Execution: 
             1.The first dashboard - �Nursing Home Performance� includes three parts:
               A.State Choropleth Map: 
                 -Hover the mouse on a state to see the tooltip that includes a bar chart of how many Nursing Home in each rating range, and the average rating.  
                 -Click a State to see the County level view in the County Choropleth map.
               B.County Choropleth Map: 
                 -Click a blue dot to see the Nursing Home�s location in google map.  
                 -Hover the mouse on the County to see the address of the Nursing home in the tooltip. 
                 -Click a County to see the County�s average rating score in tooltip. 
                 -Click a County and click the hyperlink shown in the tooltip to open a google search of that Nursing Home.
               C.Nursing Home(NH) Contact List: When you click a county in the County Choropleth Map, the table only shows Nursing Homes in that selected county. 
                 -Apply filter to the dropdown list (Rating, Provider) to see the Nursing Homes� information.

             2.The second dashboard- �Effect of Features�: 
                 -Drag range filter sliders to change features� values and see the average rating score changes at State level and County level. 
                 -Click a State to zoom in the view of the County level in the County choropleth map.

             3.The third dashboard - �Nursing Home Comparison�: 
                 -Click �Reset Filters Button� before select the Nursing Homes of your interest.
                 -Select State/County/Nursing Home name to compare their features.

