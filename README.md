
**About Ruby Ai**

## Features

- 🔊 Live audio transcription
- 📊 Interactive data visualization
- 🤖 AI-powered conversation analysis
- 🔍 Search and filtering capabilities
- 📱 Responsive design for all devices

## Technology Stack

- **Frontend**: Next.js 13, React, TypeScript
- **UI Components**: Tailwind CSS, Shadcn UI
- **Data Visualization**: Tremor
- **Database**: Supabase
- **Voice Processing**: Retell AI
- **Scheduling**: Cal.com
- **Real-time Processing**: WebSocket
- **Authentication**: NextAuth.js

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm
- Retell AI API key
- Cal.com API key
- Supabase URL and keys

### Installation

1. Clone the repository:
```bash
git clone https://github.com/punisher-303/Ruby-Retell-AI.git
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env` file in the root directory:
```bash

# Supabase Configuration
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key

# Site Configuration
NEXT_PUBLIC_SITE_URL=your_site_url
NEXT_PUBLIC_APP_URL=your_app_url

# Retell Configuration
RETELL_WEBHOOK_URL=your_webhook_url
NEXT_PUBLIC_WEBSOCKET_URL=wss://api.retellai.com/retell-llm/llm-websocket
NEXT_PUBLIC_RETELL_AGENT_ID=your_agent_id
RETELL_API_KEY=your_retell_api_key
NEXT_PUBLIC_RETELL_API_KEY=your_retell_api_key
RETELL_AGENT_ID=your_agent_id

# WebSocket Configuration
NEXT_PUBLIC_WEBSOCKET_PORT=3001
WEBSOCKET_PORT=3001

# Cal.com Configuration
CAL_API_KEY=your_cal_api_key
CAL_EVENT_TYPE_ID=your_event_type_id
```

4. Run the development server:
```bash
npm run dev
```
Vercel is recommended for deployment 

## Usage

1. **Dashboard Overview**: View real-time metrics and KPIs
2. **Live Calls**: Monitor ongoing calls with live transcription
3. **Analytics**: Access detailed reports and insights
4. **Settings**: Configure AI parameters and dashboard preferences
