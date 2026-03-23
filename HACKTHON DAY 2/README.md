# NIT Delhi Hackathon Project

## About The Event
This project was created for a hackathon happening at NIT Delhi. The goal is to build practical student-focused web solutions with simple deployment and clear user experience.

## Project Title
Smart Mess Feedback and AI Chat Assistant

## Project Overview
This repository contains multiple mini web modules developed during the hackathon sprint:
- A multi-step Student Mess Feedback System
- A simple AI-powered chat interface integrated with OpenAI through a backend server
- Additional learning/demo pages in separate folders

The core idea is to collect structured mess feedback from students and support interaction through a lightweight chat assistant.

## Problem Statement
College hostels need a clear and usable system where students can:
- Submit personal details and food preferences
- View only relevant menu options (Veg or Non-Veg)
- Give day-wise ratings for the mess menu
- Share final feedback in one flow

## Key Features
1. Multi-page form flow for student mess feedback
2. Local storage support to persist form progress
3. Preference-first menu flow (Veg or Non-Veg)
4. Day-wise rating collection for all weekdays
5. Final summary page after submission
6. Separate AI chat demo integrated with OpenAI API

## Folder Structure
HACKTHON DAY 2
- Day2
  - index.html
  - page_02.html
  - page_03.html
  - page_04.html
  - page_05.html
  - End.html
- javascript
  - temp.html
  - server.js
  - package.json
  - .env.example

## Tech Stack
- HTML
- CSS
- JavaScript
- Node.js
- Express
- OpenAI API

## How To Run

### A) Mess Feedback Frontend
1. Open the Day2 folder.
2. Launch index.html in your browser.
3. Complete the form flow step by step.

### B) AI Chat Integration
1. Open terminal in the javascript folder.
2. Install dependencies using npm install.
3. Create a .env file using .env.example.
4. Add OPENAI_API_KEY in .env.
5. Start backend using npm start.
6. Open temp.html in browser and send messages.

## Important Notes
- Keep your API key private and never push .env to public repositories.
- If chat does not respond, check server logs for quota or key errors.
- Backend runs on localhost port 3000 by default.

## Future Improvements
- Store feedback in a database (MongoDB or PostgreSQL)
- Add admin dashboard for mess committee insights
- Add charts for weekly and monthly rating trends
- Add authentication for student login
- Deploy frontend and backend for campus-wide usage

## Acknowledgement
Built during the NIT Delhi hackathon with focus on practical student utility and fast prototyping.
