# An Overview of Healthcare Prescribers in the United States 

# Executive Summary
I will build a tool to display an overview of prescribers in the United States, and filter the providers to identify the suspicious ones. For example, providers who incur high cost when their patient risk score is low. By visualizing some important features, we can solve the problem of identifying suspicious providers. This tool can be viewed as a provider search engine. After patients or employers specify some important parameter of interest, the tool will list or plot the best providers based on their inputs.

 # Motivation
I wanted to expand on my educational and work background in healthcare because I am very passionate about serving the community and helping people. It makes me feel good and motivated to attempt to possibly save lives and help patients find better care.

# Data Question(s)
How to filter the providers, and identify the suspicious ones.

- Where the providers are located?
- What is their specialty?
- What are they prescribing?  
- How sick are the patients?
- What are drug costs in top ten states and top ten specialty categories?
- Is patient risk correlated to cost? (scatter plot)

- Number of Providers 
- Number of claims 
- Average claims per Providers 
- Average 30- day refill per Providers 
- Average drug costs per Providers 

- Calculate total charge per provider
- Distribution of patient severity of illness per drug
- Patient demographic distribution (Age, race, sex)
- Cost per drug
- Prescription per drug

Schedule (through 6/25/2020)
1.	Get the Data (05/30/2020)
2.	Clean & Explore the Data (06/12/2020)
3.	Create Presentation  (06/17/2020)
4.	Internal Demos (6/19/2020)
5.	Demo Day (6/25/2020)

# Data Sources
Part D Prescriber Summary Table CY2017 

https://data.cms.gov/Medicare-Part-D/Medicare-Provider-Utilization-and-Payment-Data-Par/psut-35i4 

This data is from Centers for Medicare and Medicaid Services (CMS.gov) and contains aggregated details of the prescription each provider gives, such as opioids, antibiotics, branded drugs, generic ones, and also about the demographics of the providers and thier patients.

# Known Issues and Challenges
Its big data contain 84 features.
- I plan to EDA and extract important attributes that will help to identify providers that practice fraudulent activities.
Missing values.
- I plan to find effective approaches to impute or fill the missing values.
