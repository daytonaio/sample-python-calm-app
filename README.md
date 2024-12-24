# C.A.L.M - AI-Powered Mental Health and Emotional Support Chatbot for Students

This repository contains the source code for C.A.L.M, an AI-powered mental health and emotional support chatbot designed specifically for students. The chatbot leverages the Gemini language model to provide responses to user queries in a conversational manner.

## 🚀 Project Overview
C.A.L.M is designed to assist students by providing mental health and emotional support through conversational AI. The chatbot ensures a supportive and user-friendly experience, maintaining a history of interactions and offering real-time responses. With its streamlined interface powered by Streamlit, it is both intuitive and effective.

---

## 🌟 Features

- **Conversational Support**: Provides mental health and emotional support tailored to student needs.
- **Real-Time AI Responses**: Utilizes the Gemini language model for accurate and context-aware answers.
- **Session-Based Chat History**: Retains chat history for a seamless user experience.
- **Streamlit Framework**: Ensures a user-friendly and visually appealing interface.
- **Daytona Integration**: Leverages the Daytona framework for efficient model deployment and optimized performance.

---

## 🛠️ Getting Started

### Prerequisites

Before running the application, ensure you have the following installed:
- **Python 3.12** or higher
- **pip** (Python package installer)

---

### Installation

#### 1.  Install Daytona
Follow the [Daytona installation guide](https://github.com/daytonaio/daytona#installation) to set up Daytona on your system.

#### 2. Create the Workspace
Run the following command to create your workspace:
```bash
daytona create https://github.com/daytonaio/sample-python-calm-app
```

---

#### 3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

#### 4. **Set Up Environment Variables**:
   - Create a `.env` file in the project root directory.
   - Add your Google API key:
  ```bash
    GOOGLE_API_KEY=your_api_key_here
   ```

#### 5. **Run the Application**:
   ```bash
   streamlit run app.py
   ```
   Open the application in your browser at `http://localhost:8501` (default).

---

## 🚦 Usage

1. Launch the application using the command:
   ```bash
   streamlit run app.py
   ```
2. Interact with the chatbot by entering your questions or concerns in the input field.
3. Continue the conversation seamlessly as the chatbot provides supportive and empathetic responses.

---https://github.com/CodeProcastinator/

## 📂 Project Structure

- **`app.py`**: Main application file for running the chatbot.
- **`.env`**: Stores sensitive environment variables, including the API key.
- **`requirements.txt`**: Contains all dependencies required for the project.

---

## 🛡️ Contributing

We welcome contributions to make C.A.L.M even better! If you want to contribute:

1. Fork the repository on GitHub.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push your branch and open a pull request:
   ```bash
   git push origin feature-name
   ```

Ensure your code is well-documented and follows the project’s coding standards.

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 📧 Contact

For questions, suggestions, or feedback, please reach out to:
- **Email**: srinathdilliraj@gmail.com

---

## 🚀 Future Enhancements

- **Multi-Language Support**: Enable responses in various languages.
- **Persistent Storage**: Store chat history across sessions.
- **Improved Emotional Intelligence**: Enhance the chatbot’s ability to detect and respond to emotional cues.
- **Mobile Compatibility**: Optimize for mobile devices.
- **Enhanced Daytona Integration**: Further utilize Daytona for scaling and additional performance optimization.

---

Thank you for exploring C.A.L.M! We hope this tool supports you in meaningful ways.

