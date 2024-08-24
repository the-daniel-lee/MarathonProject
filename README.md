# MarathonProject

### Project Overview
This guided data analysis project aims to explore and provide insights into a dataset using Python and the Pandas library. The focus is on performing Exploratory Data Analysis (EDA) on ultra-marathon races to understand
the data processing steps and apply various analysis techniques. 

### Data Source
Marathon Data: The dataset used for this project was obtained from [here](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running/data).

### Tools
* Python

### Data Cleaning/Preparation
This data project focused on analyzing the USA's ultra-marathon races, limited to 50K and 50-mile events in 2020. Several data preparation steps were performed to achieve this. Column names were standardized, new columns were created for additional analysis, and unnecessary columns were removed. The data was cleaned by handling null values, removing duplicates, and fixing data types to ensure consistency and accuracy before proceeding with the analysis.

### Exploratory Data Analysis
This project aimed to answer these key questions:
1. Difference in speed for the 50k/50mi for male to female?
2. What age groups are the best in the 50m race (20 + races minimum)?
3. What age groups are the worst in the 50m race (20 + races minimum)?
4. Are racers slower in the summer than in winter?

### Data Analysis
The dataset contained more entries for 50 km races than 50 mi races. In terms of gender distribution, 50 km races had a roughly equal split between male and female participants, while 50 mi races had a higher proportion of male athletes. The average speed for athletes of both genders ranged between 5.5 and 7.5 km/h. Male athletes exhibited higher average speeds than females across both race types. Additionally, there was a noticeable trend of decreasing speed with increasing age, indicating that older athletes generally had slower race times.


### Results Findings
1. The analysis revealed that male athletes had higher average speeds than female athletes across both race distances. For the 50K races, males averaged a speed of approximately 7.74 km/h, while females averaged 7.09 km/h. In the 50-mile races, males averaged about 7.25 km/h, compared to 6.83 km/h for females.
2. Athletes in their late 20s and early 30s exhibit the best performance in the 50 m races.
3. Athletes in their late 50s and early 60s show the lowest performance levels in the 50 mi races.
4. Racers generally perform slower in the summer, with an average speed of 6.86 km/h, compared to a faster average speed of 7.52 km/h in the winter.

### Limitations
The analysis was constrained by the quality and completeness of the available data. Missing and incomplete data entries were removed, which may have impacted the results.
