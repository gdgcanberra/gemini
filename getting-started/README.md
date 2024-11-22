# Gemini API Node.js Integration

This project demonstrates how to integrate Google's Gemini AI into a Node.js application.

## Prerequisites

- Node.js installed on your system
- Google Cloud Platform (GCP) account
- Gemini API key

## Setup

1. **Google Cloud Platform Setup**
   - Create a GCP account at [Google Cloud Console](https://console.cloud.google.com)
   - Enable the Gemini API for your project
   - Create an API key in the "Credentials" section

2. **Project Installation**
   ```bash
   # Install dependencies
   npm install @google/generative-ai
   ```

3. **Environment Setup**
   Create a `.env` file in the root directory:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```

## Running the Application

1. **Start the Application**
   ```bash
   npm start
   ```

2. **What to Expect**
   - The application will initiate a conversation with Gemini AI
   - You'll see the AI's response streamed to your console
   - The default prompt is "Hello, how are you doing?"

3. **Modifying the Code**
   - Open `src/index.ts` to modify the prompt or change the model parameters
   - The code uses the `gemini-1.5-flash` model, which is optimized for quick responses
   - You can experiment with different prompts by changing the text in `generateContentStream()`

## Resources

- [Gemini API Documentation](https://ai.google.dev/gemini-api/docs)
- [Prompting Guide](https://www.promptingguide.ai/)

## Contributing

Feel free to submit issues and enhancement requests!
