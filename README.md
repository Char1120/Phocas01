# PS Chatbot  

A simple AI-powered chatbot using Flask and OpenAI's API. This chatbot provides intelligent responses based on user queries.  
## 🚀 Features  
- Built with **Flask** for web-based interaction  
- Uses **OpenAI's GPT API** for generating responses  
- Supports environment variable configuration for security  
- Lightweight and easy to set up  

---

## 📌 Prerequisites  
Before you begin, ensure you have the following installed:  
- **Python 3.7+**  
  If you don’t have Python installed, download it from the official [Python website](https://www.python.org/downloads/). Follow the instructions for your operating system (Windows, macOS, or Linux).

- **pip (Python package manager)**  
  Most recent Python installers include `pip` by default. If `pip` is missing, follow the [official pip installation guide](https://pip.pypa.io/en/stable/installation/).
---

## ⚙️ Setup Instructions  

### 1️⃣ Install Dependencies  
Run the following command to install required libraries:  
```sh
pip install flask openai python-dotenv
```

### 2️⃣ Configure Environment Variables
To modify OpenAI API key, go to .env file in the project root directory:  
```sh
OPENAI_API_KEY=valid_api_key_here
```

### 3️⃣ Ensure Template File Exists
Verify that the index.html file is inside the /templates directory:
```sh
/templates/index.html
```

### 4️⃣ Run the Chatbot Script
Start the chatbot server using:
```sh
python ps-prompt.py
```
The Flask application will start, and you can access the chatbot in your web browser at:
```sh
http://127.0.0.1:5000/
```
---

## ✨ How It Works 
1. Open a web browser and go to http://127.0.0.1:5000/.
2. Enter your query in the Query text box.
3. Click on Send button and chatbot will display response generated by OpenAI's API.


## 🗂 Project Structure 
/ps-code-exercise
│── /templates
│   └── index.html
│── .env
│── ps-prompt.py
│── README.md

