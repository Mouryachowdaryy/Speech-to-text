🎙️ Speech to Text Converter (Jupyter Notebook)

A simple and interactive Jupyter Notebook application that allows you to **record audio using your microphone** and instantly convert speech to text using Python’s `speech_recognition` library.

 🚀 Quick Start

 1. Requirements

Make sure you have Python and Jupyter Notebook installed. Then install the required packages:

```bash
pip install speechrecognition pyaudio
```

> ⚠️ For Windows: If `pyaudio` fails, install it using a `.whl` file from:
> [https://www.lfd.uci.edu/\~gohlke/pythonlibs/#pyaudio](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)

 2. Open the Notebook

```bash
jupyter notebook
```

Open the `speech to text.ipynb` file in your browser.


 3. Run the Cells

* Run all cells in order
* Speak clearly into your microphone when prompted
* Get instant transcription directly in the notebook


 🎯 Features

* 🎤 Record speech using your system’s microphone
* 🧠 Uses Google Web Speech API via `speech_recognition`
* 📝 Instantly converts spoken words into clean text
* 🧪 Fully interactive inside Jupyter Notebook

---

🛠️ How It Works

 🎧 Input

* Uses `speech_recognition.Microphone()` to capture audio from your mic

 ⚙️ Processing

* Captures a short audio snippet and converts it to text using:

  ```python
  recognizer.recognize_google(audio)
  ```

 📝 Output

* Recognized speech is printed in real-time in the notebook
* Displays an error message if speech is unclear or if connection fails


📂 Repository Structure

```
speech-to-text/
├── speech to text.ipynb         ← Jupyter Notebook with full code
└── README.md                    ← This documentation
```
