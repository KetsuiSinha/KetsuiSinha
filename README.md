<h1 align="center">Nishchay Sinha</h1>

<p align="center">
  <strong>AI Engineer</strong><br>
  Building production LLM and conversational AI systems
</p>

<br>

## About

I design and ship AI systems that work reliably in production. My focus is the layer between a model and a real user: data pipelines, intent handling, feedback loops, and human escalation when confidence is low. I build the backend in Python and the interface in TypeScript, and I care about measurable outcomes over demos.

Mumbai, India &nbsp;|&nbsp; B.E. Electronics & Telecommunication Engineering, 2026

<br>

## Impact at a Glance

| 78% | 500+ | 45% | 40 hrs |
| :---: | :---: | :---: | :---: |
| support automation in production | monthly patient interactions | gain in draft relevance scoring | staff time saved per week |

<br>

## Selected Work

### Pulse
**LLM-powered client update generator**

Turns scattered activity from GitHub, Linear, and Slack into polished client updates, cutting manual effort from 2-3 hours per client each week to under 15 minutes.

- Ingestion pipeline with an activity normalization layer and relevance filter
- Draft generation calibrated to each user's tone from their own examples
- Edit-capture feedback loop that feeds user corrections back into the system
- Async LLM jobs with Celery and Redis, multi-client review dashboard, tiered Stripe billing

`FastAPI` `SQLAlchemy` `Next.js` `PostgreSQL` `Redis` `Celery` `Vercel` `Railway`

<br>

### HospiBot
**Multilingual healthcare assistant**

A production chatbot serving patients in English, Hindi, and Marathi across Web, WhatsApp, and Telegram, with sub-2-second responses and a 4.2/5 satisfaction score.

- Intent classification, entity extraction, and multi-turn context for appointments, prescription refills, lab reports, and FAQs
- Symptom triage with a 0.7 confidence threshold and live handoff to a human nurse over Socket.io
- Channel-adapter webhook architecture with CRM and EMR integration
- Audit logging and patient consent handling, deployed on AWS with CI/CD

`Dialogflow` `Node.js` `Express` `MongoDB` `Socket.io` `AWS EC2` `GitHub Actions`

<br>

## Experience

**Software Engineering Intern** &nbsp;|&nbsp; G10 Consultancy

Developing Django and Django REST Framework backends for business applications: dynamic models, serializers, RESTful endpoints, and CRUD workflows built for integration with data and AI-driven features.

<br>

## Technical Stack

| | |
| :-- | :-- |
| **AI / ML** | LLM Integration, Prompt Engineering, Conversational AI, NLP, Dialogflow, LangChain.js, Human-in-the-Loop Systems |
| **Languages** | Python, TypeScript, JavaScript, SQL, C++ |
| **Backend** | FastAPI, Django, Django REST Framework, Node.js, Express, Socket.io, Celery |
| **Frontend** | React, Next.js, Tailwind CSS, shadcn/ui, React Query |
| **Data** | PostgreSQL, MongoDB, MySQL, Redis, Supabase |
| **Infrastructure** | Docker, GitHub Actions, AWS EC2, Vercel, Railway, Linux |
| **Testing** | Jest, React Testing Library, Cypress, Postman |
