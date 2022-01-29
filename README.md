# Bacterial_Data_Visualization

using JavaScript, Plotly and D3.js 

### Overview of Project: Explain the purpose of this analysis.

Using bacterial data collected from volunteers, We have a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. Specifically, volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, our volunteers will be able to identify whether that species is found in their navel.

1. Create a Horizontal Bar Chart
2. Create a Bubble Chart
3. Create a Gauge Chart
4. Customize the Dashboard

### Results:

We'll create a horizontal bar chart to display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu on the webpage. The horizontal bar chart will display the sample_values as the values, the otu_ids as the labels, and the otu_labels as the hover text for the bars on the chart. the result is shown in the below picture. 

![This is an image](https://github.com/samiramghd/Bacterial_Data_Visualization/blob/main/static/images/del1.PNG)

and then we'll create a bubble chart that will display, when an individual’s ID is selected.

![This is an image](https://github.com/samiramghd/Bacterial_Data_Visualization/blob/main/static/images/del2.PNG)

then we'll create a gauge chart that displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu. in the picture below we can see the final results.

![This is an image](https://github.com/samiramghd/Bacterial_Data_Visualization/blob/main/static/images/final.PNG)


### Summary:

 we'll add three Bootstrap to customize the webpage for our dashboard and show in the picture how the plots change by changing ID.

 <img src="https://github.com/samiramghd/Bacterial_Data_Visualization/blob/main/static/images/style.PNG" width=60% height=40%>

 ![This is an image](https://github.com/samiramghd/Bacterial_Data_Visualization/blob/main/static/images/change.PNG)
