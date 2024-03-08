# ISEA_Session7_NLP
Code for topic model: ISEA_topic_model.Rmd

Code for LDA: ISEA_LDA.ipynb

Code for LLM: ISEA_topic_label_using_openai.ipynb

The data used in the in-class demonstration is not available for public distribution. However, you are encouraged to apply the demonstrated code to your own dataset.

# Assignment
**Conduct a comprehensive thematic analysic on COVID-related research article titles using topic modeling and LLM.**
**Data Provided:** You are given a dataset comprising 5,000 titles from COVID-related research articles. To facilitate a more efficient analysis, you are recommended to use a random sample for your study. The suggested sample size is as follows:
* For Topic Modeling: Consider using a subset of less than 5,000 titles.
* For Large Language Model (LLM) Analysis: The subset size of titles for analysis may vary depending on the version of ChatGPT or a similar LLM you are utilizing. A smaller subset from the topic modeling results might be necessary.

**Research Question:** Identify the prevailing topics in COVID-related research articles.

**Output:**
1. Annotated Coding Script for topic modeling: Submit a detailed, annotated script of your coding process. You can choose to use programming languages and libraries such as R or Python, and tools like Tidy, STM, Gensim etc. Ensure that your annotations clearly explain each step of the process.
2. Prompt designs for LLM: Submit prompts that you used for the LLM (e.g., open-api, ChatGPT, etc.).

3. Excel Spreadsheet of Topics: Prepare spreadsheets presenting your final topics. The format should be as follows:

Codebook:
   | Topic | Your Label for Topic | Top 10 Topic Terms | Top Document Example 1 | Top Document Example 2 | 
   |-------|----------------------|--------------------|-----------------------|-----------------------|
   | 1     | [Your Label]         | [Terms]            | [Document Title]      | [Document Title]      |
   | 2     |                      |                    |                       |                       |
   | ...   |                      |                    |                       |                       |

20 examples for Label:
   | Topic | Document Example | Topic Model Label for Topic | LLM Label for Topic |  
   |-------|----------------------|--------------------|-----------------------|
   | 1     | [Document Title]     | [Topic Label]      | [LLM Label]           | 
   | ...   |                      |                    |                       |
   | 20    |                      |                    |                       | 
