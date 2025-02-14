# Tripwise - AI-Powered Trip Planner 🌍✈️

Tripwise is an AI-powered travel planner that creates personalized travel itineraries using React, Gemini AI, Firebase, and TailwindCSS.  It offers a streamlined and intelligent way to plan your next adventure. 🚀

## Features 🌟

*   **AI-Driven Trip Generation:**  Uses advanced AI algorithms to generate customized travel plans based on your preferences, budget, and desired destinations. 🧠✨
*   **Personalized Hotel Recommendations:** Suggests the best accommodations based on your needs, ensuring a comfortable and enjoyable stay. 🏨💤
*   **Detailed Itinerary Planning:** Creates a well-structured schedule for your trip, including must-visit attractions and activities. 📅🗺️
*   **Google Maps Integration:** Visualize your travel plans and navigate easily with the seamless integration of Google Maps. 🗺️🚗
*   **Secure Authentication:** Protect your travel plans and personal data with the robust Google OAuth authentication system. 🔒🔐

### Technologies Used 💻

*   JavaScript
*   Google Maps API
*   Vite
*   Google OAuth
*   ShadCn UI
*   Firebase
*   Tailwind CSS

## Getting Started 🚀

To run Tripwise locally, follow these steps:

1.  **Clone the repository:** 

    ```
    git clone https://github.com/sahilbambarkar/Tripwise-AI-Trip-Planner.git
    cd Tripwise-AI-Trip-Planner
    ```

2.  **Install Dependencies:**

    ```
    npm install
    # or
    yarn install
    # or
    pnpm install
    # or
    bun install
    ```

3.  **Set up Environment Variables:**

    *   Create a `.env.local` file in the project root.
    *   Add your Google Maps API, Gemini AI Key, and Google OAuth client ID to the file:

        ```
        GOOGLE_MAPS_API_KEY=your-google-maps-api-key
        VITE_GOOGLE_GEMINI_AI_API_KEY=your-gemini-ai-api-key
        VITE_GOOGLE_AUTH_CLIENT_ID=your-google-oauth-client-id
        ```

    *   **Important:** Replace `your-google-maps-api-key`, `your-gemini-ai-api-key`, and `your-google-oauth-client-id` with your actual API keys and client ID.  Make sure you have enabled the necessary APIs (Google Maps, Gemini API) in your Google Cloud Console and obtained the appropriate credentials.

4.  **Run the Development Server:**

    ```
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    # or
    bun dev
    ```

5.  **Open in Browser:**

    Open <http://localhost:5173> with your browser to see the result.

## Live Demo 🌐
### [Tripwise-AI-Trip-Planner](https://tripwise-ai-trip-planner.vercel.app)
