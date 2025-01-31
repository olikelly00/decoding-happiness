# 🌍 Decoding Happiness: an analysis of global happiness trends in 2019

## 📌 Overview  
This mini-project explores global happiness trends in 2019, using data on happiness scores and their relationship with key socio-economic factors. The dataset includes numerical metrics for each country, along with categorical information such as country names and continents (which I later joined to the dataset).  

## 📊 Dataset Features  
The dataset contains the following columns:  
- Overall Rank (int, discrete)
- Country Name (string, discrete)  
- Happiness Score (float, continuous)
- GDP per Capita float, continuous
- Social Support (float, continuous)
- Healthy Life Expectancy (float, continuous)
- Freedom to Make Life Choices (float, continuous)
- Generosity (float, continuous)
- Perceptions of Corruption (float, continuous)
- *[subsequently added]* Continent (string, discrete)


---


## 🎯 Project Goals  
This project was intended to learn the fundamentals of:  
- **Pandas** 🐼 → For data parsing, manipulation, and cleaning  
- **Matplotlib** 📊 → For visualising trends and distributions  
- **Scikit-learn** 🤖 → For building simple **machine learning models** to make predictions  

I approached this analysis through a set of **exploratory** and **predictive** research questions, listed below  


---


## 🔍 Exploratory Data Analysis (EDA)  
*Descriptive insights into happiness scores and their influencing factors.*

1️⃣ Which country had the highest and lowest happiness scores in 2019?

2️⃣ What is the average happiness score across all countries?

3️⃣ Which factors have the highest correlation with happiness score?

4️⃣ Which continent has the highest average happiness score?

5️⃣ Which countries have the highest and lowest social support?

6️⃣ How does GDP per capita vary across countries?

7️⃣ Is there a relationship between corruption perception and happiness?

8️⃣ Which country has the highest combination of GDP per capita and social support?

9️⃣ Which two factors combined have the strongest correlation with happiness score?

🔟 Does the impact of GDP on happiness differ between high-social-support and low-social-support countries?

1️⃣1️⃣ Does generosity play a larger role in happiness in wealthier or poorer countries?

1️⃣2️⃣ Do countries with high corruption perception have lower happiness scores, even if they have high GDP per capita?  


---


## 🤖 Predictive Analysis  
*Building models to understand key drivers of happiness.*

1️⃣ Can we predict whether a country is above or below the median happiness score? 

2️⃣ What's the best single predictor of a country's happiness score?

3️⃣ Can we predict a country's continent based on its data?
