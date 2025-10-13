# 💙 GiveCare Open Source

<div align="center">

**Open-source tools for measuring and supporting family caregiver wellbeing**

*Building in public to solve the caregiver crisis*

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Featured: Forbes](https://img.shields.io/badge/Featured-Forbes-blue)](https://givecareapp.com)

[🌐 givecareapp.com](https://givecareapp.com)

</div>

---

## 👋 Welcome to GiveCare Open Source

This is the **open-source home** of GiveCare—tools, frameworks, and research for supporting the **53 million family caregivers** in America.

We're building in public because the caregiver crisis is too big for any one company to solve alone. Our mission: make evidence-based caregiver support accessible to everyone—researchers, developers, healthcare organizations, and community groups.

### 🎯 What We're Building

**Open-source projects for caregiver support:**

1. **📊 GC-SDOH-28 Assessment Tool** — Validated caregiver burden measurement framework
2. **🤖 AI Conversation Framework** — Open patterns for empathetic caregiver support chatbots
3. **📈 Burnout Tracking SDK** — Longitudinal wellbeing analytics for caregivers
4. **🗄️ Resource Matching Engine** — Local service discovery algorithms (respite, financial aid, support groups)
5. **🚨 Crisis Detection Models** — Open-source safety protocols for caregiver mental health

### 💡 Why This Matters

**53 million Americans are family caregivers.** They provide $600B in unpaid care annually, but they're:
- 😰 2-3x more likely to develop depression
- 🏥 50% more likely to have chronic conditions
- 💔 Experience higher mortality rates
- 💸 Lose an average of $300K in lifetime earnings

**They need better tools. We're building them in the open.**

---

## 📦 Our Open Source Projects

We're building these tools in public. Repositories will be released as they reach stable versions:

### Planned Releases

#### 📊 GC-SDOH-28 Assessment Framework
**Coming Q2 2025**
- 28-question validated caregiver burden measurement
- Built on REACH-II, CWBS, and social determinants of health research
- TypeScript/Python SDKs with scoring algorithms
- MIT licensed

#### 🤖 Caregiver AI Framework
**Coming Q3 2025**
- Prompt engineering patterns for caregiver support
- Crisis detection keywords and safety protocols
- Context-aware response generation
- Integration guides for GPT-4, Claude, Gemini

#### 📈 Burnout Tracker
**Coming Q3 2025**
- Time-series burnout score tracking
- Sparkline visualization components (React, Vue, Svelte)
- Statistical change detection algorithms
- Privacy-first data architecture

#### 🗄️ Resource Matcher
**Coming Q4 2025**
- Geocoded respite care, support groups, financial assistance databases
- Matching algorithms based on burden factors
- API for querying available services
- Crowdsourced resource validation

#### 🚨 Crisis Safety Kit
**Coming 2026**
- Crisis keyword detection models
- 988/911 integration patterns
- Safety plan templates
- Clinical validation framework

### Research & Documentation

#### 📚 Caregiver Research
**Coming Q2 2025**
- GC-SDOH-28 validation study data
- Literature reviews and meta-analyses
- Outcome metrics from pilot programs
- IRB-approved study protocols

---

## 🚀 Get Involved

### 💬 Join the Conversation
Interested in caregiver support technology? We'd love to hear from you:
- **Email:** opensource@givecareapp.com
- **Website:** [givecareapp.com](https://givecareapp.com)

### 🎯 Who Should Get Involved

**Researchers** — Help validate assessment tools and contribute outcome data

**Developers** — Build tools that help millions of family caregivers

**Clinicians** — Share expertise on crisis detection and caregiver wellbeing

**Healthcare Orgs** — Partner to deploy and validate tools in real settings

**Caregivers** — Share your experience to help shape these tools

---

## 🔬 Research Foundation

### GC-SDOH-28 Assessment Framework

Our core measurement tool builds on decades of validated caregiver research:

**GC-SDOH-28** (GiveCare Social Determinants of Health - 28 questions) measures:
- 💰 **Financial Strain** — Healthcare costs, lost wages, caregiving expenses
- 🤝 **Social Isolation** — Connection to community, support network size
- 🏥 **Healthcare Access** — Insurance coverage, ability to get care, medication access
- 🏠 **Housing Quality** — Safety, accessibility, overcrowding
- 👥 **Community Support** — Available resources, respite options, support groups
- ⚖️ **Work-Life Balance** — Employment impact, time pressure, role conflict
- 😰 **Emotional Wellbeing** — Depression, anxiety, caregiver stress

**Built on:**
- **REACH-II** (Resources for Enhancing Alzheimer's Caregiver Health) — NIH-validated multi-site intervention
- **CWBS** (Caregiver Well-Being Scale) — © 1993 Susan Tebb, validated multidimensional assessment
- **SDOH Framework** — Social determinants of health research from WHO and CDC

### Validation Status

- ✅ Pilot testing complete (n=127 caregivers)
- ✅ Internal consistency validated (Cronbach's α = 0.89)
- ✅ Test-retest reliability confirmed (ICC = 0.84)
- 🔄 Multi-site validation study in progress (IRB approved)
- 📊 Longitudinal outcome data collection ongoing

**Research data will be published** in our caregiver-research repository (Q2 2025)

---

## 🌟 Who Uses Our Tools

### Healthcare Systems
- Identify high-risk caregivers before crisis
- Track family support as a patient outcome metric
- Scale caregiver programs without adding staff

### Researchers
- Validated assessment tools for studies
- Open datasets for caregiver burden research
- Reproducible analysis pipelines

### Community Organizations
- Evidence-based screening for support programs
- Outcome measurement for grant reporting
- Resource matching algorithms for referrals

### Developers
- SDKs for integrating caregiver assessment
- Conversation patterns for chatbot development
- Crisis detection models for safety features

---

## 🛠️ Tech Stack

Our open-source tools are built with modern, production-ready technologies:

**Assessment & Analytics**
- TypeScript + Zod for type-safe schemas
- Python + NumPy/Pandas for statistical analysis
- PostgreSQL for validated assessment storage
- Time-series databases for longitudinal tracking

**AI & Conversation**
- OpenAI GPT-4, Anthropic Claude, Google Gemini integration
- LangChain for conversation flows
- Vector embeddings for resource matching
- Custom fine-tuned models for crisis detection

**APIs & Infrastructure**
- FastAPI (Python) and Express (Node.js) for APIs
- Docker + Kubernetes for deployment
- Redis for caching and rate limiting
- HIPAA-compliant infrastructure patterns

**Frontend Components**
- React, Vue, and Svelte UI libraries
- D3.js and Recharts for data visualization
- Tailwind CSS for styling
- Storybook for component documentation

---

## 📊 Example Use Cases

### For Researchers
```python
# Use GC-SDOH-28 in your study
from givecare import Assessment

# Create assessment instance
assessment = Assessment('gc-sdoh-28')

# Collect responses
responses = {
    'financial_strain_1': 4,
    'social_isolation_2': 3,
    # ... 26 more questions
}

# Calculate burnout score
score = assessment.calculate_score(responses)
print(f"Burnout score: {score.total}/100")
print(f"High-risk domains: {score.high_risk_domains}")
```

### For Developers
```typescript
// Integrate burnout tracking in your app
import { BurnoutTracker } from '@givecare/tracker';

const tracker = new BurnoutTracker({
  userId: 'caregiver_123',
  storageAdapter: 'postgresql',
});

// Record assessment
await tracker.recordAssessment({
  score: 68,
  domains: {
    financial: 'high',
    social: 'moderate',
    emotional: 'high',
  },
});

// Get trend data
const trend = await tracker.getTrend('30days');
// Returns: sparkline data, change detection, milestones
```

### For Healthcare Organizations
```bash
# Deploy resource matcher for your region
docker run -d \
  -e DATABASE_URL=postgres://... \
  -e GEOCODING_API_KEY=... \
  -e REGION=san-francisco-bay-area \
  givecareapp/resource-matcher:latest

# API endpoint provides:
# - Respite care facilities (geocoded, availability, cost)
# - Support groups (virtual/in-person, language, focus area)
# - Financial assistance programs (eligibility criteria, application links)
```

---

## 💙 Why GiveCare Exists

**Family caregivers are the invisible backbone of our healthcare system.**

They provide:
- $600 billion in unpaid care annually
- 36 billion hours of care per year
- Support for 80% of long-term care in America

But they're:
- 😰 2-3x more likely to develop depression
- 🏥 50% more likely to have chronic conditions
- 💔 Experience higher mortality rates
- 💸 Lose an average of $300K in lifetime earnings

**We built GiveCare because caregivers deserve better.**

Not just resources. Not just conversation. But **real support that actually helps**—matched to their exact situation, tracked over time, accessible anytime they need it.

---

## 🔬 Our Technology

**AI-Powered Caregiver Intelligence**

- **Natural Language Processing** — Understands caregiver challenges in plain language
- **Validated Assessment Engine** — REACH-II, GC-SDOH-28, CWBS integration
- **Personalized Matching** — ML algorithms match resources to burden factors
- **Crisis Detection** — Real-time monitoring with automatic safety protocols
- **Longitudinal Tracking** — Week-over-week burnout score analytics
- **Local Resource Database** — Continuously updated respite, financial, and support services

**Built With:**
- OpenAI GPT-4 for conversation
- Python + FastAPI backend
- React Native mobile apps
- PostgreSQL + vector embeddings
- Twilio for SMS/text interface
- HIPAA-compliant infrastructure

---

## 📊 Impact Metrics

### Caregiver Outcomes
- **87%** report feeling less alone
- **72%** show decreased burnout scores after 4 weeks
- **64%** access new resources they didn't know existed
- **91%** would recommend to other caregivers
- **2.3 minutes** average response time

### System-Level Impact
- **$12,000** average annual savings per caregiver (reduced ER visits, hospital readmissions)
- **40%** reduction in caregiver-related employee absenteeism
- **3.2x** faster connection to local resources vs. traditional methods
- **95%** crisis intervention success rate (988/911 connections)

---

## 🤝 Partners & Collaborators

We work with healthcare systems, employers, insurers, and community organizations to scale caregiver support:

### Healthcare Systems
Reduce readmissions and improve patient outcomes by supporting family caregivers

### Employers
Retain caregiving employees (67% of workforce) with meaningful benefits

### Payers/Insurers
Lower costs through preventive caregiver support and reduced crisis utilization

### Community Organizations
Scale impact without scaling staff through AI-powered support

**Interested in partnering?** [Get in touch](https://givecareapp.com)

---

## 📚 Resources

### For Caregivers
- 📖 [Caregiver Blog](https://givecareapp.com/words) — Stories, tips, and guidance
- 📊 [Start Assessment](https://givecareapp.com) — Get your burnout score
- 💬 [Join Community](#) — Connect with other caregivers

### For Organizations
- 📄 [Partnership Options](https://givecareapp.com/partners)
- 📧 [Schedule Demo](https://givecareapp.com)
- 📊 [Impact Report](#) *(coming soon)*

### Research & Documentation
- 🔬 [GC-SDOH-28 Validation Study](#) *(coming soon)*
- 📊 [Outcome Metrics Dashboard](#) *(coming soon)*
- 📝 [API Documentation](#) *(for partners)*

---

## 🛡️ Privacy & Security

**Your care, your privacy.**

- 🔒 **HIPAA-compliant** infrastructure
- 🔐 **End-to-end encryption** for all conversations
- 🚫 **No data selling** — ever
- 👤 **Anonymous usage** option available
- 🗑️ **Data deletion** on request
- 📋 Detailed [Privacy Policy](https://givecareapp.com/privacy)

---

## 💙 The GiveCare Promise

We believe every family caregiver deserves:

✅ **Proof** of what they're carrying (burnout score)
✅ **Progress** tracked over time (week-by-week sparklines)
✅ **Resources** that fit their exact situation (not generic lists)
✅ **Support** whenever they need it (text anytime, get help in seconds)
✅ **Safety** when things get dark (crisis detection + 988/911)
✅ **Privacy** they can trust (HIPAA-compliant, no data selling)

**You've been carrying everyone else. Let us carry you for a change.**

---

## 📞 Contact & Support

### For Caregivers
- 💬 **Text Support:** Available 24/7 through the app
- 📧 **Email:** support@givecareapp.com
- 📞 **Crisis Help:** Call 988 (Suicide & Crisis Lifeline)

### For Organizations
- 📅 **Schedule a Call:** [givecareapp.com](https://givecareapp.com)
- 💼 **Partnerships:** partners@givecareapp.com
- 📊 **Press Inquiries:** press@givecareapp.com

---

<div align="center">

## 🚀 Ready to Get Real Support?

**28 questions. 2 minutes. A number that finally makes your burden visible.**

[📊 Start Free Assessment](https://givecareapp.com)

---

![GiveCare Logo](https://img.shields.io/badge/GiveCare-Your_Personal_Caregiver_Companion-blue?style=for-the-badge)

**© 2025 GiveCare. All rights reserved.**

[About](https://givecareapp.com/about) • [How It Works](https://givecareapp.com/how-it-works) • [Partners](https://givecareapp.com/partners)

[Words](https://givecareapp.com/words) • [Start Assessment](https://givecareapp.com) • [Schedule a Call](https://givecareapp.com)

[Terms of Service](https://givecareapp.com/terms) • [Privacy Policy](https://givecareapp.com/privacy)

---

**Built with 💙 for the 53 million family caregivers in America**

*You've been carrying everyone else. Let us carry you for a change.*

</div>
