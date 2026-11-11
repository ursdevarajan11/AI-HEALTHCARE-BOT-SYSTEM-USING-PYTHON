# 🏥 Healthcare Chatbot (Python)

## 📌 Overview
The **Healthcare Chatbot** is a Python-based conversational assistant designed to provide patients with quick, structured health information and care navigation. It uses natural language processing (NLP) to answer common queries, guide users toward appropriate resources, and integrate location-aware features for nearby healthcare services. The chatbot emphasizes compliance, clarity, and accessibility.

---

## 🔧 Features
- **Patient Interaction**
  - Conversational interface for answering health-related questions
  - Provides symptom-based guidance (general, non-diagnostic)
  - Directs users to appropriate care resources

- **Healthcare Navigation**
  - Location-aware suggestions for nearby hospitals, clinics, or pharmacies
  - Integration with maps or APIs for directions

- **Information Management**
  - Structured responses with clinical formatting
  - Access to general health FAQs and preventive care tips

- **Compliance & Accessibility**
  - Designed with ethical boundaries (non-diagnostic, informational only)
  - Clear, accessible language for diverse users

---

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**:  
  - `Pandas` / `scikit-learn` for symptom and health prediction workflows
  - `Flask` for the web application

## Deploying on Render

The repository root contains `render.yaml`, `.python-version`, and a root
`requirements.txt` that delegates to this folder's dependency list. The Render
start command changes into this folder and serves `app:app` with Gunicorn.

Create or update a Render Blueprint from this repository to apply these
settings. Render generates `SECRET_KEY`. For persistent user data, configure
`DATABASE_URL` with a PostgreSQL connection string; SQLite on Render's
ephemeral filesystem is not durable across restarts or redeploys. Set
`UPLOAD_FOLDER` to a mounted persistent disk path if uploaded prescriptions
must survive redeploys.

Optional integrations use `GOOGLE_MAPS_API_KEY` and the SMTP settings
`SMTP_HOST`, `SMTP_PORT`, `SMTP_USER`, `SMTP_PASS`, `FROM_EMAIL`, and
`SMTP_USE_TLS`. The current `gemini_client.py` is a mock/fallback stub, not a
live Gemini API integration.
