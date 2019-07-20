
# Coursework_Summary
The summary, description and document navigation of course work

Last update:2019.7.20
## You Hu
### Msc. Computer Science (Joint with UvA) at Vrije University Amsterdam
### Track Big Data Engineering
## Course list
### Large Scale Data Engineering
#### Project assignment 2
Bitcoin criminality analysis                                   
* Handled bitcoin transaction records through different approaches (Spark, Web APIs)
* Trained random forest model as criminality classifier
* Visualized transaction networks, filtered discriminable structures
* Score: 5.7 (6.7 for whole course)
* Contribution (group of 3): most of coding work and as team leader 
* Report:[LSDE11-BitcoinCriminality.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/LSDE11-BitcoinCriminality.pdf "LSDE11-BitcoinCriminality.pdf")
### Software Asset Management
#### Literature  study
Manual software estimation
* Read book and summarized the ideas, and made  presentation
* Score: 8 ( 8 for whole  course)
* Contribution (group of 3): part of sub topic of report
* Report:  [SAM_paper_7.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/SAM_paper_7.pdf "SAM_paper_7.pdf")
###  Programming Large-scale Parallel Systems
Exam only (Score: 6.5) 
### Distributed Systems
#### Practical assignment
Design and Implementation of a MapReduce Framework
* Implemented Master/worker architecture with scalability and fault tolerance
* Implemented priority queue for scheduling, using mutex for concurrency control, RPC for communicating
* Score:3600/6000 (10 for whole course)
* Contribution (group of 4): implenmented part of components
* Github Repo:[https://github.com/azimafroozeh/Distributed_Systems](https://github.com/azimafroozeh/Distributed_Systems)
* Report:[VU_Distributed_System_Lab_Report.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/VU_Distributed_System_Lab_Report.pdf "VU_Distributed_System_Lab_Report.pdf")
### Web Data Processing Systems
#### Practical assignment
Building a Knowledge Extraction Engine
* Established pipeline for entity linking (Spark, Elastic Search) from web pages, including NLP process, candidate entity ranking and disambiguation
* Extended pipeline for relation extraction based on hand written patterns
* Score: 9 (8 for whole course)
* Contribution (group of 4): built up the main pipeline and implemented most of functions
* Github Repo: [https://github.com/azimafroozeh/WDPS](https://github.com/azimafroozeh/WDPS)
* Report: [VU_Web_Data_Processing_System_Lab_Report.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/VU_Web_Data_Processing_System_Lab_Report.pdf "VU_Web_Data_Processing_System_Lab_Report.pdf")
### History of digital cultures
#### Final report
History of process algebra
* Read about the general development of software engineering in the second half of the last century
* Interviewed with three Dutch computer scientist and narrated the stories into formal historical text
* Performed bibliometrics to interpret the history according to their publication, citation and other data
* Score: 8.5 (8.5 for whole course)
* Contribution (group of 4): mainly worked on bibliometrics part and interviewed one Prof.
* Report: unable to show due to the potential privacy issue
### Experimental Design and Data Analysis
Many homeworks, I had bad feeling about this course. It proves that math is broing for me.

So, no detial.

8.0 in the end, thanks to Azim and Saliha

Contribution is few.
### Information Visualization
#### Practical assignment
GENSEQ: A Personal Sequence Flow Generator
* Implemented a HTML based generator of customized picture flow by utilizing D3
* Designed sequence ordering function by multiplication of attribute matrix
* Score: 8 (7.5 for whole course)
* Contribution (group of 4): implemented one of two core components and ordering function
* Github Repo: Private Repo created by course supervisor
* Report: [IV_team_12.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/IV_team_12.pdf "IV_team_12.pdf")
### Data Mining Techniques
#### Assignment1 Advanced
Predictors of Mental Health
* Performed feature engineering on streaming/time series data
* Applied multiple models ( RandomForestRegression, LSTM and fbprophet) 
* Tuned paramenters for each model, and achieved 20% less error compared to benchmark
* Score: 8+1 bonus(for choosing advanced variant)
* Report: [DMT_Assigment1_Advanced_Group53.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/DMT_Assigment1_Advanced_Group53.pdf "DMT_Assigment1_Advanced_Group53.pdf")
#### Assignment2
 [Expedia Ranking (Kaggle) Competition](https://www.kaggle.com/c/vu-dmt-2assignment/overview)
* Performed feature engineering by normalization, imputation and hot spot detection
* Built up model by XGBoost with NDCG as objective
* Tuned parameter settings, and achieved [Rank 27/151]( https://www.kaggle.com/c/vu-dmt-2assignment/leaderboard)
* Score: 8.5 (9.3 on competition ranking)
* Report: [DMT_Assignment2_Group53.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/DMT_Assignment2_Group53.pdf "DMT_Assignment2_Group53.pdf")

Contribution (group of 3): worked on part of feature engineering and established most of models 

Github Repo: [https://github.com/AdolphusEnvy/data_mining_course](https://github.com/AdolphusEnvy/data_mining_course)

Score for whole course: 8.5
### Web Service and Cloud-based Systems
#### Service Oriented Architecture
Compare top-down and button-up approaches of architecture
* Implemented URL-shortener by SOAP (JAVA) and RESTful (Flask-Python) architectures
* Score: 6.5
* Contribution: implemented RESTful approach
* Reports
	* SOAP: [WSCS_Report_Assignment1_1.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/WSCS_Report_Assignment1_1.pdf "WSCS_Report_Assignment1_1.pdf")
	* RESTful: [WSCS_Report_Assignment1_2.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/WSCS_Report_Assignment1_2.pdf "WSCS_Report_Assignment1_2.pdf")
#### Distributied systems
Learning virtual resources management
* Managed virtual machines in OpenNebula and deployed URL-shortener on it
* Bonus: established 3 nodes Hadoop cluster and performed PageRank testing on Spark
* Score: 8
* Contribution: worked on building up Hadoop cluster
* Reports
	* OpenNebula: [WSCS_Report_VM_Contextualization.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/WSCS_Report_VM_Contextualization.pdf "WSCS_Report_VM_Contextualization.pdf")
	* Spark for PageRank: [WSCS_Report_spark_pagerank.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/WSCS_Report_spark_pagerank.pdf "WSCS_Report_spark_pagerank.pdf")
#### Virtualization using containers(Docker)
Learning virtualization on light weight and orchestration of containers
* Deployed URL-shortner on single container and tested communication between containers
* Deployed URL-shortner on multi nodes organized by Kubernetes
* Score: 7.5
* Contribution: worked on kubernetes system
* Reports:
	* Docker container: [WSCS_Report_ Container Virtualization.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/WSCS_Report_%20Container%20Virtualization.pdf "WSCS_Report_ Container Virtualization.pdf")
	* Kubernetes: [WSCS_Report on kubernetes experiment.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/WSCS_Report%20on%20kubernetes%20experiment.pdf "WSCS_Report on kubernetes experiment.pdf")
#### Literature study on cloud systems
Disaster recovery on cloud infrastructure
* Read about peer reviewed papers and technical documents of AWS and Alibaba Cloud
* Concluded the main approach for disaster recovery on both traditional and cloud systems
* Compared AWS and Alibaba Cloud to analyze the trade off between two disaster recovery architectures
* Score: 7
* Contribution: worked together with another group member on reading and writing

Github Repo: [https://github.com/AdolphusEnvy/web-service-and-cloud-system](https://github.com/AdolphusEnvy/web-service-and-cloud-system)

Score for whole course: 7.5
### Machine Learning for the Quantified Self
#### Assignment 3
Activity recognition according to data collected by wearable devices
* Performed feature engineering on time domain, reduced 1000 visual concept features to a reasonable level
* Used randomforest model for recognition
* Score:8.7 ( 7 for whole course)
* Contribution (group of 3): part of feature engineering and modeling
* Github Repo: [https://github.com/AdolphusEnvy/ML4QS_2019](https://github.com/AdolphusEnvy/ML4QS_2019)
* Report: [ML4QS_Assignment3_group100.pdf](https://github.com/AdolphusEnvy/coursework_summary/blob/master/ML4QS_Assignment3_group100.pdf "ML4QS_Assignment3_group100.pdf")
