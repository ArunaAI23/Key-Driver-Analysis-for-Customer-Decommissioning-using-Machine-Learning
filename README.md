# Key-Driver-Analysis-for-Customer-Decommissioning-using-Machine-Learning


The customer decommissioning process is the last phase in the life cycle of a customer system and is the permanent removal of an IT service or any other configuration item, from the live customer environment. The purpose of decommissioning process is to provide a structured and standardized way to decommission system/server and network and to facilitate transparency on the decommission process globally.

Decommissioning involves the deactivation of the customer system/tenant performed by the responsible decommissioning personnel upon the customer contract end date or system end date and confirmation provided by the customer to decommission their system. 

**Purpose**


The project aims at performing Key Driver Analysis affecting delays using the Mean Time to Resolve (MTTR) of the tickets created for decommissioning requests. Further to identifying the factors affecting delays in the end-to-end decommissioning process, the business objective is to provide a roadmap for Cost savings beneficial by optimizing the process thereby reducing delays in the end-to-end process.

Data consisting of tickets created in the JIRA tool for customer decommissioning requests have been considered from Q1 of FY2021 to Q2 of FY2022 forming the basis of our study on factors that are most significant to higher MTTR.

The project exemplifies a machine learning classification that can be used to create a decision tree model for arriving at the key driver analysis of factors resulting in delays. The business impact of this project would result in cost optimization by performing customer decommissioning within the defined Service Level Agreement (SLA). 

**Results**


This project was performed in SPSS Statistics. The dependent variable MTTR is a continuous variable, and the independent variables are also continuous variables. To handle continuous variables, the decision tree created a threshold and then split the list into those whose attribute value is above the threshold and those that are less than or equal to it. 

The main goal of the model was to find an attribute that will be used for the first split. In the case of variables considered for the decision tree, isolation (Days) was used for the first split. In the case of the continuous type of variable, the ‘standard deviation reduction’ metric was used. 

The accuracy obtained in the decision tree is 90.3% with Mean Absolute Error (MAE) being 9.67. In this project, the continuous variable decision tree outcome can be predicted based on multiple variables rather than a single variable. The accuracy achieved with KNN is 96.7% with MAE being 3.27%. 

Key drivers influencing the MTTR as shown in the decision tree are –
Isolation (Days)
Cooling Period
Sub-Contractor (Vendor)


**How to execute**

Output.html file provides the model output from SPSS Statistics. 

