# Cheating-Analysis

This is a mini-project for a quantitative biology fellowship intended to be used as practice for data tidying and cleaning to facilitate further analysis. 
This analysis revolves around identifying a list of potential "cheaters" by looking at the scores of individual participants in different rounds of the 
competition to determine outliers.

## Rules

The scores are from individuals who participated in a League competition with an honor system round as well as live championship rounds. Honor system round is
conducted at the participants own discretion, with 24hrs of completion time. The live championship is observed real-time by audiences under high pressure and
time constraints for completion. Initially, performances of participants must exceed a certain threshold for them to be eligible to compete in the live championship. Honor system scores from these participants are recorded as well as their performances in the individual rounds in the live championship. Between
rounds 2 and 3, there is an elimination process to allow only the top performing participants to proceed to rounds 3 and 4 of the live championship.

Several methods to identify potential cheaters have been listed; involving both parametric (z score and p value thresholding) testing as well 
as non-parametric (ranking) testing.

## Data Explained
Name: Name of Participant (imaginary names)

Year: Year of competition

Round: Round of live championship

Merge: Indicates whether or not the participant successfully entered the live championship
(all individuals listed in dataset will have "merged" present in this column to indicate that their honor system performance qualifies for participation in the 
live championship, hence the other additional data available)

Qs 1-12: Indicates whether or not the individual has answered that specfic question correctly
(0=incorrect response for that question; 1=correct response for that question)

Number correct: Total number of questions correct in live championship

Honor system correct: Percent of questions correct in honor system round
