# Pranava AI Assistant - Portfolio Chatbot

A professional, premium, and recruiter-friendly offline conversational chatbot integrated into the bottom-right corner of Pranava's portfolio website. 

The chatbot is designed to simulate a real-time conversational helper representing Pranava Chanduri (using a first-person tone: *"I"*, *"my"*, *"me"*), guiding recruiters and visitors through education, experience, technical skills, projects, and contact info.

---

## ✨ Features

- **Recruiter-Friendly Pill Trigger**: A modern, dark-blue floating action button in the bottom-right labeled **"Ask PranavaAI"** featuring custom hover scale states and clean sparkle vector graphics.
- **Header Avatar & Live Indicator**: Features a clean "PC" initials avatar badge accompanied by a pulsing green online indicator to reassure visitors they are interacting with Pranava's active assistant clone.
- **Suggested Question Chips**: Quick reply option buttons to help recruiters jump straight into key queries (e.g., *"Tell me about yourself"*, *"What are your technical skills?"*, *"What projects have you worked on?"*).
- **Suggestions Auto-Collapse**: Once a query is triggered, suggestions collapse automatically into a clean click toggle ("Suggested questions • click to show/hide") to preserve vertical screen space for the chat feed.
- **Human Texting Experience**: Responses feature a 1000ms delay and a typing dot indicator animation, simulating a natural human typing cadence.
- **Client-Side Conversational Engine**: Fully self-contained and implemented locally in browser JS, removing any external API key exposures, rate limit constraints, or hosting costs.
- **Responsive & Glassmorphism Design**: Designed with responsive layouts fitting cleanly on mobile screens, scroll transitions, and a dark theme blending with the portfolio's aesthetics.

---

## 📂 Project Architecture

The chatbot is built entirely into the existing single-page structure:
* **[index.html](index.html)**: 
  * Contains the HTML layout for the floating chat window (`#pranava-ai-panel`) and trigger button (`#pranava-ai-toggle`).
  * Integrates vanilla CSS styles for glassmorphism styling, scrolling, keyframe animations, and typing indicator layouts.
  * Embeds the local JavaScript mockup matching keywords (skills, projects, contacts, education, experience, greetings) and serving pre-defined recruiter response packages.

---

## 💬 Conversation Mapping

The local engine supports key word-matching queries and replies dynamically:
- **Greetings**: Friendly intro asking the recruiter how to help them learn about skills, projects, or background.
- **Technical Skills**: Formatted lists of Languages, Frameworks/Libraries, Data Visualization, Tools/Databases, and Web Development skills.
- **Top Projects**: Bulleted summaries of *Satellite Image Land Classification*, *Time Series Demand Forecasting*, *Movie Recommendation*, *Diabetes Prediction*, and *BigMart Sales Analysis*.
- **Education**: Timeline summary of Master's in Data Science at the University of North Texas and B.Tech in CSE at SRM University.
- **Work Experience**: Highlighting internships in Application Development, Web Development, and Machine Learning, alongside published IEEE papers and the Best Paper Award.
- **Job Availability**: Friendly confirmation of active interest in full-time roles, internships, and Graduate Research Assistant opportunities.
- **Contact Details**: Fast clickable links for email client, LinkedIn, GitHub, and phone.
