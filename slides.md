---
marp: true
---

<!-- _backgroundColor: aqua -->

![bg right 100% Data Analytics in Baseball Today](./baseball-analytics.png)


# **STEMTeach 2025 Spring Mentor Day**

## Data Analytics & Sports

---

# Data Analytics

<details>
<summary>What is it?</summary>

- **Definition:** Data analytics involves examining datasets to draw conclusions about the information they contain. It uses various techniques to uncover patterns, correlations, and trends.

- **Relevance:** In today's data-driven world, the ability to analyze and interpret data is a crucial skill across various fields, including education, business, healthcare, and sports.

</details>

---

# Recognizing Patterns

- **Decision-Making:** Identifying patterns in data helps make informed decisions. For example, in sports, recognizing performance trends can guide player selection, game strategies, and training focus.

- **Predictive Power:** Patterns can reveal insights about future outcomes. By understanding historical data, we can make predictions and prepare for potential scenarios.

- **Efficiency:** Recognizing patterns allows for more efficient problem-solving. Instead of addressing issues on a case-by-case basis, we can apply solutions that have worked in similar situations.

---

# Real-World Applications

<details><summary>Sports</summary>

> Teams use data analytics to evaluate player performance, develop game strategies, and enhance training programs. For instance, analyzing batting averages and on-base percentages can help identify key players.
</details>

<details><summary>Business</summary>

> Companies analyze consumer data to understand buying behaviors, optimize marketing campaigns, and improve customer satisfaction. Recognizing sales patterns can drive business growth.
</details>

<details><summary>Education</summary> 

> Educators can use data to track student progress, identify learning gaps, and tailor instruction to meet individual needs. Recognizing patterns in student performance data can lead to more effective teaching strategies.
</details>

---

# Today's Plan

<details>
<summary>

## CODAP
</summary>

https://codap.concord.org/

- Free, web-based data analysis and visualization tool developed by the Concord Consortium. 
- Designed to support students in grades 5-12 in learning and doing data science.
</details>

<details>
<summary>

## Baseball
What data is collected?
</summary>

[Lahman Baseball Database (seanlahman.com)](http://seanlahman.com/)

- Relatable, real-world, and fun context
- Interactive, hands-on activity
- Skill development
    - Critical thinking and analytical skills for students.
    - [Meta] Enhance educators' ability to assess student performance and improve instructional methods.

</details>

---
![bg right:35% fit](./codap-1.png)

# Let's Go!

- Visit https://codap.concord.org/ 
    - Click ***Launch CODAP***
    - ***Create a new Document***
    - From the menu, "***Import...***" 
        - Click "***URL***" 
        - Enter:

***https://cs.berry.edu/stemteach-s25/teams.csv***


---

# Data Table & Schema

[Teams Table Schema handout](./teams-schema.pdf)

- How many rows are there?
- What range of years is in the data?
- Sort by "rank" (ascending); then "year" (descending)
- Explore...

---

# Graph

![bg right fit](./codap-2-graph.png)

<details>
<summary>How many World Series winners are there?</summary>

- Add "WSWin" to the "X"
- Click the ruler - Show... "Count"
</details>

<details>
<summary>Is there a correlation between runs scored and number of wins?</summary>

- Add "R" to the x-axis (bottom)
- Add "W" to the y-axis (left)
</details>

<details>
<summary>Has the trend changed over time?</summary>

- Drag the "yearId" column header from the table onto the main graph area.
- Anything interesting?
</details>

<details>
<summary>"Best fit" line</summary>

- Click the ruler --> choose "Least Squares Line"
</details>

---

# Discuss - Explore - Share

- Brainstorm questions you could ask about the data 
    - Refer to the table schema

- Make a graph in CODAP to explore those questions

- Share: what do you find?

---

# Analytics Process

![](./analytics-process.png)

> https://medium.com/codex/life-cycle-of-a-data-analytics-project-954d0e6926fe

