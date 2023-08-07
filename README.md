# belly-button-challenge-Belly Button Biodiversity Dashboard
This project is an interactive dashboard that allows users to explore the Belly Button Biodiversity dataset. The dataset catalogs the microbes that colonize human navels, and it reveals that a small handful of microbial species (operational taxonomic units, or OTUs) are present in more than 70% of people, while the rest are relatively rare.

The dashboard provides the following features:

**Horizontal Bar Chart**: This chart displays the top 10 OTUs found in an individual's navel. Users can select an individual from a dropdown menu, and the chart will update accordingly. The chart uses sample_values as the values for the bars, otu_ids as the labels, and otu_labels as the hover text.

**Bubble Chart**: This chart displays each sample from the dataset. It uses otu_ids for the x-axis, sample_values for the y-axis, sample_values for the marker size, otu_ids for the marker colors, and otu_labels for the text values.

**Sample Metadata Display**: The dashboard also displays the demographic information of the selected individual. It shows each key-value pair from the metadata JSON object.

## Technologies Used

The following technologies and libraries were used to build the interactive dashboard:

D3.js: Used for data visualization and creating the horizontal bar chart and bubble chart.

HTML: Used for structuring the webpage layout.

CSS: Used for styling the dashboard elements and charts.

JavaScript: Used to fetch and manipulate the data, handle user interactions, and update the charts.
