I used NFLFastR to pull the open source data for this kicking analysis all play by play data from 1999-2024
You can skip to the NFL Kicker Analysis Post Cleaning RMD and run that file. 
The Cleaning file is the initial data collection from NFLFastR and the steps I took to scrub the data for analysis. (I will still inlcude those files in here). 
The only file you need for the Post Cleaning analysis is the pbp_complete.csv file. 
In the Predictive Model RMD, you do not need to run lines 431-516 (these are tuning rounds which will take hours for your system). Simply run up until 431 and skip to the chunk starting 519
The Shiny Application will take the saved model you generated in the predictive rmd and deploy it on a UI (play around with it). 
Enjoy :)
