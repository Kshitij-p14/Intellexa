# Intellexa - AI-Powered Study Platform

![Demo](https://github.com/Kshitij-p14/Intellexa/raw/main/photo.png)

##  Demo Video

https://github.com/Kshitij-p14/Intellexa/assets/117811916/intellexa-demo.mp4

> **Watch the full demo above to see Intellexa in action!**

##  Documentation

View the complete project documentation: [Intellexa-Documentation.pdf](./Intellexa-Documentation.pdf)

---

A modern web application built with Flask that transforms study materials into AI-powered summaries, 
flashcards, quizzes, and interactive learning tools.

## Features

-  **Landing Page** - Modern, responsive design showcasing the platform
-  **Authentication** - User registration and login system
-  **Dashboard** - Main interface for uploading and processing documents
-  **AI Features**:
  - Smart document summaries
  - Interactive flashcards generation
  - Adaptive quiz creation
  - AI chat assistant for Q&A
-  **User Profile** - View user statistics and progress
-  **Settings** - Customize AI preferences and privacy settings

## Installation & Setup

### 1. Clone the Repository
`ash
git clone https://github.com/Kshitij-p14/Intellexa.git
cd Intellexa
`

### 2. Install Python Dependencies
`ash
pip install -r requirements.txt
`

### 3. Set Up Environment Variables
Create a .env file in the project root:
`ash
GOOGLE_API_KEY=your_gemini_api_key_here
`

**To get your Gemini API key:**
1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account
3. Create a new API key
4. Copy and paste it into your .env file

### 4. Run the Application
`ash
python app.py
`

The application will automatically:
- Create a SQLite database (intellexa.db)
- Set up all required tables
- Initialize the uploads directory

### 5. Access the Application
Open your web browser and go to: http://localhost:5000

## Technology Stack

- **Backend**: Flask (Python web framework)
- **Database**: SQLite (with proper schema and relationships)
- **AI**: Google Gemini Pro (for content generation)
- **PDF Processing**: PyPDF (text extraction)
- **Authentication**: Werkzeug (password hashing)
- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Custom CSS with Inter font family
- **Icons**: Font Awesome
- **Charts**: Chart.js (for growth dashboard)

## Key Features

###  Implemented
-  Real AI content generation using Gemini API
-  Full SQLite database with proper relationships
-  Secure authentication with password hashing
-  Multiple PDF upload with modal interface
-  Auto-generated summaries, flashcards, and quizzes
-  Real-time progress tracking and statistics
-  AI chat assistant for Q&A
-  Growth analytics dashboard
-  Beautiful, responsive UI with animations

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is for educational and demonstration purposes.

---

**Intellexa** - Learn smarter, not harder! 
