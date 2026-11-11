# Hi, I'm Adityan Kesavan 👋

I'm a Computer Science student at Western University who enjoys turning ideas into reliable, user-focused software. My work spans full-stack and mobile development, data engineering, and machine learning, with a focus on building practical products and understanding the systems behind them.

-  Pursuing a BSc in Computer Science at Western University
-  Interested in software engineering, full-stack development, data, and machine learning
-  Experienced with object-oriented programming, relational databases, algorithms, and testing
-  I enjoy hackathons, collaborative projects, and learning new technologies by building
-  Reach me at [akesava5@uwo.ca](mailto:akesava5@uwo.ca)

## Featured Projects

### [Triagent](https://github.com/adi-btw/triagent)

An evidence-grounded incident triage system for on-call engineers. Paste an error report or log excerpt, and Triagent searches a corpus of runbooks and past incidents with hybrid retrieval (BM25 + vector), then returns a structured report: severity (SEV1–4), likely causes, and next steps. Every claim cites a retrieved passage, and the citations are checked in code. When the documents don't cover a problem, the report says so instead of guessing. An LLM agent chooses whether to draft, retry with a rewritten query, or ask a clarifying question, and a 32-case evaluation compares it with no retrieval and plain RAG: exact severity rises from 38% to 79% to 93%. A separate experiment uses QLoRA to fine-tune a 1.5B open model as a severity classifier, taking it from 28% to 88.5% on 200 held-out incidents. Citation checks and output guards cut successful prompt-injection attacks from 16 of 16 to 2 of 16. The project also includes SSE streaming, Prometheus metrics, Slack and Alertmanager integrations, a reviewer feedback loop, 448 tests, and CI.

**Tech:** Python, FastAPI, RAG, LLM Agents, Gemini, QLoRA (Hugging Face Transformers, PEFT), PostgreSQL, SQLite, Docker, GitHub Actions  
**Live demo:** [triagent-duer.onrender.com](https://triagent-duer.onrender.com/?sample=checkout&mode=agent)

### [Vestora](https://github.com/adi-btw/Vestora)

A cross-platform stock research and paper-trading application built with React Native and TypeScript. Vestora integrates Finnhub, Alpaca, Twelve Data, and Gemini APIs to support stock quotes, historical charts, financial news, and an AI assistant. Its Supabase backend includes authenticated Edge Functions, PostgreSQL row-level security, transactional paper trading, caching, request retries, rate limiting, and quote-provider fallback.

**Tech:** React Native, Expo, TypeScript, Supabase, PostgreSQL, REST APIs, TanStack Query, Zod, Gemini

### [DuckSpeak](https://github.com/CSUWO/DuckSpeak)

A real-time ASL recognition web application developed during HackHarvard 2025. I collaborated on the React interface and an in-browser machine-learning workflow using webcam landmarks, MediaPipe, classification models, and temporal smoothing.

**Tech:** React, TypeScript, JavaScript, MediaPipe, KNN, Logistic Regression  
**Live demo:** [duckspeak.netlify.app](https://duckspeak.netlify.app/)

### [Tales of Artemis](https://github.com/adi-btw/Tales-of-Artemis)

A Java desktop typing adventure game where players defeat enemies by typing words, progress through timed levels, and compete on leaderboards. It was built as a team project for Software Engineering II at Western University, and I was responsible for all backend development: player accounts and profiles, persistent progress, score tracking and leaderboards, level progression, typing mechanics, game-state management, and parental-control logic. The game follows an MVC architecture with JSON persistence through Gson. I also wrote JUnit 5 unit tests, ran integration and system testing, and documented the design with UML diagrams and Javadoc.

**Tech:** Java, Swing, Maven, Gson, JUnit 5, MVC

### [Followthrough](https://github.com/adi-btw/Followthrough)

A Ruby on Rails app for tracking supplement care plans. A practitioner signs in, adds patients, and writes a plan. Each patient then records doses from a private, login-free check-in link. The app calculates 7-day adherence as doses taken divided by doses expected, accounting for plan start dates and morning and evening slots. A background job flags plans that fall below 50% adherence for follow-up. It's a portfolio demo that uses only fictional data.

**Tech:** Ruby, Ruby on Rails 8, SQLite, Solid Queue, Hotwire (Turbo, Stimulus), Minitest, Capybara

### [Forge - Gym Tracker](https://github.com/adi-btw/Forge)

An offline-first, cross-platform gym tracking application built with React Native, Expo, and TypeScript. Forge supports workout creation, calendar-based scheduling, live set tracking, streaks, session history, and performance analytics backed by SQLite.

**Tech:** React Native, Expo, TypeScript, SQLite, Zustand, Supabase

### [Python Music Player](https://github.com/adi-btw/Music-Player)

A desktop music player with MP3 playback, playlist management, seek and volume controls, track timing, and a basic equalizer for bass, mid, and treble adjustments.

**Tech:** Python, Tkinter, Pygame, NumPy, librosa

## Technical Skills

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Frameworks, Data, and Tools

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Ruby on Rails](https://img.shields.io/badge/Ruby_on_Rails-D30001?style=flat-square&logo=rubyonrails&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

## What I'm Working Toward

I'm continuing to strengthen my full-stack development and software-design skills while exploring machine learning, data-intensive applications, cloud integration, and systems programming. I am always interested in projects where I can learn quickly, solve meaningful problems, and contribute to a collaborative team.
