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
## Week 8:
- Fails of the week
- None
- ### Successes of the week
- Environment data is set up for loading and processing
- Explored Gymnasium website to gather more information about creating custom environmnets
-  ### Difficulties of the week
-  Sorting out the data in one time series as there are weekly and daily data
-  Configuring moving averages to gather a broader picture of the trends
-  ### Goals for the next week
-  Start with the code and continue exploring Gym environment
-  Continue working on the design document
-  Goals is to have the Competency Demo on November 19 and design document on Dec 3rd

  ## Week 9:
  - Fails of the week
  -None
  - ### Successes of the week
  - Features Data is loaded and validated
  - Fininding more reliable sources of data for calculating current ratio
  - ### Difficulties of the week
  - Some problems with files and data types glitches
  - Determining action space based on the data, for now considering Q-learning
  - ### Goals for the next week
  - Keep working on the datasets
  - Start working on competency demo
  - Simultaneously working on design document, gathered more resources on determining current assets and curent liabilities

  ## Week 10:
  - Fails of the week
  - The Assets/Liabilities dataset is not deterministic and relevant enough
  - Will need new data source
  - ### Successes of the week
  - Features Data Processed and loaded in DataFrame
  - Configuring Environmnet set up
  - Found sources for selecting more reliable data for current ratio variable
  -  ### Difficulties of the week
  -  Working with the features data and determining actions
  - ### Goals for the next week
  - Prepare Competency Demo
  - Work on the new Data Source, determine ways to download and inspect the data
  - Work on design document, formulating hypothesis
    
## Week 11:
- Fails of the week
- My calculations on the new datasets are failing due to encoding issues, as the column names in the datasets are either not being recognized or misinterpreted. This is likely caused by inconsistencies in the character encoding of the files, which prevents proper alignment of column headers with the expected schema during processing. Mismatch in encoding ( UTF-8 vs. mixed data types)
- ### Successes of the week
- New dataset script worked very well for downloading and saving the data
- Other features datasets are validated and the data is mostly cleaned with no missing values
- Completing Competency Demo
- ### Difficulties of the week
- Encoding issues
- Misalignment in the data frequency ( daily vs. quarterly) and finding ways to handle it
- Raw data for the current ratio very sporading, with outliers, skewed
- ### Goals for the next week
- Normalize, standardize the datasets
- Fix the encoding issues and add the missing data
- Work on time series alignment
- Work on design document

## Week 12:
- Fails of the week
- Interpolation of quarterly data to daily data for assets and liabilities 
- ### Successes of the week 
- Found more Asset Liability Management Reinforcement Learning articles for reference
- Created mappings susccessfully of all the  asets and liabilities columns included in the dataframe
- Narrowed the dataset with limited number of institutions to match the 2052 Liquidity daily reporting requirements,i.e. indicating which institutions should submit the liquidity report daily
- Successflully created stasts dataFrame with Coefficient Variance and heurustic to determine the type of the interpolation to daily time series based on the  CV Categorization
- Redownloaded 2014 data files and was able to include them in the raw dataframe
- ### Difficulties of the week
- Interpolation to Daily Buisiness Day from quarterly
- How to handle multiple rows with the same quarterly date to extend to daily , need carefully to select groupping sorting of the dataset
- Determine ways to interpolate - linear, spline, logarithmic
- ### Goals for the next week
- Get the daily time series dataset for assets and liabilities working
- Merge the above dataframe with the other market and economic indicators datasets
- Work on the merged dataset to identify action set and reward functions
- Desing document

  
## Week 13:
- Fails of the week
- None
- ### Successes of the week 
- Interpolated the qurterly data into daily and maerged wih the market data
- DataFrame is complete for next steps in RLHF
- Completed Demo Notebook
- ### Difficulties of the week
- Interpolation to Daily Buisiness Day from quarterly using scaled weight and Coefficient of Variance
- The liquidity data is very unstable, current assets cover only 31% of current liabilities, very low values
- Designing a reward function - in process
- ### Goals for the next week
- Reward functions and action sets
- Design document

  ## Week 14: Week of Dec. 4
- Fails of the week
- None
- ### Successes of the week 
- Reviewed the balance sheet data and included more asset variables to the Current Asset feature
- ### Difficulties of the week
- Figuring out which Balance sheet variables will be counted toward Current Assets
- Literature Review organization for Design paper
- ### Goals for the next week
- Use the new developed Current Assets data and redo the Inputs dataset representing an input for the environment
- Design document - Introduction and Literature Review

  ## Week 15: Week of Dec. 11
- Fails of the week
- None
- ### Successes of the week 
- Completed Introduction Section of the Design Document
- New dataset is saved to csv file
- New dictionary is set up with all the variables and definitions for each variable of Current Assets and Current Liabilities
- ### Difficulties of the week
- Design document preparation - structure, sections, literature review
- Literature Review organization for Design paper
- ### Goals for the next week
- Review articles and highlight the most important parts
- Continue with Design Literature

   ## Week 16: Week of Dec. 18
- Fails of the week
- None
- ### Successes of the week 
- Reviewed the technical articles for RL and RL in finance
- Drafted the first 2 sections of Literature review for the design document 
- ### Difficulties of the week
- Relating the articles to the RLHF design
- ### Goals for the next week
- Complete Literature Review

 ## Week 17: Week of Dec. 25
