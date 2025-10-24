# BIO_350_F25
Starting our BIO350 assignments repo.

IC Assignment 1: Chapter 1 of Ecology Handbook
 -  Making a difference equation
 -  technical difficulties 

IC Assignment 2: Chapter 2 of Ecology Handbook
 -  Making an exponential equation to measure how quickly duckweed covers a pond
 -  confusion and technical difficulties
 -  introduced matplotlib and plotting on x y axis
 -  graph was blank at first but somehow managed to get data to show up 

IC Example 1 : log and conditional elements
 - turned graph from assignment 2 into a log 
 - created if, if else, and else conditions 
 - created more graphs changing the algoritm

IC Assignment 3: Chapter 3 of Ecology Handbook
 - logistic growth model
 - understand and define variables before coding ; type out parameters in markdown to ease process
 - make sure to add correct spaces/symbols in code and make sure the names of the variables are consistent throughout

IC Example 2 : importing data and messing with inline copilot chat
 - imported our own data file and saving it in the right place (BIO 350 file)
 - utilized previous code for plots
 - relied on Copilot to generate code based on what I told it to do and how I wanted the plot to look
 - used average function to determine carrying capactiy and further used Copilot to display it on the graph

IC Assignment 4: Chapter 4 of Ecology Handbook
 - logistic growth with two species competing
 - understand and define variables before coding ; type out parameters in markdown to ease process
 - ensure variables are defined consistently throughout the code
 - used copilot to understand the competitive exclusion principle and how it relates to the equations
 - don't overuse copilot, try to understand the code yourself first

IC In-Class Example 3: Modifying the two-species competition model
 - modified the two-species competition model to include an external event that increases the population of one species at a specific time point
    - understand and define variables before coding ; type out parameters in markdown to ease process
    - ensure variables are defined consistently throughout the code
    
IC Assignment 5: Rabies Removal - SIR Models
 - SIR model to simulate the spread of rabies in a fox population
 - understand and define variables before coding ; type out parameters in markdown to ease process
 - ensure variables are defined consistently throughout the code
 - used copilot to help generate the SIR model function and plotting code
 - got tripped up on indentation and variable names, need to be careful with these details ; don't rush through the code

IC In-Class Example 4: Importing R script and translating it into python
 - imported R script and translated it into python using inline copilot chat
 - had to re-translate the code multiple times to get it to work properly
 - realized we needed to install scipy package and struggled through activating workspace 
    - was finally able to install scipy after restarting VS code and reopening bash terminal, and actually typing out the name of the environment 
 - translated sections piece by piece and ran all code to ensure it was running smoothly   

IC Assignment 6: Intro to vectors, matrix multiplication (Chapters 11 and 12 of Ecology Handbook)
 - create an algoritm that calculates the population of 3 ages of a beetle population and the total population over 150 years
 - understand and define variables before coding ; type out parameters in markdown to ease process
 - ensure variables are defined consistently throughout the code
 - used numpy to create arrays and perform matrix multiplication
 - got tripped up on indentation and variable names, need to be careful with these details ; don't rush through the code
 - added a trap rate to account for 5% of beetles being caught in traps each year
 - got confused a lot with inconsistent coding and getting left behind during instruction while trying to work through my issues

 IC In-class example 5: Real-life example of an age structured model in a population
 - used ChatGPT to create an example population that includes age-structuring and how it grows over 50 years. 
 - used suggested code from ChatGPT and edited it slightly to see different scenarios play out
 - created two graphs to observe how the population would look after 50 years (for each age group) and one that showed the proportion of each age of the total population
 - evaluated results by understanding what transient and stable behavior of the model was 

 IC Assignment 7: Chapter 13 (Transition matrices) + Chapter 14 (metapopulation analysis and absorption)
 - Chapter 13
   - model how the composition of a forest changes as adult trees are replaced by saplings of different species 
   - used a transition matrix and difference equations to model how the relative proportions of tree species changed over time as adult trees were replaced by saplings
   - used a for loop with matrix multiplication to project the population over 50 years
   - evaluated what the stationary/stable distribution of the population was and tested the probabilities of randomly selecting a specific tree
- Chapter 14
   - looked at a metapopulation of butterflies occupying two habitat patches and evaluated the probability of them going extinct from both patches within 50 years
   - used a transition matrix and algebra to predict the state of the population over time as it transitions with colonization and population shifts
   - created a line plot to visualize the extinction probability of the metapopulation (both patches)
- overall : I took my time to organize the markdown instructions/information before jumping into the code to help my understanding of what the code is trying to achieve overall.