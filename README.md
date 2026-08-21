<h1 align="center">Wasay Rabbani</h1>
<h3 align="center">I build systems that see and understand — Computer Vision + LLMs, in production</h3>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=WasayRabbani&style=flat-square&color=blue" alt="profile views" />
<img src="https://img.shields.io/badge/Status-Open%20to%20Work-brightgreen?style=flat-square" alt="open to work" />
</p>

<p align="center">
🟢 Open to full-time AI/ML &amp; Computer Vision roles (internships included) &nbsp;|&nbsp; 🟢 Taking on freelance CV/LLM projects
</p>

---

### What I do

Most AI portfolios are either pure computer vision or pure LLM work. I do both, and combine them — vision systems that don't just detect, but explain what they see, and respond, in natural language. That's a narrow but real skill set, and it's what the projects below are built on.

### Proof of work

**SignBridge — two-way sign language communication for hotel guests**  
Deaf/mute hotel guests can't easily communicate with staff in real time. SignBridge closes that gap in both directions: MediaPipe Holistic extracts 144 hand/body landmarks per frame from live video, a LSTM classifies gesture sequences across 22 hospitality-specific signs in real time (96.96% test accuracy), and detected signs are segmented and assembled into full sentences — not just isolated word predictions. For replies, a Groq-powered LLaMA 3.1 model translates staff's free-text messages into vocabulary-constrained sign sequences, rendered as smooth 3D avatar animations. Flutter handles the guest/staff-facing UI, Flask serves the models, and the backend is containerized with Docker and deployed on Hugging Face Spaces.  
`Python` · `TensorFlow/Keras` · `MediaPipe Holistic` · `OpenCV` · `Flask` · `Flutter` · `Firebase` · `Groq (LLaMA 3.1)` · `Docker` · `Hugging Face Spaces`

**Real-Time Safety & Biometric Monitoring (Freelance Project)**  
A client was relying on slow, manual inspections to check if workers were wearing safety gear. To automate this, I trained an AI (YOLOv8) to instantly detect safety gear compliance and falls from a live video feed. On top of that, I added an ultra-fast facial recognition system to automatically track worker attendance using the exact same camera.
To make this run smoothly without crashing or lagging, I built a smart resource manager that allows both systems to share the camera flawlessly. I also optimized the facial recognition to load worker data directly into the computer's RAM, dropping the face-scanning time to under 30 milliseconds—completely fixing the lag issues seen in heavier AI models. The system was successfully delivered and is currently running in production for the client. 
`Python` · `YOLOv8` · `C++` · `dlib` · `face_recognition` · `OpenCV`

**Automated code review that actually reads the code**  
Fine-tuned LLaMA-3-8B with QLoRA/Unsloth to evaluate code submissions across 5 languages, served through a FastAPI backend. Delivered as a paid freelance project.  
`Python` · `LLaMA-3` · `QLoRA/Unsloth` · `FastAPI`

*Each of these started as someone's manual, repetitive problem — checking compliance by eye, translating sign language by hand, reviewing code line by line — and ended as a system that runs on its own.*

### How I work

I don't ship code I can't explain. Every project here I can walk through line by line — the architecture choices, why the model made a specific mistake, what I'd change with more time. If you're hiring or hiring out work, that's the difference between a demo and something you can actually rely on.

---

### Stack

**Vision:** YOLOv8 · OpenCV · MediaPipe Holistic · Face_recognition  
**Deep Learning / LLMs:** TensorFlow/Keras · PyTorch · BiLSTM · LLaMA-3 · QLoRA/Unsloth · Hugging Face  
**Serving & Infra:** FastAPI · Flask · Docker · Hugging Face Spaces
**Languages:** Python · Java · SQL

---

### Beyond the code

I run **[MindWired](https://www.youtube.com/@MindWired_ai)** on YouTube — AI/ML concepts explained in Urdu, for learners across Pakistan.

---

### Let's talk

**Hiring?** → [LinkedIn](https://www.linkedin.com/in/wasay-rabbani-147b4926b) · [Email](mailto:wasayrabbani69@gmail.com)  
**Have a project?** → [Email](mailto:wasayrabbani69@gmail.com), tell me what problem you're trying to solve
