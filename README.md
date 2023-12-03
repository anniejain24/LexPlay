# LexPlay
Estimating and visualizing semantic networks using verbal fluency data from 5-8 year olds.

Code for Naive Random Walk and U-INVITE are from the Semantic Network and Fluency Utility library: https://github.com/AusterweilLab/snafu-py

In this study, a semantic fluency task was performed, testing the categories: "animals", "foods", "things at the zoo", and "things at the grocery store" twice for each participant, counterbalancing order. Csv files storing dataframes with fluency lists, fluency metrics, individual-level network matrix representations and metrics, and code for all analyses are located here.

Participants 1-6, 16, 17, 27, and 39 have missing/incomplete data, so are generally excluded from analyses in the preprocessing steps. Participants 33 and 34 are excluded from analyses because they each have one list with no utterances, but there is an option to retain these participants in the code for loading the data. 

Simplified fluency lists have already been preprocessed and pos tagged, with all non-nouns removed. Non-simplified lists are also provided, combined by category or separately for each participant.

