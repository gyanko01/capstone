# Introduction
This is initial set up for my Capstone project, where I will be developing an end-to-end solution.This README will be updated weekly to reflect progress,
futures added, and milestones acheived throughout the development process.
# Weekly Updates
## Week 1:
- ### Fails of the week
  - None
- ### Successes of the week
  - Submitted Weekly status report and created project proposal
- ### Difficulties of the week
  - Drafting the proposal - focusing on one main straight objective.
- ### Goals for next week
  -  *Review Public Data:* Identify and gather relacant datasets that align with the project's main objective - fiannacial stgatements, market data, federal reserve aviaalble datasets and FDIC datasets
  -  *Literature Review:* Begin reviewing literature to understand current research and approaches related to the project objective
  -  *Breakdown Project Components:* Define and outline the project's components, such as necessary data, policy implications, environment set up, actions and state determination

  ## Week 2:
  - ### Fails of the week
  - None 
- ### Successes of the week
  - *Literature Review:* Selected a few articles discussing Reinforcement Learning in Finance and began reviewing them
    -   Reinforcement learning in financial markets - a survey Fischer, Thomas G
    -   A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem, Zhengyao Jiang, Dixing Xu, Jinjun Liang
  - *Review Public Data:* Explored Board of Governors of the Federal Reserve System's Data website and started examining the available datasets
- ### Difficulties of the week
  - Sorting through relevant  articles: There are numerous articles related to financial risk and machine learning techniques, making it challenging to determine how best to apply the avaialble data
- ### Goals for next week
- *Continue with the letrature review and Fiancial data review:*
- *Breakdown Project Components:* Define and outline the project's components, such as necessary data, policy implications, environment set up, actions and state determination

## Week 3:
- ### Fails of the week
- None
- ### Successes of the week
- Had a productive discussion with Dr. Allen regarding the project proposal
- Gained more clarity on the next steps, specifically focusing on :
    - Acquiring the necessary data
    - Creating a hypothesis
    - Defining the main research question that my project aims to answer
- ### Difficulties of the week
- Encountered difficulties in locating the necessary datasets, sepcifically related to liquidity forecasting
-  ### Goals for next week
-  Continue exploring and analyzing the avaialable datasets
-  Use insights from selected articles to refine hypothesis and further develop key research question for the project
-  Start working on Requirement Specification

## Week 4:
-Fails of the week
- None 
- ### Successes of the week
- Added one more article to my literature review which helped with formation of some of the research questions and gives better direction of what data to use
  - An Artiﬁcial Neural Network and Bayesian Network model for liquidity risk assessment in banking - Madjid Tavana, Amir-Reza Abtahi , Debora Di Capro , Maryam Poortarigh
- Explored and identified below datasets from FRED website:
  -  Total Assets, All Commercial Banks - weekly from 2014-09-25 to 2024-09-25
  -  Deposits, All Commercial Banks - weekly from 2014-09-25 to 2024-09-25
  -  Cash Assets, All Commercial Banks - weekly from 2014-09-25 to 2024-09-25
- Defined research questions:
- What are key factors affecting liquidity in banks and how can the RLHF agent compute their occurence probabilities to improve liquidity management?
- How can human feedback be used to imporve the decision making process  of the RL agent?
- How can the RL agent learn the trade-offs between different asset classes and liability management to maintain optimal liquidity levels?
- How can the RLHF agent be used to improve dynamic stress testing for liquidity crises?
- ### Difficulties of the week
- Finding suitable proxy datassets that can serve as a close representation of the actual datasets has proven to be more complex than anticipated
- ### Goals for next week
- Working on Requirement Specficiation
- Downloading the datasets, organizing the data into structured format and ensure consistency in the data formatting of the datasets

## Week 5:
- Fails of the week
- None
- ### Successes of the week
- Explored Yahoo finance dataset
- Worked on formulating questions and finding ways of how to show the improvements that human feedback would bring to the model
- Started the Requirements Specification powerpoint presentation
- ### Difficulties of the week
  - Organizing all the datasets
  - Engineering Graph for the Requirements Specification Document
- ### Goals for next week
- Finish the Requirements Specification Presentation and Present it
- Focus on cleaning the datasets and loading them into pandas.
- Begin inspecting the data, converting it to the appropriate units and preparing it for further analysis 
  
## Week 6:
- Fails of the week
- None
- ### Successes of the week
  - Requirements presentation is done
  - Data files are downloaded and saved for further processing
- ### Difficulties of the week
  - Formatting of the data files and finding datasets within the same timeframe
- ### Goals for next week
  - Data processing, cleaning and normalizing
  - Start working on the environment set up
## Week 7:
- Fails of the week
- None
- ### Successes of the week
- Completed data mapping document covering all the study data
- Reviewed the assets and liabilities composities, which will be used to calculate the current ratio, the main indicator of liquidity
- Organized the time series data into a table with 6 columns detailing the date range, attribute, data type, units, frequencies, information, source, and mapping/notes.This format is a more convenient way to set up environment.
- ### Difficulties of the week
-  Working with asset and liability composites to define actions for the agent has been challenging, especially in mapping each indicator that will impact the agent's decisions
-  Mapping relevant actions precisely to each indicator influencing the agent's behavior is requiring careful planning
-    ### Goals for next week
-    Continue working on the mappings anf prepare all data
-    Load, inspect, normalize and standardize the data
-    Begin drafting the design document 
