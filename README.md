# Lexie Smith — Data Analytics Portfolio

## About

Hi, I'm Lexie, a data analyst with a dual background in Psychology (B.A., Eastern Washington University, Magna Cum Laude) and Data Analytics (B.S., Washington State University, 4.0 GPA). I care about data that connects to people: mental health outcomes, environmental equity, and the friction points in everyday experiences.

My psychology background shapes how I approach analysis. I don't just ask what does the data show, I ask what decision does this support, and for who? That lens shows up in every project below.

📄 [Resume]() | 🔗 [LinkedIn](https://www.linkedin.com/in/alexis-smith-0169101a2/) |

---

## Table of Contents

- [Portfolio Projects](#portfolio-projects)
  - [Mental Health & COVID-19: Unmet Need Analysis](#mental-health--covid-19-unmet-need-analysis)
  - [Oregon Air Quality Analysis](#oregon-air-quality-analysis)
  - [Sewing Pattern Discovery: UX Research Case Study](#sewing-pattern-discovery-ux-research-case-study)
- [Education](#education)
- [Contact](#contact)

---

## Portfolio Projects

### Mental Health & COVID-19: Unmet Need Analysis

**The question:** During the COVID-19 pandemic, which populations were most likely to need mental health care, and least likely to receive it?

**Why it matters:** Unmet mental health need doesn't distribute evenly. Policymakers and public health programs need to know where the gaps are to allocate resources effectively. This analysis makes those gaps visible.

**What I did:** Using CDC Household Pulse Survey data, I cleaned and analyzed responses across demographic groups (age, income, race/ethnicity, employment status) to identify patterns in reported mental health distress and treatment access. I built an interactive Tableau dashboard to make findings accessible to non-technical audiences.

**Key findings:**
- Unmet need peaked at **12.4%** in January 2021, meaning roughly 1 in 8 
  American adults needed mental health care but couldn't access it at the 
  height of the pandemic's second wave.
- Disparities were not evenly distributed. Transgender adults reported the 
  highest unmet need of any group at **39.4%**, this is more than triple the 
  national peak, followed by bisexual adults (31.0%) and adults with 
  disabilities (24.1%).
- Younger adults were disproportionately affected: adults aged 18–29 
  averaged **19.8%** unmet need compared to **3.3%** for adults aged 70–79.
- A regression model confirmed that demographic group membership alone 
  explains **96.1% of variation** in unmet need, suggesting these gaps 
  are structural, not random.
**Tools:** Python (pandas, matplotlib), Tableau  
**Code:** [Jupyter Notebook](https://github.com/Lexie-s/Unmet-Mental-Health-Need-During-COVID-19) | **Dashboard:** [Tableau Public — Unmet Mental Health Need During COVID-19](https://public.tableau.com/app/profile/lexie.smith3341/viz/UnmetMentalHealthNeedDuringCOVID-19/UnmetMentalHealthNeed)

---

### Oregon PM2.5 Air Quality Analysis

**The question:** How has PM2.5 air quality in Oregon changed over time, and which communities face the greatest exposure risk?

**Why it matters:** Air quality data is public, but it's not accessible. Translating 25 years of monitoring data into clear trends and geographic patterns supports both regulatory decision-making and community awareness.

**What I did:**
- Downloaded and processed 25 years of EPA Air Quality System (AQS) daily PM2.5 data for Oregon monitoring stations (1999–2022)
- Built a normalized MySQL database with two tables storing readings across 47 statewide monitoring stations
- Wrote SQL queries to analyze exceedances of the federal 35 µg/m³ standard by year, county, and season
- Created a Power BI dashboard visualizing trends, geographic hotspots, and seasonal patterns

**Key findings:**
- PM2.5 pollution in Oregon has become more intense in recent years even as total exceedance day counts fluctuated
- Klamath, Jackson, and Lane counties show the highest exposure risk when normalized by monitoring station count
- Winter wood smoke inversions in valley communities account for more total unhealthy days than wildfire season when measured across the full 24-year period
- April and May had zero unhealthy air days across the entire dataset — spring is Oregon's cleanest season
**Tools:** Python, MySQL, Power BI, SQL

## Repository Contents
| File | Description |
|------|-------------|
| `Oregon_Air_Quality_Pipeline.ipynb` | Data download, extraction, and MySQL loading pipeline |
| `oregon_air_quality_analysis.sql` | Five analysis queries and normalized county view |
| `dashboard_screenshot.png` | Power BI dashboard preview |

## Dashboard
[View interactive dashboard](#)

## Data Source
[EPA Air Quality System (AQS) — Daily PM2.5 FRM/FEM Mass (Parameter 88101)](https://aqs.epa.gov/aqsweb/airdata/download_files.html)

## Limitations
- Counties with fewer monitoring stations may show less reliable averages due to limited sampling
- Larger rural counties are underrepresented relative to their geographic area
- 2023–2024 data excluded due to EPA certification lag

---
---

### Sewing Pattern Discovery: UX Research Case Study

**The question:** Why is it so hard to find the right sewing pattern — and what would a better discovery experience look like?

**Why it matters:** The sewing community is large, passionate, and underserved by existing tools. This project applies UX research methods and data analysis to a real gap in a niche but growing market, and demonstrates how human-centered design starts with listening before building.

**What I did:** Designed and distributed a survey to active sewing communities (Reddit: r/sewing, r/PatternReview. Facebook: Young and Millenial Quilters) to understand how people currently search for patterns, what frustrates them, and what attributes they prioritize. Synthesized responses into user insights and translated findings into a proposed app concept with wireframes in Figma.

**Skills:** Survey design, qualitative + quantitative synthesis, Figma prototyping, user persona development  
**Tools:** Google Forms, Python (analysis), Figma  
**Case Study:** [Link when available]

> 🔧 *Research phase in progress.*

---

## Education

**Washington State University**  
B.S. in Data Analytics — *In Progress* (4.0 GPA, President's Honor Roll)  
Relevant coursework: Data Ethics, Statistical Analysis, Data Visualization

**Eastern Washington University**  
B.A. in Psychology — *Magna Cum Laude*  
Washington State Seal of Biliteracy (Spanish)

---

## Contact

- 📧 [lexieksmith76@gmail.com]
- 💼 [LinkedIn](https://www.linkedin.com/in/alexis-smith-0169101a2/) 
