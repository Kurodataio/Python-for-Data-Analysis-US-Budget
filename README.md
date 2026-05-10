# Python-for-Data-Analysis-US-Budget
This project explors how U.S. federal spending changed from 1962 to 2018. 

[Notebook Link](https://github.com/Kurodataio/Python-for-Data-Analysis-US-Budget/blob/main/Practical_Activity-US_Budget.ipynb)  


---

## Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Analysis & Visualizations](#analysis--visualizations)  
- [Conclusion](#conclusion)  
- [Credits](#credits)  
- [License](#license)  

---

## Overview

- How has the U.S. federal spending changed from 1962 to 2018?
- How have how priorities shifted over time?

---

## Dataset

- Source of the dataset is **'us_budget.csv'** and sourced from ITOnlinelearning/Datawars
- The dataset has **1710 rows and 6 columns/features**
- The dataset covers the period 1962 to 2018
- Key features/columns are Department, Year, President, Budget in $ and Budget (Inflation Adjusted) in $
- The dataset has been pre-processed already

---

<h2>Technologies Used</h2>

<ul>
  <li><strong>Languages & Libraries:</strong> Python, Pandas, NumPy, Matplotlib</li>
  <li><strong>Tools:</strong> Jupyter Notebook, VS Code, Git, GitHub</li>
</ul>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib">

</p>

<P>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code"/>  
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</p>
<p>
  <img src="https://img.shields.io/badge/MIT%20License-000000?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="MIT License">

</p>

---

## Installation

Step-by-step instructions to set up the project locally:

```bash

# Clone the repository
git clone https://github.com/Kurodataio/Python-for-Data-Analysis-US-Budget.git

# Navigate to the project folder
cd Python-for-Data-Analysis-US-Budget

# Launch Jupyter Notebook
jupyter notebook


```

## Usage

Instructions for using the project:

1. Open the main notebook (`Practical_Activity-US_Budget`)  
2. Run each cell sequentially to reproduce the analysis  
3. Visualizations and results will be generated automatically  


---

## Analysis & Visualizations 

- The US budget has been increasing from 1962 through to 2018.

![Inflation Adjusted Budget Dollars by Fiscal Year](images/Inflation_Adjusted_Budget_Dollars_by_Fiscal_Year.png)

- In 1962 under John F. Kennedy, the Department of Defense had the highest budget
- In 2018 under Donald Trump, the Department of Defense still had the highest budget
- Of the top 5 funded departments, the Department of Defense was still the biggest funded in 1962 and 2018.
![Top 5 U.S. Departments by Budget Allocation in 1962](images/Top_5_US_Departments_by_Budget_Allocation_in_1962.png)

- Between the Excutive, Legislative and Judicial branches, the judicial has had the biggest share of the federal budget at 50.3%

![Proportion of Total Federal Budget Allocated to Branches](images/Proportion_of_Total_Federal_Budget_Allocated_to_Branches.png)


<!-- ![Proportion of Department of Defense vs. Other Departments (1962-2018)](images/Proportion_Departments-1962-2018.png)
 -->

The data shows increasing numbers of departments such as Homeland Security contributing to the nominal and inflation adjusted budgets. 
![Proportion of Each Department\'s Budget Relative to Total Budget](images/Proportion_of_Depart_Budget_Relative_Total_Budget.png)

Between 1962 to 2018, Barack Obama, George W. Bush and Bill CLinton had the highest budgets. The caveat is that all three served 2 terms, so it is a cumulative total.
![Which President Had the Largest Inflation-Adjusted Budget?](images/President_Largest_Budget.png)

Some departments such as the Department of Agriculture show no long term trends. Increases or decreases in budget are linked to each presidents policy or reaction to events.
![Percentage Change in Inflation-Adjusted Budget for the Department of Agriculture by President](images/Percentage_Change_Dept_Agriculture_by_President.png)


---

## Conclusion 

- The data shows that even as the federal budget increases, the Department of Defense has maintained the largest singular departmental funding. This funding has been immune to partisan or elected presidents

- There is a difference between nominal growth vs real growth. Once we adjust for inflation the apparent continual nominal rise chnages. There are slower periods of growth and peaks which ay be attributed to policy actions.

- The data and visuaizations are warnings that using nominal values without adjusting for inflation can be misleading. 

- The data does not give the historical, political and social context that drive it. Deeper insight will require further context and research.

---

## Credits

- **Tutorials / References:** Datawars/ITOnlinelearning.com 
- **Dataset Source:** Datawars/ITOnlinelearning.com 

---

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).  

---
