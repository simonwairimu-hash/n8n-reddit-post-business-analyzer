<img width="758" height="401" alt="image" src="https://github.com/user-attachments/assets/a2047306-bf2f-4d71-af00-af742b137ae0" />


# 📊 Automated Market & Sentiment Analysis Engine for Reddit

This project automates the process of gathering, analyzing, and summarizing recent posts from Reddit to uncover *emerging market trends*, *customer needs*, and *overall sentiment*. It uses a multi-step AI-powered workflow to transform raw Reddit data into *actionable insights*, which are then neatly organized in a **Google Sheet**.

> 📌 *The image above is a visual representation of the automated workflow.*

---

## 🚀 How It Works

The entire process is broken down into **four key stages**, moving from data collection to final insight generation.

---

### 1️⃣ Data Collection

The workflow begins by tapping into specific Reddit communities to gather relevant conversations.

* **Fetch Posts**  
  Retrieves recent and popular posts from targeted subreddits.

* **Filter & Refine**  
  Automatically filters posts based on engagement metrics (upvotes, comments) and keywords to ensure relevance.

* **Extract Data**  
  Extracts key information from each post to prepare it for deeper analysis.

---

### 2️⃣ Content Analysis

Filtered data is passed to an AI model to understand the core themes.

* **AI-Powered Analysis**  
  An OpenAI Chat model identifies emerging market needs and underserved customer demands.  
  Helps pinpoint what users are looking for or complaining about.

---

### 3️⃣ Parallel Processing: Insights & Sentiment

Two parallel AI workflows further enrich the data:

* **🧠 Insight Generation**  
  Summarizes key opportunities and suggests potential solutions or business ideas.

* **💬 Sentiment Analysis**  
  Classifies each post into:  
  * 🟢 Positive  
  * 🟡 Neutral  
  * 🔴 Negative

---

### 4️⃣ Final Output

All streams are merged to create a polished, shareable report.

* **Consolidate Findings**  
  Combines sentiment, insights, and raw data.

* **Export to Google Sheets**  
  Generates a structured, actionable report in a connected Google Sheet.

---

## 🛠️ Technologies Used

This engine integrates the following tools and services:

* **Data Source:** [Reddit API](https://www.reddit.com/dev/api/)
* **AI Models:** [OpenAI API (Chat Models)](https://platform.openai.com/)
* **Output Format:** [Google Sheets API](https://developers.google.com/sheets/api)
* **Automation Platform:** e.g., [n8n](https://n8n.io), [Make](https://www.make.com/), or [Zapier](https://zapier.com)

---

## ⚙️ Getting Started

To replicate this workflow:

1. **Create accounts** on Reddit, OpenAI, and Google Cloud.
2. **Obtain API keys/credentials** for each service.
3. **Choose an automation platform** (n8n, Zapier, or Make).
4. **Build the workflow**, connecting the steps as described.
5. **Configure each node**:
   * Input your API keys
   * Set target subreddits and keyword filters
   * Link your destination Google Sheet


