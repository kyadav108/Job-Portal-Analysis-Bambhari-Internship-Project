# 📊 Job Portal Analysis – Web Scraping & Data Processing

## 🔹 Overview
- Analyzed 160K+ real job postings from Indian job portals
- Focused on hiring trends, salary patterns, skills, and experience requirements
- Performed large-scale data cleaning, preprocessing, and text analysis
- Built Tableau dashboard for interactive visualization and insights

---

## 📊 Tableau Dashboard
🔗 Live Dashboard: [https://public.tableau.com/app/profile/khushi.yadav3650/viz/NaukriJobPostingDashboard_updated/SkillJobProfilesInsights]

---

## 🎯 Objectives
- Analyze hiring trends across industries
- Identify in-demand skills
- Study experience-level distribution
- Normalize salary information
- Prepare structured datasets for analytics and visualization

---

## 🌐 Data Sources
Scraped job postings from:
- Naukri.com
- TimesJobs

### Extracted Fields
- Job Title
- Company Name
- Location
- Experience Required
- Salary
- Skills / Tags
- Industry
- Job Description
- Qualification
- Employment Type

---

## ⚙️ Methodology

### ✅ Data Collection
- Web scraping using Python & BeautifulSoup
- Pagination-based crawling
- Randomized delays to avoid blocking

### ✅ Data Cleaning & Preprocessing
- Removed duplicate records
- Handled missing values
- Standardized inconsistent fields
- Normalized text data

### ✅ Feature Engineering
- Industry binning
- Experience extraction & categorization
- Salary normalization (LPA conversion)

### ✅ Text Processing (Rule-Based)
Extracted information from job descriptions:
- Degrees & Qualifications
- Required Experience
- Soft Skills
- Responsibilities

Created a `Must_Have` column summarizing key job requirements.

### ✅ High-Cardinality Reduction
Applied grouping techniques on:
- Industry labels
- Job titles
- Skills / Tags

---

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- BeautifulSoup
- Regex
- Excel
- Tableau

---

## 📊 Dataset Summary
- Initial Records: 163,188
- Final Cleaned Records: 149,274

---

## 📈 Key Analyses
- Skill demand analysis
- Salary benchmarking
- Industry hiring comparison
- Experience distribution
- Geographic hiring trends

---

## 🚧 Limitations
- Many salaries were not disclosed
- Skill tags were inconsistent
- Highly fragmented job titles
- Possible platform-specific bias

---

## 🔮 Future Enhancements
- Skill clustering automation
- Salary prediction modeling
- Time-series hiring trend analysis

