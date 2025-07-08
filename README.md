# Profile Chat

A Gradio-based AI profile chat app that answers questions about Hema Surya B using OpenAI, PDF, and summary context.

## About

This project is an interactive chatbot that represents Hema Surya B, answering questions about their career, background, skills, and experience. The chatbot uses:
- A summary of Hema Surya B's background (`summary.txt`)
- The full LinkedIn profile extracted from `Profile.pdf`
- OpenAI's API for generating responses
- Gradio for the web interface

## Features
- Faithfully answers questions about Hema Surya B's professional background
- Records user interest, feedback, and bug reports
- Handles unknown questions and encourages users to get in touch

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Profile_chat.git
   cd Profile_chat
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up environment variables:**
   Create a `.env` file in the root directory with the following variables:
   ```env
   PUSHOVER_TOKEN=your_pushover_token
   PUSHOVER_USER=your_pushover_user
   GEMINI_API_KEY=your_gemini_api_key
   ```
4. **Run the app:**
   ```bash
   python app.py
   ```
   This will launch the Gradio chat interface in your browser.

## Files
- `app.py`: Main application code
- `requirements.txt`: Python dependencies
- `summary.txt`: Professional summary of Hema Surya B
- `Profile.pdf`: Full LinkedIn profile (used for context)

## License
This project is for personal/professional portfolio use. Contact Hema Surya B for more information. 
