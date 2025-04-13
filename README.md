# 🧠 Azure AI Language - Text Analysis App (Python)

![Azure](https://img.shields.io/badge/Azure-AI--Language-blue?logo=microsoftazure&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.7+-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)

Analyze text like a pro using the power of Azure AI Language services! This Python application demonstrates how to perform intelligent text analytics such as:
```bash

🔍 Language Detection
❤️ Sentiment Analysis  
📝 Key Phrase Extraction 
🏷️ Entity Recognition 
🌐 Linked Entity Recognition

```

---

## 📦 Features

- Detects the **language** a document is written in
- Evaluates the **sentiment** (Positive / Neutral / Negative)
- Extracts **key phrases** to summarize content
- Identifies **named entities** (people, places, etc.)
- Retrieves **linked entities** with Wikipedia references

---

## 🚀 Getting Started

### 1. ✅ Prerequisites

- ✅ Azure Subscription
- ✅ Azure AI Language Resource
- ✅ Python 3.7 or later
- ✅ Git + Visual Studio Code (recommended)

---

### 2. ⬇️ Clone the Repository

```bash

git clone https://github.com/MouryaSagar17/Text-Analysis-App-Python-.git
cd Python/text-analysis

```
---

### 3. 📦 Install Dependencies
``` bash

pip install azure-ai-textanalytics==5.3.0
pip install python-dotenv

```
---

### 4. ⚙️ Configure Environment
Create a .env file in the text-analysis folder with the following content:

``` env

AI_LANGUAGE_KEY=your-azure-language-key
AI_LANGUAGE_ENDPOINT=https://your-endpoint.cognitiveservices.azure.com/

```

Get these values from the Azure Portal > Your Language Resource > Keys and Endpoint.

---

### 5. ▶️ Run the App
``` bash

python text-analysis.py

```
---

Watch as the app processes each review file and reveals:
```bash

📌 Language

😊 Sentiment

🗝️ Key Phrases

👤 Entities

🔗 Linked Entities
``` 

### 📂 Project Structure

``` bash

text-analysis/
├── .env                  # Azure credentials
├── reviews/              # Sample review texts
├── text-analysis.py      # Main Python script

``` 
--- 

### 📘 Learn More

📄 Azure AI Language Overview

📊 Text Analytics in Azure

🧪 SDK Reference - Python

--- 

### 🧹 Clean Up Resources

Don't forget to delete your Azure resources when you're done to avoid unnecessary charges.

