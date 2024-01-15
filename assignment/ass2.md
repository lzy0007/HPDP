<a href="https://github.com/drshahizan/HPDP/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/HPDP" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/HPDP/network/members"><img src="https://img.shields.io/github/forks/drshahizan/HPDP" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/HPDP/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/HPDP" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/HPDP/issues"><img src="https://img.shields.io/github/issues/drshahizan/HPDP" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/HPDP/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/HPDP?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2FHPDP&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

🌟 Hit star button to save this repo in your profile

# Assignment 2: Exploratory Data Analysis

<p align="left">
<img src="https://editor.analyticsvidhya.com/uploads/61798ti2.png"  height="300" />
</p>

An Exploratory Data Analysis (EDA) assignment is a task given to students or data analysts to explore and understand a dataset before performing more advanced statistical or machine learning analyses. EDA is a critical initial step in the data analysis process, and it involves summarizing, visualizing, and making sense of the data to gain insights and identify patterns. Here's a description of what an EDA assignment typically involves:

1. **Data Collection**: The first step in EDA is to obtain the dataset. The dataset may be provided to students, or they may be required to source it from publicly available data repositories or collect their own data.

2. **Data Cleaning**: Before any analysis can begin, students need to clean the data. This involves handling missing values, removing duplicates, and addressing any outliers or anomalies in the data. This step ensures that the data is reliable and ready for analysis.

3. **Data Summary**: Students are usually asked to provide a summary of the dataset, which may include basic statistics such as mean, median, standard deviation, and percentiles for numerical variables. For categorical variables, they may list unique categories and their frequencies.

4. **Data Visualization**: Visualization is a key component of EDA. Students are typically required to create various plots and charts to visualize the data's distribution and relationships. This can include histograms, scatter plots, bar charts, box plots, and more.

5. **Correlation Analysis**: Students may need to explore the relationships between variables in the dataset. They can calculate correlation coefficients to identify potential associations between variables.

6. **Hypothesis Testing**: Some EDA assignments may involve testing hypotheses about the data. Students may need to conduct statistical tests to determine if certain assumptions or hypotheses hold true for the dataset.

7. **Pattern Identification**: EDA often focuses on identifying interesting patterns or trends within the data. Students may be asked to look for clusters, trends, or anomalies that can provide valuable insights.

8. **Narrative and Interpretation**: After conducting the above analyses, students are typically expected to write a narrative that explains their findings and interpretations. They should provide insights into what the data reveals and its potential implications.

9. **Visualization and Reporting**: Students may be asked to create a report or presentation summarizing their EDA process and findings. This report should include clear visualizations and well-structured explanations.

10. **Reproducibility**: EDA assignments often emphasize the importance of reproducibility. Students may be required to document their data cleaning, analysis, and visualization processes in a way that others can replicate their work.

11. **Challenges and Limitations**: Students may also be asked to discuss the challenges they encountered during the EDA process and the limitations of their analysis. This demonstrates critical thinking and a deeper understanding of the data.

EDA assignments are essential for developing data analysis skills and gaining a deeper understanding of a dataset's characteristics. They provide valuable insights that can inform further data-driven decision-making processes.

## 📚 Case Study 1

### Project Description

Your submission will be evaluated using the following criteria:

* Dataset must contain at least 5 columns and 10,000 rows of data
* You must ask and answer at least 10 questions about the dataset
* Your submission must include at least 10 visualizations (graphs)
* Your submission must include explanations using markdown cells, apart from the code.
* Your work must not be plagiarized i.e. copy-pasted from somewhere else.

Follow this step-by-step guide to work on your project.

### Step 1: Select a real-world dataset 

