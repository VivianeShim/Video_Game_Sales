# Video_Game_Sales

![Figure0](https://user-images.githubusercontent.com/49568184/118910140-01febc00-b8f2-11eb-81c8-69c705e331f2.jpg)

1. Import the vgsales.csv file in Tableau
2. Analyze the dataset using Tableau
3. Data cleaning and feature engineering on Jupyter notebook
4. Improve root mean square error using Azure Machine Learning


## Business Problem
What is the trend of global video game industry and how accurately can we predict video games sales?

## The trend

 • From the year 1980 to 2015, all categories in genre increased especially in Action, Sports, Shooter, Misc and Role-Playing.
Between 2005 to 2010, video games are popular, especially for Action and Sports games, the highest point of sales is 139.4 which is achieved by Action games.
Figure1. 
![Figure1](https://user-images.githubusercontent.com/49568184/118910141-01febc00-b8f2-11eb-94b1-543b84f2e509.jpg)

 • Wii is the most popular video game platform.  Wii sports is the most popular game worldwide. It achieved the highest sales of 82.74.
The graph demonstrates top 6 popular platforms: Wii, DS, PS4, PS3 and X360.

Figure2.
![Figure2](https://user-images.githubusercontent.com/49568184/118910142-01febc00-b8f2-11eb-8e26-04b30cea3635.jpg)

 • The top 3 publishers are Nintendo, Electronic Arts and Activision. 
I created a bar plot to visualize their sale rates by grouping different market. Market is dominated especially by the NA sales. 
![Figure3](https://user-images.githubusercontent.com/49568184/118910144-01febc00-b8f2-11eb-8ac5-68ff43de7947.jpg)

## Machine Learning 

## 

 •At the first attempt, I used linear regression model. We got 0.64 root mean squred error.
 
![Figure4 (1)](https://user-images.githubusercontent.com/49568184/118910146-02975280-b8f2-11eb-9fee-b3dc68f5b0bd.jpg)

 •I wanted to imporve my model so I cleaned the dataset and used feature enginnering. 
 I only found 3 records for the year 2017 and 1 record for the year 2020. I revmoed the years 2017 and 2020 from my dataset.
 There is a dramatic drop of Global Sales after 2015. I can say that this is due to a lack of the dataset.
 
![Figure4 (2)](https://user-images.githubusercontent.com/49568184/118910147-02975280-b8f2-11eb-8e16-8dedc2c631c0.jpg)
![Figure4 (3)](https://user-images.githubusercontent.com/49568184/118910148-02975280-b8f2-11eb-883f-4fff06e11ad4.jpg)
![Figure4 (4)](https://user-images.githubusercontent.com/49568184/118910149-02975280-b8f2-11eb-9f33-089ad8b68b47.jpg)
![Figure4 (5)](https://user-images.githubusercontent.com/49568184/118910152-02975280-b8f2-11eb-876f-5ef564580dad.jpg)
![Figure4 (6)](https://user-images.githubusercontent.com/49568184/118910153-032fe900-b8f2-11eb-87c9-0110051f19b6.jpg)
![Figure4 (7)](https://user-images.githubusercontent.com/49568184/118910156-032fe900-b8f2-11eb-94e7-1603c33a5eb8.jpg)
![Figure4 (8)](https://user-images.githubusercontent.com/49568184/118910157-032fe900-b8f2-11eb-8e03-8255b23fc1d6.jpg)
![Figure4 (9)](https://user-images.githubusercontent.com/49568184/118910159-032fe900-b8f2-11eb-9c10-c924e7dff446.jpg)
![Figure4 (10)](https://user-images.githubusercontent.com/49568184/118910137-01662580-b8f2-11eb-9fa0-ddcbce78989b.jpg)
