# Job-Recommender-System
# 🤖 AI Job Recommender System

An AI-powered job recommender system that analyzes your **resume** and provides personalized **career insights** and **job opportunities**.  
Built with **Streamlit**, **OpenAI LLM**, **MCP**, and job APIs from **LinkedIn** & **Naukri.com**.

---

## ✨ Features

- 📑 **Resume Analysis**
  - Summarizes your skills, education, and experience.
- 🛠️ **Skill Gap Detection**
  - Highlights missing skills, certifications, or experiences.
- 🚀 **Career Roadmap**
  - Suggests future learning paths, certifications, and industry exposure.
- 💼 **Job Recommendations**
  - Fetches job opportunities directly from **LinkedIn** and **Naukri.com**.
  - Uses **OpenAI LLM** + **MCP** to generate personalized insights.

---

## 🛠️ Tech Stack

- **Frontend:** [Streamlit](https://streamlit.io/) – interactive UI  
- **LLM Integration:** [OpenAI API](https://platform.openai.com/) + [MCP (Model Context Protocol)](https://modelcontextprotocol.io/)  
- **Resume Parsing:** [PyMuPDF](https://pymupdf.readthedocs.io/en/latest/) – extract text from PDF resumes  
- **Environment Management:** [python-dotenv](https://pypi.org/project/python-dotenv/) – manage API keys securely  
- **Job Search APIs:**  
  - [Apify Client](https://docs.apify.com/api/client/python) – fetch LinkedIn job postings  
  - Naukri.com API – fetch job recommendations from Naukri  

---

🚀 Usage

Run the Streamlit app:
streamlit run app.py

Upload your resume (PDF) and explore:

📑 Resume Summary

🛠️ Skill Gaps & Missing Areas

🚀 Career Roadmap

💼 Personalized Job Recommendations (LinkedIn + Naukri)

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

👨‍💻 Author

Ranjan Yadav
GitHub-https://github.com/Ranjan83711
LinkedIn-https://www.linkedin.com/in/ranjan-k/