# Powerlifting Visualization
Data science project for DSC 106 class at UCSD. It is a group project using data from a powerlifting dataset. My collaborators are Yujin Lee and Aile Banuelos.

<script src="https://d3js.org/d3.v6.min.js">
    d3.csv("https://noahdanan.github.io/Powerlifting-Visualization/powerlifting.csv")
  .then(function(data) {
    // This logs the data to the console
    console.log(data);

    // You can proceed to create the visualization here
    createVisualization(data);
  })
  .catch(function(error) {
    // Log any error that occurs during the data loading
    console.error('Error loading the CSV file: ', error);
  });

function createVisualization(data) {
  // Visualization creation code goes here
  // Example: console.log the first row to check data
  console.log("First entry:", data[0]);
}
</script>

<div id="my_dataviz">
    
</div>
