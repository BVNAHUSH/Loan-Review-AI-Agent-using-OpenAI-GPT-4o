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
from google.colab import drive
drive.mount('/content/drive')
```
### 2. Install Required Packages (if needed)
```python
pip install openai pandas
```
### 3. Load Your Dataset
```
/content/drive/MyDrive/PROJECTS/Building an AI Agent using OpenAI API/loan_prediction.csv
```
### 4. Initialize OpenAI Client
```
from openai import OpenAI
client = OpenAI(api_key='YOUR_API_KEY')  # 🔐 Replace with your real API key
```
### 5.🧠 How It Works
1.Dataset Summary: Automatically summarizes the dataset (columns, datatypes, shape).

2.Prompt Creation: Builds a detailed prompt with dataset summary + user query.

3.OpenAI API Call: Sends prompt to GPT-4o and receives an intelligent response.

4.Conversational Loop: Lets the user interact with the agent until "exit" is typed.
### 🧪 Sample Interaction
<img width="794" height="576" alt="image" src="https://github.com/user-attachments/assets/b37145d4-b144-4e10-8c7d-6b3291f43a0e" />


### Some Visualizations
<img width="1024" height="1024" alt="3rd" src="https://github.com/user-attachments/assets/861c8f08-0e24-485e-8b1b-2571777b1b7b" />



### 📂 Folder Structure
```cpp
📁 PROJECTS
│
├── Building an AI Agent using OpenAI API
│   ├── loan_prediction.csv
│   └── loan_agent_colab.ipynb
```

### Quick running
```cpp
1.have a API Key from OPEN AI by creating one from their website.
2.Paste your API key in the .py  file.
3. run the overall project.
```
