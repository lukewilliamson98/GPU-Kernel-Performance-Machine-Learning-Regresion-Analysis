# GPU-Kernel-Performance-Machine-Learning-Regresion-Analysis
In this project, a GPU kernel performance dataset was cleaned, machine learning regression algorithms were run on it, and the algorithms were analyzed.

To view the project in a pleasing format, please open Regression.pdf

If you'd like to run the code yourself, download the R markdown file and run each chunk sequentially. Please note that your results will differ, as a random 10000 instances are chosen each time due to processing constraints.

If your computer's processing power is on the higher end, change 10000 in the line:
df <- df[sample(1:nrow(df), 10000, replace=FALSE,] in the "Cleaned Data Exploration" chunk
to any number greater than 10000 and less than 241600. To run the algorithms on the entire cleaned data set, remove the line completely.