- The Malaysian dataset must be used for your case study.
- The dataset is available at:
  * [Portal Data Terbuka Malaysia](https://www.data.gov.my/data/ms_MY/dataset)
  * [Department of Statistics Malaysia](https://open.dosm.gov.my/)
  * [data.world](https://data.world/datasets/malaysia)
  * [Dataportal.asia](https://dataportal.asia/dataset?vocab_economy_names=Malaysia)
  * [knoema](https://knoema.com/atlas/Malaysia/datasets)
  * [The World Bank](https://data.worldbank.org/country/MY)
  * [Dataset Search - Google](https://datasetsearch.research.google.com/)
  * [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.php)
  * [Kaggle datasets](https://www.kaggle.com/datasets)
  * [Awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets)
  * [Datahub.io](https://datahub.io/collections)
  * [Earthdata](https://www.earthdata.nasa.gov/)
  * [CERN Open Data Portal](http://opendata.cern.ch/)

### Step 2: Perform data preparation & cleaning

- Load the dataset into a data frame using Pandas
- Explore the number of rows & columns, ranges of values etc.
- Handle missing, incorrect and invalid data
- Perform any additional steps (parsing dates, creating additional columns, merging multiple dataset etc.)

### Step 3: Perform exploratory analysis & visualization

- Compute the mean, sum, range and other interesting statistics for numeric columns
- Explore distributions of numeric columns using histograms etc.
- Explore relationship between columns using scatter plots, bar charts etc.
- Make a note of interesting insights from the exploratory analysis

### Step 4: Ask & answer questions about the data

- Ask at least 10 interesting questions about your dataset
- Answer the questions either by computing the results using Numpy/Pandas or by plotting graphs using Matplotlib/Seaborn
- Create new columns, merge multiple dataset and perform grouping/aggregation wherever necessary
- Wherever you're using a library function from Pandas/Numpy/Matplotlib etc. explain briefly what it does


### Step 5: Summarize your inferences & write a conclusion

- Write a summary of what you've learned from the analysis
- Include interesting insights and graphs from previous sections
- Share ideas for future work on the same topic using other relevant datasets
- Share links to resources you found useful during your analysis

### Step 6: Make a submission

- Upload your notebook to github.

## 📚 Case Study 2: Automated EDA Tools

In this case study, you will study two types of **Automated Exploratory Data Analysis (EDA) Tools**. You are required to choose two such tools and demonstrate how they can be implemented step by step using a **Malaysian dataset**. Additionally, you will summarize the **pros and cons** of the **Automated EDA Tools** used. Here are the instructions to guide you through this case study:

1. **Selecting Automated EDA Tools**:
   - Research and select two different **Automated EDA Tools** that you would like to study. These tools are designed to automate the process of data exploration and visualization.
   - Ensure that the selected tools are suitable for analyzing data from a **Malaysian dataset**.

2. **Malaysian Dataset**:
   - Choose an appropriate **Malaysian dataset** for this case study. It could be related to any domain or topic of your choice (e.g., healthcare, finance, demographics, etc.).

3. **Data Preparation**:
   - Collect and load the **Malaysian dataset** into a format compatible with the selected **EDA tools**.
   - Make sure the data is clean and ready for analysis. Perform data preprocessing tasks if necessary.

4. **Implementation of Automated EDA Tools**:
   - Provide a detailed step-by-step guide for implementing each of the selected **Automated EDA Tools**. Include screenshots and explanations where necessary.
   - Cover the following aspects for each tool:
     a. How to load the dataset into the tool.
     b. How to generate basic statistics and visualizations.
     c. How to explore relationships and patterns in the data.
     d. Any unique features or capabilities of each tool that you find noteworthy.

5. **Pros and Cons Analysis**:
   - After implementing both **EDA tools**, summarize the **pros and cons** of each tool based on your experience and observations. Consider factors such as ease of use, comprehensiveness, visualization capabilities, and any limitations.
   - Include your insights on how each tool performed in the context of the **Malaysian dataset** you chose.

6. **Conclusion**:
   - Conclude your case study by summarizing the key findings and insights from your analysis.
   - Provide recommendations or insights on when each tool may be more suitable or preferable based on the specific needs of EDA projects.

7. **References**:
   - Include a list of references and citations for any sources or documentation you used in your case study.

Ensure that your case study is well-organized, well-documented, and provides a clear understanding of how the selected **Automated EDA Tools** work and their applicability to **Malaysian datasets**. Use clear and concise language to convey your findings and conclusions.

### 2. Team Collaboration
🚀 Form project teams comprising a minimum of three and a maximum of four students. Teamwork is essential for this assignment. Please complete the Google Sheets page with your group information [**here**](https://docs.google.com/spreadsheets/d/1vLDgDAu2ai9rAOIKUfE1xUfTEvK2ikpXJ_1F-Xqtk_c/edit?pli=1#gid=834124190). Please update your group information:

| No | Group |  File | Dataset | EDA Tools 1 | EDA Tools 2 | EDA Tools 3 |
| -----: |  ------ | :-----: |  ----- |  ----- | ----- | ----- |
| 0. | Sample  |  <a href="submission/ass2/Sample/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> | 
| 1. | DEADPOOL | <a href="submission/ass2/DEADPOOL/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> |  
| 2. | ohSheet |  <a href="submission/ass2/ohSheet/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> | 
| 3. |  GPS |  <a href="submission/ass2/GPS/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> | 
| 4. | sheemart |  <a href="submission/ass2/sheemart/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> | 
| 5. | ATG |  <a href="submission/ass2/ohSheet/read.me" ><img src="../images/answer.png" width="24px" height="24px" ></a> | 
| 6. | KHUCHIN |  <a href="submission/ass2/KHUCHIN/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> |
| 7. | BERUK |  <a href="submission/ass2/BERUK/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> 
| 8. | ATONG |  <a href="submission/ass2/ATONG/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> |
| 9. | 3H |  <a href="submission/ass2/3H/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> |
| 10. | HANY |  <a href="submission/ass2/HANY/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> |
| 11. | ByteNav |  <a href="submission/ass2/ByteNav/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> |
| 12. | SEK KITO  |  <a href="https://github.com/drshahizan/HPDP/tree/main/assignment/submission/ass2/SEK%20KITO/readme.md" ><img src="../images/answer.png" width="24px" height="24px" ></a> | 

### 3. Academic Integrity
🚫 Uphold the highest standards of academic integrity. Any candidate suspected of cheating in the assignment will face disciplinary action, which may include suspension or expulsion from the University. Moreover, any materials or devices found to be in violation of examination rules and regulations will be confiscated.

### 4. Submission Requirements
📝 Prepare a comprehensive document that outlines the step-by-step process for creating the case study. This document should include details about the formulas used. Additionally, you must submit a Google Sheets file containing the results of the case study's execution.

The deadline for submission is **October 26, 2023, at 3:30 PM**. Late submissions will not be accepted and will be disregarded.

## File and Folder Structure 

You must place your file in the submission folder. Within the [`submission/ass2/`](./submission/ass2/) folder, create a folder called your group. Name the default file as `readme.md`. You can refer to the [documentation template here](./submission/ass2/Sample/readme.md). Suggested folder structure for this project:

```html
assignment/your_group/
├── 📁 case_study1/
│   ├── 📄 readme.md
│   └── 📄 cs1.ipynb
├── 📁 case_study2a/
│   ├── 📄 readme.md
│   └── 📄 cs1.ipynb
└── 📁 case_study2a/
    ├── 📄 readme.md
    └── 📄 cs2.ipynb

```

## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/HPDP/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)

