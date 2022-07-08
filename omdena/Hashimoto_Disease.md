

<h1 align="center">Modeling Triggers and Symptoms of Hashimoto’s Disease</h1>

<p float="center">
  <img src="https://github.com/wbgreen0405/wbgreen0405/blob/main/img/Hashiona.png" width="500" />
  <img src="https://github.com/wbgreen0405/wbgreen0405/blob/main/img/Hashimoto%20Disease.png" width="500" />
</p>
      
      
<h2 align"left">The Problem</h2>

Hashimoto’s disease is an autoimmune disorder that causes hypothyroidism. Hashimoto’s and other frequent autoimmune diseases are incurable and hard to treat. Hashimoto’s is described with at least 45 medical symptoms, which are hard to detect. Exactly as in the treatment of diabetes, patients have to implement comprehensive lifestyle changes to mitigate the autoimmune response in their body & feel better (i.e. go into remission).  Patients with Hashimoto’s disease may experience persisting symptoms despite normal hormone levels.

Hashiona is the first mobile application dedicated to people with Hashimoto’s disease and/or hypothyroidism. Hashiona´s user base exceeds 10,000 and their approach has been validated by Stanford, Draper University, MIT, and more. 



<h2 align"left">Objective & Motivation</h2> The objective of this project is to find the correlation between symptoms, triggers, and morbidity of Hashimoto’s disease. 
<h2 align"left">Role</h2> Task Leader for exploratory data analysis (EDA). Managed a team of 15 members to analyze and discover the patterns in Hashimoto’s dataset and to find any anomalies in the data. 
<h2 align"left">Data</h2> The total records in the dataset are 21,619, which has been derived after combining the records for all the active profiles currently in the Hashiona app. The data consists of all the important features for each profile in a single row.
<h2 align"left">Models</h2> Correlation analysis was used to check if there is any possible relationship and pattern among the features like triggers and symptoms. K-means clustering analysis was to see if certain segments could emerge from the dataset of users - segments based on similarities between the triggers and symptoms that the users in that particular group experienced. This would help Hashiona identify some dominant sects between the app users and health solutions could be tailored to the different requirements of these groups. 



<h2 align"left">The Project Outcomes </h2>

<h3 align"left">The data</h3>

The first step was to apply Exploratory Data Analysis (EDA) to discover the hidden patterns and anomalies in the entire dataset. Next, the team divided the data into subsets for analysis:

* Profiles who suffer from Hashimoto
* Profiles who suffer from Thyroidism
* Profiles with Thyroidism symptoms
* Profiles having any triggers, mind or body symptoms
 

Next, top triggers and symptoms were identified. Examples include:

* Overtraining
* Cold
* Caffeine consumption
* Relationship with family
* Heat
 

The team identified user profiles who either suffer from Hashimoto’s or Thyroidism and have recorded their hypothyroidism symptoms. Among these profiles, correlation analysis was performed for body symptoms, mind symptoms, and thyroid symptoms with triggers.

Next, clustering analysis and modeling have been applied to show the most occurring triggers for various clusters. After grouping data by cluster, the average population in the cluster affected by a trigger or symptom was calculated. 

<h2 align"left">The Models and Dashboard</h2>

To visualize the models and outcome the team choose Streamlit. Streamlit allows users to quickly build highly interactive web applications and is generally used for deploying Machine learning models.

For the demo, static charts have been implemented.


<p float="center">
  <img src="https://github.com/wbgreen0405/wbgreen0405/blob/main/img/Hashimoto%20Dashboard.png" width="500" />
</p>

 
