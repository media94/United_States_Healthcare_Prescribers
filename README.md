# An Overview of Healthcare Prescribers in the United States 

![CMS](/images/cms-logo-pic.png)

# Table of Contents 
* Title 
* Objective 
* Background 
* Data Limitations
* Scenario
* Overview of Prescibers Dashboard
* Deep Dive Analysis Dashboard 
* Findings
* Sources

# Motivation
I wanted to expand on my educational and work background in healthcare because I am very passionate about serving the community and helping people. It makes me feel good and motivated to attempt to possibly save lives and help patients find better care.

# Executive Summary
I will build a tool to display an overview of prescribers in the United States, and filter the providers to identify the suspicious ones. For example, providers who incur high cost when their patient risk score is low. By visualizing some important features, we can solve the problem of identifying suspicious providers. This tool can be viewed as a provider search engine. After patients or employers specify some important parameter of interest, the tool will list or plot the best providers based on their inputs.

# Data Question(s)
How to filter the providers, and identify the suspicious ones by visualizing 

- Where the providers are located?
- What is their specialty?
- What are they prescribing?  
- How sick are the patients?
- What are drug costs in top ten states and top ten specialty categories?
- Is patient risk correlated to cost? (scatter plot)

<<<<<<< HEAD
# Data Limitations 
* It contains 84 features of aggregated measures.
* It does not indicate the quality of care provided by individual providers.
* I plan to EDA and extract important attributes that will help to identify providers that practice fraudulent activities.

# Dashboard Link 
This link will lead you to the tools created for this project. 

https://public.tableau.com/views/OverviewofUSHealtharePrescribersin2017/US_Healthcare_Providers?:language=en&:display_count=y&publish=yes&:origin=viz_share_link

![Dashboard Preview ](/images/overivew-prescribers-dashboard.png)
=======
- Number of Providers 
- Number of claims 
- Average claims per Providers 
- Average 30- day refill per Providers 
- Average drug costs per Providers 

- Calculate total charge per provider
- Distribution of patient severity of illness per drug
- Cost per drug
- Prescription per drug

Schedule (through 6/25/2020)
1.	Get the Data (05/30/2020)
2.	Clean & Explore the Data (06/12/2020)
3.	Create Presentation  (06/17/2020)
4.	Internal Demos (6/19/2020)
5.	Demo Day (6/25/2020)
>>>>>>> d976cd9a256c0f8742dfed62b8de3540590bbbef

# Data Sources
Part D Prescriber Summary Table CY2017 

https://data.cms.gov/Medicare-Part-D/Medicare-Provider-Utilization-and-Payment-Data-Par/psut-35i4 

This data is from Centers for Medicare and Medicaid Services (CMS.gov) and contains aggregated details of the prescription each provider gives, such as opioids, antibiotics, branded drugs, generic ones, and also about the demographics of the providers and thier patients.