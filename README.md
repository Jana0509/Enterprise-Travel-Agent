# Enterprise-Travel-Agent
AI-Powered Multi-Agent System using Amazon Bedrock

Here’s a **clean, copy-paste-ready README.md** (no extra formatting, no distractions):

---

# 🚀 Enterprise Travel Agent

### AI-Powered Multi-Agent System using Amazon Bedrock

An intelligent **multi-agent enterprise assistant** that automates HR and travel workflows using **Amazon Bedrock Agents** and a cloud-native architecture.

---
## Architecture

<img width="1636" height="804" alt="Screen Recording 2026-04-26 at 8 11 45 PM" src="https://github.com/user-attachments/assets/e6d19865-9eec-438e-8d83-3610cf2dfe00" />



## 📌 Overview

The **Enterprise Travel Agent** enables employees to:

* 📄 Query HR policies
* 🗓️ Check leave balances
* 🏨 View hotel room details
* 🔍 Check availability
* ✅ Book rooms

All through a **single conversational AI interface**.

---

## 🎯 Problem

In most enterprises:

* Employees switch between multiple systems
* HR queries take time
* Travel booking is manual
* Data is scattered

👉 Result: Low productivity and poor experience

---

## 💡 Solution

This project uses **Multi-Agent AI Architecture** to:

* Understand user intent
* Route requests to specialized agents
* Retrieve knowledge (RAG)
* Execute real backend actions

---

## 🧠 Architecture

### Components

* **Supervisor Agent**

  * Orchestrates the entire workflow
  * Routes user queries

* **HR Agent**

  * Handles HR policies and leave balance

* **Hotel Booking Agent**

  * Handles room details, availability, booking

* **Action Groups**

  * Execute backend APIs (via Lambda + OpenAPI YAML)

* **Knowledge Bases**

  * HR Policy Documents
  * Hotel Room Data

---

## ⚙️ Tech Stack

### Frontend

* Streamlit (chat-based UI)

### Backend / AI

* Amazon Bedrock Agents
* Nova Pro Model
* Multi-Agent Orchestration

### AWS Services

* AWS Lambda
* Amazon S3
* Bedrock Knowledge Base
* API Gateway (optional)

### Integration

* OpenAPI (YAML)

---

## 🔄 Workflow

1. User sends query via UI
2. Supervisor Agent detects intent
3. Routes to HR Agent or Hotel Agent
4. Agent retrieves knowledge or calls APIs
5. Response is returned to user

---

## 🧪 Example Queries

### HR

* "What is my leave balance?"
* "Show HR policy for sick leave"

### Travel

* "Show available rooms in Bangalore"
* "Book a room for tomorrow"

---

## 📸 Architecture Diagram

Add your diagram here:

![Architecture](./architecture.png)

---

## 🛠️ Setup Instructions

### Prerequisites

* AWS Account
* Bedrock access enabled
* Python 3.9+
* Streamlit

---

### 1. Clone Repo

git clone [https://github.com/your-username/enterprise-travel-agent.git](https://github.com/your-username/enterprise-travel-agent.git)
cd enterprise-travel-agent

---

### 2. Create Virtual Environment

python -m venv venv

Mac/Linux:
source venv/bin/activate

Windows:
venv\Scripts\activate

---

### 3. Install Dependencies

pip install -r requirements.txt

---

### 4. Configure AWS

aws configure

Make sure you have:

* Bedrock access
* Proper IAM permissions

---

### 5. Run Application

streamlit run app.py

---

## 🔐 IAM Permissions

* Bedrock access
* Lambda execution role
* S3 read access
* API Gateway invoke access

---

## 📁 Project Structure

enterprise-travel-agent/

├── app.py
├── agents/
│   ├── supervisor_agent.py
│   ├── hr_agent.py
│   └── hotel_agent.py
│
├── lambda/
│   ├── leave_balance/
│   ├── room_availability/
│   └── booking/
│
├── knowledge-base/
│   ├── hr-policy/
│   └── hotel-data/
│
├── openapi/
│   ├── leave.yaml
│   ├── availability.yaml
│   └── booking.yaml
│
├── architecture.png
└── README.md

---

## 🚀 Future Enhancements

* Authentication (Cognito)
* Payment integration
* Flight & cab booking
* Memory for personalization
* Multi-language support
* Voice interface

---

## 📊 Business Impact

* Reduces manual effort
* Improves employee experience
* Enables self-service workflows
* Scalable across departments

---

## 🤝 Contributing

Feel free to fork and raise PRs.

---

## 📬 Contact

Add your details here:

* LinkedIn
* Email

---

## ⭐ Support

If you like this project:

* Star ⭐ the repo
* Share with others

---

## 🧠 Final Thought

The future of enterprise applications is not dashboards…
It’s **AI agents that understand, decide, and act.** 🚀
