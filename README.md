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
- **pip (Python package manager)**  

---

## ⚙️ Setup Instructions  

### 1️⃣ Install Dependencies  
Run the following command to install required libraries:  
```sh
pip install flask openai python-dotenv
```

### 2️⃣ Configure Environment Variables
Create a .env file in the project root directory and add your OpenAI API key:  
```sh
OPENAI_API_KEY=your_api_key_here
```

### 3️⃣ Ensure Template File Exists
Verify that the index.html file is inside the /templates directory:
```sh
/templates/index.html
```

### 4️⃣ Run the Chatbot Script
Start the chatbot server using:
```sh
python pschatbot.py
```
The Flask application will start, and you can access the chatbot in your web browser at:
```sh
http://127.0.0.1:5000/
```
