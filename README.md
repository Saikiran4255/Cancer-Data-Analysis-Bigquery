# Cancer Data Analysis Using GCP/BigQuery
The goal of personalized cancer data analysis is to utilize advanced analytics methods to delve into individual patient profiles, leveraging genetic and variation data. Our objective is to uncover unique patterns in gene expression and variations among various cancer types. This analysis is facilitated through the application of data life cycle techniques. By employing these methods, we aim to gain a deep understanding of the intricacies of cancer biology and ultimately contribute to the advancement of personalized treatment strategies.
## Data Collection
The initial step of the data life cycle is the generation/collection of data. The dataset was obtained from Kaggle's MSK Redefining Cancer Challenge.
The dataset comprises five features With a total of 3321 data points, each entry represents a unique profile.
  - ID: Numerical identifier for each data entry.
  - GENE: Represents molecular genetic information related to cancer.
  - VARIATION: Describes genomic variations associated with cancer.
  - CLASS: Indicates the cancer classes or types.
  - TEXT: Description of type of cancer.
The combination of molecular and clinical data in this dataset makes it valuable for comprehensive cancer research and personalized medicine.
## Data Preprocessing
After collecting the raw data from the Kaggle, we performed the data preprocessing. Techniques to process the data are listed below: 
- Data Cleaning
- Exploratory Data Analysis(EDA)
- Feature Engineering
- Class Imbalance Handling
- Normalization / Scaling
- Simple Imputation
## Storage/Analysis - GCP/BigQuery Queries
GCS is ideal for storing large volumes of structured and unstructured data, making it suitable for diverse data types present in cancer datasets, including genomic and clinical data.
Big Query is well-suited for analytical queries and real-time data analysis, making it an excellent choice for cancer data that requires frequent analysis and exploration.
### Queries
1. Personalized gene expression profile
2. Unique genes in specific cancer class
3. Variations of a specific gene
4. Patients with specific genetic variation
5. Textual Descriptions of specific patients
## Data Visualization
1. Stacked Bar Chart for Variation Types
2. Heat Map for Gene Mutations
3. Word Cloud for Text Data for Each Class
4. Bubble Chart for Gene Expression Vs. Variation
5. Counter Plot for Variation by Cancer Class
## References
- https://www.kaggle.com/c/msk-redefining-cancer-treatment
- https://data.wisc.edu/data-literacy/lifecycle/#:~:text=A%20data%20lifecycle%20illustrates%20how,through%20its%20lifecycle%20of%20usefulness
- https://www.simplilearn.com/tutorials/python-tutorial/data-visualization-in-python
- https://scikit-learn.org/stable/modules/generated/sklearn.impute.SimpleImputer.html
- https://cloud.google.com/bigquery/docs/introduction
- https://console.cloud.google.com/welcome?project=saikiran-adta5240. 



