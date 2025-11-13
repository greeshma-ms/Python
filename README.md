#**Business-Case-Yulu-Hypothesis-Testing**(H1) <br>

Welcome to the Yulu Hypothesis Testing project! 🇮🇳

Yulu is India's leading micro-mobility service provider, committed to eliminating traffic congestion by offering unique shared electric cycles for daily commutes.<br>
**About Yulu �**�<br>
Yulu operates in key locations, including metro stations, bus stands, office spaces, residential areas, and corporate offices, to make commuting smooth, affordable, and sustainable. 🏙️🏢
<br>
Recently, Yulu has faced challenges with its revenues, and they've partnered with a consulting company to understand the factors influencing the demand for shared electric cycles in the Indian market. This project aims to uncover these insights. 📉📈 <br>
**How You Can Help 🤝** <br>
Yulu is eager to find out:<br>

Which variables significantly predict the demand for shared electric cycles in the Indian market?<br>
How well these variables describe the electric cycle demand?<br>
**Dataset 📊**
Column Profiling:
datetime: Date and time
season: Season (1: spring, 2: summer, 3: fall, 4: winter)
holiday: Whether it's a holiday or not
workingday: If it's a working day (1) or not (0)
weather:
Clear, Few clouds, partly cloudy
Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
temp: Temperature in Celsius
atemp: Feeling temperature in Celsius
humidity: Humidity
**Concepts Used 📚**
Bi-Variate Analysis
2-sample t-test: Testing for differences across populations
ANOVA
Chi-square
**How to Begin �**�
windspeed: Wind speed
Import the dataset and perform exploratory data analysis to understand its structure and characteristics.

Establish relationships between the dependent variable, "Count," and independent variables like Workingday, Weather, Season, etc.

Select an appropriate test to determine:

If Working Day affects the number of electric cycles rented.
Whether the number of cycles rented differs in different seasons.
Whether the number of cycles rented differs under different weather conditions.
If weather is dependent on the season.
Set up Null Hypothesis (H0).

State the alternate hypothesis (H1).

Check assumptions of the test (Normality, Equal Variance). Use tools like histograms, Q-Q plots, or statistical methods like Levene’s test and Shapiro-Wilk test (optional).

Continue with the analysis even if some assumptions fail. Double-check using visual analysis and report wherever necessary.

Set a significance level (alpha).

Calculate test statistics.

Make a decision to accept or reject the null hypothesis.

Draw meaningful inferences from the analysis.

Let's work together to help Yulu make data-driven decisions and improve their micro-mobility services! 🚴‍♀️🔍💡

Feel free to contribute, collaborate, and create insights for Yulu's success! 🌟📈

Happy analyzing! 📊📚🛴👩‍💼👨‍💼
casual: Count of casual users
registered: Count of registered users
count: Count of total rental bikes, including casual and registered users
