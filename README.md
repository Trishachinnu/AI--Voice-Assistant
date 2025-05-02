# 🗣️ AI Voice Assistant

This is a simple AI-based voice assistant built using Python. The assistant can recognize voice commands and perform a variety of tasks such as opening applications, searching the web, or telling the time.

## 🚀 Features

- Speech recognition from microphone input  
- Text-to-speech responses  
- Open websites or applications  
- Answer general questions using web search  
- Report current time and date  
- Modular and easily expandable

## 🛠️ Built With

- **Python 3.x**
- **SpeechRecognition** – for voice input
- **pyttsx3** – for text-to-speech output
- **webbrowser** – to open URLs
- **datetime** – to report time and date
- **os** – to interact with system applications

## 📁 Project Structure
voice_assistant/
│
├── assistant.py # Main voice assistant script
├── requirements.txt # Python dependencies
└── README.md # Project documentation
## 📦 Installation

1. Clone the repository:
       git clone https://github.com/yourusername/ai-voice-assistant.git
       cd ai-voice-assistant
2. Install dependencies:
       pip install -r requirements.txt
3. Run the assistant:
       python assistant.py
   
**📌 Requirements**
    Python 3.6 or higher
    Microphone connected
    Internet connection (for search functionality)
    requirements = """
    speechrecognition
    pyttsx3
    pyaudio
    datetime
    """

# Save the requirements.txt file
requirements_path = "/mnt/data/requirements.txt"
with open(requirements_path, "w") as file:
    file.write(requirements.strip())

requirements_path


**💡 Future Improvements**
    Add integration with APIs (weather, news, etc.)
    GUI using Tkinter or PyQt
    Support for multiple languages
    Personalization features

👩‍💻 Author
Yogeshwari S
📧 yogeshwarisgowda@gmail.com
🔗 LinkedIn
 


