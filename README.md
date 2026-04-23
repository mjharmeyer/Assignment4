# Assignment4
Data Mining Assignment 4: Clustering Analysis

Description:
This project implements a custom k-Means clustering algorithm from scratch and 
compares it against standard off-the-shelf clustering algorithms.

Directory Contents:
- 5243hw4.py       : The main python script.
- TwoDimEasy-1.csv      : Dataset 1
- TwoDimHard-1.csv      : Dataset 2
- winequality-red.csv   : Dataset 3
- README.txt            : This instructions file.
- 5243hw4 Write up.pdf    : The formal analysis write-up.

Dependencies:
Ensure you have the following Python packages installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Interpreting the Output:
- The terminal will print the True SSE, True SSB, Predicted SSE, 
  Predicted SSB, and Cross-Tabulation matrices for each dataset and k-value. 
  It also prints the silhouette scores for the off-the-shelf algorithms.
- The script automatically generates and saves four PNG scatterplots 
  in the current directory. These plots overlay the actual actual true clusters (represented 
  by marker shape) with the assigned k-Means clusters (represented by marker color).
