<<<<<<< HEAD
# notime
=======
# Notime - AI-Powered Note Taking App

A modern note-taking application with AI-powered summarization and idea clustering.

## Features

- Create text, image, and voice notes
- AI-powered summarization and analysis
- Automatic idea clustering
- Beautiful, responsive UI
- Search functionality

## Setup

1. **Prerequisites**
   - Node.js v20 (recommended)
   - An OpenAI API key (get one at https://platform.openai.com/api-keys)

2. **Installation**
   ```bash
   # Install dependencies
   npm install
   ```

3. **Environment Setup**
   Create a `.env` file in the root directory with:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

4. **Running the App**
   ```bash
   # Start the development server
   npm run dev
   ```
   The app will be available at http://localhost:5000

## Usage

- **Creating Notes**: Click the "New Note" button to create text, image, or voice notes
- **Searching**: Use the search bar to find specific notes
- **Reflecting**: Use the "Reflect" feature to see AI-generated clusters of related ideas
- **Viewing**: Click on any note to view its details and related notes

## AI Features

Note: AI features (summarization, clustering, image analysis) require a valid OpenAI API key. Without it, the app will still work but with limited functionality:
- Basic text notes will work
- Manual summaries will be used instead of AI-generated ones
- Basic text similarity will be used for clustering instead of AI embeddings
>>>>>>> ecc40d4 (Add OpenAI API key integration and improve user experience by adding error handling and a README with setup instructions.)
