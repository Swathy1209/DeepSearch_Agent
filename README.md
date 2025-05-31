# 📘 OpenAI Deep Research Agent

A Streamlit-based tool that performs **deep web research** using the **OpenAI Agents SDK** and **Firecrawl**. This app lets you input any topic and get an AI-generated, multi-source, citation-rich research report — enhanced with real-world examples and deep insights.

---

## 🚀 Features

- 🔍 **Topic-based deep research** using Firecrawl's multi-source analysis
- 🤖 **Agent-based architecture** using OpenAI Agents SDK
- 📚 **Two specialized agents**:
  - `research_agent`: Performs deep web research and compiles a structured report
  - `elaboration_agent`: Enhances the report with deeper context, examples, and predictions
- 🧠 **Async processing** for responsive UI
- 📥 Download enhanced reports in Markdown format

---

## 🗂️ Project Structure

.
├── deep_research_openai.py # Main Streamlit application
├── requirements_deep.txt # Required Python packages

yaml
Copy
Edit

---

## 📦 Requirements

Install dependencies from `requirements_deep.txt`:

```bash
pip install -r requirements_deep.txt
requirements_deep.txt content:

txt
Copy
Edit
openai-agents
firecrawl
streamlit
firecrawl-py
🔑 API Keys Required
You need:

✅ OpenAI API Key (for agent communication)

✅ Firecrawl API Key (for deep web research)

Enter both via the Streamlit sidebar before running.

🧠 How It Works
1. research_agent
Uses the deep_research tool to gather and synthesize knowledge from the web

Parameters:

max_depth: 3

time_limit: 180 seconds

max_urls: 10

Generates a structured report with sources

2. elaboration_agent
Enhances the initial report by:

Expanding on complex points

Adding examples and case studies

Predicting trends

Structuring content for maximum clarity

💡 Example Topics
"Latest trends in generative AI"

"Impact of electric vehicles on oil demand"

"Regulations around data privacy in the EU"

"Open-source LLMs vs Proprietary LLMs"

🎯 How to Run
bash
Copy
Edit
streamlit run deep_research_openai.py
Then:

Enter both API keys in the sidebar

Type a research topic

Click "Start Research"

View and download the enhanced report

📥 Output
Enhanced, structured research report

Includes:

Summarized findings

Key takeaways

Source citations

Practical insights

Downloadable as .md file

📌 Notes
Make sure your API keys are active and valid

Requires Python 3.9+

Works best on desktop browsers for full layout experience

📄 License
MIT License — Free to use, modify, and distribute.

