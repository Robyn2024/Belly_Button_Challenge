# Belly_Button_Challenge

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.  The dataset reveals that a small handful of microbial species were present in more than 70% of people, while the rest were relatively rare.

## Instructions

Complete the following steps:

### 1. Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

### 2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

- Use sample_values as the values for the bar chart.

- Use otu_ids as the labels for the bar chart.

- Use otu_labels as the hovertext for the chart.

![image](https://github.com/Robyn2024/Belly_Button_Challenge/assets/138690945/19bec09c-ae2d-420f-82b1-a84a141a28b4)


### 3. Create a bubble chart that displays each sample.

- Use otu_ids for the x values.

- Use sample_values for the y values.

- Use sample_values for the marker size.

- Use otu_ids for the marker colors.

- Use otu_labels for the text values.

![image](https://github.com/Robyn2024/Belly_Button_Challenge/assets/138690945/29231d88-5623-4445-a1fd-cad6392f7f07)


### 4. Display the sample metadata, i.e., an individual's demographic information.

### 5. Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://github.com/Robyn2024/Belly_Button_Challenge/assets/138690945/18c91685-fe30-45c4-932b-72a8c644dafa)


### 6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

![image](https://github.com/Robyn2024/Belly_Button_Challenge/assets/138690945/3422a9ef-86b5-4daf-b277-4497e47ec723)


### 7. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

## Advanced Challenge Assignment (Optional with no extra points earning)

The following task is advanced and therefore optional.

- Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

- You will need to modify the example gauge code to account for values ranging from 0 through 9.

- Update the chart whenever a new sample is selected.

![image](https://github.com/Robyn2024/Belly_Button_Challenge/assets/138690945/be0e41d6-32d3-4b05-9d55-6ccadbeaef44)


#### Hints
- Use console.log inside of your JavaScript code to see what your data looks like at each step.

- Refer to the Plotly.js documentationLinks to an external site. when building the plots.

## References

Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.
