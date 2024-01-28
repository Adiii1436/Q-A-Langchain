## Conversational Q&A Chatbot with Streamlit, LangChain, and OpenAI

This GitHub project showcases the implementation of a conversational question-and-answer (Q&A) chatbot using Streamlit, LangChain, and OpenAI. The chatbot is designed to engage in natural language conversations, providing responses to user queries in a dynamic and interactive manner.

### Features:

1. Streamlit User Interface:
The chatbot comes with a user-friendly Streamlit interface, making it easy for users to interact with the conversational AI.

2. LangChain Integration:
The project leverages the LangChain library to define and handle different message types within the conversation, such as HumanMessage, SystemMessage, and AIMessage.

3. OpenAI Model:
Utilizes OpenAI's powerful GPT-3.5 architecture for generating responses to user inputs. The temperature parameter is set to 0.5 to control the randomness of the model's output.

4. Dynamic Conversation Flow:
The chatbot maintains a dynamic conversation flow by storing and updating a list of messages exchanged between the user and the AI. This flow is crucial for providing context-aware responses.

5. System Messages:
Introduces system messages to set the tone of the conversation. In the provided code, the chatbot starts with a SystemMessage stating that it is a comedian AI assistant.

### How to Use:

1. Clone the GitHub repository to your local machine using the provided link.<br>
``` git clone https://github.com/Adiii1436/Q-A-Langchain.git ```

2. Ensure you have the required dependencies installed. You may use a virtual environment for this.<br>
```pip install -r requirements.txt```

3. Configure OpenAI API:
Obtain OpenAI API credentials and set them as environment variables or update the code accordingly.

4. Execute the Streamlit application to start the chatbot.<br>
```streamlit run app.py```

5. Interact with the Chatbot:
Open your web browser and navigate to the provided local address. Input questions in the text box and click the "Ask the question" button to receive responses.

### Contributions and Issues:
Contributions to enhance the chatbot's capabilities, improve the user interface, or fix any issues are welcome. Please fork the repository, make your changes, and submit a pull request.

If you encounter any bugs or have suggestions for improvement, feel free to open an issue on the GitHub repository.

