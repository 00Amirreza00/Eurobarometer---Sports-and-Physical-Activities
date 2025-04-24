# Eurobarometer---Sports-and-Physical-Activities
The main idea of this project came from this article:
Van Tuyckom, C. Six sporting worlds. A cluster analysis of sports participation in the EU-25. Qual Quant 47, 441–453 (2013). https://doi.org/10.1007/s11135-011-9528-8

The aim of the project was to identify clusters of European nations grouped by sports participation outcomes (organizational context and intensity of sports participation), in order to provide sensible groupings for international comparisons. In the original article, the sport participation data were distracted from the 2004 Eurobarometer survey which is Standard European Trend Questions and Sport, while I tried to update the results based on the latest Eurobarometer survey which was Eurobarometer 97.3 by that time. In the survey, 26569 individuals were questioned from 27 European members between April and May 2022. The respondents were 15 years and older. The data contains 328 variables and it has been stored as categorical data. So, I had to deal with categorical data.  

In first, I performed EDA, Chi-square test and ANOVA to understand the relations underly between features. Then, I prepared the data for applying hierarchical clustering and K-means++ clustering. I clustered nations based on sports participation outcomes, like in the original article, and physical participation outcomes. The results show that we can consider nations as 5 different clusters: average organized countries, average non-organized countries, active non-organized countries, average multi-context countries, and very active countries.


