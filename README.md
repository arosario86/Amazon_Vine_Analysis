# Amazon_Vine_Analysis
## Overview
Vine is a product that allows users and manufacturers to review ratings on various Amazon products. The overall goal of this project was to review and analyze the Amazon review data to see if there is any skewed data based on biases from Vine members. The dataset I chose to analyze was the toy reviews.
## Results
I used Google colab as my jupyter notebook as well as PySpark to perform the ETL, extract the data, clean and transform, and connect it to my AWS RDS instance. Once completed, I attempted to load my data into my pgAdmin database. For whatever reason, my pgAdmin would not connect with my PySpark, no matter all of my trouble shooting.
* During my Vine Review Analysis, I was able to see that there are a total of 4,864,249 total reviews.
  * I broke up the review analysis by sold and unsold toys. The total votes for sold toys were 1266, while the total votes for unsold toys was 62,028.

![Vine_Reviews](https://user-images.githubusercontent.com/104965708/200471646-425f3596-3c21-451c-aa41-caf4161863b1.png)

  * Of these reviews, 432 were five star reviews for sold toys, and 29,982 five star reviews for unsold toys.
   * 834 of the five star reviews for sold toys were non-Vine, and 32,046 of the five star reviews for unsold toys were by non-Vine.
   
![Vine_Reviews_Totals](https://user-images.githubusercontent.com/104965708/200472156-054ea75b-efea-4979-a363-9ed0e84980ed.png)
