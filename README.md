## Matplotlib_challenge ##
Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

Final code includes:
 * Clean dataframe (removing duplicate mice that can skew data) 
 * Aggregated statistics df per each drug regimen
 * Bar graph to show the Total Number of Measurements taken on the mice per each drug regimen
 * Pie chart showing the almost equal distribution of mouse gender
 * Box and whiskers plots across top 4 drugs of interest
 * Line graph of Tumor Volumes in 1 random mouse treated with Capomulin
 * Scatterplot of average weight & Tumor volumes in mice treated with Capomulin

Findings: 
 * Ramicane and Capomulin were the most studied drugs, as indicated by the number of measurements taken 
 * Additionally, Ramicane and Capomulin were the most successful drugs to reduce tumor volume throughout timepoints provided
 * There is a distinct positive correlation between weight and tumor volume on Capomulin. To improve success rate of (SCC) drugs, healthy weight must be obtained.


Challenges: 
  * Loop through Tumor Volumes in Last measurements of Tumors and append to empty tumor volume list, I was unclear on the purpose of this method as I would have chosen to use Boolean Masks and save to individual lists per each drug regimen in order to pull data for later graphs 
  * Creating a line graph for 1 random sample of mouse treated with Capomulin
  * Navigating through the differences of charting using pandas vs. pyplot and the advantages of both
