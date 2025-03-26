# Sarah Cook - Data Science Portfolio
# 👋 Hi, I'm Sarah!

I'm a data enthusiast with a background in Neuroscience and Economics, currently expanding my toolkit with a certificate in Data Analytics Fundamentals. With hands-on experience as a Teaching Assistant for a SQL Databases course and a growing portfolio of projects in Python, SQL, and C++, I love turning complex data into clean, insightful stories.

I bring together analytical depth from my science background and real-world application through roles in education, investment research, and tech recruiting. Whether I’m designing fantasy Survivor databases (yes, really!) or writing functions in C++ to reverse-engineer strings, I’m motivated by solving interesting problems and making sense of messy data.

---

## 🧠 Background Snapshot
- 🎓 Neuroscience & Economics @ Tulane University  
- 📊 Data Analytics Certificate @ City College of San Francisco (Dec 2024)
- 🎓 Teaching Assistant for SQL Databases & MySQL Programming
- 🔬 Lab assistant in neuroscience research, investment intern, and education professional
- 🧰 Tools: Python, C++, SQL, Tableau, Java, Stata

---

## 📁 What You'll Find in This Repository

This GitHub serves as a hub to showcase my projects, track my learning, and share examples of how I apply data tools to real-world questions. Projects range from classroom-inspired work to independent explorations — like building a fantasy Survivor schema with relational SQL tables.

---

## 📬 Let's Connect
- 💼 [LinkedIn](https://www.linkedin.com/in/SarahAnneCook)
- 📫 scook5@tulane.edu
# Stata

## Smoking Regression Analysis (BRFSS 2015 - Louisiana)

This project uses Behavioral Risk Factor Surveillance System (BRFSS) 2015 data for Louisiana to explore correlations between smoking and variables such as sex, marital status, and binge drinking behavior.

## Tools
- Stata for variable generation, regression analysis, and heteroskedasticity tests

## Key Findings
- Women are ~2.9% less likely to smoke than men.
- Married individuals are ~4.6% less likely to smoke than those never married.
- Binge drinkers show a slight negative correlation with smoking (~1.76%).

Both Breusch-Pagan and White tests indicate evidence of heteroskedasticity in initial models, which was reduced in models replacing `sex` with `pregnant`.

## File
- `smoking_regression_analysis.do`: Full Stata script including regression modeling and interpretation.

