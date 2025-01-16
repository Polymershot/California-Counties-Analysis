# Analyzing California counties using the Smart Location Database (EPA)
The main objective of this college project was to pick a large dataset suitable for unsupervised learning. The main dataset is called the "Smart Location Database" from the Environmental Protection Agency. It consists of variables like jobs per industry, traffics stats, and other environmental factors on the county/census block groups level. My main objective was to do clustering on this data to see if there were any insights when it comes to classifying California regions (Southern, Northern, Central, Bay Area) in terms of their Census Block Groups. You can think of Census Block Groups as smaller "ZIP" code areas. For more information, please view the report file in the "Report" folder.

## Remarks
1. The code is quite messy and unoptimized. If I were to improve the code, I would look into better ways to store the data. I heard Parquet is something I should look into. I don't think using SQL to clean the data is quite possible for me because it would be quite complex in my opinion. Creating more subfolders to store intermediate results instead of rerunning the code would be much better also.
2. The main objective I had didn't have great results when it came to clustering. I thought there would be certain "hidden" variables that would show a pattern between the California regions for the Census Block Groups. Nevertheless, I'm pretty surprised that such a dataset exists. I hope they release an updated version soon.

### Example Pictures
<p align="center">
  <img src="https://github.com/user-attachments/assets/eca7ba92-6b58-4409-8977-de62e661b812" />
</p>
<p align="center">
Clustering variables (after feature selection) with t-SNE (nonlinear clustering method)
</p>

