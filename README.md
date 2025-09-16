# Mantra Counter

A Flutter-based application that counts mantras using **voice input**.  
The app uses the [Vosk Speech Recognition Toolkit](https://alphacephei.com/vosk/) for offline voice recognition.

---

## 📥 Setup Instructions

This repository does **not** include the Vosk model due to GitHub's file size limits.  
You need to download the model manually before running the app.

### 1. Download Vosk Model
- Download the English model (`vosk-model-en-us-0.22`) from the official Vosk models page:
  - https://alphacephei.com/vosk/models

The file you download will be something like: `vosk-model-en-us-0.22.zip`

---

### 2. Extract and place the model

Before extracting the model, **make sure the following folders exist in your repo root**:

```text
assets/
  model/
```
Unzip the downloaded archive and place the extracted folder **inside** `assets/model/` so your project structure looks like this:

```text
assets/
  model/
    vosk-model-en-us-0.22/
      <model files...>
```

# Ignore Vosk model folder
assets/model/

---

### 3. Flutter Setup
Make sure you have Flutter installed.  
Then run:

```bash
flutter pub get
flutter run
```
