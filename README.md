# 🩺 Doctor Ruby AI — Real-Time Medical Conversation Assistant

Doctor Ruby AI is a real-time, AI-powered voice assistant designed to enhance telemedicine and healthcare support. Whether assisting doctors during consultations or offering conversational medical guidance, Doctor Ruby leverages advanced speech and AI technologies to make healthcare more accessible, accurate, and intelligent.

Built for modern clinical workflows. Designed with precision. Powered by trusted tools like Retell AI, Supabase, and Cal.com.

---

## ⚙️ Features

* 🗣️ Live medical transcription of patient-doctor conversations
* 🤖 AI-powered analysis for symptom detection and clinical insights
* 📊 Interactive dashboards for health metrics and summaries
* 🔍 Smart search and filtering of previous consultations
* 📅 Scheduling and appointment coordination via Cal.com

---

## 🧰 Technology Stack

| Layer              | Technologies Used             |
| ------------------ | ----------------------------- |
| Frontend           | Next.js 13, React, TypeScript |
| UI Components      | Tailwind CSS, Shadcn UI       |
| Data Visualization | Tremor                        |
| Database           | Supabase                      |
| Voice Intelligence | Retell AI                     |
| Scheduling         | Cal.com                       |
| Real-Time Layer    | WebSocket                     |
| Authentication     | NextAuth.js                   |

---

## 🚀 Getting Started

### ✅ Prerequisites

* Node.js v18 or higher
* npm or pnpm
* API keys for:

  * Retell AI
  * Cal.com
  * Supabase

### 🛠 Installation

1. Clone the repository:

```bash
git clone https://github.com/punisher-303/DoctorRubyAi.git
cd Doctor Ruby Ai
```

2. Install dependencies:

```bash
npm install
```

3. Configure environment variables:

Create a `.env` file in the root directory with the following content:

```dotenv
# Supabase
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key

# URLs
NEXT_PUBLIC_SITE_URL=your_site_url
NEXT_PUBLIC_APP_URL=your_app_url

# Retell AI
RETELL_WEBHOOK_URL=your_webhook_url
NEXT_PUBLIC_WEBSOCKET_URL=wss://api.retellai.com/retell-llm/llm-websocket
NEXT_PUBLIC_RETELL_AGENT_ID=your_agent_id
RETELL_API_KEY=your_retell_api_key
NEXT_PUBLIC_RETELL_API_KEY=your_retell_api_key
RETELL_AGENT_ID=your_agent_id

# WebSocket
NEXT_PUBLIC_WEBSOCKET_PORT=3001
WEBSOCKET_PORT=3001

# Cal.com
CAL_API_KEY=your_cal_api_key
CAL_EVENT_TYPE_ID=your_event_type_id
```

4. Start the local development server:

```bash
npm run dev
```

> 💡 Recommended deployment: [Vercel](https://vercel.com/) with environment variables configured.

---

## 🩻 Application Highlights

* 📝 Consultation Transcripts — Automatically generated and editable
* 🧾 Case History Search — Retrieve old visits and records
* 📆 Patient Scheduling — Through integrated Cal.com workflows
* ⚙️ AI Parameters — Customize model behavior for specialty focus (e.g., pediatrics, neurology)

---

## 👥 Who Is This For?

* Doctors and clinicians needing real-time transcription
* Health tech startups building conversational care platforms
* Researchers analyzing patient interactions
* Developers building HIPAA-compliant AI interfaces

---

## 📄 License

MIT © [Anand (punisher-303)](https://github.com/punisher-303)

---

## 🤝 Contribute

We welcome medical innovators, AI engineers, and open-source contributors to collaborate and elevate Doctor Ruby AI.

Open a PR or issue to get involved.

---

## 📚 Resources

* Retell AI Documentation: [docs.retellai.com](https://docs.retellai.com)
* Cal.com Documentation: [docs.cal.com](https://docs.cal.com)
* Supabase Documentation: [supabase.com/docs](https://supabase.com/docs)
