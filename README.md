
## 👋 Hi, I'm Sarah!

I'm a data enthusiast with a background in Neuroscience and Economics and a certificate in Data Analytics Fundamentals from City College of San Francisco. I enjoy using data to explore human behavior, uncover patterns, and turn complex information into meaningful insights.

My experience spans education, neuroscience research, and investment research. As a Teaching Assistant for courses in SQL, data visualization, and Foundations of Data Science, I've helped students develop their programming, analytical, and problem-solving skills. My work as a preschool teacher has also strengthened my interest in how data can inform decisions that support students and educators.

Whether I'm analyzing student experiences using national survey data or designing a database for a fantasy Survivor season (yes, really!), I'm motivated by asking interesting questions, working through messy data, and communicating what I discover.

---

## 🧠 Background Snapshot

- 🎓 **Education:** B.S. in Neuroscience & Economics, Tulane University
- 📊 **Certificate:** Data Analytics Fundamentals, City College of San Francisco (Dec 2024)
- 💻 **Teaching Assistant:** SQL Databases, MySQL Programming, Data Visualization, and Foundations of Data Science
- 🔬 **Professional experience:** Preschool education, neuroscience research, and investment research
- 🧰 **Technical skills:** Python, SQL, Tableau, Stata, Java, C++
- 📈 **Analytical skills:** Data cleaning, exploratory analysis, data visualization, statistical hypothesis testing, and database design

---

## 📁 What You'll Find in This Repository

This GitHub serves as a hub to showcase my projects, track my learning, and share examples of how I apply data tools to real-world questions. Projects range from classroom-inspired work to independent explorations.

---

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

