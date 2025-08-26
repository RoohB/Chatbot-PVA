# PowerBi Chatbot with Copilot Studio 

## Problem Statement
Business users often struggle to explore Power BI dashboards efficiently without prior knowledge of navigation or filters. They require a chat-based interface to query sales, profit, customers, and inventory metrics in plain language.
---
## Solution

- Built a chatbot using **Microsoft Copilot Studio** (formerly **Power Virtual Agents**) integrated with **Power Automate** and **Power BI datasets**.
- Users can chat naturally with the bot to get insights from Power BI reports.
- The chatbot triggers Power Automate flows, which query the dataset, process results, and return formatted responses.
---
## Features

- Interactive question and answer interface for business KPIs.
- Predefined topics: Sales & Revenue, Profitability, Customer Trends, Inventory, Reports.
- Drill-down queries
- Backend automation via **Power Automate flows**.
- Results formatted and returned to chatbot in real time.

# Tech Stack
1. **Copilot Studio (Power Virtual Agents)** – chatbot creation & conversation design

2. **Power Automate** – backend automation (dataset queries, JSON parsing, response formatting)

3. **Power BI** – data source for business metrics

# How it Works
1. User interacts with chatbot - selects a choice of question

2. Chatbot triggers a Power Automate flow.

3. Flow queries the Power BI dataset and prepares the output.

4. Chatbot responds with formatted insights.

# Future Enhancement
- Enable natural language queries without predefined options.
- Integrate with real-time Power BI datasets.

## Disclaimer

This is a demonstration project showcasing chatbot + Power BI integration. Dataset and flows are simplified versions. Sensitive business data is excluded.