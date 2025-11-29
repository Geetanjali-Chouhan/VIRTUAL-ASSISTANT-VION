# VION VIRTUAL ASSISTANT
VION ASSISTANT
Shifra – Your Virtual Assistant (HTML + CSS + JavaScript)

**VION** is a beginner-friendly voice-based virtual assistant built using **HTML**, **CSS**, and **JavaScript**. It greets the user based on the time of day and can respond to simple voice commands using the **Web Speech API**.

---

## 🌟 Features

- 🕒 Time-based greeting (Good Morning / Afternoon / Night)
- 🎤 Voice recognition using Web Speech API
- 💬 Speech synthesis for audio responses
- 🔗 Can open websites like Google, YouTube, Facebook, Instagram
- 🧮 Reads current time and date aloud
- 🧠 Responds to basic queries like "who are you", "hello", etc.

---

## 🛠 Tech Stack

- **HTML5** – Page structure
- **CSS3** – Styling and layout
- **JavaScript** – Core logic, voice recognition, and speech synthesis
- **Web APIs** – `SpeechRecognition` and `SpeechSynthesis`

---

## 📁 Folder Structure

virtual-assistant/
│
├── index.html # Main webpage
├── style.css # Styling for layout and theme
├── script.js # JavaScript logic (speech, greeting, commands)
├── robotai.jpg # Assistant logo
├── sirilogo.jpg # Assistant voice logo
├── mic.svg # Microphone icon
└── README.md # Project documentation

## 🧠 How It Works

- **Greeting Logic**:
  - Uses `Date().getHours()` to determine current hour.
  - Greets with "Good Morning", "Good Afternoon", or "Good Night".
  - Greeting is triggered automatically on page load.

- **Voice Recognition**:
  - Activated when user clicks the microphone button.
  - Listens to user commands using `SpeechRecognition`.
  - Matches phrases like:
    - `"open youtube"` → opens YouTube
    - `"what is the time"` → reads out current time
    - `"who are you"` → introduces itself

- **Speech Output**:
  - Uses `SpeechSynthesisUtterance` to speak responses aloud.


## 🗣 Supported Voice Commands

   Command                  Action                            

| `hello` / `hey`      | Greets the user                   
| `who are you`        | Introduces itself                 
| `open youtube`       | Opens YouTube in a new tab        
| `open google`        | Opens Google                      
| `open facebook`      | Opens Facebook                    
| `open instagram`     | Opens Instagram                   
| `open calculator`    | Tries to open system calculator   
| `what is the time`   | Tells current time                
| `what is the date`   | Tells current date                
| Any other query      | Searches on Google                


