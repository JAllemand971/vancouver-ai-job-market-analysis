# Vancouver AI & Data Job Market Analysis

## Overview

This project analyzes the AI and Data job market in the Greater Vancouver area.

The goal is to understand which roles, skills, and technologies are currently in demand in Vancouver's AI ecosystem.

The analysis is based on AI and Data-related job postings collected from LinkedIn.

After cleaning and removing duplicates, the final dataset contains **147 unique job opportunities**.

## Project Goals

This project aims to answer the following questions:

- Which AI and Data roles are most in demand in Vancouver?
- Is the market more focused on research or industry applications?
- Which technical skills appear most frequently?
- Which technologies are companies actively looking for?
- What does the local job market suggest for people trying to enter AI?

## Dataset

The Vancouver dataset contains:

- Initial job postings: **200**
- Cleaned unique postings: **147**
- Location focus: **Greater Vancouver Area**
- Source: **LinkedIn job postings**
- Domain: **AI, Machine Learning, Data Science, Data Engineering, Analytics, and related roles**

## Job Categories

![Job Categories](https://raw.githubusercontent.com/JAllemand971/AI_Job_Market_Analysis/main/vancouver_ai_job_market_analysis/images/jobCategory.png)

The largest categories in the Vancouver dataset were:

- AI Engineer
- Data Engineer
- Data Scientist
- Machine Learning Engineer

Research-oriented positions represented a smaller portion of the market.

This suggests that the Vancouver AI job market is primarily focused on building, integrating, and deploying AI systems rather than only developing new algorithms in research environments.

## Market Orientation

![Market Orientation](https://raw.githubusercontent.com/JAllemand971/AI_Job_Market_Analysis/main/vancouver_ai_job_market_analysis/images/orientation.png)

To better understand the structure of the market, job categories were grouped into broader orientations:

- Applied AI
- Data & Analytics
- Research
- Platform Engineering
- Solutions Engineering

The analysis shows that most opportunities are industry-oriented.

Only a smaller portion of the market appears to be research-focused.

![Market Repartition]()

This challenges the common perception that AI careers are mainly centered around research labs, PhD-level work, or academic research.

In Vancouver, most companies appear to be looking for people who can build, integrate, and deploy AI or data solutions into real-world environments.

## Skills Demand

![Skills Heatmap](https://raw.githubusercontent.com/JAllemand971/AI_Job_Market_Analysis/main/vancouver_ai_job_market_analysis/images/skills_heatmap.png)

The skills analysis shows several important trends.

### Core Skills

Python appears as the most important technical skill across most AI and Data roles.

SQL is also highly relevant, especially for:

- Data Engineering
- Data Science
- Analytics roles

### Applied AI Skills

AI Engineer roles show demand for skills related to:

- Large Language Models
- Retrieval-Augmented Generation
- Cloud platforms
- AI application development

### Machine Learning Skills

Machine Learning Engineer roles are more likely to require:

- PyTorch
- TensorFlow
- Model development
- Machine learning fundamentals

### Data Engineering Skills

Data Engineering roles frequently mention:

- SQL
- Spark
- Databricks
- Airflow
- Cloud data platforms

## Key Findings

### 1. Vancouver's AI market is mostly industry-oriented

Most opportunities are focused on practical AI implementation, data platforms, and production systems.

Research roles exist, but they represent a smaller share of the market.

### 2. Python remains the dominant AI skill

Python appears across many job categories and remains one of the most valuable technical skills for AI and Data roles.

### 3. SQL is still highly important

Even with the rise of generative AI and large language models, SQL remains a core skill for many data-related positions.

### 4. Generative AI is entering production roles

Technologies related to modern AI systems are appearing in job postings, including:

- Large Language Models
- Retrieval-Augmented Generation
- Vector databases
- MLOps
- Cloud AI services

### 5. Practical engineering skills matter

The data suggests that companies are looking for candidates who can connect AI models to real products, workflows, and business systems.

## Interpretation

The Vancouver AI job market appears to be practical, applied, and engineering-driven.

While research skills remain valuable, the strongest demand seems to be for people who can:

- Build AI applications
- Work with data pipelines
- Deploy models
- Use cloud platforms
- Integrate AI into existing systems
- Understand both software and machine learning workflows

For aspiring AI professionals, a strong technical foundation should include:

- Python
- SQL
- Machine Learning fundamentals
- Cloud platforms
- Data engineering basics
- Generative AI concepts
- MLOps and deployment workflows

## Limitations

This analysis has some limitations:

- The dataset is relatively small.
- The data comes from job postings and may not represent the entire market.
- Some job descriptions may be incomplete or inconsistent.
- Job titles can be ambiguous.
- Skills are extracted from postings and may not capture every requirement.
- The analysis focuses only on the Vancouver area.

Despite these limitations, the dataset provides a useful snapshot of the local AI and Data job market.

## Conclusion

The Vancouver AI job market is not only about research.

Most opportunities are focused on applied AI, data infrastructure, analytics, and production-ready systems.

The strongest career signal from this analysis is that AI professionals should combine machine learning knowledge with practical software, data, and cloud engineering skills.

In other words, the local market appears to value people who can turn AI concepts into working systems.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Data cleaning
- Exploratory data analysis
- Data visualization

## Repository Structure

```text
vancouver-ai-job-market-analysis/
│
├── images/
│   ├── jobCategory.png
│   ├── orientation.png
│   ├── repartition.png
│   └── skills_heatmap.png
│
├── notebooks/
│   └── Vancouver_AI_Job_Market_Analysis.ipynb
│
├── data/
│   └── README.md
│
└── README.md
