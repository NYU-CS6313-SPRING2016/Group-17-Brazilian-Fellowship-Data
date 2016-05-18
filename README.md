#Visual DeepChoice - Understanding the predictions from DeepChoice system
![alt text](https://raw.githubusercontent.com/NYU-CS6313-SPRING2016/Group-17-Brazilian-Fellowship-Data/master/VDC-screenshot.png "Visual DeepChoice")

**Authors**: Andre Mendes ([MendesSP](https://github.com/MendesSP))

##Description
DeepChoice is a machine learning system that learns to select the best applicants in a selection process. It uses the data from previous processes to create a model that is able to assign a score from 0 to 1 to new applicants. This score represent how likely it is for this new applicant to be selected in the future process. 

Visual DeepChoice is a visualization tool to visualize and interact with the the predictions from DeepChoice. The goal with Visual DeepChoice is to provide information about the performance of the DeepChoice System, how changes in the threshold affects the system performance, what are the most important features on DeepChoice predictions and what kind of system is the best for the HR team.

The threshold is very important in the system because it represents the minimum score that an applicant has to have to be approved. Every time the user changes the value for the threshold, all the metrics change accordingly to provide the new results. Even though Visual DeepChoice was designed specifically for the predictions from DeepChoice, the visualization tool is general enough to analyze the results from any binary classifier.

**Video**: https://vimeo.com/167052043?utm_source=email&utm_medium=vimeo-cliptranscode-201504&utm_campaign=29220

**Demo**: http://NYU-CS6313-SPRING2016.github.io/Group-17-Brazilian-Fellowship-Data

**Document**: https://github.com/NYU-CS6313-SPRING2016/Group-17-Brazilian-Fellowship-Data/blob/master/AndreMendes-Final-VisualDeepChoice.pdf

###Runing
1. Open the demo
2. On the top left corner of the central panel, click in Data1, Data2 or Data3 to load a dataset.
3. Change the values for threshold and check how it affects the performance of the system.
