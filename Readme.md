# 📊 Data Analysis with LLM and Langchain  
**AI-Powered Retail Sales Insights using LangChain & OpenAI**  

## 📌 Overview  
This project demonstrates how to use **Large Language Models (LLMs)** with **LangChain** for **automated data analysis**.  
It connects a **Pandas DataFrame agent** to a **retail sales dataset**, enabling users to perform **natural language queries** on the dataset without manual coding.  

Simply ask questions like:  
- *"What is the total sales for each category?"*  
- *"Which product had the highest sales in July?"*  
- *"Show me a trend of monthly revenue."*  

The LLM translates the query into Pandas operations and executes them.  

---

## 🚀 Features  
✅ **Natural Language Data Analysis**  
- Query datasets in plain English (no SQL/Pandas required).  

✅ **LangChain + OpenAI Integration**  
- Powered by `ChatOpenAI` and `create_pandas_dataframe_agent`.  

✅ **Retail Dataset Analysis**  
- Pre-loaded with `retail_sales_dataset.csv`.  
- Supports descriptive analytics and visualization.  

✅ **Google Colab Ready**  
- API key + dataset stored in Google Drive.  
- Easy setup for experimentation.  

---

## 🛠️ Installation  

1. **Clone the repository**  
```bash
git clone https://github.com/Arsalan80425/Data_Analysis_with_LLM_and_Langchain.git
cd Data_Analysis_with_LLM_and_Langchain
```

2. **Install dependencies**  
```bash
pip install -r requirements.txt
```

*(Or run directly in **Google Colab** with pre-installed dependencies.)*  

---

## ▶️ Usage  

1. Mount Google Drive in Colab and set the working path.  
2. Store your OpenAI API key inside `api/openai`.  
3. Upload your dataset (default: `data/retail_sales_dataset.csv`).  

Run the notebook:  
```bash
Data_Analysis_with_LLM_Main.ipynb
```

Ask queries like:  
- *"Show top 5 products by sales"*  
- *"Plot monthly revenue trends"*  
- *"Which store performed best in Q2?"*  

---

## 📂 Project Structure  
```
.
├── Data_Analysis_with_LLM_Main.ipynb   # Main Jupyter Notebook
├── data/
│   └── retail_sales_dataset.csv        # Sample dataset
├── api/
│   └── openai                          # File containing API key
└── README.md                           # Project documentation
```

---

## 📚 Tech Stack  
- **LLM**: OpenAI GPT (via LangChain)  
- **Framework**: LangChain Experimental Agents  
- **Data Handling**: Pandas  
- **Environment**: Google Colab + Drive  
- **Visualization**: Matplotlib, Pandas built-in plotting  

---

## 🏆 Achievements  
- Built an **LLM-powered Pandas agent** for real-time analytics.  
- Enabled **query-driven insights** without coding.  
- Demonstrated practical **GenAI x Data Science** workflow.  

---

### Contact Information
- **Developer**: Mohammed Arsalan  
- **Email**: arsalanshaikh0408@gmail.com  
- **LinkedIn**: [LinkedIn Profile](http://www.linkedin.com/in/mohammed-arsalan-58543a305)  

---

## 👨‍💻 Author  
Developed by **Mohammed Arsalan**  
🎯 Exploring the intersection of **AI, LLMs, and Data Science**  

