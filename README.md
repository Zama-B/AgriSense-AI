# 🌱 AgriSense-AI

> **AI-Powered Agricultural Intelligence for South Africa**
>
> Addressing the water scarcity crisis through intelligent crop diagnosis, livestock monitoring, and water-conscious farming solutions.

---

## 📖 Table of Contents

- [Overview](#overview)
- [The Problem](#-the-problem)
- [Our Solution](#-our-solution)
- [Core Features](#-core-features)
- [Screenshots](#-screenshots)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [Future Roadmap](#-future-roadmap)
- [Team](#-team)
- [License](#-license)
- [Contact & Support](#-contact--support)

---

## 🎯 Overview

**AgriSense-AI** is a free, mobile-first web application designed to revolutionize farming practices across South Africa by combining AI-powered image diagnosis, intelligent agricultural guidance, and water-conscious farming solutions.

The platform empowers farmers—from urban smallholders in townships to large-scale commercial operations—with actionable AI insights to diagnose crop and livestock problems, optimize irrigation strategies, and conserve water.

### Target Users

| User Type | Use Case |
|-----------|----------|
| **Urban Smallholders** | Backyard farming, township agriculture, water-efficient crop production |
| **Rural Farmers** | Crop optimization, livestock monitoring, resource management guidance |
| **Commercial Farmers** | Large-scale analytics, irrigation optimization, sustainability practices |
| **Agricultural NGOs** | Scalable AI-powered extension services for farming communities |

---

## 🌍 The Problem

South Africa faces a deepening structural water crisis, with agriculture consuming a significant portion of the country's freshwater resources. Key challenges include:

- **Limited Access**: Many farmers lack immediate access to agronomic expertise
- **Water Wastage**: Inefficient irrigation practices waste critical resources
- **Delayed Diagnosis**: Crop and livestock problems go unidentified, causing losses
- **Infrastructure Issues**: Load-shedding affects irrigation systems and farm operations
- **High Costs**: Agricultural support services remain inaccessible to smallholders
- **Knowledge Gaps**: Lack of accessible, AI-powered tools tailored to South African agriculture

---

## 💡 Our Solution

AgriSense-AI combines cutting-edge AI technology with water-conscious agricultural practices to deliver:

✅ **AI Photo Diagnosis** - Instant analysis of crop, livestock, soil, and irrigation problems  
✅ **Intelligent Advisor Chat** - Context-aware farming recommendations  
✅ **Water-First Intelligence** - Every recommendation prioritizes conservation  
✅ **Sample Diagnoses** - One-tap demonstration for instant testing  
✅ **Mobile-First Design** - Works seamlessly in rural and urban environments  

---

## ✨ Core Features

### 📸 AI Photo Diagnosis

Upload images to receive instant AI-generated diagnoses including:

- **Crop Health**: Disease detection, water stress analysis, nutrient deficiency identification
- **Livestock Assessment**: Health indicators, weight analysis, disease recognition
- **Soil Evaluation**: Condition assessment, moisture analysis, fertility insights
- **Irrigation Diagnostics**: System leak detection, efficiency analysis, water conservation opportunities

### 🤖 AI Advisor Chat

Interactive assistant providing:

- Contextual farming recommendations
- Irrigation and watering guidance
- Sustainable and water-conscious farming advice
- South Africa-specific agricultural insights
- Real-time problem-solving support

### 💧 Water-First Intelligence

Every recommendation prioritizes:

- Water conservation strategies
- Efficient irrigation scheduling
- Drought-resilient farming methods
- Sustainable agricultural practices
- Cost-effective resource management

### ⚡ One-Tap Sample Diagnoses

Preloaded agricultural samples including:

- Diseased maize leaves
- Underweight livestock
- Wilted vegetables
- Leaking irrigation systems
- Cracked dry soil
- Tomato blight and fungal diseases

Perfect for users to test functionality and for project evaluators to demonstrate capabilities instantly.

### 📱 Mobile-First Experience

Optimized for:

- Rural and urban connectivity
- Low-data usage scenarios
- Smartphone accessibility
- Fast interactions
- Responsive design across all devices

---

## 📸 Screenshots

Get a visual walkthrough of AgriSense-AI's interface and features:

### Home Screen & Navigation
![AgriSense-AI Home Screen](https://github.com/Zama-B/AgriSense-AI/blob/main/Screenshot%202026-05-21%20151457.png?raw=true)
*Main landing page with quick access to AI Photo Diagnosis and Sample Diagnoses*

### AI Photo Diagnosis Interface
![AI Photo Diagnosis](https://github.com/Zama-B/AgriSense-AI/blob/main/Screenshot%202026-05-21%20151806.png?raw=true)
*User-friendly image upload interface with camera and gallery options*

### Diagnosis Results
![Diagnosis Results](https://github.com/Zama-B/AgriSense-AI/blob/main/Screenshot%202026-05-21%20151919.png?raw=true)
*Comprehensive AI-generated diagnosis with water-conscious recommendations*

### AI Advisor Chat
![AI Advisor Chat](https://github.com/Zama-B/AgriSense-AI/blob/main/Screenshot%202026-05-21%20151457.png?raw=true)
*Interactive chatbot providing contextual farming advice and support*

### Sample Diagnoses
![Sample Diagnoses](https://github.com/Zama-B/AgriSense-AI/blob/main/Screenshot%202026-05-21%20151457.png?raw=true)
*Pre-loaded examples demonstrating the app's diagnostic capabilities*

### Mobile Responsiveness
![Mobile View](https://github.com/Zama-B/AgriSense-AI/blob/main/Screenshot%202026-05-21%20151919.png?raw=true)
*Optimized interface for smartphone access in the field*

---

## 🧠 Tech Stack

| Category | Technologies |
|----------|--------------|
| **Frontend** | React 19, TanStack Start, Vite 7, Tailwind CSS v4 |
| **Backend** | Supabase Edge Functions, Lovable Cloud |
| **AI/ML** | Google Gemini 2.5 Flash, Lovable AI Gateway |
| **Database** | Supabase PostgreSQL (planned), Row-Level Security (RLS) |
| **Storage** | Cloud Storage (Firebase/AWS S3) |
| **Development** | GitHub, JavaScript, Markdown, Vite |
| **DevOps** | Docker, GitHub Actions, Cloud Deployment |

---

## 🔄 Architecture

### System Workflow

```
User uploads image
    ↓
AI Processing (Gemini 2.5 Flash)
    ↓
Intelligent Diagnosis Generation
    ↓
Water-First Recommendations
    ↓
Action Plan Output
    ↓
User Takes Action
```

### Security & Privacy

- ✅ AI API keys securely handled server-side
- ✅ No farmer images permanently stored
- ✅ Protected edge-function architecture
- ✅ Future database security using Row-Level Security (RLS)
- ✅ GDPR-compliant data handling

---

## 🚀 Installation

### Prerequisites

- **Node.js** v16 or higher
- **npm** or **yarn** package manager
- **Git** version control
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Quick Start

#### 1. Clone the Repository

```bash
git clone https://github.com/Zama-B/AgriSense-AI.git
cd AgriSense-AI
```

#### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

#### 3. Configure Environment Variables

Create a `.env.local` file in the root directory:

```env
VITE_API_URL=http://localhost:5000
VITE_GEMINI_API_KEY=your_gemini_api_key_here
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

#### 4. Start the Development Server

```bash
npm run dev
# or
yarn dev
```

Visit `http://localhost:5173` in your browser.

### Building for Production

```bash
npm run build
npm run preview
```

---

## 💻 Usage

### For Farmers

1. **Access the Platform**: Open AgriSense-AI in your web browser
2. **Upload an Image**: Select a photo of your crop, livestock, soil, or irrigation system
3. **Get AI Diagnosis**: Receive instant analysis and problem identification
4. **View Recommendations**: Read water-conscious action plans and guidance
5. **Access Advisor Chat**: Ask follow-up questions and get contextual advice
6. **Track Solutions**: Implement recommendations and monitor improvements

### For Developers

Clone the repository and follow the [Installation](#-installation) section above.

```bash
# Development mode with hot reload
npm run dev

# Build for production
npm run build

# Run tests (when available)
npm run test
```

See [CONTRIBUTING.md](CONTRIBUTING.md) for development guidelines and contribution workflow.

---

## 📁 Project Structure

```
AgriSense-AI/
├── src/
│   ├── components/          # Reusable React components
│   ├── pages/               # Route pages
│   ├── styles/              # Global styles & Tailwind config
│   ├── utils/               # Helper functions & utilities
│   ├── services/            # API & external service calls
│   └── App.tsx              # Root component
├── public/                  # Static assets
├── docs/
│   └── screenshots/         # Screenshot images for README
├── .github/
│   └── workflows/           # CI/CD pipelines
├── .env.local               # Environment variables (local)
├── vite.config.ts           # Vite configuration
├── tailwind.config.ts       # Tailwind CSS configuration
├── package.json             # Dependencies & scripts
└── README.md                # This file
```

---

## 🤝 Contributing

We welcome contributions from developers, agricultural experts, and community members!

### How to Contribute

1. **Fork** the repository
2. **Create** a feature branch
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make** your changes and test thoroughly
4. **Commit** with clear, descriptive messages
   ```bash
   git commit -m "Add: Brief description of changes"
   ```
5. **Push** to your fork
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Open** a Pull Request with a detailed description

### Contribution Areas

- 🐛 **Bug Fixes**: Report and fix issues
- ✨ **Features**: Propose and implement new features
- 📚 **Documentation**: Improve README and docs
- 🎨 **UI/UX**: Enhance design and usability
- 🧪 **Testing**: Improve test coverage
- 🌐 **Localization**: Add language support

For detailed guidelines, see [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📈 Future Roadmap

### Phase 2 (Q3 2026)

- [ ] Multi-language support (isiZulu, Sesotho, Xhosa)
- [ ] Offline Progressive Web App (PWA) capability
- [ ] WhatsApp integration for SMS-based access
- [ ] Weather alert system
- [ ] Soil moisture sensor integration

### Phase 3 (Q4 2026)

- [ ] AI-powered crop forecasting
- [ ] Agricultural finance & insurance integration
- [ ] Community forum for farmer knowledge sharing
- [ ] Regional yield benchmarking
- [ ] Export recommendations reports

### Phase 4 (2027 & Beyond)

- [ ] Mobile app (iOS/Android) native versions
- [ ] Drone/satellite imagery integration
- [ ] Blockchain-based produce tracking
- [ ] Carbon credit marketplace
- [ ] Supply chain optimization tools

---

## 👥 Team

AgriSense-AI was proudly created by a dedicated team of innovators:

- **Zizipho Malangeni**
- **Sibongiseni Magutshwa**
- **Zama Bhengane** (Project Lead)
- **Thabang Lesotho**
- **Lungile P. Nzimande**

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👥 Contact & Support

- **Project Lead**: Zama Bhengane
- **Email**: support@agrisense-ai.com
- **GitHub Issues**: [Report Bugs & Request Features](https://github.com/Zama-B/AgriSense-AI/issues)
- **Discussions**: [Join Community Discussions](https://github.com/Zama-B/AgriSense-AI/discussions)

---

## 🌍 Impact & Vision

AgriSense-AI is committed to making a measurable positive impact on South African agriculture:

### Our Commitment

- 💧 **Reduce water consumption** by 20-30% for early adopters
- 📈 **Increase crop yields** through better management and diagnostics
- 🛡️ **Strengthen food security** in urban and rural communities
- 💼 **Enable agricultural innovation** and entrepreneurship
- 🌱 **Promote sustainability** across farming practices
- ♿ **Ensure accessibility** for all farmers regardless of technical expertise

### Vision Statement

> *"To make AI-powered agricultural support accessible to every farmer in South Africa—from township gardens to large-scale commercial operations—while enabling smarter water usage and building a more resilient, sustainable agricultural future."*

---

## 📊 Project Status

- 🚧 **Status**: Active Development
- 🔄 **Current Version**: v1.1
- 📱 **Platform**: Mobile-First Web Application
- 🇿🇦 **Focus**: South African Agriculture
- 🌍 **Scope**: Expanding to continental agriculture

---

## ⭐ Show Your Support

If AgriSense-AI has helped you or you believe in our mission, please consider:

- ⭐ Starring the repository
- 🔗 Sharing with other farmers and agricultural professionals
- 💬 Providing feedback and feature suggestions
- 🤝 Contributing to the project
- 📢 Spreading the word about sustainable farming solutions

---

**Together, we're growing a more sustainable, water-conscious agricultural future for South Africa. 🌾**

*Last Updated: May 2026*
