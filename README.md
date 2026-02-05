# Call_Audio_Analysis
Built a comprehensive audio analysis system for voice scoring (sentiment, empathy, politeness) and implemented speaker diarization using MFCC and KMeans also integrated LLM APIs (OpenAI, Hugging Face) for natural language analysis and created automated reporting and a user interface using Gradio and SQLite.


# Call Audio Analysis Tool

A Python-based application designed to process call recordings, perform audio analysis, and provide insights (such as sentiment or transcription) using a Gradio web interface.

## 🚀 Features
* **Audio Upload:** Support for common formats (MP3, WAV).
* **Noise Reduction:** Automated cleaning of background noise for better clarity.
* **Sentiment Analysis:** (Optional: mention if you are using an LLM for this).
* **Interactive UI:** Built with Gradio for easy browser-based interaction.

## 🛠️ Prerequisites
Before running the project, ensure you have:
* Python 3.8+
* A GitHub account (for version control)
* API Keys (if using external services like OpenAI or Gemini)

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
   cd call-audio-analysis
Create a virtual environment:

Bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate
Install dependencies:

Bash
pip install -r requirements.txt
⚙️ Configuration
Create a .env file in the root directory and add your credentials:

Code snippet
API_KEY=your_key_here
DEBUG=True

🖥️ Usage
Run the main script to launch the Gradio interface:

Bash
python app.py
