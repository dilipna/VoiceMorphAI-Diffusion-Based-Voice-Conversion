# 🎙️ VoiceMorphAI — Diffusion-Based Voice Conversion 🎵

Transform *any voice* into a new style using cutting-edge **AudioLDM2 diffusion models**.  
VoiceMorphAI combines generative AI, deep learning, and audio synthesis to convert speech while preserving natural tone and emotion.

---

## 🚀 Demo

**Try it live (no login needed):**  
🌐 Gradio link : https://33033413572f1d0fc5.gradio.live

<img width="1919" height="681" alt="Screenshot 2025-11-04 192402" src="https://github.com/user-attachments/assets/99a50481-c707-422e-aa70-8818dbfe300f" />



---

## 🎨 Interface Preview

Below is a live demo snapshot of **VoiceMorphAI**, showing the clean Gradio-based user interface:

![VoiceMorphAI Demo Interface](6a53d1a4-df3a-4cef-8539-b2adcd5fed7c.png)

> 🎤 Upload a `.wav` sample, describe a new voice style (e.g., “calm robotic female”), and generate your transformed output using diffusion models.

---

## 🧠 Project Overview

**VoiceMorphAI** performs **text-guided voice transformation** using the **AudioLDM2 Large** model — an open-access diffusion model for audio generation.  
Users can upload a voice recording and describe a new style (e.g., _“robotic whisper”_ or _“energetic podcast host”_) to synthesize a new version of the same speech.

### 🔊 Key Features
- 🎧 **Voice-to-Voice Transformation** – Converts uploaded voice to any target style.
- 🎨 **Spectrogram Visualization** – See the generated audio’s frequency energy map.
- 🔁 **Side-by-Side Comparison** – Listen to *original vs generated* voices.
- 💾 **Download Option** – Save the generated voice instantly.
- ☁️ **Fully Public** – No API key or Hugging Face token required.

---

## ⚙️ Tech Stack

| Category | Tools / Frameworks |
|-----------|--------------------|
| ML Model | 🧩 AudioLDM2 (Diffusion-based audio generation) |
| Libraries | PyTorch · Diffusers · Transformers · Gradio · Librosa · SoundFile |
| Visualization | Matplotlib · Librosa.display |
| UI / Deployment | Gradio Blocks with public sharing |
| Environment | Google Colab / Python 3.10 |

---

## 🧩 Architecture

Input Voice (.wav)
      │
      ▼
Audio Preprocessing ───► Diffusion Model (AudioLDM2)
      │                           │
      ▼                           ▼
Spectrogram                 Generated Audio
      │                           │
      ▼                           ▼
Visualization          Gradio Output + Download

---

## 📂 Folder Structure

VoiceMorphAI/
│
├── VoiceMorphAI.ipynb        # Main Colab notebook
├── README.md                 # Project overview & documentation
├── requirements.txt          # Dependencies
└── converted.wav             # Sample generated output (created after running)

---

## 🔧 Installation & Usage

# Clone this repository

# Install dependencies
pip install -r requirements.txt

# Run in Colab or Jupyter
python VoiceMorphAI.ipynb

Or simply open it on Colab (recommended):  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dilipgou/VoiceMorphAI/blob/main/VoiceMorphAI.ipynb)

---

## 🎯 Future Improvements

- Add voice cloning using speaker embeddings
- Train fine-tuned models for emotion-based conversion (RAVDESS dataset)
- Integrate with Hugging Face Spaces for permanent hosting
- Add waveform visualization alongside spectrogram

---

## 🧑‍💻 Author

**👋 Dilip N**  
💼 Passionate about ML, Audio AI, and Generative Systems  


---

## 🪶 License

MIT License © 2025 – Dilip N
Feel free to use, modify, and share this project for learning and research.

