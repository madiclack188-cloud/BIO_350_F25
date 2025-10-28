# BIO_350_F25
Staring our BIO350 assignments repo.
IC Assignment 1: Chapter 1 of Ecology Handbook 
    - Making a difference equation 
    - Technical difficulties, SHOULD be better from now on 
    - It works! 



IC Assignment 2: Chapter 2 of Ecology Handbook 
 - Making an exponential equation to measure how quickly duckweed something
 - Minimal technical difficulties, bit better 
 - Works and indtroduced matplotlib, and plotting on x and y axis 



IC Assignment 3: Chapter 3 of Ecology Handbook 
  - logistic growth 
  - how long to fill a 2mx2m plot 
  - 12 starting plant 
  - 40% die every year 
  -  seed germinates 
  - k=400 
  - s=1 
  - x=400
  - b=75 
  - d=0.4
  - r=0.96
  - total days=240
  - Made a good amount of errors before I got it right 
  - how long to fill? 
     - Around 15 years I think 
  - What does the population even out to? 
    - Around 240 I think 




    IC Example 2
      - Instering csv file 
        - Making sure to save it into BIO file
      - Plot code we have been using already 
      - Making adjustments through highlighting code, right click, select "Copilot", then select "editor inline chat"
      - Used this to find a carrying capacity 
      - Enter and hit tab until copilot gave me what I wanted the graph to look like 




      IC Assignment 4
       - I missed class the day this assignment was done 
        - uploaded code from a classmates GitHub 
         - Have not had the chance to full go through it yet, but will update ReadMe once I do

      




      IC Example 3
       - Chapter 4
        - How to calculate and solve for the ability to coexist?
       - Stability 
        - Properties for an equilibrium state 
        - What happens when there is a pertubation (distrubance)?
       - rx= maxium population growth rate of X
       - Kx= carrying capacity
       - competion term alpha: denotes the per capita* effect of y* on x to the effect of X on X
        - in other words, measure intensity of interspecific to* intraspecific competition effects 
       - Paid attention when more changes were made by prof, however I did not follow along because I was worried I   would mess up the code again






      IC Assignment 5
        - SIR models 
          - Susceptable Infection Removed
        - Rabies in foxes (removed/death rate)
          - Fox pop=1000
          - 50% death chance per day 
          - 1/1000 infected to susceptable meet 
          - S=999
          - I=1
          - R=0
          - Beta=1/1000
          - S-beta*S_t*I_t
          - I_t-d*I_t+beta*S_t*T_t
          - R_t+d*I_t
          - S_t+1 + I_t+1 + R_t+1 = S_t + I_t + R_t
          - Beta 
            - Habitat space 
              - Quarantine 
            - Vaccines
          - Death rate 
            - effective treatment 
          - Process 
            - import mat plot 
            - days = 30
            - for loop (30 days)
            - Set return variables 
              - S_t+1
              - St
              - I_t+
              - It
              - R_t+1
              - Rt
          - Giving the function 
            - beta 
            - death rate 
            - S0
            - I0
            - R0
            - time
         






IC Example 4
 - downloading files from canvas
    - make sure to move file to right folder after download
 - translating files into python using in line editor 
 - make sure to create a new bash terminal 
 - make sure to activate IC_Assignments in bash terminal before trying to activate anything 
 - What worked: 
    - importing things before actually starting 
    - checking translations
    - re-translating when given an error 




IC Assignment 6
  - Matrix Models
    - Nt+1=1.2(Nt)+o(St)
    - St+1=0.2(Nt)+1.4(St)
    - nt+1=A(nt)
    - Problem info 
      - 3 years in wild 
      - F=first year 
      - S=second year 
        - 0.3(F)
        - 2 offspring
      - T=third year  
        - 0.5(S)
        - 10 offspring 
      - ~1000 F+S
      - 20 years pop? 
      - age-structured model
      - Equations 
        - Ft+1 = 1St + 5Tt
        - St+1 = 0.3(Ft)
        - Tt+1 = 0.5(St)
  - Questions 
    - What differences do you see between the two plots?
      - The differences include different starting and ending populations that may decrease of increase depending on the traps/outside factors
    - How much of an effect did setting up traps have on the beetle population over 150 years? 
      - Over 150 years the traps decreased the beetle population despite their high reproduction rate/population size







IC Example 5
  - Structured Population Models (chapter 3 in Intro book)
    - "In the language we introduced earlier, structured population models have more
      detail than their nonstructured counterparts. They account for the differences among individuals within a population, usually by explicitly modeling them as distinct state variables. So, our single population may now be represented with two, three, or maybe 20 state variables that each depict the numbers of individuals in each population group"
        - "A population is said to be “stage structured” if it undergoes distinct  shifts in habitat use, morphology, behavior, or any aspect of its ecology throughout its life"
        - Transient models stabilize after a while of looking crazy
  - Example 
    - 




 


 In Class Assignment 7
  - Bt+1 = 0.8Bt + 0.25Mt + 0.1Ot
    Mt+1 = 0.1Bt + 0.15Mt + 0.25Ot
    Ot+1 = 0.1Bt + 0.6Mt + 0.65Ot
  - What is the stationary state distribution of this population?
    Pr(S = B) = 0.42
    Pr(S = M) = 0.17
    Pr(S = O) = 0.41
  - A = larger patch
  - B = smaller patch
  - eA = probability the butterflies go locally extinct in patch A each year = 0.03
  - eB = probability the butterflies go locally extinct in patch B each year = 0.13
  - cA = cB = probabilities that each patch is colonized by immigrants from the other  patch each year = 0.02
  - What is the probability that both plots will be extinct after 50 years?
    - There is ~75% chance that both patches will be extinct after 50 years.





 In Class Example 6
  - Using example data/code to create a normal distribution 
    - bell curve 
    - Used sample code from a website which explained what a normal distribution was and the process of coding it in python 
      - https://www.geeksforgeeks.org/data-science/data-science-with-python-tutorial/ 
    - Example given on website: 
      - Suppose there are 100 students in the class and in one of the mathematics tests the average marks scored by the students in the subject is 78 and the standard deviation is 25. The marks of the student follow Normal probability distribution. We can use this information to answer some questions about the student's marks. 
      - relatively simple example however worked to improve my understanding 
