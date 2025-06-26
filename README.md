
👩🏽‍💻 Project Overview
This project demonstrates the use of OpenAI's GPT-3.5 model via API to build a Text Completion App using Python. The application accepts natural language prompts from the user and returns AI-generated responses in real-time.

It includes:

Interactive user prompts

Dynamic response generation

Basic error handling and input validation

Customizable settings for AI creativity and length (temperature, max_tokens)

🔧 Setup Instructions
1. Clone or download the project folder
Make sure you have Python 3.7+ installed.

2. Install dependencies
bash
Copy
Edit
pip install openai python-dotenv
3. Add your OpenAI API key
Create a .env file in the root of your project:

ini
Copy
Edit
OPENAI_API_KEY=your_api_key_here
4. Run the App
You can run either:

text_completion_app.py (script version)

text_completion_notebook.ipynb (Jupyter Notebook version)

🧪 Part 3: Experimentation & Evaluation Summary
Tested 5 prompt types (creative, instructional, informational, etc.)

Used different temperature and max_tokens values to explore response variation

Responses were evaluated for relevance, coherence, accuracy, and creativity

Findings:

GPT-3.5 is strong in general knowledge, creative writing, and simplified explanations.

It struggles with deeply logical reasoning or niche technical knowledge.

Higher temperature leads to more creative (but sometimes less accurate) output.

More tokens enable longer, more detailed responses.

📄 Files Included
File	Description
text_completion_app.py	Python script for the text completion app
text_completion_notebook.ipynb	Jupyter Notebook version
.env	API key storage (not included — you create this)
Generative_AI_Evaluation_Report.pdf	Experimentation report with 5 prompts and detailed analysis
README.md	This documentation

