# EthiBank Web App

**Objective:**

Develop a web-based platform that promotes ethical AI usage in banking services like credit scoring, fraud detection, and personalized financial advice.

**Tech Stack:**

* **Frontend:** React.js, Next.js, TailwindCSS, shadcn/ui
* **Backend:** Serverless API routes in Next.js
* **APIs:** OpenAI (GPT-4), Anthropic (Claude), RAGChat, Mapbox
* **Database:** Upstash (Redis)
* **Deployment:** Vercel

**Features:**

### 1. Bias Detection & Mitigation
**Purpose:**
Identify and reduce biases in AI systems, ensuring fair treatment of all customers.

**Implementation:**
* Utilize Anthropic's Claude API for bias analysis in AI models.
* Store bias metrics and analysis logs in Upstash (Redis).
* Visualize biases and provide actionable insights in the admin dashboard.

### 2. Explainable AI (XAI)
**Purpose:**
Enable users to understand the rationale behind AI-driven decisions like credit approvals or fraud detection alerts.

**Implementation:**
* Generate human-readable explanations for AI decisions using OpenAI's GPT-4 API.
* Integrate an interactive "Why This Decision?" modal in the user portal.

### 3. Personalized Financial Advice
**Purpose:**
Provide ethical and tailored financial advice to users.

**Implementation:**
* Facilitate contextual chatbot interactions using RAGChat.
* Retrieve user location using the Mapbox API for geo-specific financial advice.
* Store user feedback and preferences in Upstash for ongoing personalization.
