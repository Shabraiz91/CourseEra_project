# 🛠️ Rozee.pk Job Scraper & Job Market Analyzer

This project scrapes job postings from [Rozee.pk](https://www.rozee.pk/) related to software jobs in Pakistan, and performs data cleaning, categorization, and exploratory analysis to help **recruitment agencies** or **freelancers** improve job vacancy sourcing and gain a competitive edge.

---

## 📌 Objective

- Scrape live job listings from Rozee.pk across multiple pages.
- Extract meaningful data such as job title, company, posted date, experience, and job link.
- Analyze job trends and patterns to improve sourcing efficiency.
- Visualize data to uncover high-demand roles, companies, and locations.

---

## 🚀 Features Implemented

### ✅ Web Scraping using Selenium
- Scrapes 20 pages (500+ jobs) from Rozee.pk's search results.
- Captures the following fields:
  - `Title`
  - `Company`
  - `Date Posted` (Parsed properly)
  - `Experience`
  - `Job Link`
  - `Posted Day` (Day of the week for trend analysis)

### ✅ Data Cleaning (Pandas)
- Removed incomplete rows with all `NaN` values.
- Cleaned whitespace, parsed dates, and removed duplicates.

### ✅ Feature Engineering
- Extracted `Posted Day` and `Month` from job date.
- Tagged job `Category` (e.g. Developer, Internship, Management).
- Grouped and counted jobs by:
  - Day of the week
  - Experience level
  - Job category
  - Top hiring companies
  - Remote vs. on-site detection (optional)

### ✅ Visualizations
- Bar plots of:
  - Jobs by category
  - Jobs by experience level
  - Weekly posting trends
  - Most active hiring companies

---

## 📂 Folder Structure

