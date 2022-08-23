## Vote centers and turnout by election type in Texas

Vote centers (or countywide polling places) are voting spaces that gather all voters, regardless of their address. The idea that favors its implementation is due to the efficiency that these centers theoretically employ. The locations, because they are specifically created for voting, increase voter convenience and, by concentrating voting in a reduced number of spaces, also reduce costs and the number of employees working in the elections. It is also believed that Vote Centers can increase voter turnout.
Theories show that the main effects on voter turnout are collective factors, which include social and demographic issues, the rules used in structuring the electoral process, and the mobilization of political groups. The ease of voting, whether due to the distance to the polling center or the rules employed, theoretically reduces abstention. Among the main causes pointed to abstention are the availability of time and the difficulty of reaching the polling center.
Previous academic studies propose that switching to Vote Centers potentially increases the presence of voters who are less likely to attend the vote. However, studies show that no qualitative studies prove this efficiency. In addition, it is left out in analyzes that favor the implementation of Vote Centers if this effect is the same between the different types of voting or if the effectiveness of these places continues over time. Instead of increasing voter turnout, as previous polls show, there is a risk of actually decreasing it by replacing temporary voting centers in the neighborhood, which generally use the space of schools or community centers. With it, the community habit of voting is lost - of finding acquaintances and strengthening the ties of the neighborhood.


## Hypothesis

The idea of this work is to assess the validity of the Cortina and Rottinghaus (2019) study, assessing their used methods and applying a Robustness test further. Observing if the same results were reached, I created the following hypothesis.
*H1*: Voter turnout will increase in counties that switch to a vote center method in midterm/gubernatorial and presidential elections, compared with constitutional elections.
*Outcome*: county-level voter turnout.
*Main predictor:* the interaction between a variable of the presence of a vote center in an election and a variable indicating whether that period is before or after the implementation of the policy.
*Control variables*: size of the county ( population), median county income and percentage of higher education degree in the county.
 
 
## Methodology
 
In order to analyze the causal effect of the voting center on voter turnout, controlling for different types of election, median income, population and education, the following methods are used: 
* Difference-in-Differences estimator and fixed effect focused on all three elections;
* Difference-in-Differences focused on constitutional elections; 
* Propensity score matching and linear regression on Difference-in-Differences.
 
 
## Results
![](https://github.com/rennnas/Stats-II-Replication-Project/blob/main/imagem%202.png)
 
 
## Conclusion 

The analysis of what was accomplished by the authors can lead us to the perception of how solid the model is built and to start with different strategies on how to build other forms of analysis of the hypothesis. When analyzing the process that resulted in Table 1, we see that when creating models for the three types of election, there is no significant causal effect of voter turnout by type of election, considering the presence of the vote center in different electoral cycles.
The same can be said of the results in Table 2. When trying to prove that the vote center can have a specific positive effect on Constitutional Elections, the result was not statistically significant, despite a small increase in the short-term voter turnout shortly after the program implementation, which is not consistent over the long term.
While the chosen robustness test using propensity score matching pointed to the same direction and the parallel trend assumption was not violated, is important to make some remarks about the methods used.
