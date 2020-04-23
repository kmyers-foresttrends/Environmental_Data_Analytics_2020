# Comparison of community and individual natural resource rights across Sub-Saharan Africa
Course final project repository for Environmental Data Analytics (ENV 872L) at Duke University, spring 2020

Student: Kimberly Myers (krm75@duke.edu)


## Summary
The "Rights to Resource" data used in this analysis come from World Resource Institute's Land and Resource Rights Initiative and were published in November 2013.  In the data set, there are 5 sets of 11-question surveys detailing policies on water, trees, wildlife, minerals, and petroleum resources.  Questions in the survey pertain to individual and community resource rights in sub-Saharan Africa.  In total, the project collected data on framework laws for 49 countries. Many of the nations studied enforce state-managed resource use. Resource Watch intended for this information to empower citizens and communities, investors, and policymakers to promote change. 

The purpose of this analysis is to further quantify the Rights to Resource data trends.  I compared community access across the 5 resources and presented a policy-based ranking of nations with all resources combined.  I also plotted these results on a map to facilitate interpretation.


## Investigators
Kimberly Myers
Nicholas School of the Environment, Duke University
krm75@duke.edu
Graduate Student


## Keywords
africa, governance, resource rights, natural resources, policy, communities


## Database Information
The dataset was created by the Governance Center at World Resources Institute, which manages the Land and Resource Rights Intitiative.  They published the data in November 2013 and I first accessed the data in April 2020.  They formatted the data as a survey and analyzed existing policy to provide categorical responses to the questions (yes, no, partially, silent, implied, etc.).


## Folder structure, file formats, and naming conventions 
Project > Data > rights_to_resources_data_set.xlsx
- This file contains all survey responses data used for statistical analysis (composite of all 5 resources).
- It also hosts tabs to explain the purpose of the dataset and lists the survey questions.

Project > Data > rights_to_resources_water.csv
- This file contains all survey responses data relating to water policy.

Project > Data > rights_to_resources_wildlife.csv
- This file contains all survey responses data relating to wildlife policy.

Project > Data > rights_to_resources_trees.csv
- This file contains all survey responses data relating to forest policy.

Project > Data > rights_to_resources_petroleum.csv
- This file contains all survey responses data relating to petroleum policy.

Project > Data > rights_to_resources_minerals.csv
- This file contains all survey responses data relating to mineral policy.

Project > Docs > FinalProject_Myers.pdf
- This file is the final output of my analysis, including code, outputs, and interpretations.

Project > Scripts > FinalProject_Myers.rmd
- This file is the editable version of my final document.


## Metadata
All datasets used in analysis were formatted as follows:
- Country code = 2-letter code of country (cat)
- Country = Country name (cat)
- Q1 = Does the law provide that the natural resource is the property of the state or part of the public domain? (cat)
- Q2 = Does the law recognize any private ownership of the natural resource? (cat)
- Q3 = Does the law recognize customary or traditional rights to the natural resource? (cat)
- Q4 = Does the law provide for the use of the natural resource by any person without authorization from the government or payment of fees (hereafter called “free” natural resource use rights)? (cat)
- Q5 = By law, are “free” natural resource use rights linked to land rights or are they independent of land rights? (cat)
- Q6 = By law, can a person employ any equipment, technology or method for exercising “free” natural resource use rights? (cat)
- Q7 = By law, can “free” natural resource use rights be extended for commercial purposes without a government authorization? (cat)
- Q8 = Does the law provide certain conditions, restrictions or limitations on the exercise of “free” natural resource use rights? (cat)
- Q9 = Does the law provide for registration of “free” natural resource use rights? If not, does the law empower an institution to monitor the exercise of “free” use rights? (cat)
- Q10 = Does the law provide for revocation or taking away of “free” natural resource use rights? (cat)
- Q11 = Does the law have grievance and dispute resolution mechanisms available to holders of “free” natural resource use rights? (cat)


## Scripts and code
All code used in the analysis will be contained in FinalProject_Myers.rmd.


## Quality assurance/quality control
All data published by WRI is subjected to strict academic standards.  They strive to disperse information that is 'rigorous' and 'objective'.

The data were well-organized into 5 identically-formatted tabs, one for each resource group.  