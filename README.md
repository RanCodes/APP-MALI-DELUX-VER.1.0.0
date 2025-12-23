<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/drive/1opEp8cgkWuI9LzxoNlv40Ly4UgVr6Iwd

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Run with Docker

1. Create a `.env` file (you can copy from `.env.example`) and set your Gemini API key:
   ```bash
   cp .env.example .env
   echo "API_KEY=your_gemini_api_key" >> .env
   ```
2. Build and start the container:
   ```bash
   docker compose up --build
   ```
3. Open the app at [http://localhost:8080](http://localhost:8080).
