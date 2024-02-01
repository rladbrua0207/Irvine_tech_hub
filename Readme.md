# Data Analysis Report - Yugyeom Ghim

## Introduction
The purpose of this analysis is to explore the most frequently used tasks, the popularity of dataset loaders (based on star ratings), and the frequency of benchmark tasks in the 'paperswithcode.com' dataset. This analysis aims to understand the main features and trends of the dataset.

## Data Description
The dataset used for analysis was collected from 'paperswithcode.com' and includes the following columns:
- 'Dataset Loader': A string variable representing the source of dataset loading.
- 'Task Name': A string variable representing the name of the task.
- 'Stars': A numeric variable representing the number of stars for each dataset loader.

## Methodology
### Data Crawling
Data was scraped from 'paperswithcode.com' using BeautifulSoup, including dataset loaders, task names, and star ratings.

### Data Preprocessing

- Missing values were filled with blanks.
- Non-specific or overly generic categories ('English', 'Unknown', 'Images', 'Texts') were excluded from the dataset.

### Data Visualization

Matplotlib and Seaborn libraries were used to visualize the distribution of main tasks, dataset loaders, and benchmark tasks.

## Analysis

The following basic statistics were calculated through data analysis:

- Task Statistics:
    - count: 9982
    - mean: 3.47
    - std: 12.73
    - min: 1
    - max: 520
- Dataset Loaders Stars Statistics:
    - count: 1,084
    - mean: 20,170
    - std: 501,500
    - min: 0
    - max: 16,420,000
- Most Common Benchmark Statistics
    - count: 4617
    - mean: 2.23
    - std: 6.40
    - min: 1
    - max: 229
- Top 10 Most Common Tasks
	- <img width="825" alt="image" src="https://github.com/rladbrua0207/Irvine_tech_hub/assets/48901587/3084eeb0-2fa4-4e4a-b910-3631a12089d0">
- Top 10 Dataset Loaders
	- <img width="793" alt="image" src="https://github.com/rladbrua0207/Irvine_tech_hub/assets/48901587/864d5eb3-60ad-474a-b2da-25e4842cb289">
- Top 10 Most Common Benchmarks
	- <img width="858" alt="image" src="https://github.com/rladbrua0207/Irvine_tech_hub/assets/48901587/f794ce36-9bdc-453d-b803-ce89cd07aaf2">

## Results
- It was observed that the most frequently used tasks are concentrated in specific categories.
- The number of stars for dataset loaders is related to the popularity of the loaders, with some loaders receiving particularly high ratings.
- The frequency of benchmark tasks varied widely, with certain tasks being used more frequently.
