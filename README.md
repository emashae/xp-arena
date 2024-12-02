# XP Arena

XP Arena is a video game discovery web app that helps you find new and interesting games to play. With XP Arena, you can search for games by platform, genre, and more.

## Getting Started

To get started with XP Arena, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/emashae/xp-arena
   cd xp-arena
   ```

2. Install the required dependencies:

   ```bash
   npm install
   ```

3. Get a RAWG API key from [RAWG API](https://rawg.io/apidocs).

4. Create a `.env` file in the root of your project and add your API key:

   ```env
   VITE_RAWG_API_KEY=your_api_key_here
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure

- **`src/services/api-client.ts`**: The Axios instance is configured to use the API key stored in the `.env` file.
- The app uses `VITE_RAWG_API_KEY` to securely load the API key into the application.
