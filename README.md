# AI_HealthyChatBot

An AI-powered chatbot designed to provide healthy food suggestions, with a special focus on traditional Indian cuisine. Built with **React** and **Node.js**, this project leverages the **OpenAI/OpenRouter API** to offer a conversational and user-friendly experience for anyone looking for nutritional advice.

---

### **Table of Contents**
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [API Key Setup](#api-key-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

### **🌟 Features**

- **Intelligent Food Suggestions**: Get personalized healthy food and diet recommendations.
- **Indian Cuisine Focus**: Specialized knowledge of traditional Indian recipes and their nutritional benefits.
- **Conversational AI**: Powered by cutting-edge language models for natural and engaging interactions.
- **User-Friendly Interface**: A clean and intuitive UI built with React.

---

### **🛠️ Technologies Used**

- **Frontend**: React
- **Backend**: Node.js
- **AI**: OpenAI / OpenRouter API
- **Package Manager**: npm

---

### **🚀 Installation**

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/AI_HealthyChatBot.git](https://github.com/YourUsername/AI_HealthyChatBot.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd AI_HealthyChatBot
    ```
3.  **Install dependencies for the backend:**
    ```bash
    cd server
    npm install
    ```
4.  **Install dependencies for the frontend:**
    ```bash
    cd ../client
    npm install
    ```

---

### **🔑 API Key Setup**

This project requires an API key to access the AI models.

1.  Obtain an API key from either [OpenAI](https://openai.com/) or [OpenRouter](https://openrouter.ai/).
2.  In the `server` directory, create a new file named `.env`.
3.  Add your API key to the `.env` file in the following format:
    ```
    OPENAI_API_KEY=your_api_key_here
    ```
    *(If using OpenRouter, replace `OPENAI_API_KEY` with `OPENROUTER_API_KEY`)*

---

### **💻 Usage**

Follow these steps to run the chatbot.

1.  **Start the backend server:**
    ```bash
    cd server
    npm start
    ```
    The server will run on `http://localhost:5000` (or the port specified in your code).

2.  **Start the frontend application:**
    ```bash
    cd ../client
    npm start
    ```
    The app will open in your default browser at `http://localhost:3000`.

---

### **🤝 Contributing**

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

### **📄 License**

Distributed under the MIT License. See `LICENSE` for more information.

---

### **Contact**

- **Your Name/GitHub Profile**: https://github.com/jyothsnaPeruri
- **Project Link**: `https://github.com/jyothsnaPeruri/AI_HealthyChatBot`
