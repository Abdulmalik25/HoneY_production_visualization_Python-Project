# HoneY_production_visualization_Python-Project
Uncovered the secrets of honey production in the U.S. using Python! Delve into the fascinating world of honeybees and agriculture with stunning visuals! Be amazed by the insights into America's honey industry and its global impact! Let's embark on a sweet journey of discovery

### Tech Stack Used
<img src="https://github.com/Abdulmalik25/Exploratory_Data_analysis_on_Youtube_Data--Python-project/assets/153974173/26b1b5f7-dd6e-498a-9c74-fbeba755a29d" alt="jupyter-notebook" width="250" height="250">

# Data Visualization on Honey Production dataset using seaborn and matplotlib libraries.

## Domain: Food and Agriculture

### Context:
In 2006, a global concern was raised over the rapid decline in the honeybee population, an integral component to American honey agriculture. Large numbers of hives were lost to “Colony-Collapse-Disorder”, a phenomenon of disappearing “worker-bees” causing the remaining “hive-colony” to collapse. Speculation around the cause of this disorder points to hive-diseases and pesticides harming the pollinators, though no overall consensus has been reached. Twelve years later, some industries are observing recovery but the American honey industry is still largely struggling. The U.S. used to locally produce over half the honey it consumes per year. Now, honey mostly comes from overseas, with 350 of the 400 million pounds of honey consumed every year originating from imports. This dataset provides insight into honey production supply and demand in America by state from 1998 to 2012.

### Objective:
The goal is to use Python visualization libraries such as seaborn and matplotlib to investigate the data and get some useful conclusions.

### Attribute Information
| Slno. | Attribute     | Description                                                           |
|-------|---------------|-----------------------------------------------------------------------|
| 1.    | numcol        | Number of honey producing colonies.                                   |
| 2.    | yield percol  | Honey yield per colony. (Unit is pounds)                              |
| 3.    | total prod    | Total production (numcol x yieldpercol). (Unit is pounds)             |
| 4.    | price per lb  | Refers to average price per pound based on expanded sales. Unit is dollars. |
| 5.    | prodvalue     | Value of production (total prod x priceperlb). Unit is dollars.        |
| 6.    | Stocks        | Refers to stocks held by producers. Unit is pounds                    |
| 7.    | Year          | Calendar year.                                                        |
| 8.    | State         | Different states' names.                                              |


### Some Visual Insights: Charts Illustrating Data Context and Insights


#### 1. Pie chart Explaining the percentange distribution of data in each year.

![download](https://github.com/Abdulmalik25/HoneY_production_visualization_Python-Project/assets/153974173/568385cd-bf16-4d25-942d-663cc4197948)

#### 2. Displot Explaining the dirstibution of Average price per pound of Honey each year.

![download (1)](https://github.com/Abdulmalik25/HoneY_production_visualization_Python-Project/assets/153974173/4f32f3f2-623a-4d00-9a3c-0a3672787da9)

#### 3. Scatterplot Explaining the relationship between Number of Honey Producing Colonies vs Value of production in dollars.

![download (2)](https://github.com/Abdulmalik25/HoneY_production_visualization_Python-Project/assets/153974173/8b8e6491-d699-40ef-8a12-1eb988028f1c)

#### 4. Boxplot explaining the variation value of production of honey over years.

![download (3)](https://github.com/Abdulmalik25/HoneY_production_visualization_Python-Project/assets/153974173/ee1811bf-6b47-4cfd-9384-4e31209d606a)

#### 5. Pairplot describing the relationship between the multiple pairs of variables throughout different years  with columns 'numcol', 'yield percol', 'total prod', 'prodvalue','year'.

![download (4)](https://github.com/Abdulmalik25/HoneY_production_visualization_Python-Project/assets/153974173/95023a64-1dda-40c2-8cdc-3bd43b4bf1b0)

#### 6. Heatmap showing the correlation between all the numerical varibales of the dataset.

![download (5)](https://github.com/Abdulmalik25/HoneY_production_visualization_Python-Project/assets/153974173/6cbf181b-ab80-4aa4-979e-6d487b75d40d)

