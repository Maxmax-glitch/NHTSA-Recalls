# NHTSA-Recalls
Analyze the NHTSA Recalls Dataset

What is the NHTSA?
    "The National Highway Traffic Safety Administration (NHTSA, pronounced "NITZ-ah") 
    is an agency of the U.S. federal government, part of the Department of Transportation.
    It describes its mission as "Save lives, prevent injuries, reduce vehicle-related crashes"
    related to transportation safety in the United States."
     Source: https://en.wikipedia.org/wiki/National_Highway_Traffic_Safety_Administration

    
What is a Recall?
    "A product recall is a request from a manufacturer to return a product after the discovery of safety issues 
    or product defects that might endanger the consumer or put the maker/seller at risk of legal action."
    https://en.wikipedia.org/wiki/Product_recall
    
    In this context it is meant in regards to vehicle recalls in the United States, where specific rules apply.
    
What is the NHTSA Recalls Dataset?
    'Manufacturers who determine that a product or piece of original equipment either has a safety defect, 
    or is not in compliance with federal safety standards, are required to notify NHTSA within five business days. 
    NHTSA requires that manufacturers file a defect and noncompliance report as well as quarterly recall status reports, 
    in compliance with Federal Regulation 49 (the National Traffic and Motor Safety Act) Part 573, 
    which identifies the requirements for safety recalls. NHTSA stores this information and the data can be used to search 
    for recall information related to specific NHTSA campaigns and product types.''
    Source: https://www.nhtsa.gov/nhtsa-datasets-and-apis


The NHTSA Recalls Dataset is regularly updated and contains all filed recalls of road vehicles and equipment since 1966.
Since 1977 additional information about the recalls is included in the dataset in the column #Recall description' therefore
the dataset is filtered to include only entries since 1977.
The current version of the dataset can be downloaded on the NHTSA web-page as CSV or requested through API connection.
For this analysis a local copy of the dataset is used - download date: 2021-Aug-09


The following analysis tries to answer some basic questions about the data:
    
    #1. Question: What are the Top3 biggest recalls by number of affected vehicles?
    
    #2. Question: How many software related recalls happen and how does it compare over time?
    
    #3. Question: How does the performance of different passenger vehicle manufacturers adjusted by their market share?


#Licence
Academic Free License v3.0	afl-3.0
