# University Financial Analysis Insights from Form 990 Data

The purpose of this project is to analyze the financial and operational activities of multiple  universities through their Form 990 filings. By collecting, organizing, and analyzing data from  these forms, you will gain insights into trends and relationships among different institutions. 

# Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning / Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results--findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

# Project Overview
This project analyzes the financial and operational activities of 22 universities in New England from 2004–2023, leveraging IRS Form 990 data. The objective is to evaluate financial stability, operational performance, and trends across key metrics, including Net Income, Total Revenue, Total Expenses, Net Assets, Total Assets, Total Liabilities, Contributions, Program Services Revenue, Executive Compensation, and Other Salaries and Wages. By examining these variables, the project aims to uncover insights into revenue generation, cost management, debt sustainability, and workforce investments, offering a comprehensive view of institutional financial health and areas for strategic improvement.

# Data Sources
Data was manually collected by the team from IRS Form 990 filings, accessed via the ProPublica Nonprofit Explorer. The dataset spans from 2004–2023, providing a robust basis for analysis.

Key metrics collected include:

- Net Income: Captures overall profitability across fiscal years.
- Total Revenue: Reflects all income generated, including tuition, contributions, and other sources.
- Total Expenses: Represents operational and administrative costs.
- Net Assets: Measures financial stability and long-term resource availability.
- Total Assets: Highlights the size and financial scope of each institution.
- Total Liabilities: Assesses debt levels and financial obligations.
- Contributions: Tracks donations and other forms of external funding.
- Program Services Revenue: Evaluates income tied to mission-driven activities.
- Executive Compensation: Assesses leadership costs in relation to institutional size and performance.
- Other Salaries and Wages: Reflects overall workforce investment and financial flexibility.

# Tools
The following tools were utilized for data collection, analysis, and visualization:
- Microsoft Excel for trend analysis
- Power BI for reporting analysis
- R and Python for data extraction
- ProPublica Nonprofit Explorer for sourcing IRS Form 990 data

# Data Cleaning / Preparation
Data Extraction and Categorization:

- Retrieved Form 990 filings and extracted key financial metrics, including Net Income, Total Revenue, Total Expenses, Net Assets, Total Assets, Total Liabilities, Contributions, Program Services Revenue, Executive Compensation, and Other Salaries and Wages.
- Standardized extracted variables into consistent categories across institutions to ensure uniform analysis and meaningful comparisons.

Data Structuring:

- Consolidated cleaned data into a master database (Excel) with consistent column headers, data types, and formats, covering all ten variables of interest.
- Added calculated fields, such as Compound Annual Growth Rate (CAGR) and Year-over-Year (YoY) percentage changes, to facilitate trend and relationship analyses.

Handling Missing or Incomplete Data:

- Identified data gaps and outliers through statistical validation, filling minor gaps using linear interpolation or peer averages where appropriate.
- Excluded universities with substantial missing data from specific analyses to ensure reliability of trends and comparisons across all ten key variables.

Cross-Validation for Accuracy:

- Cross-referenced extracted values against original IRS Form 990 filings to verify accuracy and ensure consistency with source data.
- Conducted team reviews of data entry and calculated metrics for variables like Executive Compensation, Program Services Revenue, and Net Income to minimize potential errors.

Data Readiness for Analysis:

- Organized data into pivot tables and summary views to streamline visualization and exploratory analysis for all variables, including revenue, expenses, liabilities, and compensation.
- Structured the dataset for seamless integration with tools like Power BI, ensuring advanced analysis and interactive dashboards could accommodate the full scope of financial metrics.

# Exploratory Data Analysis (EDA)
Key insights were derived using the following approaches:

Trend Analysis: 

- Tracked year-over-year changes in key financial metrics such as revenue, expenses, and net assets to identify long-term growth patterns and periods of instability.
- Highlighted significant shifts during key economic events, such as the 2008 financial crisis and the post-COVID-19 recovery, to assess their impact on university financials.

Comparative Analysis:

- Benchmarked institutions against peer groups based on size, region, and mission to evaluate financial performance relative to similar universities.
- Identified leaders and laggards in areas like fundraising efficiency, expense management, and program service revenue as a percentage of total revenue.

Visualizations:

- Developed dynamic dashboards in Power BI and detailed charts in Excel to visualize trends, making it easier to detect outliers and anomalies.
- Used bar charts, line graphs, and scatterplots to compare financial health metrics across universities, highlighting disparities and correlations between variables like executive compensation and revenue growth.

This comprehensive EDA approach provided a nuanced understanding of financial patterns, peer performance, and the underlying factors influencing university financial stability.

# Data Analysis

Trend Analysis:

- Analyzed long-term trends in Net Income to assess profitability stability across universities, highlighting institutions with consistent growth versus those with fluctuating results.
- Evaluated year-over-year changes in Total Revenue and Total Expenses, identifying universities with effective revenue generation strategies and cost-control mechanisms.
- Investigated Net Asset trends to assess financial health, focusing on institutions with significant asset growth versus those with stagnant or declining assets.
- Reviewed changes in Total Liabilities to understand risk exposure and debt management across institutions, identifying those with rising liabilities relative to revenue.

Comparative Analysis:

- Benchmarked financial metrics like Total Assets, Net Income, and Contributions, identifying universities with strong financial positions and diverse revenue streams.
- Compared Executive Compensation and Other Salaries and Wages to determine alignment with organizational size, revenue, and overall spending priorities.
- Evaluated Program Services Revenue as a percentage of total revenue, analyzing its alignment with industry standards (e.g., 80–90%) and identifying institutions that prioritize mission-driven activities.

Relationship Exploration:

