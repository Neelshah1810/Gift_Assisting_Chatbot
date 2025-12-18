# Gifting Assistant

This project is a web application that provides personalized gift suggestions using an AI-powered chatbot. It was created by Team Cyber Crafters.

## Description

The Gifting Assistant helps users find the perfect gift by asking for details about the recipient and the occasion. The user provides information such as:

*   Occasion (e.g., Birthday, Anniversary)
*   Relationship with the recipient
*   Recipient's age and interests
*   Budget
*   Preferences on uniqueness, personalization, price, and more.

The application then sends this information to the Groq API, which uses the Llama 3.1 model to generate tailored gift suggestions. The user can also chat with the assistant to ask for more ideas or refine the recommendations.

The project consists of two main pages:
*   A home page that introduces the "Cyber Crafters" team and their projects.
*   A "Gifting Assistant" page where users can get gift ideas.

## Technology Stack

*   **Backend:** Flask
*   **Frontend:** HTML, CSS, JavaScript
*   **AI:** Groq API (Llama 3.1 model)

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/gifting-assistant.git
    cd gifting-assistant
    ```

2.  **Create a virtual environment and activate it:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Create a `.env` file** in the root directory and add your Groq API key:
    ```
    GROQ_API_KEY=your_api_key_here
    ```

5.  **Run the application:**
    ```bash
    python app.py
    ```

6.  Open your web browser and go to `http://127.0.0.1:5000` to view the application.

## Usage

1.  Navigate to the "Gifting Assistant" page.
2.  Fill out the form with the required details.
3.  Click "Get Suggestions" to receive gift ideas from the AI.
4.  Use the chatbox to ask follow-up questions or get more recommendations.
