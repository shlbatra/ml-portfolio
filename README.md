# ML / Data Engineer

## Education
- Machine Learning Engineer | FourthBrain.AI (_Sep 2021_)								       		
- M.S., Data Science	| The University of Texas at Austin (_May 2015_)	 			        		
- B.Tech., Electronics & Communication | GGS Indraprastha University (_June 2010_)

## Work Experience
**Data / Machine Learning Engineer @ Shopify (_July 2022 - Present_)**
-	Migrated ML pipelines (XGBoost) from internally supported ML platform (Merlin) to Vertex (GCP) using TFX deployed on vertex pipelines, the training and inference pipelines were triggered via airflow. 
-	Experimented with KubeFlow to build ML pipelines supporting PyTorch model deployment, training and inference.
-	Built custom components within TFX to support end to end ml pipeline including retraining and enable calibration of predicted probabilities for trained models.
-	Built an LLM system using gpt4o to identify shop product and recommend first action based on ticket metadata and shop context.
-	Built and improved fraud detection models for no intent to ship and card cashing use cases by developing better features related to orders, billing, and admin navigation, with hit rate (precision) improvement of 10bps.
-	Built streaming features for real time training and inference for card cashing fraud detection using apache beam on dataflow.
-	Contributed to python package for model training, calibration, inference, and monitoring using ray on kubernetes and model management on comet, the package was built on top of internal ML platform called Merlin. The package was used to deploy fraud related models to production trained using xgboost-ray package to terminate fraud shops.  

**Sr Data Scientist @ Dell (_May 2018 - July 2022_)**
- Manage the AI platform & strategy, stakeholder engagement and technical work across 4 data scientists & data engineers.
- Built AI systems & Data Pipelines 
  - Setting up the Analytics Data Lake (Tools used - S3, Spark, PostGres Database, Airflow, Containers, Kubernetes) to incorporate data from multiple internal & cloud-based sources within Security Organization using APIs.
  - Created infection risk KPI across countries and provided time to return using covid public datasets (RMSE 10 days) using LSTM model. The model was shared across Security Executive Council and 500 companies across the globe.
  - Classical imbalanced fraud risk scoring model to detect fraudulent emails, using PySpark for data ingestion, and random forest for model training, with deployment on API end point. (Prec 30-50%, Rec 95%+, $1M + saved). 
  - Identified characteristics of employees susceptible to phishing based on phishing simulations data (Prec 83% & Rec 89%). Logistic regression model used.
  - Applied Anomaly Detection techniques using an ensemble of Local Outlier Factor, Isolation Forest & AutoEncoder to identify anomalous traffic using Producer Consumer Ratio, Session & Volume of traffic across network.

**Data Scientist @ Dell (_July 2015 - Feb 2018_)**
-	Built Metrics & KPI from ground up for Servers Business Unit on weekly operational performance (100+ attendees).
- Applied ML models in sales domain
  - Customer market segmentation using K Prototype based on company attributes, and recency, frequency & monetary attributes, to label customers into different market segments for sales targeting. 
  -	Commodity data clustering to identify trends of most common vs least configurations using K Medoids with Jaccard similarity.
  -	Clustering using KNN & Quantile Regression to identify customer software spend across different market segments based on company, and recency, frequency & monetary attributes for all customers.
  -	Lead generation cross-sell model to help sales to identify better candidates for cold calling.

**Software Developer @ AON Hewitt (_Nov 2013 - May 2014_)**
-	Utilized informatica to build data pipelines & hadoop for data storage for ingestion of employee workday data.

**Software Developer @ Computer Sciences Corporation (_Nov 2013 - May 2014_)**
-	Built ETL Data pipelines using SAS & Informatica to pull data feeds to create data warehouse & data marts in SQL & IBM DB2 using Fact/Dims. 

## Projects
### [Wake Word Detector](https://github.com/shlbatra/TriggerWakeWordDetection)
-	Built an open source wake word detector using Mozilla Common Voice Dataset & Google Speech to Text (85% + acc). 
-	Created audio generation features using Log MelSpectogram, modelling using CNN and implemented server & client-side inference using AWS Beanstalk.

### [Identifying Valued Repeat Buyers using Purchase History](https://github.com/shlbatra/Acquire-Value-Shoppers-Challenge)
- Worked with transaction data of nearly 350 million rows and investigated post-incentive behavior for an acquisition campaign to predict which customers are most likely to repeat purchase
- Implemented RFM technique for feature extraction and logistic regression for classifying repeat buyers


## Technical Skills: 
##### Cloud: GCP / AWS
##### Database Programming:  Relational Databases (IBM DB2, SQL Server, Teradata), BigQuery, RedShift
##### Programming Language: Python, Bash, SQL
##### Data Pipeline Tools: DBT, DataProc(Spark), DataFlow(Beam), Informatica 9.1
##### ML Packages: scikit-learn, numpy, pandas, ray, sklearn, tensorflow, pytorch, ray / xgboost-ray, auto ml, langchain
##### ML Deployment Tools: SageMaker, Vertex, TFX, Kubeflow, Comet, MLFlow
##### Dev Ops Tools: Airflow, Github (CI/CD), Docker, Kubernetes 
##### Certifications: 
- [Data Engineering Nanodegree](https://github.com/shlbatra/Udacity_DataEngineering_Projects) (Udacity)
- [Deep Learning Specialization](https://github.com/shlbatra/Coursera_DeepLearning) (Coursera)
- [Natural Language Processing Specialization](https://github.com/shlbatra/Coursera_NLPSpecialization) (Coursera)
- Splunk Fundamentals & Advanced Searching (Splunk)
- GIAC Security Essentials (GSEC)
