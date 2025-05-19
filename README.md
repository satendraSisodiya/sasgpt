# SASGPT Chat Application

**SASGPT** is an AI-powered chat application developed as a final-year project at **BKIT**. It enables users to interact with a conversational AI model, offering concise answers for general queries and detailed explanations for programming-related questions.

---

## 🚀 Features

- **User-Friendly Interface** – Seamless interaction with the AI.
- **Concise Responses** – Short answers for general questions.
- **Detailed Explanations** – In-depth output for technical queries.
- **Code Block Support** – Syntax-highlighted code in responses.

---

## 📦 Prerequisites

Make sure the following are installed on your system:

- [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- Python 3.11+

---

## 🛠️ Setup Instructions


# Step 1: Create Conda environment

```bash
conda create -n gptenv python=3.11 -y
```
# Step 2: Activate the environment

```bash
conda activate gptenv
```

# Step 3: Clone the repository

```bash
git clone https://github.com/satendraSisodiya/sasgpt.git
cd sasgpt
```

# Step 4: Install dependencies

```bash
pip install -r requirements.txt
```

# Step 5: Create a .env file (see below)

# Step 6: Run the application

```bash
python app.py
```

---

## 📁 Project Structure

sasgpt/
├── app/                 # Main application code
├── config/              # Configuration files
├── logger/              # Logging utilities
├── app.py               # Application entry point
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

---

## 🧰 Technologies Used

- **Python 3.11**: Core programming language.
- **GROQ API**: Used for processing user queries with powerful AI capabilities.
- **Flask**: Web framework for handling HTTP requests and responses.
- **Other Dependencies**: Listed in `requirements.txt`.

---

## 🔐 Environment Variables

Create a `.env` file in the root directory and add the following:

```env
GROQ_API_KEY=your_groq_api_key_here
```
⚠️ Replace your_groq_api_key_here with your actual GROQ API key.

---

## 🤝 Contribution

Contributions are welcome! If you'd like to enhance the application or fix issues:

- Fork the repository.
- Create a new branch:

  ```bash
  git checkout -b feature-name
  ```
  
- Commit your changes:

  ```bash
  git commit -m 'Add new feature'
  ```
  
- Push to the branch:

  ```bash
  git push origin feature-name
  ```
  
- Open a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgments

Developed by **Satendra Sisodiya** and team as part of the **final-year project at BKIT**.

---

### **Usage:**

Once the application is running, open your web browser and navigate to `http://127.0.0.1:5000/` to access the chat interface. You can start asking questions, and the AI will respond based on your input.

