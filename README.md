# TubeChat

**TubeChat** is a real-time chat platform integrated with YouTube videos, allowing users to watch videos together while engaging in interactive discussions. This project is designed to enhance collaborative viewing experiences and provide synchronized playback with seamless chat functionality.

---

## 🚀 Features

- **YouTube Video Integration**: Search, play, and watch YouTube videos in sync with others.
- **Real-Time Chat**: Engage with friends or community members using a built-in chat interface.
- **Playback Synchronization**: Ensure all users in a session are watching the same frame.
- **Room Management**: Create public or private rooms for group viewing.
- **User-Friendly Interface**: Intuitive design for a seamless experience.

---

## 🛠️ Tech Stack

- **Programming Language**: Python (97.9%)
- **Containerization**: Docker (2.1%)
- **Frontend**: [Your choice, e.g., React.js, HTML/CSS]
- **Backend**: Flask/Django with REST APIs
- **Database**: Firebase or PostgreSQL
- **Real-Time Communication**: WebSocket or Socket.IO
- **YouTube Integration**: YouTube Data API

---

## 🖥️ Installation and Setup

### Prerequisites
- Python 3.8 or higher
- Docker (optional, for containerized deployment)
- API Key for [YouTube Data API](https://developers.google.com/youtube/registering_an_application)

### Steps to Set Up Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/tubechat.git
   cd tubechat
2. **Set Up Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. **Install Dependencies**
```bash
pip install -r requirements.txt
```
4. **Configure API Key**
   
- Create a .env file in the root directory.
- Add your YouTube API key:
```bash

YOUTUBE_API_KEY=your_api_key_here
```

5. **Run the Application**
```bash
python app.py

```
6. **Access the App**

Open your browser and navigate to http://localhost:5000.






🐳 Docker Deployment
1. Build the Docker Image

```bash

docker build -t tubechat .

```
2. Run the Container

```bash

docker run -p 5000:5000 tubechat

```
3. Access the App
Open your browser and navigate to http://localhost:5000.
