# AI Interview Simulator

An AI-powered interview practice tool that simulates a real job interview and provides automated feedback on candidate responses.

The application uses a Large Language Model to act as an HR interviewer. It asks structured interview questions based on the user's experience, skills, and target role. After the interview is completed, the system analyzes the responses and generates a performance score and feedback to help users improve their interview skills.

# Features

• Simulated HR interview conversation
• Personalized interview questions based on user profile
• Real-time chat interface
• Automated performance scoring
• AI-generated feedback after the interview
• Restart interview functionality

# How It Works

1. The user enters personal details including:

   * Name
   * Experience
   * Skills

2. The user selects:

   * Job level (Junior, Mid-level, Senior)
   * Target position
   * Company

3. The AI interviewer:

   * Asks **4 structured interview questions**
   * Waits for the candidate to respond before asking the next question

4. After the interview:

   * The conversation is analyzed by an LLM
   * A score (1–10) and structured feedback are generated

# Tech Stack

**Frontend / App Interface**

* Streamlit

**AI & Backend**

* OpenAI API
* GPT-4o model

**Programming Language**

* Python

**Additional Libraries**

* streamlit-js-eval (for restarting the session)

⭐ If you find this project helpful, feel free to star the repository.
