# Cattle Supplementation and Pasture Monitoring
Cattle Supplementation is essential to increase herd production. Despite this, it is one of the most expensive processes in the beef production chain. Using tools to estimate pasture parameters such as forage quantity and quality, can help decrease production costs  and optimizing the amount of supplements supplied to the herd. 
Thus, the use of satellite remote sensing (SRS) has contributed to the monitoring of parameters related to the amount of pasture. 
Likewise, the need to estimate such parameters due to their importance, confronts the lack of technologies capable of accurately estimating information such as pasture biomass and dry matter. In addition, in pasture environments, forage consumption and trampling are parameters that make it difficult to estimate forage production. The use of statistical techniques and machine learning are tools capable of overcoming barriers and showing the effects that animals and high temporal seasonality can cause on forage canopy.

# The dataset
For the construction of statistical or machine learning models capable of predicting Dry Matter and Biomass data from the pasture, 
the composition of a dataset that has independent variables with large effects on the response variables is essential. Despite this, 
the difficulties related to the acquisition of target variables through chemical analysis are known by this area of study. 
Here, we have a dataset with the average of Biomass and Dry matter obtained through an experiment carried out in months 10, 11, and 12 of the years 2017 and 2018 and 
months 1, 2, and 3 of the years 2018 and 2019. In total, 12 paddocks of 0.5 ha had soil samples collected and analyzed via laboratory. 
Sentinel-2 satellite reflectance data were collected from six bands (NIR, Red, Red_Edge, SWIR1, Green, and Blue). With the magnitudes of surface reflectances, 
25 vegetation indices were calculated and can serve as independent variables. In addition, climatic data such as temperature and humidity were also entered in this 
dataset. Each paddock had from 1 to 4 animals and this variable has been studied and proved to be an important factor of effect on the target variables. All vegetation indices used, their equations and, references can be verified in the table below.


![tableinGit](https://user-images.githubusercontent.com/72608354/186172514-2aa19bb1-22ac-4723-9977-53a5ed318ea5.jpg)
![References - Git](https://user-images.githubusercontent.com/72608354/186177990-7b8d8ab4-ffa6-4468-9499-8b9910437c5c.png)
