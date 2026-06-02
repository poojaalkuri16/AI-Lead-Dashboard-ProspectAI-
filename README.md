# ProspectAI – AI Lead Intelligence Dashboard

ProspectAI is an AI-powered lead management and sales intelligence platform that transforms raw lead data into actionable business insights.

Built with Next.js, Supabase, and Gemini AI, the platform enables users to upload lead datasets, analyze sales opportunities, track pipeline performance, and generate AI-driven recommendations in real time.

---

## Features

### Authentication
- Secure user signup and login using Supabase Auth
- User session management
- Protected dashboard access

### Lead Management
- Upload leads through CSV files
- Store and manage leads in Supabase
- View lead details, status, revenue, source, and engagement metrics

### AI-Powered Insights
- Analyze uploaded leads using Google Gemini AI
- Generate business recommendations automatically
- Identify high-value lead sources
- Discover conversion opportunities and revenue trends

### Sales Analytics Dashboard
- Total Leads Tracking
- Qualified Leads Analysis
- Conversion Rate Monitoring
- Revenue Metrics
- Lead Source Distribution
- Pipeline Visualization

### Real-Time Data
- Supabase PostgreSQL database
- Live dashboard updates
- Dynamic statistics and insights

---

## Tech Stack

### Frontend
- Next.js 16
- React 19
- TypeScript
- Tailwind CSS
- Framer Motion
- Recharts

### Backend
- Supabase
  - PostgreSQL Database
  - Authentication
  - REST API

### AI
- Google Gemini 2.5 Flash

### Data Processing
- PapaParse (CSV Processing)

---

## Project Architecture

```text
CSV Upload
     │
     ▼
Supabase Database
     │
     ▼
Lead Analytics Engine
     │
     ▼
Gemini AI Analysis
     │
     ▼
AI Insights Dashboard
```

---

## Screenshots

### Dashboard
- Lead KPIs
- Revenue Analytics
- Conversion Funnel
- AI Insights
<img width="1894" height="982" alt="image" src="https://github.com/user-attachments/assets/ebd80657-dbed-4b4f-a896-f4d97b1a7091" />
<img width="1888" height="995" alt="image" src="https://github.com/user-attachments/assets/8d26a30b-59ec-41a1-aefa-9c53ded905d3" />
<img width="1898" height="998" alt="image" src="https://github.com/user-attachments/assets/c2373079-64a1-466e-b3f4-d25b77f28a14" />




### Upload Leads
- CSV Upload
- Data Processing
- AI Enrichment

---

## Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-lead-dashboard.git

cd ai-lead-dashboard
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a file named:

```text
.env.local
```

Add:

```env
NEXT_PUBLIC_SUPABASE_URL=YOUR_SUPABASE_URL
NEXT_PUBLIC_SUPABASE_ANON_KEY=YOUR_SUPABASE_ANON_KEY
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

### Run Development Server

```bash
npm run dev
```

Application will run on:

```text
http://localhost:3000
```

---

## Database Schema

### Leads Table

| Column | Type |
|----------|----------|
| id | UUID |
| name | TEXT |
| email | TEXT |
| company | TEXT |
| title | TEXT |
| status | TEXT |
| revenue | NUMERIC |
| source | TEXT |
| engagement_score | INTEGER |
| last_contact | TIMESTAMP |
| created_at | TIMESTAMP |

---

## AI Insights Example

ProspectAI automatically generates insights such as:

- Referral and Partnership channels deliver the highest revenue conversions.
- High engagement leads should be prioritized for immediate outreach.
- LinkedIn generates qualified leads but requires better qualification strategies.

---

## Future Enhancements

- AI Lead Scoring
- AI Email Generation
- Lead Prioritization Engine
- Predictive Conversion Analysis
- Team Collaboration Features
- CRM Integrations
- Advanced Reporting

---

## Deployment

### Frontend
- Vercel

### Backend
- Supabase

### AI
- Google Gemini API

---

## Author

**Pooja Alkuri**

Aspiring Software Engineer passionate about AI-powered applications, analytics platforms, and intelligent automation.

---

## License

This project is licensed under the MIT License.
