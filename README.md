# VidGenAI: AI-Powered TikTok/Reel Generator

This project is a sophisticated, full-stack web application designed to automate the content generation workflow. It leverages modern Python frameworks and external media APIs to convert simple inputs into ready-to-share social media reels.


# Key Features

- **AI Voice Integration:** Seamlessly generates high-quality, realistic voiceovers using the ElevenLabs API.  
- **Multi-Stage Media Pipeline:** Utilizes FFmpeg for robust, server-side audio/video synchronization and file assembly.  
- **Full Backend Pipeline:** Manages the entire process from user file upload to final content display (Gallery).  
- **Scalable Architecture:** Built on the Python Flask framework for streamlined web service delivery.  


# Technology Stack

| Layer | Technologies Used |
|-------|--------------------|
| **Backend Framework** | Python, Flask |
| **API Integration** | ElevenLabs API (for AI Audio) |
| **Media Processing** | FFmpeg Library |
| **Storage** | Server-side file handling |


# Getting Started

### Prerequisites
- **Python 3.8+**  
- **FFmpeg** installed and added to your system PATH  


###  Setup

**1️. Clone the Repository**

git clone https://github.com/saoirseros/VidGenAI

cd VidGenAI

**2️. Create and Activate Virtual Environment**

Create the virtual environment
python -m venv venv

Activate (Windows)
.\venv\Scripts\activate

**3️. Install Dependencies**
pip install -r requirements.txt
