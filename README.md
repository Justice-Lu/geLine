# geLine

Welcome to geLine. 

The geLine is built from [shiny app](https://shiny.rstudio.com/) in R, while all single cell and gene expression processing is done with python. 


## About geLine 
geLine app is a basic tool that allow you to visualize the gene expression trajectory across the neuronal lineage of the olfactory sensory neurons. 

Y axis : Normalized gene expression. Every gene's expression count is normalized by it's minimum and maximum counts. 
X axis : Contains continuous value of diffusion pseudotime value. This represents how mature is the given cell in the olfactory sensory neurons lineage. 
Color/Hover :  Color and hover value displays the RMSD of how far apart is the query gene compared to the subject gene's trajectory. 


![Campsite chart](www/geLine_screenshot.png)
