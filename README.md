# 🇮🇳 Code-Katha: The Story of Code

> **Project for AI for Bharat Hackathon 2026**
>
> *Turning complex Code into relatable Stories for India.*

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
**Code-Katha** (literally "Code Story") is an AI-powered "Pedagogical Localization" engine. It doesn't just translate language; it translates **Context**.

It intercepts technical documentation and code in real-time and rewrites them as **relatable Indian stories**—making complex concepts instantly intuitive.

| Original Concept (Western) | Code-Katha Rewrite (Indian Context) |
| :--- | :--- |
| **Load Balancer** managing "Black Friday Traffic" | **Traffic Police** managing "Mumbai Ganpati Visarjan" |
| **Array Indexing** using "Baseball Innings" | **Tiffin Box Layers** (Dabba System) |
| **Dijkstra's Algo** on "New York Grid" | **Shortest Path** on "Delhi Metro Network" |

---

## ✨ Key Features

### 1. 🧠 The "Katha" Engine (Analogy Generator)
A powerful LLM-based engine that detects technical concepts (Recursion, APIs, OOPs) and swaps generic examples with culturally relevant stories (Bollywood, Cricket, Festivals, Agriculture).

### 2. 🔌 Model Context Protocol (MCP) Server
We go beyond the browser! Code-Katha runs as an **MCP Server**, meaning it works natively inside:
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
