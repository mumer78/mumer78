<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=6C63FF&center=true&vCenter=true&width=650&lines=Hi+there%2C+I'm+Muhammad+Umer+%F0%9F%91%8B;CS+Student+%40+Forman+Christian+College;I+Build+Real-Time+AI+Voice+Agents;Full-Stack+Dev+%7C+LLM+Orchestration+%7C+WebSockets" alt="Typing SVG" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-6C63FF?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-muhammad-umer.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-umer-247970318)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:umerwaheed093@gmail.com)
[![Location](https://img.shields.io/badge/Lahore%2C_Pakistan-4CAF50?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

<br/>

## 🚀 About Me

```yaml
name: Muhammad Umer
role: CS Student & Freelance Full-Stack / AI Developer
based_in: Lahore, Pakistan
education: BS Computer Science @ Forman Christian College (2023 - 2027)
currently_building: Production-grade AI systems from scratch — no low-code, ever.
focus:
  - Real-time voice agents (streaming audio, STT/TTS pipelines)
  - Autonomous meeting bots & LLM orchestration
  - Computer vision & deep learning
  - Full-stack apps with live WebSocket infrastructure
mindset: "Ship it. Debug it under real production constraints. Ship it again."
```

<br/>

## 🛠️ Tech Stack

<div align="center">

**Languages**
<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frontend**
<br/>
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend & APIs**
<br/>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)

**AI, Voice & ML**
<br/>
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud_STT-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Cloud, Tools & DB**
<br/>
![GCP Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

</div>

<br/>

## 🎯 Featured Production Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ Royale AI — Real-Time Voice Agent
**Hotel booking, fully autonomous, over the phone.**

Caller speaks naturally in Urdu or English, and hangs up with a confirmed reservation — no forms, no buttons.

- 🎧 Low-latency streaming pipeline: browser mic → PCM16 16kHz via AudioWorklet → WebSocket → Google Cloud STT v2 (Chirp 3) with VAD silence detection
- 🌐 Multilingual per-utterance detection (Urdu/English)
- 🧠 GPT-4o-mini drives multi-turn booking state
- 🔊 OpenAI TTS streams PCM audio replies in real time
- 📊 Live admin dashboard via persistent WebSocket
- ☁️ Deployed on Google Cloud Run — solved a Chirp 3 regional endpoint constraint in production

`FastAPI` `Google STT v2` `GPT-4o-mini` `OpenAI TTS` `WebSockets` `Cloud Run`

**[🔗 Live Demo](https://royale-ai-agent.vercel.app)**

</td>
<td width="50%" valign="top">

### 🤖 MeetingIntel — Autonomous Meeting Summarizer
**Joins your meetings. Transcribes. Summarizes. Acts.**

An autonomous bot that joins Google Meet / Zoom / Teams, transcribes live, and generates structured summaries and action items.

- 🔗 Joins meetings via Recall.ai
- 🎙️ Live transcription with Deepgram Nova-3
- 🧠 LangChain + GPT-4o-mini for structured summaries
- 🏗️ 5-service architecture: Django Daphne, Celery Worker, Celery Beat, Redis, React
- 🌉 Custom HTTP bridge to solve WebSocket broadcasting limits
- 📧 Auto-fires Email + Slack post-meeting
- 🔤 Custom Urdu/Hindi → Roman Urdu transliteration engine (no API, microsecond latency)
- 🏆 Gamified team leaderboards with XP, ranks & radar charts

`Django` `Celery` `Redis` `Deepgram Nova-3` `Recall.ai` `LangChain`

**[🔗 Source Code](https://github.com/mumer78/Meeting-summarizer)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 😃 Live Emotion Detection (CNN)
**Real-time facial emotion classification from webcam.**

- 🧠 CNN trained from scratch, classifying 5 facial emotions in real time
- 📈 Data augmentation and dropout regularization for robustness
- 🚀 Deployed on Render + Vercel

`Python` `TensorFlow` `Keras` `OpenCV` `Flask` `React`

**[🔗 Source Code](https://github.com/mumer78/Emotion-detection)**

</td>
<td width="50%" valign="top">

### 💼 Freelance Full-Stack Development
**End-to-end ownership, from Figma to production.**

Delivering custom full-stack web apps using React.js, Django, and Flask — managing the full lifecycle from UI/UX design to cloud deployment.

- 🎨 Figma-to-code UI/UX
- 🔧 Full lifecycle: dev → Git → cloud deploy
- 🤝 Strong client communication & ownership

`React.js` `Django` `Flask` `Git` `Cloud Deployment`

*Aug 2025 – Present*

</td>
</tr>
</table>

<br/>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mumer78&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mumer78&layout=compact&theme=tokyonight&hide_border=true" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=mumer78&theme=tokyonight&hide_border=true" />

</div>

<br/>

## 🌱 Currently

- 🔭 Building production AI systems — voice, vision, and orchestration — with zero low-code shortcuts
- 🐛 Debugging multilingual AI products under real constraints: latency, streaming, regional API limits, live traffic
- 🎓 Pursuing my BS in Computer Science at Forman Christian College
- 🧩 Active with **IEEE — FCC Chapter** (Logistics Team) and **U.N.I Startup** (Social Media Team)
- 💬 Ask me about real-time audio streaming pipelines, LLM orchestration, or WebSocket architecture

<br/>

<div align="center">

### 📫 Let's Connect

[![Portfolio](https://img.shields.io/badge/-Portfolio-6C63FF?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-muhammad-umer.vercel.app)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-umer-247970318)
[![Gmail](https://img.shields.io/badge/-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:umerwaheed093@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=mumer78&color=6C63FF&style=flat-square&label=Profile+Views)

</div>
