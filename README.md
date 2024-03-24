<a name="readme-top"></a>

<div align="center">
  <h1><b>Indian Startup Ecosystem : Funding Trends 2018-2021</b></h1>
</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- Overview
- [🛠 Built With ](#-built-with-)
- [Tech Stack ](#tech-stack-)
- Packages and Libraries
- Cleaning The Data
- Exploratory Data Analysis
- Visualizations
- Analysis
- Findings
- [Key Insights ](#key-insights-)
- [💻 Getting Started ](#-getting-started-)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Install](#install)
- [Usage](#usage)
- [👥 Authors ](#-authors-)
- [🔭 Future Features ](#-future-features-)
- [🤝 Contributing ](#-contributing-)
- [⭐️ Show your support ](#️-show-your-support-)
- [🙏 Acknowledgments ](#-acknowledgments-)
- [📝 License ](#-license-)

<!-- PROJECT DESCRIPTION -->

# Indian Startup Ecosystem : Funding Trends 2018-2021 <a name="about-project"></a>

## Overview 

India's startup ecosystem has experienced rapid growth, adding over 16,000 new tech companies in 2020. Despite funding challenges, Indian startups secured $8.4 billion in funding in 2023, showcasing investor confidence. The ecosystem boasts 99,000 startups and 108 unicorns valued at $340.80 billion, ranking third globally.

Key drivers of this growth include government support, access to capital, a robust talent pool, and a supportive entrepreneurial culture. India's focus on fostering entrepreneurship has been instrumental in its rise as a major player in the global startup landscape, with Silicon Valley maintaining its top position.

## Data Sources 📊
- The dataset is provided in CSV format for transparency and reproducibility.
- Statistics on Indian startup funding from 2018 to 2021.

## Topical Questions and Hypotheses
#### Questions 🤔:

- What was the average funding amount in 2018 compared to 2019?
- What was the average funding amount in 2020 compared to 2021?
- How has the funding trend evolved from 2018 to 2021?
- Which startup received the highest average funding?
- What are the top 10 cities with the highest number of start-ups?
- What are the top 10 cities that attract the most start-up funding?
- What are the top 10 sectors attracting the most start-up funding?
- How has the funding trend been for different sectors over the years?
- Which stage is predominant among start-ups?
- Which startup stage received the most funding?
- How has the funding trend evolved for different stages over the years?

### Hypotheses 🔬:
#### A significance level (α) of 5% will used to perform all the hypothesis testing

- Bengaluru's start-ups receive funding equal to or greater than those in New Delhi.
- Fintech companies receive funding exceeding or equal to the average funding.
- The funding received in 2020 is no greater than the funding in 2021.
- Funding received in 2018 equals or exceeds that of 2019.
- Companies aged 5 years or more receive funding equal to or less than the average amount


### Features
1. **Founders**: Name of the Company founders or owners
2. **Founded**: The year the company began 
3. **Stage**: The investment stage at which the funding was received 
4. **Amount**: The amount of money received by the companies from the investors 
5. **Sector**: The Sectors in which different companies are classified based on their services or functions;
6. **AboutCompany**: What the company is about and what they do
7. **Location**: Different cities where the startups are located;
8. **Year**: The year the company received funding;




## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>





<details>
<summary>Language</summary>
  <ul>
    <li><a href="https://www.python.org/">Python</a></li>
  </ul>
</details>


<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.microsoft.com/en-us/sql-server">SQL</a></li>
  </ul>
</details>

<details>
<summary>Libraries</summary>
  <ul>
    <li><a href="https://pandas.pydata.org/">Pandas</a></li>
  </ul>
</details>

## Packages and Libraries 📚
#### Collection of significant Python Libraries:
- Pandas
- Numpy
- Seaborn
- Scipy
- Matplotlib
- Pyodbc
- Dotenv

## Cleaning the Data 🧹
#### We begin by thoroughly cleaning our data.
- Replacing any missing values
- Eliminating duplicates
- Organizing columns

## Exploratory Data Analysis 🕵



- Univariate Analysis
  
  ![image](https://github.com/Koanim/Team-Lawrencium-Indian--startup-funding-Analysis-from-2018-to-2021/assets/87522676/a70a3b7f-5ce0-4f52-8386-0bfdda76779c)

  
- Bivariate Analysis





## Visualizations 👀

- Line Chart 📈
- Bar chart 📊
- Swarm Plot ◼▪◾

## Analysis 🔍
- Utilizing Python and data analysis libraries such as Pandas, Matplotlib, and Seaborn, we performed exploratory data analysis (EDA) to uncover trends and insights.
- We analyzed funding trends by year, sector-wise funding distribution, top investors, geographical distribution, and funding rounds.

## Findings 📈
- Indian startup funding has shown significant growth from 2018 to 2021, with notable peaks in certain sectors.
- The analysis reveals key sectors attracting major investments and identifies top investors contributing to the startup ecosystem.

## Key Files 📂
- `LP1_Lawrencium _project.ipynb`: Jupyter Notebook containing the code for data cleaning, EDA, and visualization.
- `startup_funding_data.csv`: Raw data used for analysis.
- `README.md`: This file providing an overview of the project.



<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- Features -->

## Key Insights <a name="key-features"></a>

- **A dataset which analyzed the Indian startup ecosystem from 2018-2021**
- **Insights on the funding trends**
- **Insights on Amount in circulation from 2018-2021**
- **Sampling Techniques, Inferences, and Hypothesis tests on location and year for differences**


<p align="right">(<a href="#readme-top">back to top</a>)</p>



![image](https://raw.githubusercontent.com/Koanim/Team-Lawrencium-Indian--startup-funding-Analysis-from-2018-to-2021/27fa53558e249dc650bb404ee9c6ba3610a18d23/exploratoty%20data.JPG
![Exploratory Data Visualization](https://raw.githubusercontent.com/koanim/Team-Lawrencium-Indian--startup-funding-Analysis-from-2018-to-2021/branch/exploratory_data_viz.png)






<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Python


### Setup

Clone this repository to your desired folder:


```sh
  cd my-folder
  git clone hhttps://github.com/Koanim/Team-Lawrencium-Indian--startup-funding-Analysis-from-2018-to-2021
```

Change into the cloned repository

```sh
  cd Team-Lawrencium-Indian--startup-funding-Analysis-from-2018-to-2021
  
```

Create a virtual environment

```sh

python -m venv env

```

Activate the virtual environment

```sh
    env/Scripts/activate
```


### Install

Here, you need to recursively install the packages in the `requirements.txt` file using the command below 

```sh
   pip install -r requirements.txt
```



<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

🕵🏽‍♀️ **Victor Anim**                                   
🕵🏽‍♀️ **Aluko Oluwadamilola**                        [GitHub Profile](https://github.com/damzking?tab=repositories)
🕵🏽‍♀️ **Aminu Oluwarotimi Desmond**
🕵🏽‍♀️ **Nana Kwame Frimpong Baah**
🕵🏽‍♀️ **Leticia Blay**
🕵🏽‍♀️ **Richmond Tetteh**




<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project kindly show some love, give it a 🌟 **STAR** 🌟

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

We acknowledge the following persons for their coaching and support

Violette Naa Adoley Allotey
Racheal Appiah-Kubi
Israel Anaba Ayamga

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


