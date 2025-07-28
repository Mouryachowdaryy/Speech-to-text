
🎙️ Speech to Text Converter (Jupyter Notebook)

A simple and interactive Jupyter Notebook application that lets you **record or upload audio** and instantly convert speech to text using Python’s `speech_recognition` library.

 🚀 Quick Start

 1. Requirements

Make sure you have Python and Jupyter Notebook installed. Then install the required packages:

```bash
pip install speechrecognition pyaudio
```

> ⚠️ For Windows: If `pyaudio` fails, try installing via `.whl` file from [https://www.lfd.uci.edu/\~gohlke/pythonlibs/#pyaudio](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)

 2. Open the Notebook

```bash
jupyter notebook
```

Open `speech to text.ipynb` in your browser.

---

 3. Run the Cells

Click **Run All** or run each cell step by step.

* 📁 Upload an audio file (or)
* 🎤 Record using microphone
* ✅ Get instant transcription in text form

 🎯 Features

* 🔊 Record speech using your system’s microphone
* 📂 Upload `.wav` audio files for transcription
* ✨ Real-time speech recognition using `SpeechRecognition`
* 🧠 Converts speech into clean, readable text
* 🧪 Works directly from Jupyter – no external UI needed

🛠️ How It Works

🎧 Input

* Use `speech_recognition.Microphone()` for live recording
* Use `speech_recognition.AudioFile()` for uploaded `.wav` file

⚙️ Processing

* Audio is processed using:

  ```python
  recognizer.recognize_google(audio)
  ```
* Uses Google Web Speech API (free, online)

📝 Output

* Final text is printed in the notebook
* Handles common errors like silence or recognition failure

 📂 Repository Structure

```
speech-to-text/
├── speech to text.ipynb         ← Jupyter Notebook with full code
└── README.md                    ← This documentation
```
