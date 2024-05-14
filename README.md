# Powerlifting Visualization
Data science project for DSC 106 class at UCSD. It is a group project using data from a powerlifting dataset. My collaborators are Yujin Lee and Aile Banuelos.

<script src="https://d3js.org/d3.v6.min.js"></script>

<div id="my_dataviz"></div>

d3.csv("https://noahdanan.github.io/Powerlifting-Visualization/Powerlifting.csv").then(function(data) {
    // Data processing and visualization code goes here

    // For example, to log the loaded data:
    console.log(data);

    // You can now create the visualization:
    createDonutChart(data);
});

function createDonutChart(data) {
    // Visualization code using the data
}
