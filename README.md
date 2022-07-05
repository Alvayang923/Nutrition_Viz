# Group S: Nutrition Intake 

### Contacts
- Huan Sun: hs3240@columbia.edu
- Renfang Yang: ry2403@columbia.edu
- Yixuan Li: yl4564@columbia.edu

### Abstract
There’s a saying that what we eat determines what we are. Intuitively, diet directly affects health. And we aim to test this hypothesis and study the effect of nutrition on life expectancy and cancer rate in this project. To be more specific, our research questions include:
##### 1. Dietary Structure:
- What's the people's overall impression on dietary structure in twitter? 
- How does the nutrition intake change across the world changes in relation to time?
- How does the dietary structure vary for different countries, area, and sex?
- Did dietary structures change over time in country, area, sex level?
##### 2. Food Intake & Life Expectancy:
- How's the distribution of life expectancy in the world?
- Do people from certain countries, area, or sex more likely to have longer life expectancy?
- Is there a correlation between the dietary structure and life expectancy?
##### 3. Food Intake & Cancer Rate:
- How's the distribution of cancer rate in the world?
- Do people from certain countries, area, or sex more likely to have higher cancer rate?
- Is there a correlation between the dietary structure and cancer rate?
By answering these questions, we hope to give some insights into medical research, health institutions, the public health sector, and relevant businesses.

### Techniques
- ggplot2
- Spatial data techniques
- Text mining techniques

### Data Source
- Global Dietary Database: https://www.globaldietarydatabase.org/
Variables: Type of food, Intake, Year, Country, Age, Sex, Residence, Education level
- Global Cancer Observation: https://gco.iarc.fr/
- the World Bank (life expectancy): https://data.worldbank.org/indicator/SP.DYN.LE00.IN
- Twitter API: scrapped tweets under **#nutritional** within the recent 7 days

### Visualization
- **Word Cloud:** Created a word cloud of the tweets talking about **#nutritional**
- **Box Plot:** Visualized average daily intake for each type of food in the world
- **Bar Chart:** Visualized average daily food intake by gender worldwide, changes of dietary structure (1990 vs 2018) in 9 countries, and changes of dietary structure (1990 vs 2018) in rural and urban China
- **Line Chart:** Visualized food intake changes worldwide, changes of refined grains and non-starchy vegetables intake by gender in China, and changes of refined grains and non-starchy vegetables intake by super regions between 1990 and 2018
- **Map:** Visualized the distribution of refined grains intake, non-starchy vegetables intake, life expectancy and cancer rate distribution in the world.
- **Point Chart with Linear Regression Result:** Visualized the correlation between 6 types of food intake and life expectancy and the correlation between the same type of food intake and cancer rate








