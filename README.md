# Enhanced Cybersecurity Chatbot

This is a C# console application designed to provide users with information and guidance on various cybersecurity topics. The chatbot aims to be helpful and informative, and it even attempts to understand the user's sentiment to provide more appropriate responses.

## Features

* **Keyword-Based Responses:** The chatbot recognizes specific keywords in user input (e.g., "password", "scam", "privacy") and provides relevant information.
* **Topic-Based Responses:** The chatbot offers detailed information on pre-defined cybersecurity topics, including:
    * "phishing tips"
    * "malware advice"
    * "safe browsing habits"
* **Follow-up Question Handling:** If a user asks for more information (e.g., "more detail", "explain further", "I'm confused"), the chatbot will attempt to provide additional details on the previously discussed topic.
* **Sentiment Recognition:** The chatbot tries to identify the user's sentiment (e.g., "worried", "curious", "frustrated", "unsure", "overwhelmed") and offers supportive or encouraging responses.
* **Basic Conversation Handling:** The chatbot can handle basic conversational elements like:
    * Greetings ("hello", "hi")
    * Farewells ("goodbye", "bye")
    * Acknowledgement of gratitude ("thank you", "thanks")
* **Formatted Output:** The chatbot uses colored text and a typewriter effect in the console to improve readability and user experience.
* **Optional ASCII Art:** The chatbot attempts to display ASCII art from a file named `ascii-art.txt` located in the user's Downloads folder. If the file is not found, a default header is displayed.
* **Personalized Greeting:** The chatbot greets the user by their name after they provide it.
* **Example Questions:** The chatbot suggests a list of questions that the user can ask to get started.

## Getting Started

### Prerequisites

* [ .NET SDK](https://dotnet.microsoft.com/download) (Version 6.0 or later is recommended)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone <YOUR_REPOSITORY_URL>
    cd EnhancedCybersecurityChatbot
    ```
    (Replace `<YOUR_REPOSITORY_URL>` with the actual URL of your GitHub repository.)

2.  **Build the application:**
    ```bash
    dotnet build
    ```

## Usage

1.  **Run the application:**
    ```bash
    dotnet run
    ```
2.  **Interact with the chatbot:** The application will prompt you to enter your name. After that, you can ask questions about cybersecurity.

    Example:

    ```
    You: Tell me some phishing tips.
    Bot: Be wary of emails from unknown senders...
    ```

## Example Interaction

Welcome to the Enhanced Chatbot!Please enter your name: AliceHello, Alice! I'm here to help you learn about cybersecurity.You: What is malware advice?
Bot: Install and keep your antivirus software up to date.You: Explain further.Bot: Be cautious when downloading files from the internet, especially from untrusted sources.You: I'm worried about online scams.Bot: It's completely understandable to feel that way. Scammers can be very convincing. Let me share some tips to help you stay safe.
## Contributing

Contributions are welcome! If you'd like to improve this chatbot, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes.
4.  Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE) .

## Future Enhancements

* Expand the knowledge base with more cybersecurity topics and responses.
* Implement more advanced Natural Language Processing (NLP) for better understanding of user input.
* Improve the sentiment analysis to be more accurate and handle a wider range of emotions.
* Add a logging mechanism to track conversations and errors.
* Consider adding a simple GUI.

## Author

* [Lisakhanya](https://github.com/ST10437798)

## Acknowledgments

* This project was inspired by the need for increased cybersecurity awareness.
* The C# programming language and the .NET framework were used to develop this application.
