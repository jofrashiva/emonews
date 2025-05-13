# EmoNews – Emotion-Based News Reader

EmoNews is a mood-aware news application built using **ReactJS**, **Node.js**, and **MongoDB**. It uses **facial emotion detection** to personalize and filter news content based on the user’s current mood, enhancing the browsing experience with emotionally relevant articles.

## Features

- **Emotion Detection:** Uses facial expression analysis to determine the user's mood in real-time.
- **Personalized News Feed:** Displays news articles that align with detected emotions (e.g., happy, sad, angry).
- **Dynamic Content:** Automatically updates and filters news based on changing moods.
- **Responsive Design:** Works seamlessly on desktops, tablets, and mobile devices.
- **Tech Stack:** ReactJS, HTML, CSS, JavaScript, Node.js, Express.js, MongoDB.

## Tech Stack

- **Frontend:** ReactJS, HTML5, CSS3, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **APIs:** News API for fetching news articles
- **Other:** Emotion detection using face-api.js or any suitable ML model

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/jofrashiva/emonews
   cd emonews

# EmoNews – Version 1

## Description

Initial version of EmoNews with a static UI built using HTML, CSS, and JavaScript. This version features a basic layout for the news portal with placeholder articles.

## Features

- Basic homepage layout with header, footer, and sample news cards.
- Static sample news articles.
- Responsive design for mobile and desktop.

## Tech Stack

- HTML5
- CSS3
- JavaScript

## Instructions

1. Open `index.html` in a browser to view the project.
2. This version does not have backend or mood detection.

## Status

- [x] UI Setup
- [ ] Mood Detection
- [ ] News API Integration

# EmoNews – Version 2

## Description

This version introduces a ReactJS frontend with dynamic news loading using the News API. Users can now see real-time news updates based on categories.

## Features

- ReactJS single-page application structure.
- Fetching live news using NewsAPI.
- Category-based filtering (e.g., Technology, Health, Sports).

## Tech Stack

- ReactJS
- NewsAPI
- Bootstrap (optional)

## Instructions

1. Navigate to `client/` directory.
2. Install dependencies and start React app:
   ```bash
   npm install
   npm start


---

# EmoNews – Version 3

## Description

In this version, facial emotion detection is integrated using face-api.js. News is now filtered based on the user's mood, detected through the webcam.

## Features

- Real-time mood detection using webcam.
- Dynamic filtering of news based on mood (happy, sad, angry, etc.).
- Enhanced UI with webcam component.

## Tech Stack

- ReactJS
- face-api.js
- NewsAPI
- CSS Modules / Styled Components

## Setup

1. Navigate to the `client/` directory.
2. Install dependencies:
   ```bash
   npm install
   npm install face-api.js

   npm start

---

### `README_v4.md` – *Final Full Stack Version*

```markdown
# EmoNews – Version 4 (Final)

## Description

Final version with full-stack architecture. Features include mood detection, news filtering, MongoDB integration for storing user preferences, and a fully polished UI.

## Features

- Emotion-based personalized news display.
- Backend integration with Node.js and MongoDB.
- Responsive and mobile-friendly UI.
- Error handling and loading states for better UX.

## Tech Stack

- **Frontend:** ReactJS, face-api.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **API:** NewsAPI

## Installation

### Backend Setup

1. Navigate to the backend folder:
   ```bash
   cd server
   npm install

## Mangodb setup

PORT=5000
MONGO_URI=your_mongodb_connection_string
NEWS_API_KEY=your_newsapi_key

npm start

cd client


npm install
npm install face-api.js

npm start