- Fails of the week
- None
- ### Successes of the week 
- Completed Literature Review
- ### Difficulties of the week
- Relating the articles to the RLHF design
- ### Goals for the next week
- Formulating Hypotheses 

## Week 18: Week of Jan. 1
- Fails of the week
- None
- ### Successes of the week 
- Completed Hypotheses 
- ### Difficulties of the week
- Designing the state space for Q-learning model - discretizing the states to get finite state space
- Formulating Action space to be able to use the market and balance sheet data 
- ### Goals for the next week
- Action Space
- Reward Function

  ## Week 19: Week of Jan. 8
- Fails of the week
- Reward for Q-learning - need to come up with logic how to represent the gap of the $current\_ratio$ to 1.The state space is not including the shortage values, so need to find a way of calculating the new current_ratio
- ### Successes of the week 
- Action Space is formulated
- Cost of the actions for PPO is set up on high level
- Refining the PPO cost calculation to use in Q-learning  
- ### Difficulties of the week
- Reward construction for PPO and Q-learning
- Formulating Action space to be able to use the market and balance sheet data 
- ### Goals for the next week
- Action Space
- Complete Q-learning  and PPO reward functions
- Simulate actions to test the reward calculation
- Design document

  ## Week 20: Week of Jan. 15
- Fails of the week
- Reward for Q-learning -need to develop a clear representation for the gap to current ratio to 1, particualrly when the shortage values are not explicitly included in the state space
- ### Successes of the week
- Achieved promising preliminary calculations using correlation coefficients to approximate the adjustment to current_ratio.
- Incorporated correlation-based logic into the calculation of the new current_ratio
- Finalized the shared layered architecture for the actor-critic network, clearly distingushing shared inputs and separate outputs
- Completed the reward construction for PPO, including integration of human feedback , market indicators, permormance ratio and balance sheet data
- Created a diagram for PPO design to visually represent the architecture and flow of the shared layer and netwrok outputs
- Reward Construction for PPO is complete  
- ### Difficulties of the week
- Evaluation metrics - need to better align metrics with the project hypotheses, particularly around human feedback improving decision-making
- Finding appropriate ways to measure the agent's efficiency and accuracy in achieving solvency and cost minimization
- ### Goals for the next week
- Complete the design document - articulate the finalized reward function for Q-learning
- Ensured the PPO design includes justification for shared and separate network layers
- Develop evaluation metrics

  ## Week 21: Week of Jan. 22
- Fails of the week
- NONE
- ### Successes of the week
- Q-learning and PPO architectures
- Reward construction and evaluation metrics
- Completed the design document
- ### Difficulties of the week
- Faced challenges in developing designs that are still proposals for experimentation
- Uncertainty about how well the simulated logic and reward mechanisms will align with the agent's actual learning outcomes in practice
- ### Goals for the next week
- Review Gym documentation and explore initialization of the environment for the agent
- Verify data completeness
  
## Week 20: Week of Jan. 15
- Fails of the week
- Reward for Q-learning -need to develop a clear representation for the gap to current ratio to 1, particualrly when the shortage values are not explicitly included in the state space
- ### Successes of the week
- Achieved promising preliminary calculations using correlation coefficients to approximate the adjustment to current_ratio.
- Incorporated correlation-based logic into the calculation of the new current_ratio
- Finalized the shared layered architecture for the actor-critic network, clearly distingushing shared inputs and separate outputs
- Completed the reward construction for PPO, including integration of human feedback , market indicators, permormance ratio and balance sheet data
- Created a diagram for PPO design to visually represent the architecture and flow of the shared layer and netwrok outputs
- Reward Construction for PPO is complete  
- ### Difficulties of the week
- Evaluation metrics - need to better align metrics with the project hypotheses, particularly around human feedback improving decision-making
- Finding appropriate ways to measure the agent's efficiency and accuracy in achieving solvency and cost minimization
- ### Goals for the next week
- Complete the design document - articulate the finalized reward function for Q-learning
- Ensured the PPO design includes justification for shared and separate network layers
- Develop evaluation metrics

  ## Week 22: Week of Jan. 22
- Fails of the week
- NONE
- ### Successes of the week
- Design paper completed
- Evaluation metrics reviewed and included PPO design
- Initial Q-learning framework set up with binned data
- ### Difficulties of the week
- Reward construction - how to incorporate and account for all the different scenarios
- Q-learning and binned data - ensuring appropriate state-action representations
- Uncertainty about how well the simulated logic and reward mechanisms will align with the agent's actual learning outcomes in practice
- ### Goals for the next week
- Review Gym documentation and explore initialization of the environment for the agent
- Verify data completeness and refine prepocessing steps

    ## Week 22: Week of Jan. 29
- Fails of the week
- NONE
- ### Successes of the week
- Environment setup completed using custom classes and code from scratch
- Encoded the data each row has "state_id"
- Evaluation metrics reviewed and included PPO design
- Initial Q-learning framework set up with binned data
- ### Difficulties of the week
  -Data preprocessing - ensuring that each row is enoded and the duplicated "state_ids" correspond to the same binned data
  - Setting up the reward function 
- ### Goals for the next week
- Complete code and train the agent
