##Short Description
The aim of this project was to learn how to collect information with APIs using GET requests, and then to subsequently analyze this data in R. For my research topic, I chose to collect information from two ProPublica APIs, one that stored biographical information for members of congress, and another that summarized campaign contribution data. I explored various APIs while researching this project, but was unable to add all of the data sources that I wanted. I plan on adding information from other APIs such as the US Census so that I can ultimately gain a comprehensive picture of the information currently available related to a legislator's performance. The end goal with my analysis is to develop meaningful evaluative measures with this publically available data.


##Dependencies
- R, version 3.1
- Python, version 3.5, Anaconda distribution


##Files
####Data
- ppbio.csv: A summary list of biographical data for every member of the current US Senate
- ppcampfin.csv: Data form the ProPublica Campaign Finance API that pulls summary information for every FEC identifier


####Code
- 01_collect-data.ipynb: Collects data from ProPublica Congress API and ProPublica Campaign Finance API and exports data to the files ppbio.csv and ppcampfin.csv respectively.
- 02_analysis.Rmd: Merges ppbio.csv and ppcampfin.csv and creates plots to analyze the data 


####Results
- loyalty_attendance.pdf: Graphs the percentage of votes missed by a senator compared to the loyalty of their votes to their party
- next_election.pdf: Graphs the number of votes missed for senators whose terms will end in 2016, 2018 and 2020
- party_comparison.pdf: Graphs how the number of votes missed compares between the parties, along with a graph of the current breakdown of party controlled seats in the chamber

##More Information
The inspiration for this project came from witnessing the impact of advanced statistics was having on professional sports like baseball and basketball. The way to evaluate and predict an athelets impact had transformed from the legacy "vanity" statistics and the fabled "eye test" to objective measurements of their impact on the game. Statistics like Wins Above Replacement (WAR) in baseball provided a standard for milliciting how many wins a player was worth, as compared to the league average or "replacement" player. similarly, Real Plus/Minus in basketball measures the performance of a team with a player on the floor as compared to how it performed when that player was on the bench. Staring at the dearth of information that I had about the candidates on my ballot, not to mention a relative ignorance about how to effectively evaluate or benchmark an incumbent's performance, I found myself wishing that I knew more about these people I was electing beyond a brief bio, a few statements and a few endorsements. 

Now I'm not naiive enough to think that this would be a simple, easy or even harmless addition to the information resources available to voters. Politics, despite what many old white men in congress might say, isn't baseball, and it certainly doesn't come close to producing teh relatively controlled, reproduced and obsessively measured dataset that baseball does. And impact is really hard to measure, just ask nonprofits. And what about perverse incentives that are all too common in public policy, or the old accountant's dilemma that "whatever get's measured, matters?" Well, those are all valid criticisms that I will have to take into account as I embark on this project. Assumptions, process and reliability will have to be noted along the way, and transparency of the measures would be paramount. In order to prevent "gaming" of any algorithm or model, measurements will need to be taken from multiple angles in order to ensure that they aren't incentivising negative outcomes.

The end result of this project is unclear at this moment, it could end up creating a clearinghouse or census of the information on elected representatives that is publically available, be used to create a more comprehensive "scorecard" of useful metrics, or be rolled up into a higher-level statistic consisting of various weighted measures.

The project for PS239-T is a proof of concept on whether this idea might have the promise to continue working on over the course of my graduate studies.
