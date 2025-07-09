# 🔎 Google Search Trends Analysis

A Python-based tool that fetches, analyzes, and visualizes real-time **Google Trends** data using the `pytrends` API. This project allows users to input any keyword and receive insightful visual analytics including regional popularity, time-based search trends, and related keyword comparisons.

---

## 🚀 Project Overview

This interactive, command-line tool enables users to:

- Retrieve search interest over time for any custom keyword
- Analyze geographic distribution of search volume
- Compare related search terms
- Visualize all insights using rich plots and maps

---

## 🧠 Core Workflow

1. **🔤 User Input**
   - Prompts the user to enter a keyword for analysis

2. **📥 Data Retrieval**
   - Uses `pytrends.build_payload()` to query real-time Google Trends data
   - Fetches:
     - **Interest over time**
     - **Interest by region**
     - **Related search queries**

3. **🌍 Geographic Analysis**
   - Ranks countries by normalized interest scores
   - Displays data using **interactive choropleth map** via `plotly.express`

4. **📊 Temporal Trend Visualization**
   - Plots 12-month historical trend using **Matplotlib** and **Seaborn**

5. **🔁 Keyword Comparison**
   - Visualizes related keywords with bar charts for comparative analysis

---

## 🛠️ Technologies Used

| Category        | Tools/Libraries                        |
|----------------|----------------------------------------|
| Data Collection | `pytrends`                             |
| Data Handling   | `pandas`, `numpy`                      |
| Visualization   | `matplotlib`, `seaborn`, `plotly.express` |
| User Interaction| Command-line interface (`input()`)     |

---

## 💡 Features

- ✅ Dynamic keyword entry
- ✅ Modular codebase (easy to extend)
- ✅ Real-time data from Google Trends
- ✅ Clear and colorful visualizations
- ✅ Ideal for SEO research, market trend analysis, or keyword strategy

---

## 📌 Use Cases

- 📈 Marketing trend analysis
- 🌐 Keyword research for SEO
- 📊 Social media or brand interest tracking
- 🔍 Competitor keyword comparison

---


> ⚡ *This project demonstrates practical skills in API integration, automated data analysis, and visual storytelling using Python.*
