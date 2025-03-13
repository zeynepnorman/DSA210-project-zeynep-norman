# DSA210 Project Proposal by Zeynep Norman
# How does increasing immigration to Europe influence the rise of nationalist parties?

## Project Idea
In this project, I aim to find whether recent increases of immigration to Europe affected the rise of nationalism in the region. To investigate the relationship between immigrants and nationalism, I will work with immigration data from EU countries, and vote share data of each EU country’s nationalist party. 

---

## Constructing the Hypothesis
**Null Hypothesis (H₀):** There is no relationship between recent increasing immigration to EU countries and increasing vote shares of nationalist parties in those countries.

**Alternative Hypothesis (H₁):** There is a causal relationship between recent increasing immigration to EU countries and increasing vote shares of nationalist parties in those countries. Rise of nationalism is connected to rise of immigrants in Europe. 

---

## Project Plan

**Collection and Measurment of Immigration Data**

To measure immigration, I will use annual crude rate of net migration to Europe ((number of immigrants – migrants) / population). I decided to use ratio values rather than actual numbers to eliminate biases such as global population increase that affects both number of immigrants and number of votes of each party. When searching for immigration rates of each country, I plan to use “Population change - Demographic balance and crude rates at national level” data, provided by official site of EU, Eurostat.  https://ec.europa.eu/eurostat/databrowser/view/demo_gind/default/table?lang=en 


**Collection and Measurment of Nationalism Data**

To measure nationalism, I will use each country’s most recent and most popular nationalist party’s vote shares from at least two recent elections. Then I will show the increase of nationalism by comparing each nationalist party’s vote shares at the last and previous elections that they participated in. When searching for parties and vote shares, I plan to use official election authority websites of the respective countries, pull data from researches on relevant topics, and use databases created for research purposes. (e.g  https://parlgov.fly.dev/ )


**Methodology** 

In the project, I plan to work with scikit learn, pytorch, xgboost, BeautifulSoup tools. At the first instance, I am planning to construct a linear regression model between immigration and nationalism data. Aim of this regression is to prevail how strongly does increasing immigration affects rise of nationalist party vote shares in EU countries. Along with the process of the project and further findings, I may work with time series models or decision tree models too. After finding my results, as an extra research topic in the project, I plan to use my findings to estimate vote shares of nationalist parties in an imaginary upcoming election (e.g 2025 December election), based on found relationship between nationalism-immigration, again by using linear regression. 


**Further Data Analysis**

To minimize measurement errors and to make my argument more accurate, I plan to search for data on economic and demographic indicators and use them as control variables in my model. To ensure balanced representation, I will try to include more regional (city and state level) data on project-based topics too, additional to country-based data.

