# 🚀 Rozar

*India's First Vernacular Agentic Workforce AI*



![Status](https://img.shields.io/badge/Status-Demo_Ready-16A34A?style=for-the-badge)



Rozar is a voice-first, multi-agent AI platform built to help India's 450 million informal gig workers find jobs, get trained, and access government schemes. By breaking down language and literacy barriers, Rozar allows users to apply for jobs and schemes using their mother tongue over a simple chat or voice interface.



## ✨ Key Features



* 🌐 *Vernacular First:* Instantly toggle the entire UI and chatbot between *English, Hindi, Telugu and Tamil* without page reloads.

* 🎙️ *Voice-Enabled AI Chatbot:* Features browser-native Speech-to-Text (STT) and Text-to-Speech (TTS) for highly accessible, hands-free interaction.

* 🤖 *Multi-Agent Workflow:* A simulated LangGraph-style architecture featuring specialized agents:

  * *Receptionist:* Understands user intent and routes queries.

  * *Job Matcher:* Matches skills to gig jobs (Swiggy, Zomato, Porter, etc.) and auto-applies.

  * *Document Assistant:* Features simulated OCR to extract data from Aadhaar/PAN cards.

  * *Scheme Navigator:* Checks eligibility and guides users through govt schemes (PMKVY, NRLM, etc.).

* 📊 *Personalized Dashboard:* A mock authenticated state showing applied jobs, eligible schemes, and upcoming training.



## 🛠️ Tech Stack (Demo Setup)



This repository contains the high-fidelity frontend prototype built during the 10-hour hackathon window. 



* *Frontend:* HTML5, Tailwind CSS (via CDN), Vanilla JavaScript

* *Voice & AI Simulation:* Web Speech API (SpeechRecognition & SpeechSynthesis), Simulated multi-turn prompt flows.

* *Architecture (Simulated/Planned for Backend):* Sarvam AI (STT/NLU), Gemini Flash 2.0 (Orchestrator), and LangGraph (Agents).



## 🚀 How to Run the Demo



Since this is a fully standalone frontend prototype, no local server or build tools are required!



1. Clone this repository or download the ZIP.

2. Double-click the index.html file to open it in any modern web browser (Google Chrome or Microsoft Edge recommended for full Voice API support).



## 🎯 Demo Guide for Judges



To experience the full capabilities of the Rozar platform, follow this testing flow:



1. *Change the Language:* Use the dropdown in the top right navigation bar to switch between English, Hindi, and Tamil. Notice how the entire UI updates instantly.

2. *Demo Login:* Click *Login* in the top right, then click *"Login as Demo User"*. You will be redirected to the personalized worker Dashboard.

3. *Test the Multi-Agent Chat:*

   * Click the floating *🤖 bot icon* in the bottom right.

   * Click the *"Try demo flow →"* quick-reply chip to see the simulated Job Matcher and Document Assistant agents auto-apply for a delivery role.

   * Click the *🎙️ Mic button* and speak (e.g., "I am looking for a delivery job") to test the native browser voice input.

4. *Explore the Hubs:* Navigate to the *Job Matcher* to see skill-matched cards, and the *Schemes Hub* to open step-by-step eligibility modals. 

5. *View Architecture:* Navigate to the *Tech & Impact* tab to view our system architecture, 10-hour build timeline, and cost breakdown.



## 💡 The Impact



Current gig-work platforms require app downloads, typing, and English literacy. Rozar replaces this friction with a 30-second, voice-first interaction.



## 👥 Contributors



* Suriyaa S – Frontend Development & Architecture 

* Shashank Prasad– AI Integration & Prompt Engineering 

* Divyanshi Mishra – UI/UX Design & Documentation 

* Nataasha Leo-  Ideation , System Architecture and UI/UX



Team Algo Architects
