# **AI-Powered Movie/TV Show/Anime Recommendation App with Chatbot**

## **Overview**
This is a **Movie, TV Show & Anime Recommendation App** built using **JavaScript and React**, featuring an **AI-powered chatbot** that suggests content based on user queries. The chatbot uses **OpenAI's GPT-4 API**, and the movie data is fetched from **TMDB API**.

## **Features**

- 🎬 **Movie, TV Show & Anime Search & Recommendations**
- 🤖 **AI Chatbot for Personalized Suggestions**
- 🌐 **TMDB API Integration for Content Data**
- ⚡ **Interactive & Responsive UI**
- 💬 **Live Chat Interface for Recommendations**

## **Tech Stack**

- **Frontend:** React.js
- **APIs:** OpenAI GPT-4 API, TMDB API
- **Styling:** Tailwind CSS (Optional for better UI)
- **State Management:** React Hooks (useState, useEffect)

## **Installation & Setup**

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-username/movie-recommendation-app.git
cd movie-recommendation-app
```

### **2️⃣ Install Dependencies**
```sh
npm install
```

### **3️⃣ Get API Keys**
- **TMDB API Key:** Sign up at [TMDB](https://www.themoviedb.org/) and generate an API key.
- **OpenAI API Key:** Get an API key from [OpenAI](https://platform.openai.com/).

### **4️⃣ Store API Keys in Environment Variables**
Create a `.env` file in the root directory and add:
```env
REACT_APP_TMDB_API_KEY=your_tmdb_api_key_here
REACT_APP_OPENAI_API_KEY=your_openai_api_key_here
```

### **5️⃣ Run the Project**
```sh
npm start
```

## **Project Structure**
```
/movie-recommendation-app
  ├── /src
  │   ├── /components
  │   │   ├── Chatbot.js  # AI Chatbot component
  │   │   ├── MovieList.js  # Displays recommendations
  │   ├── /api
  │   │   ├── chatbot.js  # Handles AI responses
  │   ├── /pages
  │   │   ├── MovieDetails.js  # Content details page
  │   ├── App.js
  │   ├── index.js
  ├── .env
  ├── package.json
```

## **How the AI Chatbot Works**

1. User types a message like **“Suggest a horror anime”**.
2. The chatbot sends the request to OpenAI's GPT-4 API.
3. OpenAI processes it and returns recommendations.
4. The chatbot displays the suggestions in the UI.

