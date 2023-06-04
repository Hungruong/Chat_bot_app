# Chat_bot_app

Welcome to the Chat Bot App! This application allows users to engage in conversations with an advanced language processing chat bot. Whether you have questions, need assistance, or just want to have a friendly chat, our chat bot is here to help.

# Technical Overview

The Chat Bot App is built using the following technologies:
  Front-end: HTML, CSS, JavaScript
  Back-end: Node.js, Express.js
  Language Processing: OpenAI's GPT-3.0, trained with large-scale language models
  Version Control: Git
  Hosting: GitHub Pages
  
The front-end of the app is responsible for rendering the user interface and capturing user inputs, while the back-end handles the communication with the chat bot API and processes the responses.

# How to Install

To run the Chat Bot App locally on your machine, follow these steps:
  1. Clone the repository:
    git clone https://github.com/Hungruong/Chat_bot_app.git
  2. Navigate to the project directory:
    cd Chat_bot_app 
  3. Install dependencies:
    npm install

# Usage

Once the installation is complete, you can start using the Chat Bot App:

Adding .env file in the server folder: 
  PORT=1337
  PRIVATE_KEY=c9adff14-d3cf-4e82-ac92-1b2cd7a5d5e2
  PROJECT_ID=acde14a9-ba6b-475f-b2ee-ab42f2d4e842
  BOT_USER_NAME=AI_bot
  BOT_USER_SECRET=1234
  OPEN_API_NAME=Hung
  OPEN_API_KEY=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

Adding .env.local file in the client folder:
  VITE_BASE_URL=http://localhost:1337
  VITE_PROJECT_ID=acde14a9-ba6b-475f-b2ee-ab42f2d4e842

Start the application:
  npm run dev
Open your web browser and visit: http://localhost:5173

Engage in conversations with the chat bot through the app interface.
The chat bot is designed to understand and respond to a wide range of inquiries. Simply type your message in the chat input box and press Enter to send it. The chat bot will process your input and provide a relevant response.

# Features and Reasoning

The Chat Bot App offers the following features:
- Interactive Chat Interface: The app provides an intuitive and user-friendly chat interface for seamless conversations with the chat bot.
- Natural Language Processing: Powered by OpenAI's GPT-3.0 language model, the chat bot employs advanced NLP techniques to understand and respond to user inputs effectively.
- Personalized Responses: The chat bot adapts to each user, providing personalized and context-aware answers based on their preferences and interests.
- Knowledge Cutoff: The chat bot's responses are based on the knowledge it has acquired until September 2021. It may not have information on recent events or developments beyond that date.

# Support and Contributions

If you encounter any issues or have any questions, please feel free to open an issue on the GitHub repository.

Contributions to the Chat Bot App are welcome! If you'd like to contribute, please follow these steps:
  1. Fork the repository.
  2. Create a new branch:
    git checkout -b feature/your-feature
  3. Make your changes and commit them:
    git commit -am 'Add a new feature'
  4. Push to the branch:
    git push origin feature/your-feature
  5. Submit a pull request.

## License

    Copyright [2023] [Hung Truong]
