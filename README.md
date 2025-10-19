Business Analytics Portfolio
A comprehensive monorepo showcasing advanced business analytics, data engineering, and statistical analysis projects
Portfolio Overview
This repository demonstrates proficiency in data analysis workflows, statistical modeling, ETL pipeline development, and business intelligence applications through four major projects spanning cybersecurity analytics, database design, and empirical research.
Student: Timothy Spivey
Institution: University of South Alabama
Course: BUS 761 - Business Analytics
Contact: ts2427@jagmail.southalabama.edu

Repository Structure
Business-Analytics-Portfolio/
├── assignments/
│   ├── assignment-02/     # Python fundamentals & environment setup
│   ├── assignment-03/     # Cybersecurity disclosure timing analysis
│   ├── assignment-04/     # Database design & ETL pipeline
│   └── assignment-05/     # [Project description]
├── pyproject.toml         # Project dependencies and configuration
├── uv.lock               # Dependency lock file
└── README.md             # This file

Projects
Assignment 2: Python Development Environment
Focus: Professional Python development practices and environment configuration
Key Components:

UV package manager setup and configuration
Virtual environment management
Jupyter notebook integration
Modern Python toolchain implementation

Technologies: Python 3.10+, UV package manager, Jupyter

Assignment 3: Cybersecurity Disclosure Timing Analysis
Focus: Empirical analysis of cybersecurity disclosure timing and market reactions
Research Question:
How does cybersecurity disclosure timing affect market reactions in communications companies, and does firm governance quality moderate this relationship?
Hypothesis:
Immediate cybersecurity disclosure results in more negative short-term market reactions compared to delayed disclosure due to signaling effects, with moderation by firm governance quality.
Methodology:

Event study analysis using cumulative abnormal returns (CAR)
Governance quality interaction terms
Myers-Majluf (1984) information asymmetry framework extension

Data Sources:

SEC EDGAR Database (8-K filings, 10-K reports, proxy statements)
Yahoo Finance API (stock prices, trading volume)
Privacy Rights Clearinghouse (breach incident database)

Key Features:

SEC API integration for automated data collection
Event study regression analysis
Interactive Streamlit dashboard
Comprehensive statistical modeling

Technologies: Python, SEC API, Yahoo Finance API, Streamlit, pandas, statsmodels

Assignment 4: Database Design & ETL Pipeline
Focus: Comprehensive data breach analysis system with advanced statistical methods
Project Scope:
Analysis of 35,378 breach incidents from Privacy Rights Clearinghouse (2003-2025) using a four-stage ETL pipeline: data sourcing, cleaning, loading, and analysis.
Database Architecture:

Main Database: databreach.db (SQLite, 70 MB)
Tables: 17 total

databreach - Main breach records (35,378 rows, 20 columns)
sec_company_reference - SEC company data (10,142 companies)
15 statistical analysis tables



Statistical Analyses (15 tests):

Correlation Analysis (Pearson & Spearman)
Chi-Squared Test (χ²=5069.93, p<0.001)
ANOVA (F=2.65, p=0.010)
Tukey HSD post-hoc tests
Simple Linear Regression (R²=0.099)
Multiple Regression
Ridge & Lasso Regression
Polynomial Regression (degrees 1-3)
Logistic Regression (63% accuracy)
Time Series Analysis (2003-2025)
Descriptive Statistics by organization type

Visualizations (6 charts):

Industry vulnerability heatmap
Breach frequency analysis
Impact correlation scatter plot
Sector impact comparison
Time series trends
Regression fit visualization

Key Findings:

Healthcare: 43% more disclosure breaches than expected
Financial institutions: 169% more physical breaches than expected
Retail sector: 400% more card breaches than expected
Significant breach impact variation across industries (p=0.010)

Technologies: Python 3.13, SQLite, pandas, scipy, scikit-learn, matplotlib, seaborn
Quick Start:
bashcd assignments/assignment-04
python run_all.py  # Executes full pipeline

Assignment 5: [Project Title]
Focus: [Project description]
[Details to be added]

Environment Setup
Prerequisites

Python 3.10 or higher
UV package manager
Git

Installation Instructions

Clone the repository:

bashgit clone https://github.com/ts2427/Business-Analytics-Portfolio.git
cd Business-Analytics-Portfolio

Verify UV installation:

bashuv --version

Install dependencies:

bashuv sync

Activate virtual environment:

bash# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

Launch Jupyter Notebook:

bashuv run jupyter notebook

Key Dependencies

Data Analysis: pandas, numpy
Statistical Computing: scipy, scikit-learn, statsmodels
Visualization: matplotlib, seaborn
Database: SQLite
Web Applications: Streamlit
Development: Jupyter, pytest


Development Workflow

Navigate to specific assignment directory
Follow project-specific setup instructions
Review documentation in docs/ folders
Execute analysis scripts or notebooks
Generate visualizations and reports


Technical Skills Demonstrated

Advanced statistical analysis and hypothesis testing
ETL pipeline development and database design
Financial data analysis and event studies
Machine learning model development
Data visualization and business intelligence
API integration and web scraping
Professional Python development practices
Git version control and project management


Documentation
Each assignment contains comprehensive documentation:

Setup instructions - Installation and usage guides
Data sources - Provenance and citations
Methodology - Analysis approaches and techniques
Results - Findings and visualizations
Data dictionaries - Complete field definitions


License
This project is licensed under the MIT License - see the LICENSE file for details.

Repository Link
https://github.com/ts2427/Business-Analytics-Portfolio

Last Updated: October 2025