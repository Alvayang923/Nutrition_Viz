全球饮食与健康的数据可视化 Data Visualization for Nutritional Intake & Health
=============


数据可视化结果见：https://rpubs.com/HuanSunGo/898408

The final output is published in: https://rpubs.com/HuanSunGo/898408

#### Contributors
- [Renfang Yang](https://github.com/Alvayang923): ry2403@columbia.edu
- [Huan Sun](https://github.com/HuanSunGo): hs3240@columbia.edu
- [Yixuan Li](https://github.com/yixuan-li-727): yl4564@columbia.edu

简介
------------

人如其食，饮食对我们的健康有密不可分的影响。通过该项目，我们旨在检验这一假设，通过数据可视化方式，研究全球范围内营养成分摄入与预期寿命、癌症发病率间的关系。

我们的研究问题包括：
#### 1. 饮食结构：
- 在Twitter中，人们对饮食结构有怎样的讨论？
- 全球范围内，营养摄入量随时间如何变化？
- 不同国家、地区和性别的饮食结构有何不同？是否随时间发生变化？

#### 2. 营养摄入和预期寿命：
- 全球预期寿命如何分布？
- 是否一些特定国家、地区或性别的人更可能拥有较高的的预期寿命？
- 营养摄入和预期寿命之间是否存在相关性？

#### 3. 营养摄入和癌症发病率：
- 全球癌症发病率分布如何？
- 来自某些国家、地区或性别的人是否更有可能患上癌症？
- 营养摄入与癌症发病率之间是否存在相关性？

 通过解答上述问题，我们希望能为公共健康营养领域带来更多思考。

涉及技术
------------
- ggplot2
- 空间数据可视化
- 文本挖掘

数据源
------------
- 全球膳食数据库：https://www.globaldietarydatabase.org/

变量：食物类型、摄入量、年份、国家、年龄、性别、居住地、教育水平

- 全球癌症观察：https://gco.iarc.fr/
- 世界银行：https://data.worldbank.org/indicator/SP.DYN.LE00.IN
- Twitter API：最近7天内关于 **#nutritional** 的推文

可视化方式
------------
- **词云图：** Twitter中谈论 **#nutritional** 的词云
- **箱线图：** 可视化全球各类食物的平均每日摄入量
- **条形图：** 将全球分性别日均饮食摄入量、9个国家饮食结构变化（1990年 vs 2018年）、中国城乡饮食结构变化（1990年 vs 2018年）可视化
- **折线图：** 将1990-2018年全球饮食摄入量变化、中国精制谷物与非淀粉类蔬菜摄入量的性别间变化、各大洲精制谷物与非淀粉类蔬菜摄入量变化可视化
- **地图** 全球精制谷物摄入、非淀粉类蔬菜摄入、预期寿命和癌症发病率的地域分布
- **回归点线图：** 将饮食摄入量与预期寿命、癌症发病率间相关性可视化








Abstract
------------
There’s a saying that what we eat determines what we are. Intuitively, diet directly affects health. And we aim to test this hypothesis and study the effect of nutrition on life expectancy and cancer rate in this project. To be more specific, our research questions include:
#### 1. Dietary Structure:
- What's the people's overall impression on dietary structure in twitter? 
- How does the nutrition intake change across the world changes in relation to time?
- How does the dietary structure vary for different countries, area, and sex?
- Did dietary structures change over time in country, area, sex level?
#### 2. Food Intake & Life Expectancy:
- How's the distribution of life expectancy in the world?
- Do people from certain countries, area, or sex more likely to have longer life expectancy?
- Is there a correlation between the dietary structure and life expectancy?
#### 3. Food Intake & Cancer Rate:
- How's the distribution of cancer rate in the world?
- Do people from certain countries, area, or sex more likely to have higher cancer rate?
- Is there a correlation between the dietary structure and cancer rate?
By answering these questions, we hope to give some insights into medical research, health institutions, the public health sector, and relevant businesses.

Techniques
------------
- ggplot2
- Spatial data techniques
- Text mining techniques

Data Source
------------
- Global Dietary Database: https://www.globaldietarydatabase.org/
Variables: Type of food, Intake, Year, Country, Age, Sex, Residence, Education level
- Global Cancer Observation: https://gco.iarc.fr/
- the World Bank (life expectancy): https://data.worldbank.org/indicator/SP.DYN.LE00.IN
- Twitter API: scrapped tweets under **#nutritional** within the recent 7 days

Visualization
------------
- **Word Cloud:** Created a word cloud of the tweets talking about **#nutritional**
- **Box Plot:** Visualized average daily intake for each type of food in the world
- **Bar Chart:** Visualized average daily food intake by gender worldwide, changes of dietary structure (1990 vs 2018) in 9 countries, and changes of dietary structure (1990 vs 2018) in rural and urban China
- **Line Chart:** Visualized food intake changes worldwide, changes of refined grains and non-starchy vegetables intake by gender in China, and changes of refined grains and non-starchy vegetables intake by super regions between 1990 and 2018
- **Map:** Visualized the distribution of refined grains intake, non-starchy vegetables intake, life expectancy and cancer rate distribution in the world.
- **Point Chart with Linear Regression Result:** Visualized the correlation between 6 types of food intake and life expectancy and the correlation between the same type of food intake and cancer rate








