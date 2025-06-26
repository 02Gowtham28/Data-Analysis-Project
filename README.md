# 🏅 Olympic Sports Analysis

## 👤 Author: Gowtham R

---

## 📌 Problem Statement

The objective of this analysis is to gain valuable insights into the historical data of the Olympic Games by exploring various dimensions, including:

- Games
- Sports
- Events
- Participants
- Medals
- Regional Representation

The scope includes data from multiple Olympic editions, aiming to identify trends, patterns, and significant insights. This analysis provides a comprehensive overview of the evolution of the Olympics and aims to deliver recommendations to:

- Improve the organization of future Olympics
- Guide sport selection
- Ensure fair regional representation

**Final Deliverables**:  
A comprehensive report, Power BI dashboard, and Excel-based EDA.

---

## 🗃️ Dataset Description

The dataset is a structured collection of normalized tables from a **relational MySQL database**, capturing detailed information about Olympic Games, sports, participants, events, and results.

---

## 🧾 Table Descriptions

| Table Name              | Description |
|------------------------|-------------|
| **Sport Table**         | List of all sports featured in Summer and Winter Olympics |
| **Event Table**         | Details of events by sport and gender (Men, Women, Mixed) |
| **City Table**          | Cities that hosted or participated in the Olympics |
| **Games Table**         | Editions of the Olympics with year and season |
| **Games_City Table**    | Links Games and City tables (e.g., multi-city hosting) |
| **NOC_Region Table**    | National Olympic Committees and country/region mapping |
| **Person Table**        | Athlete demographics – name, gender, height, weight |
| **Person_Region Table** | Athletes and countries they represented |
| **Games_Competitor**    | Participation of athletes in specific Olympic editions |
| **Medal Table**         | Types of medals: Gold, Silver, Bronze, N/A |
| **Competitor_Event**    | Fact table with competitor-event-medal details |

---

## 🎯 Project Objectives

- Perform **Exploratory Data Analysis (EDA)** using SQL & Excel
- Build **interactive dashboards** using Power BI and Excel
- Analyze:
  - Game editions
  - Gender disparities
  - Sport popularity
  - Medal distribution
  - Regional performance
- Answer 18 analytical questions

---

## 🛠️ Tools Used

- 🛢️ MySQL Workbench – Data querying
- 📊 Microsoft Excel – Pivot charts, slicers, dashboards
- 🟡 Power BI – Interactive and visual-rich reporting
- 📽️ PowerPoint – Final presentation layer

---

## 📊 Dashboards

### ✅ Excel Dashboard
- 18 EDA sheets
- 1 consolidated dashboard with slicers & pivot tables
- ![Screenshot 2025-06-26 150704](https://github.com/user-attachments/assets/581b8b1e-e76e-4bec-8078-e6f801ca2c38)


### ✅ Power BI Dashboard
- 9 visuals summarizing 18 questions
- Fully interactive and presentation-ready
- ![image](https://github.com/user-attachments/assets/9bc4eb30-61ec-4d97-9cb5-115df623cfb0)


## 🔍 Sample Analytical Questions

- How have Olympic Games evolved across decades?
- Which countries/regions dominate the medal tally?
- What are the gender disparities in events?
- Are there region-specific sports?
- Which sports are emerging or discontinued?

---

## 📈 Key Insights

- **81.39%** of Olympic Games are Summer editions.
- **USA** dominates participation and medal counts.
- **London** is the most frequent host city.
- **Athletics** and **Swimming** top in athlete participation.
- **Post-2000** shows increasing inclusion of women and new sports.
- Some sports are exclusive to specific regions (e.g., Roque – USA, Pelota – Spain).

---

## 📝 Deliverables

- 📄 `Sports Analysis Document.pdf` – SQL queries + visual insights
- 📊 Excel workbook – EDA + dashboard
- 📈 Power BI dashboard – Interactive analysis
- 📽️ PowerPoint presentation – Summary of findings

---

## 🚀 Future Enhancements

- Automate workflow using **Python** (SQL → Excel)
- Publish dashboards via **Power BI Service** or **Tableau Public**
- Integrate athlete bios or economic factors for richer context
- Use ML for **medal prediction**

---


