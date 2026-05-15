📊 Job Portal Analysis – Web Scraping & Data Processing

🔹 Overview

This project analyzes the Indian job market using 160K+ real job postings scraped from Naukri.com and TimesJobs. The goal of the project is to uncover hiring trends, skill demand, salary patterns, and experience requirements through large-scale data processing, preprocessing, and rule-based text analysis.

An interactive Tableau dashboard was also created to visualize key insights related to hiring distribution, salary trends, skills in demand, and top hiring locations.

📊 Tableau Dashboard

🔗 Live Dashboard: [https://public.tableau.com/app/profile/khushi.yadav3650/viz/NaukriJobPostingDashboard_updated/SkillJobProfilesInsights]

🎯 Objectives
Analyze hiring trends across industries

Identify in-demand skills

Study experience-level distribution

Normalize and evaluate salary patterns

Prepare structured datasets for visualization and analytics

🌐 Data Sources

Job postings were scraped from:

Naukri.com
TimesJobs
Extracted Fields
Job Title
Company Name
Location
Experience Required
Salary
Skills / Tags
Industry
Job Description
Qualification
Employment Type

⚙️ Methodology

✅ 1. Data Collection
Web scraping using Python and BeautifulSoup
Pagination-based crawling
Randomized delays to avoid blocking

✅ 2. Data Cleaning & Preprocessing
Removed duplicate records
Handled missing values
Standardized inconsistent fields
Normalized text data

✅ 3. Feature Engineering

Created analytical features including:

✔ Industry Binning
✔ Experience Parsing & Categorization
✔ Salary Normalization (LPA Conversion)

✅ 4. Text Processing (Rule-Based)

Useful information was extracted from free-text job descriptions using:

Regex patterns
Keyword mapping
Rule-based text classification

Extracted information included:

Degrees & Qualifications
Required Experience
Soft Skills
Responsibilities
The extracted information was combined into a Must_Have column to create a concise summary of job requirements.

✅ 5. High-Cardinality Reduction

Applied grouping and binning techniques to manage:

Industry labels
Job titles
Skills / Tags
🛠 Tech Stack
Python
BeautifulSoup
Pandas
NumPy
Regex
Excel
Tableau

📊 Dataset Summary
Initial Records: 163,188
Final Cleaned Records: 149,274

📈 Key Analyses Supported

This dataset enables:

Skill demand analysis
Salary benchmarking
Industry hiring comparison
Experience distribution insights
Geographic hiring trends

🚧 Limitations
Salary frequently not disclosed
Skill tags inconsistent across postings
Highly fragmented job titles
Scraped data may contain platform-specific bias

🔮 Future Enhancements
Skill clustering automation
Salary prediction modeling
Trend analysis over time

⭐ Project Value

This project transforms raw job postings into structured market intelligence through large-scale web scraping, data preprocessing, feature engineering, and rule-based text analytics. The analysis helps uncover meaningful insights into hiring trends, salary structures, and evolving skill demands across the Indian job market.
