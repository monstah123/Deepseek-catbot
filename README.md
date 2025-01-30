# Deepseek-catbot
testing Deepseek api

### Prerequisites:
1. **OpenAI API Key**: You need to have an OpenAI API key. You can get one by signing up at [OpenAI](https://beta.openai.com/signup/).
2. **Install OpenAI Python Package**: You need to install the OpenAI Python package. You can do this using pip:
   ```bash
   pip install openai
   ```

How It Works:
1. **API Key**: Replace `'your-openai-api-key'` with your actual OpenAI API key.
2. **Engine**: The script uses the `text-davinci-003` engine, but you can switch to other engines like `gpt-3.5-turbo` if you prefer.
3. **User Input**: The script continuously takes user input and sends it to the OpenAI API.
4. **Chatbot Response**: The script prints the chatbot's response to the console.
5. **Exit**: The conversation ends when the user types `exit`.

### Running the Script:
1. Save the script to a file, e.g., `chatbot.py`.
2. Run the script using Python:
   ```bash
   python chatbot.py
   ```
3. Start chatting with the chatbot!

### Example Conversation:
```
Welcome to the OpenAI Chatbot! Type 'exit' to end the conversation.
You: Hello, how are you?
Chatbot: I'm just a program, so I don't have feelings, but I'm here to help you! How can I assist you today?
You: Can you tell me a joke?
Chatbot: Sure! Why don't scientists trust atoms? Because they make up everything!
You: exit
Goodbye!
```

This is a basic implementation. You can extend it by adding more features like context management, handling different types of user inputs, or integrating it into a web application.
  


