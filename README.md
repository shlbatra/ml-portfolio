# ML / Data Engineer

#### Technical Skills: 
##### Cloud: 
- GCP
- AWS
##### Database Programming: 
- Relational Databases (IBM DB2, SQL Server, Teradata),
- BigQuery,
- RedShift
#### Programming Language: 
- Python
- Bash
- SQL
#### Data Pipeline Tools: , 
- DBT
- DataProc(Spark), 
- DataFlow(Beam)
- Informatica 9.1
#### ML Packages:
- scikit-learn
- numpy
- pandas
- ray
- sklearn
- tensorflow
- pytorch
- ray / xgboost-ray
- auto ml
- comet
- mlflow
##### ML Deployment Tools: 
- SageMaker
- Vertex
- LLMs (Vertex AI Reasoning Agent)
- Langchain
- TFX
- Kubeflow 
#### Dev Ops 
- Airflow
- Git (CI/CD)
- JupyterLab
- VS Code,
- Docker,
- Kubernetes 
##### Certifications: 
- Data Engineering Nanodegree (Udacity),
- Deep Learning Specialization (Coursera),
- Natural Language Processing Specialization (Coursera),
- Splunk Fundamentals & Advanced Searching (Splunk),
- GIAC Security Essentials (GSEC)


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



**Data Science Consultant @ Shawhin Talebi Ventures LLC (_December 2020 - Present_)**
- Conducted data collection, processing, and analysis for novel study evaluating the impact of over 300 biometrics variables on human performance in hyper-realistic, live-fire training scenarios
- Applied unsupervised deep learning approaches to longitudinal ICU data to discover novel sepsis sub-phenotypes

## Projects
### Data-Driven EEG Band Discovery with Decision Trees
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Decoding Physical and Cognitive Impacts of Particulate Matter Concentrations at Ultra-Fine Scales
[Publication](https://www.mdpi.com/1424-8220/22/11/4240)

Used **Matlab** to train over 100 machine learning models which estimated particulate matter concentrations based on a suite of over 300 biometric variables. We found biometric variables can be used to accurately estimate particulate matter concentrations at ultra-fine spatial scales with high fidelity (r2 = 0.91) and that smaller particles are better estimated than larger ones. Inferring environmental conditions solely from biometric measurements allows us to disentangle key interactions between the environment and the body.

![Bike Study](/assets/img/bike_study.jpeg)

## Talks & Lectures
- Causality: The new science of an old question - GSP Seminar, Fall 2021


- [Data Science YouTube](https://www.youtube.com/channel/UCa9gErQ9AE5jT2DZLjXBIdA)

## Publications
1. Talebi S., Lary D.J., Wijeratne L. OH., and Lary, T. Modeling Autonomic Pupillary Responses from External Stimuli Using Machine Learning (2019). DOI: 10.26717/BJSTR.2019.20.003446


- [Data Science Blog](https://medium.com/@shawhin)
