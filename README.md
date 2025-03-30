UPSC & MPSC Question Generator

📌 Project Overview

This project is an AI-powered UPSC & MPSC Question Generator built using Streamlit, LangChain, Pydantic, and Groq's LLM. It generates Multiple Choice Questions (MCQs) and Fill-in-the-Blank questions based on a given topic and difficulty level.

🚀 Features

AI-Powered Question Generation: Uses Groq's LLM (Llama-3.1-8B-Instant) to generate questions.

MCQs & Fill-in-the-Blank: Supports two types of questions.

Dynamic Difficulty Levels: Choose between Easy, Medium, and Hard questions.

Quiz Attempt & Evaluation: Users can attempt the quiz, receive instant feedback, and save results.

CSV Export: Saves quiz results for further analysis.

🛠️ Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-username/upsc-mpsc-question-generator.git
cd upsc-mpsc-question-generator

2️⃣ Create a Virtual Environment

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Set Up Environment Variables

Create a .env file in the project root and add your Groq API Key:

GROQ_API_KEY=your_api_key_here

5️⃣ Run the Application

streamlit run app.py

🖥️ Usage

Enter the topic for questions (e.g., Indian History, Geography, Science, etc.).

Select the question type (MCQ or Fill in the Blank).

Choose difficulty level (Easy, Medium, or Hard).

Click Generate Quiz to create a quiz.

Attempt the quiz and submit your answers.

View your quiz results and save them as CSV.

📂 Project Structure
├── utils.py           # Question generation logic using LangChain & Groq
├── app.py             # Streamlit app for the quiz interface
├── requirements.txt   # Required Python libraries
├── .env               # API key storage (not to be shared)
├── README.md          # Project documentation (this file)
└── results/           # Folder for storing quiz results (generated dynamically)

📌 Contributing

Fork the repository.

Create a new branch: git checkout -b feature-branch

Commit your changes: git commit -m 'Add new feature'

Push to the branch: git push origin feature-branch

Open a Pull Request.
💡 Acknowledgments

LangChain for seamless LLM integration.

Streamlit for interactive UI development.

Groq for powerful question generation using LLM.
