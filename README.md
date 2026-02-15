# 🇮🇳 Context-Setu: The Concept Localizer

> **Project for AI for Bharat Hackathon 2026**
>
> *Bridging the gap between Western Code and Indian Context.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Tech Stack](https://img.shields.io/badge/Tech-MCP%20%7C%20FastAPI%20%7C%20React-blue)](https://github.com/)
[![Hackathon](https://img.shields.io/badge/Track-AI%20for%20Learning-orange)](https://aws.amazon.com/)

---

## 🧐 The Problem
Millions of Indian students learn to code using tutorials written for a Western audience.
- They struggle to understand **"Baseball Statistics"** in Data Science.
- They get confused by **"Pizza Ordering Systems"** in OOPs.
- They find **"Stock Market Portfolios"** abstract.

This creates a **cognitive disconnect**. Students understand the *syntax* (English) but fail to grasp the *logic* because the underlying story is alien to their daily life.

## 💡 The Solution
**Context-Setu** (literally "Context Bridge") is an AI-powered "Pedagogical Localization" engine. It doesn't just translate language; it translates **Context**.

It intercepts technical documentation and code in real-time and rewrites them using **hyper-local Indian metaphors**—bridging the gap between abstract concepts and daily reality.

| Original Concept (Western) | Context-Setu Rewrite (Indian Context) |
| :--- | :--- |
| **Load Balancer** managing "Black Friday Traffic" | **Traffic Police** managing "Mumbai Ganpati Visarjan" |
| **Array Indexing** using "Baseball Innings" | **Tiffin Box Layers** (Dabba System) |
| **Dijkstra's Algo** on "New York Grid" | **Shortest Path** on "Delhi Metro Network" |

---

## ✨ Key Features

### 1. 🧠 The "Setu" Engine (Analogy Generator)
A powerful LLM-based engine that detects technical concepts (Recursion, APIs, OOPs) and swaps generic examples with culturally relevant stories (Bollywood, Cricket, Festivals, Agriculture).

### 2. 🔌 Model Context Protocol (MCP) Server
We go beyond the browser! Context-Setu runs as an **MCP Server**, meaning it works natively inside:
- **VS Code** (via extensions)
- **Claude Desktop**
- **Cursor IDE**
- **Terminal**

### 3. 🗺️ Geo-Spatial Visualization
For Data Structures & Algorithms (DSA), we ditch abstract circles.
- Learning Graphs? We plot nodes on a **Leaflet.js map of the Indian Railway Network**.
- "Find the shortest path from *Andheri* to *Dadar*."

### 4. 🧩 Browser Extension
A "Highlight & Explain" Chrome Extension for reading documentation (React Docs, AWS Whitepapers) without leaving the page.

---

## 🛠️ Tech Stack

- **Core Protocol:** [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) - Python SDK
- **AI/LLM:** AWS Bedrock (Claude 3 Haiku) / Gemini 1.5 Flash
- **Backend:** Python (FastAPI)
- **Frontend:** React.js (Vite), Tailwind CSS
- **Maps:** Leaflet.js + OpenStreetMap
- **Data:** JSON-based User Context Profiles

---

## 🚀 Installation & Setup

### Prerequisites
- Python 3.10+
- Node.js & npm
- An API Key (AWS Bedrock or Gemini)

### 1. Clone the Repo
```bash
git clone [https://github.com/your-username/Context-Setu.git](https://github.com/your-username/Context-Setu.git)
cd Context-Setu
```
### 2. Set up the Backend (MCP Server)
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

# Create a .env file and add your API Key
echo "API_KEY=your_key_here" > .env

# Run the MCP Server
python server.py
```
### 3. Set up the Frontend (Chrome Extension)
```bash
cd frontend
npm install
npm run build
```
Go to chrome://extensions, enable "Developer Mode", and click "Load Unpacked". Select the frontend/dist folder.

## 📄 License
Distributed under the MIT License. See LICENSE for more information.
