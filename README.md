# Assessment
Assessing summarized statistics and proportions to recommend a pricing scheme 



A delivery company is assessing various experimental designs to optimize its pricing strategy. 

the tables are shown below, and the requirment is to assess the best Variation setting for the purpose of increasing the delivery fee and maintaining the users' share percentage

![](https://github.com/SAB4891/Assessment-/blob/e38a41739bad67a7e74405bf200e9f0b003e9e80/tables.png)

#####
Variation2 settings offer more transactions per session, an increase in the delivery fee, and maintain the users' share proportion. the below visualization of the transactions per sessions proportions' confidence interval can lead to the plausibility of the improvement made by Variation 2. 

![](https://github.com/SAB4891/Assessment/blob/82438ce2d8bf148f862b079ce63e7720045a877b/confidence_intervals.png)



####

![](https://github.com/SAB4891/Assessment/blob/main/TiersPropr.png)

Attempting to reach a 0.94KD over all tiers, it is obvious that an attempt to increase x (the second-tier user proportion) positively correlates with the 4th tier user share proportion (which means, if we desire to increase the 3rd tier proportion, we must increase the 4th tier as well (as per the 0.94 KD constraint set). However, the relationship is negatively correlated with the 3rd tier user share proportion, any attempt to increase the 2nd or 4th (which go together) we must decrease the user share proportion in the 3rd Tier


the interactive plotly chart can be downloaded (the html file in the repository) and opened regularly to interact with the 3D plotted segment (detail in the pdf report appendix)  




#### Tools & packages 

-Jupyter Notebook
-Statsmodel package
-numpy
-matplotlib
-plotly
