# 📺 Netflix Content Analytics | SQL & Power BI

## 📌 Project Overview

This project analyses **3,005 Netflix titles** to understand how the content catalogue varies across **content type, genre, production country, release year, ratings, actors, directors, and age certification**.

The project combines **SQL-based exploratory analysis** with a **7-page interactive Power BI dashboard** to transform raw Netflix titles and credits data into structured analytical insights.

The analysis focuses on three broad questions:

1. **What does the Netflix content catalogue look like?**
2. **How do content characteristics such as genre, country, release year, and contributors relate to ratings?**
3. **What patterns can be identified across IMDb and TMDb rating metrics?**

---

## 🎯 Project Objectives

The project was designed to:

- Analyse the overall composition of the Netflix content catalogue.
- Compare **movies and shows** by volume, runtime, ratings, and release trends.
- Identify the most represented genres and compare their average ratings and runtimes.
- Analyse content distribution and rating performance across production countries.
- Examine how the volume and ratings of content changed across release years.
- Identify frequently appearing actors and directors and compare their associated IMDb ratings.
- Analyse titles by age certification, runtime, seasons, and IMDb performance.
- Measure relationships between **IMDb scores, TMDb scores, and IMDb vote counts**.
- Build an interactive **Power BI dashboard** to communicate findings through KPIs and visual analysis.

---

## 🛠️ Tools & Technologies

| Tool | Application |
|---|---|
| **PostgreSQL / SQL** | Data querying, joins, CTEs, aggregations, window functions and exploratory analysis |
| **Power BI** | Data modelling, dashboard development and interactive visualisation |
| **DAX** | KPI calculations and analytical measures |
| **Power Query** | Data preparation and transformation |

---

## 📂 Dataset

The project uses two primary datasets:

### `titles.csv`

Contains title-level information including:

- Title name and ID
- Content type: Movie or Show
- Release year
- Age certification
- Runtime
- Genres
- Production countries
- Number of seasons
- IMDb score
- IMDb votes
- TMDb score
- TMDb popularity

### `credits.csv`

Contains contributor-level information including:

- Title ID
- Actor and director names
- Character information
- Contributor roles

The datasets are connected using the common **title ID**, enabling title-level information to be analysed alongside actors and directors.

---

## 🔄 Analytical Workflow

```text
Netflix Titles + Credits Data
            ↓
      Data Preparation
            ↓
       PostgreSQL
            ↓
   SQL Analysis & EDA
            ↓
 Titles + Credits Integration
            ↓
       Power BI + DAX
            ↓
  7-Page Interactive Dashboard
            ↓
     Analytical Insights
