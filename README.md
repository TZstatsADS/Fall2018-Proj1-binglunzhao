# Applied Data Science @ Columbia
## Fall 2018
## Project 1: What made you happy today?

![image](figs/title.jpeg)

### [Project Description](doc/)
This is the first and only *individual* (as opposed to *team*) this semester. 

Term: Fall 2018

+ Projec title: Lorem ipsum dolor sit amet
+ This project is conducted by [your name]

+ Project summary: [a short summary] Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.

### Main Findings from Happy Moment dataset
From more than 100,000  happy moment messages from over 10,000 respomndents, I want to figure out is "What the hottest topics are they concerned?". In order to find the mixture of words that is associated with each topic, I ran Latent Dirichlet allocation by using Gibbs sampling to generate 10 different topics. 
They are "Shopping","School","Family","Home","Emotion","Celebration","Friend","Entertainment", "Goal","Travel".

After we done this, we could compare the results with the predicted_category from the original dataset. From the heatmap, we could easily get almost the matched results,such as,“Travel and Nature”, “Freind with Bonding”,etc. 

Then, from the demographic dataset, the 101 countries catch my eyes, which I decided to have a look at “What are the happy moments from people with different nationalities?” I draw another heatmap to show the results. Because there are over 100 choices, I chose only 13 out of 101, include countries from all 5 continents. For example, people from Sweden are care most about “Family”, where people from Finland are focusing on “School or Education”. 

I also use clustering method to divide 60 countries into 5 different clusters. "AUS", "USA", "GBR","CAN" are in the green cluster, where "HKG", "UKR", "GHA" are in the purple cluster. The results indicate that people from the same clustering country most likely share the similar "happy moments".