- Examined correlations between Total Revenue and Program Services Revenue, exploring how investments in mission-related activities influence revenue generation and institutional growth.
- Investigated the relationship between Contributions and Net Asset Growth, identifying universities that effectively leverage donations to build financial resilience.
- Explored the interplay between Total Liabilities and Net Income, assessing how debt levels impact operational profitability and long-term financial stability.
  
By incorporating these additional variables into the analysis, a more holistic view of university financial performance and operational strategies was achieved, enhancing the depth and scope of insights derived from the dataset.

# Results / Findings
Key findings based on the analysis of financial metrics include:

Revenue Trends:

- Larger universities experienced consistent revenue growth, benefiting from diversified income streams and strong fundraising efforts.
- Smaller institutions faced revenue volatility, often tied to their dependence on tuition and limited contributions, which were less stable over time.

Expense Management:

- Effective cost control was observed in universities like WNEU, which maintained steady expense growth while aligning with operational needs.
- Executive compensation growth lagged in some institutions, including WNEU, highlighting potential gaps in competitive pay structures compared to peers.

Net Asset Stability:

- Lesley University displayed unusually high net asset growth (42.5%), attributed to significant fundraising and investment gains.
- Most universities exhibited moderate net asset trends, reflecting stable financial management with limited surplus reinvestment opportunities.

Program Services Revenue:

- Most universities met or exceeded industry standards (80–90%) for program service revenue as a percentage of total revenue, demonstrating a strong alignment with mission-driven activities.
- WNEU fell slightly below the average, suggesting a need to explore opportunities for enhancing mission-aligned revenue generation.

Liabilities and Debt Management:

- Institutions like Sacred Heart University and Quinnipiac University showed notable increases in liabilities, raising concerns about long-term debt sustainability.
- In contrast, WNEU demonstrated prudent debt management, maintaining a low liability growth rate of 3.8%.

Compensation Trends:

- Executive compensation varied significantly among institutions, with MIT and Northeastern setting benchmarks for competitive pay aligned with their size and revenue.
- Other Salaries and Wages, however, lagged behind peers for several universities, including WNEU, highlighting limited financial flexibility for workforce investments.

# Recommendations
Based on the analysis, the following targeted recommendations are proposed to address key financial challenges and leverage opportunities for growth:

Improve Fundraising Efforts:

- Develop targeted fundraising campaigns focusing on alumni and corporate donors, leveraging success stories and impact-driven narratives to increase contributions.
- Establish dedicated teams to identify and pursue grant opportunities, particularly in areas like research, scholarships, and capital improvements, to diversify revenue sources.

Enhance Operational Efficiency:

- Conduct a detailed audit of administrative expenses to identify redundancies and streamline processes, such as reducing overlapping roles or outsourcing non-essential services.
- Implement technology-driven solutions, such as automation in administrative workflows, to reduce long-term operational costs while maintaining service quality.

Monitor Financial Stability:

- Establish quarterly financial reviews to track trends in net assets and liabilities, ensuring potential risks are identified and mitigated promptly.
- Develop dashboards that integrate financial and operational data to provide real-time insights into financial health, enabling proactive decision-making.

Adopt Strategic Budgeting:

- Allocate additional resources to competitive employee compensation packages to attract and retain top talent, especially for executive roles and critical faculty positions.
- Prioritize investment in workforce development initiatives, such as professional training programs, to enhance staff capabilities and morale while addressing gaps in Other Salaries and Wages.

Mitigate Economic Risks:

- Develop contingency plans that include cost-reduction strategies, diversified revenue generation, and emergency reserves to safeguard against economic downturns or unforeseen crises.
- Explore endowment growth strategies, such as adopting higher-yield investment portfolios, to ensure long-term financial stability and reduce reliance on tuition and external funding.

These recommendations provide actionable strategies for universities to strengthen their financial health, operational efficiency, and resilience, ensuring long-term sustainability in a competitive academic environment.

# Limitations
The following limitations were identified during the analysis, which may impact the comprehensiveness and generalizability of the findings:

Manual Data Collection:

- The reliance on manual data extraction from IRS Form 990 filings introduces the risk of human error during data entry and categorization.
- Despite cross-validation efforts, the possibility of overlooked discrepancies or misclassifications in key financial metrics remains.

Limited Data Scope:

- The analysis focused on 22 universities over a 19-year period (2004–2023), restricting the ability to explore longer-term historical trends or more granular year-to-year variations.
- The exclusion of institutions outside the New England region limits the broader applicability of findings to universities in other regions or educational systems.

External Macroeconomic Factors:

- Key external factors, such as inflation trends, federal funding policies, or shifts in student demographics, were not quantitatively integrated into the analysis.
- As a result, the impact of broader economic events (e.g., 2008 financial crisis or COVID-19 pandemic) on institutional performance may not be fully captured.

Assumptions in Data Adjustments;

- Inflation adjustments using the Consumer Price Index (CPI) assumed uniform economic conditions across the years, which may not fully account for sector-specific financial dynamics.
- The use of averages to fill minor data gaps may introduce slight biases, particularly for institutions with highly variable financial performance.

# References
- Internal Revenue Service. (2024). About form 990, return of organization exempt from income tax. IRS. [Internal Revenue Service](https://www.irs.gov/forms-pubs/about-form-990)
- Ithaca College. (n.d.). Form 990 info. Ithaca College. [Ithaca College](https://www.ithaca.edu/division-finance-and-administration/form-990-info)
- Library of Congress. (n.d.). Nonprofit sector in the United States: A resource guide. Library of Congress. [Library of Congress](https://guides.loc.gov/nonprofit-sector/form-990)
- ProPublica, Suozzo, A., Glassford, A., Ngu, A., & Roberts, B. (2024). Nonprofit explorer. ProPublica. [ProPublica](https://projects.propublica.org/nonprofits/)
- Team findings and visualizations from Power BI, Excel, and Python analysis.

