# AA1_510_Grp_8
LA Crime Pattern Analysis
This project analyzes crime incident data from Los Angeles to uncover spatial and demographic patterns using clustering techniques. It aims to help law enforcement and policymakers identify high-crime zones, vulnerable demographics, and time-based trends to improve safety and resource planning.

Project Goals
Identify crime hotspots using clustering (e.g., MiniBatch KMeans, Gaussian Mixture, Birch)

Analyze crime by age, gender, location, and time

Support law enforcement planning and public safety awareness

Provide insights on crime severity and demographic impact

Dataset
Source: Public LA crime dataset

Records used: ~250,000

Key features:

Part 1-2, LAT, LON

Victim Age, Victim Sex

Time features: hour, time_bin

Location: Zip_Code, Area Name

Methods Used
Preprocessing: Missing value handling, encoding categorical variables, removing outliers

Scaling: StandardScaler used for normalization

Clustering Algorithms:

MiniBatch KMeans

Gaussian Mixture Model (GMM)

Birch

Model Evaluation:

Silhouette Score

Visual inspection using cluster plots

Insights
Crime clusters often correlate with specific areas and times of day

Young adults and males are frequently involved in high-density crime zones

Using lat/lon gives better clustering performance than broad categories like area names

Business Value
Helps law enforcement identify priority areas for patrolling

Supports policy design to protect vulnerable groups

Informs the public about crime-prone zones and times


Technologies
Python (Numpy,Pandas, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebooks
