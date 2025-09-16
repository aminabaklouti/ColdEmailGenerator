### 📧 Cold Mail Generator
Cold email generator for services company using groq, langchain and streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions.

Imagine a scenario:

Nike needs a Principal Software Engineer and is spending time and resources in the hiring process, on boarding, training etc
Atliq is Software Development company can provide a dedicated software development engineer to Nike. So, the business development executive (Mohan) from Atliq is going to reach out to Nike via a cold email.
<img width="1364" height="869" alt="image" src="https://github.com/user-attachments/assets/717afb68-3155-458d-8afa-7bf968167736" />
## Workflow Diagram
<img width="1335" height="590" alt="image" src="https://github.com/user-attachments/assets/5f5352ea-10ec-434d-97ba-8728125b3db2" />
## Setup

1. **Get an API Key**  
   - Go to [Groq Console](https://console.groq.com/keys) and create a new API key.  
   - Inside the `APP/.env` file, set your key:  
     ```env
     GROQ_API_KEY=your_api_key_here
     ```

2. **Install Dependencies**  
   Make sure you have Python 3.8+ installed, then run:  
   ```bash
   pip install -r requirements.txt
3. **Run the Streamlit App**
   streamlit run app/main.py





