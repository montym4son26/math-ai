# Math AI Helper

## Setup

1. Install Node.js and npm
2. In terminal: `npm install` to install dependencies
3. Set your OpenAI API key as an environment variable:
   - Mac/Linux: `export OPENAI_API_KEY="sk-xxxx"`
   - Windows: `setx OPENAI_API_KEY "sk-xxxx"`
4. Start server locally: `node server.js`
5. Open `index.html` in browser to test

## Deploy

1. Push to GitHub
2. Deploy backend on Render/Railway/Vercel
3. Set OPENAI_API_KEY in environment variables
4. Replace `fetch` URL in `index.html` with your public backend URL