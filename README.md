# SpeechBridge

SpeechBridge is a frontend-only web application that allows users to seamlessly convert speech to text and text to speech. The project focuses on a clean UI/UX experience with custom loader pages and interactive alerts using div elements, making it entirely self-contained without any backend.

**Features**

🗣️ Speech-to-Text: Converts spoken words into text in real-time.

🔊 Text-to-Speech: Converts typed text into natural-sounding speech.

⏳ Custom Loader Page: Displays a sleek loading animation while the app initializes.

⚠️ Custom Alerts: Interactive notifications implemented with styled divs, no browser popups.

📄 Separate Pages: Dedicated pages for Speech-to-Text and Text-to-Speech for clarity and ease of use.

🌐 Pure Frontend: Built entirely with HTML, CSS, and JavaScript—no backend required.

**Technologies Used**

HTML – Structure of the application.

CSS – Styling, animations, and custom loader/alerts.

JavaScript – Speech recognition, speech synthesis, and alert logic.

**Web APIs:**

SpeechRecognition / webkitSpeechRecognition for speech-to-text.

SpeechSynthesis for text-to-speech.

**Project Structure**

speechbridge/
│
├── index.html          # Loader page

├── speech-to-text.html # Speech-to-Text page

├── text-to-speech.html # Text-to-Speech page

├── css/
│   
    └── styles.css      # Styling for pages, loader, and alerts

└── js/
    └── script.js       # All JS logic for speech functionality and custom alerts

**Usage**

Open index.html in a browser.

Wait for the loader page to finish.

Navigate to the Speech-to-Text or Text-to-Speech page.

Use the buttons on each page to start speech recognition or speech synthesis.

Custom alerts will notify you of missing input or actions in a visually appealing div popup.

**Screenshots**




**Future Enhancements**

Add theme switcher (dark/light mode)

Add multi-language support for speech recognition and synthesis

Add download transcript or audio file feature

Enhance loader with progress percentage

⚠️ Note: This project works only on Chrome, Edge, and Brave. Safari and Firefox are not supported.
