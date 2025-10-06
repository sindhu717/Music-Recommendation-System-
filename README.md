# Music-Recommendation-System-
This is a Music Recommendation Web App built with Streamlit, YouTube Music API, and the Spotify API.   The app lets you search for a song and discover similar tracks recommended from YouTube Music and Spotify. You can also download your recommendations in CSV format for later use. 

## 🚀 Features  

- 🔍 Search for any song by name  
- 🔴 Get YouTube Music recommendations using ytmusicapi  
- 🟢 Get Spotify-style recommendations via Last.fm (with direct Spotify search links)  
- 📂 Export your recommendations as CSV files (per platform or combined)  
- 🎨 Built-in dark mode with a sleek custom UI  
- 📱 Fully responsive – works smoothly on both desktop and mobile  

## 🛠️ Tech Stack  

- Streamlit – Interactive web app framework  
- ytmusicapi – Wrapper for YouTube Music API  
- Last.fm API – Fetches similar tracks and metadata  
- Pandas – Data handling and CSV export  
- Requests – API requests

- ## 📂 Project Structure  
├── app.py             
├── requirements.txt   
├── README.md


- ## ⚙️ Installation
- Clone the repository
- git clone https://github.com/your-username/music-recommendation-system.git
- cd music-recommendation-system

- ## Create a virtual environment
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows


 ## Install dependencies
pip install -r requirements.txt

 ## Set up environment variables
- Create a .env file in the project root (or set directly in your terminal):
- LASTFM_API_KEY=your_lastfm_api_key_here
- If you don’t provide an API key, the app will use a demo key (with limited requests).

 ## ▶️ Running the App
- streamlit run app.py
- Then open your browser at: http://localhost:8501  🎉

- ## 📥 CSV Export Options
- YouTube Music Recommendations
- Spotify Recommendations
- Combined Recommendations (Both platforms)


## ✅ Future Improvements
- 🔑 Add authentication for personalized recommendations
- 🎶 Direct integration with the Spotify Web API
- 📋 Option to create playlists automatically on Spotify/YouTube
- 🤖 Smarter recommendations with collaborative filtering or ML

## 👨‍💻 Author
Developed by Chada Sindhu Teja 
