**Exploratory Data Analysis in Mental Disorder Classification** 

**About the dataset –**

The dataset is a collection of 120 psychology patients with 17 essential symptoms to diagnose Mania Bipolar Disorder Depressive Bipolar Disorder, Major Depressive Disorder, and Normal Individuals. The behavioural symptoms are considered the levels of patients Sadness, Exhaustiveness, Euphoric, Sleep disorder, Mood swings, Suicidal thoughts, Anorexia, Anxiety, Try-explaining, Nervous breakdown, Ignore & Move-on, Admitting mistakes, Overthinking, Aggressive response, Optimism, Sexual activity, and Concentration in a Comma Separated Value (CSV) format. The Normal category refer to the individuals using therapy time for specialized counselling, personal development, and life skill enrichments. While such individuals may also have minor mental problems, they differ from those suffering from Major Depressive Disorder and Bipolar Disorder.
The initial plan for data exploration – 
•	Examine dataset distribution of different mental disorders.
•	Perform data preprocessing and make required changes.
•	Perform data Visualization using Seaborn and Matplotlib
•	Draw inferences based on the visualizations created and use those inferences in the future.

**Actions taken for data cleaning and feature engineering –** 

•	Check for NULL values
•	Drop useless column data
•	Change range values (1-10) to single value
•	Correct spelling errors
•	Plot using subplots and countplot

**Key Findings and Insights, which synthesizes the results of Exploratory Data Analysis in an insightful and actionable manner –** 

•	People who are Never Sad and Sometimes Euphoric tend to exhibit Bipolar Type 2
•	People who are usually exhausted are depressed, those who are never exhausted are Bipolar Type 1, and those who are sometimes exhausted are Normal
•	People who are lacking sleep are most often depressed 
•	We also see that people with low concentration levels are Bipolar Type 2 and the people with high concentration levels are seen as depressed.
•	People who are highly optimistic are Bipolar type 1 and the people who tend to unoptimistic are depressed

**The next steps in analysing this data could be –** 

•	Perform cluster analysis to identify distinct subgroups of individuals based on their symptom profiles.
•	Incorporate qualitative data through interviews or surveys to gain deeper insights into individual experiences with mental illness.

**Dataset Quality Summary –** 

The dataset appears to be comprehensive, with detailed information on various mental disorders and associated factors. However, it would be beneficial to have additional data on factors such as family history, lifestyle habits, and social support networks to conduct a more thorough analysis of the determinants and outcomes of mental illness. Additionally, collecting longitudinal data would enable researchers to track individuals' progress and assess the effectiveness of different interventions over time.

**Hence we have used Matplot and Seaborn to perform EDA on the Mental Disorder Classification dataset.
We discover the counts of patients with respect to each symptom and see which disorder best lies with their case.
Hence we can draw the following inference from this -** 

* People who are Never Sad and Sometimes Euphoric tend to exhibit Bipolar Type 2
* People who are usually exhausted are depressed, those who are never exhausted are Bipolar Type 1, and those who are sometimes exhausted are Normal
* People who are lacking sleep are most often depressed 
* We also see that people with low concentration levels are Bipolar Type 2 and the people with high concentration levels are seen as depressed.
* People who are highly optimistic are Bipolar type 1 and the people who tend to unoptimistic are depressed

**Note - These inferences are only based on the dataset and may or may not be fully accurate.**
