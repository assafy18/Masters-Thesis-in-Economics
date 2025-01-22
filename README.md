# School Violence: Academic Impacts and Underlying Mechanisms
This repository presents my thesis project for the MA in Economics at the Hebrew University of Jerusalem. My supervisor is Professor Victor Lavy.

*Summary*: This paper examines the impact of exposure to violence on academic achievement, focusing on students with a history of violent behavior. Exploiting idiosyncratic variations in the exposure
to new violent classmates during the transition from elementary to middle school, the study finds that a higher proportion of violent peers negatively affects performance, with girls being
more adversely impacted than boys. These effects are driven by increased classroom disruption and weakened student-teacher and peer relationships. Limited evidence suggests that changes
in students’ behavior, as well as teachers’ workload and satisfaction, may also mediate these effects.
 
*Technical Tools*: I used R software throughout the process of this project:
1. Cleaning multiple large, complex administrative datasets (heavily using `tidyverse`, `haven`, and `Hmisc`)
2. Merging the datasets to create one rich dataset, which I utilize throughout the analysis
3. Performing exploratory data analysis (EDA), such as graphs (using `ggplot2`)
4. Estimating advanced econometric models (using `fixest`) and testing hypotheses (using `car`)
5. Building custom regression result tables in LaTeX format (using `fixest`, `stargazer`, and `xtable`)
