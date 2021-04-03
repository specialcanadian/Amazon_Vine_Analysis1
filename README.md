# Amazon_Vine_Analysis
## Overview of Project/Purpose
This analysis was done to see if there is any bias towards giving 5-star reviews for people who were paid to review through vine. The data was first extracted and cleaned a bit using PySpark, stored in an AWS server (which was done in pgAdmin), and analyzed using the Python Pandas library.

## Results
![alt text](https://github.com/specialcanadian/Amazon_Vine_Analysis1/blob/main/images/image%20(1).png?raw=true) 
![alt text](https://github.com/specialcanadian/Amazon_Vine_Analysis1/blob/main/images/image%20(4).png?raw=true)
- There were 90 reviews from people paid through the vine program, and 37385 people not paid

![alt text](https://github.com/specialcanadian/Amazon_Vine_Analysis1/blob/main/images/image%20(2).png?raw=true)
![alt text](https://github.com/specialcanadian/Amazon_Vine_Analysis1/blob/main/images/image%20(5).png?raw=true)
- 44 of the vine reviews were 5-stars, and 14626 non-vine reviews were 5-stars.


![alt text](https://github.com/specialcanadian/Amazon_Vine_Analysis1/blob/main/images/image%20(3).png?raw=true)
![alt text](https://github.com/specialcanadian/Amazon_Vine_Analysis1/blob/main/images/image%20(6).png?raw=true)
- 48.9% of the vine reviews were 5-star, and 39.1% non-vine reviews were 5--stars.
## Summary
Overall, there is about a 10% difference in 5-star ratings between vine and non-vine reviewers. I would say this shows a significant amount of positivity bias. An additional analysis I could do would be finding the p-value of review score compared to weather or not the reviewer used vine.
