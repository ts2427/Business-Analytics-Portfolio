Cybersecurity Disclosure Timing Analysis



Empirical analysis of how cybersecurity disclosure timing affects market reactions in communications companies, with governance quality as a moderating factor.



Project Overview



This research extends the Myers-Majluf (1984) information asymmetry framework to cybersecurity contexts, investigating whether immediate disclosure results in more negative market reactions and how firm governance quality moderates this relationship.



Research Question



How does cybersecurity disclosure timing affect market reactions in communications companies, and does firm governance quality moderate this relationship?



Hypothesis



Immediate cybersecurity disclosure results in more negative short-term market reactions compared to delayed disclosure due to signaling effects, but this penalty is moderated by firm governance quality.



Data Sources



\- SEC EDGAR Database: 8-K filings, 10-K reports, proxy statements via Python API

\- Yahoo Finance API: Stock price and trading volume data

\- Privacy Rights Clearinghouse: Cybersecurity breach incident database



Methodology



Event study analysis using cumulative abnormal returns (CAR) with governance quality interaction terms:



CAR\_it = α + β₁(Immediate\_Disclosure\_it) + β₂(SOX\_Weakness\_it) + 

&nbsp;        β₃(Restatement\_History\_it) + β₄(Firm\_Controls\_it) + 

&nbsp;        β₅(Market\_Conditions\_t) + ε\_it



Repository Structure



TSpivey-Assignment-3/

├── src/                    Source code modules

│   ├── data\_collection/    SEC API integration

│   ├── analysis/          Event study and regression

│   ├── visualization/     Dashboard and plotting

│   └── utils/            Helper functions

├── data/                  Data files (raw and processed)

├── notebooks/             Jupyter notebooks for analysis

├── tests/                 Unit tests

├── docs/                  Project documentation

├── dashboard/             Streamlit application

└── pyproject.toml        Dependencies and configuration



Setup Instructions



1\. Clone the repository:

git clone https://github.com/ts2427/TSpivey-Assignment-3.git

cd TSpivey-Assignment-3



2\. Install dependencies using UV:

uv sync



3\. Launch Jupyter for analysis:

uv run jupyter notebook



Expected Outcomes



\- Evidence that governance quality moderates disclosure timing penalties

\- Actionable insights for corporate disclosure strategies  

\- Policy recommendations for regulatory agencies

\- Framework for cybersecurity risk management



Author



Timothy Spivey - ts2427@jagmail.southalabama.edu



Course: Business Analytics Portfolio  

Institution: University of South Alabama  

Project Timeline: September - December 2024



License



This project is licensed under the MIT License - see the LICENSE file for details.

