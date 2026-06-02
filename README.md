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
<img width="1891" height="986" alt="image" src="https://github.com/user-attachments/assets/5ba726b6-de11-4d8e-afb1-6d7986d5227a" />

### Dashboard
- Lead KPIs
- Revenue Analytics
- Conversion Funnel
- AI Insights
<img width="1887" height="976" alt="image" src="https://github.com/user-attachments/assets/ba4378eb-227c-4130-88dd-5a8c3e19ef98" />
<img width="1894" height="986" alt="image" src="https://github.com/user-attachments/assets/11fd7d0b-b4c3-4a19-be0d-68ccf091d94f" />
<img width="1896" height="987" alt="image" src="https://github.com/user-attachments/assets/f2dcd629-2900-45da-baaf-7af40ce5ab64" />

### Upload Leads
- CSV Upload
- Data Processing
- AI Enrichment
<img width="1915" height="995" alt="image" src="https://github.com/user-attachments/assets/b07ad26e-2146-4ec6-9267-0e9e477584ea" />

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

**Pooja A**

Aspiring Software Engineer passionate about AI-powered applications, analytics platforms, and intelligent automation.

---

## License

This project is licensed under the MIT License.
