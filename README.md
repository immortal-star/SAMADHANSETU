# Samadhan Setu
**Bridging Grassroots Challenges with Institutional Innovation.**

A civic innovation platform designed to connect citizens, universities, industry, and government to identify, analyze, and solve real social and infrastructure challenges across Jharkhand. 

Samadhan Setu creates a simple, intuitive digital collaboration layer to collect community challenges (such as water access, education gaps, or agricultural distress) and route them to the right institutions for immediate action and funding.

---

## 📸 Platform Previews

### Citizen Portal
<img width="1242" height="872" alt="Citizen Portal Dashboard" src="https://github.com/user-attachment>s/assets/4ceceeac-3f7a-4ab1-9afc-925584aca4b9" />

### Government Command Center
<img width="1242" height="872" alt="Government Command Center Dashboard" src="https://github.com/user-attachments/assets/b707cfe5-e57a-4f1f-8bd4-e0cd380bf428" />

---

## 🚀 How It Works (The Platform Workflow)

Samadhan Setu operates as a seamless, 5-step collaborative ecosystem that transforms a local community problem into a fully deployed, real-world solution.

### 1. Problem Identification & Submission (Citizen Portal)
* **The Action:** A citizen, Gram Panchayat, or local organization identifies a societal issue (e.g., a broken irrigation system or a lack of digital literacy tools).
* **The Process:** They open the Samadhan Setu web app or use the WhatsApp bot integration, fill out an intuitive form with the problem description, pinpoint their district, and upload supporting evidence like photos or videos.

### 2. AI-Powered Processing & Smart Routing (The Engine)
* **The Action:** The platform's built-in AI engine takes over the moment a problem is submitted.
* **The Process:** It analyzes the problem's text and media to automatically categorize it into specific domains (such as Agriculture, Healthcare, Water Management, or Education). It then instantly routes this challenge to Higher Education Institutions (HEIs) in Jharkhand that specialize in that exact domain.

### 3. Academic Incubation & Prototyping (University Dashboard)
* **The Action:** Universities and research institutes view these categorized challenges on their dedicated dashboards.
* **The Process:** Faculty members review the problems and assign them to multidisciplinary student teams. The students accept the challenge, conduct research, and upload their proposed technical blueprints, research papers, or working prototypes back onto the platform.

### 4. Mentorship & Scaling (Industry & Startup Hub)
* **The Action:** Solutions need resources to become reality. This is where the Industry module steps in.
* **The Process:** Startups, MSMEs, and CSR organizations browse active university projects. If they see a promising prototype, they connect directly through the portal to offer funding, industrial mentorship, or manufacturing support to turn the student project into a deployable product.

### 5. Real-Time Impact Monitoring (Government Command Center)
* **The Action:** State government officials need a macro view of societal progress and accountability.
* **The Process:** The Government Dashboard aggregates all activity into real-time visual charts. Officials can monitor how many challenges were submitted per district, which universities are most active, how much industry funding has been pledged, and the overall social impact achieved.

---

## ✨ Key Features
- **Smart Submission:** Citizen challenge forms with integrated WhatsApp bot access, media uploads, and district selection.
- **AI Categorization:** Automated keyword and context scanning to classify incoming issues.
- **Role-Based Portals:** Secure, customized dashboards for Citizens, Universities, Industry Partners, and Government Officials.
- **Workflow Management:** Complete pipeline from challenge acceptance by students to funding pledges by MSMEs.
- **Governance Analytics:** Live data visualization, district trend analysis, and activity monitoring.
- **Modern UI:** Responsive, highly interactive dark-mode interface with smooth state transitions.

---

## 🛠 Tech Stack
- **Framework:** Next.js 14, React 18
- **Language:** TypeScript
- **Styling:** Tailwind CSS v4
- **Animations:** Framer Motion (utilizing interactive UI components and SVG pattern styling)
- **Data Visualization:** Recharts
- **Components:** Radix UI Primitives
- **Icons:** Lucide React

---

## 📂 Project Structure

```text
samadhan-setu/
├── src/
│   ├── app/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   │   ├── ChallengeCard.tsx
│   │   ├── Navbar.tsx
│   │   ├── dashboards/
│   │   │   ├── CitizenDashboard.tsx
│   │   │   ├── GovernmentDashboard.tsx
│   │   │   ├── IndustryDashboard.tsx
│   │   │   └── UniversityDashboard.tsx
│   │   └── ui/
│   ├── context/
│   │   └── InnovationContext.tsx
│   ├── hooks/
│   ├── lib/
│   ├── types/
│   └── ...
├── package.json
├── next.config.mjs
├── tailwind.config.ts
├── tsconfig.json
├── postcss.config.mjs
├── .gitignore
└── README.md
