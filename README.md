# AI Educational Assistant Suite for Uganda's CBC

A suite of specialized AI-powered tools designed to support educators in Uganda with the Competency-Based Curriculum (CBC). This project aims to reduce administrative workload and empower teachers to focus on what matters most: their students.

🚀 **Live Application:** [cbcaiug.github.io](https://cbcaiug.github.io)

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Core Features](#-core-features)
- [Access Tiers](#-access-tiers)
- [Assistants Available](#️-assistants-available)
- [Tech Stack](#-tech-stack)
- [How It Works](#-how-it-works)
- [Getting Started](#-getting-started)
- [Installation as PWA](#-installation-as-pwa)
- [API Providers Supported](#-api-providers-supported)
- [Data Privacy & Security](#-data-privacy--security)
- [Disclaimer](#️-disclaimer)
- [Project Creator](#-project-creator)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🎯 Overview

The AI Educational Assistant is specifically designed for Ugandan educators adapting to the Competency-Based Curriculum. This platform provides specialized AI assistants with custom-built prompts aligned to Uganda's NCDC framework, helping teachers create lesson plans, assessments, and schemes of work in minutes instead of hours.

**Key Benefits:**
- ⏱️ Reclaim 10+ hours per week
- 📚 NCDC-aligned content generation
- 🔒 Privacy-focused (chat history stored locally)
- 📱 Works on any device (mobile, tablet, desktop)
- 🌐 Progressive Web App (install for offline access)
- 🆓 Generous free tier available

---

## ✨ Core Features

### User Accounts & Quotas
- **Firebase Authentication:** Secure sign-up with email/password or Google Sign-In
- **Three Access Tiers:** Guest, Free, and Pro tiers with different quota limits
- **Real-time Sync:** Quotas sync across all devices via Cloud Firestore
- **Quota Management:** Transparent tracking of messages, downloads, and copy actions

### Specialized AI Assistants
- **14+ AI Assistants:** Each with custom-built prompts designed for Uganda's CBC educational context
- **NCDC-Aligned:** All prompts follow official curriculum guidelines
- **Versatile Use Cases:** Lesson planning, assessment creation, schemes of work, grading assistance

### Secure Prompt Management
- **Backend Storage:** Core prompts stored securely on Google Apps Script backend
- **No Client-Side Exposure:** Prompts not visible in browser code
- **Quality Control:** Centralized prompt updates for consistent quality

### Multi-API & Model Support
- **Major Providers:** Google Gemini, Anthropic Claude, OpenAI GPT, Groq Llama, DeepSeek, Qwen
- **Seamless Switching:** Change models based on preference and availability
- **Shared Keys:** Use provided shared keys or bring your own for extended usage

### Real-time Streaming
- **Live Responses:** AI responses stream in real-time for fast, interactive experience
- **Progressive Display:** See content as it's generated
- **Efficient UX:** No waiting for complete responses

### File Uploads
- **Vision Support:** Attach syllabus pages, images, or documents
- **Context-Rich:** Provide AI with visual context for accurate materials
- **Model Compatibility:** Works with vision-enabled models (Gemini, GPT-4 Vision, Claude 3)

### Export Capabilities
- **Multiple Formats:** Copy to clipboard, download as Word/PDF
- **Google Docs Integration:** Save directly to Google Docs with one click
- **Cross-Platform:** Works on any device with browser

### Admin Dashboard
- **Real-time Monitoring:** Track active users and quota usage
- **User Management:** View and manage user accounts
- **Analytics:** Service usage patterns and statistics

### Responsive Design
- **Modern UI:** Clean glass morphism interface
- **Mobile-First:** Works beautifully on all screen sizes
- **Dark Theme:** Easy on the eyes for extended use
- **Accessible:** Designed for users with varying technical skills

---

## 💳 Access Tiers

Three tiers are available to suit different needs:

### 🎭 Guest Access (No Account Required)
Perfect for trying out the platform before creating an account.

- **Messages:** 30 AI conversations
- **Document Saves:** 5 Google Docs exports
- **Copy Actions:** 5 clipboard copies
- **API Key Slots:** 3 custom API keys

### 🆓 Free Account (Sign Up Required)
Ideal for regular use with expanded quotas.

- **Messages:** 50 AI conversations
- **Document Saves:** 20 Google Docs exports
- **Copy Actions:** 20 clipboard copies
- **API Key Slots:** 6 custom API keys

### ⭐ Pro Tier (Contact for Access)
For power users who need maximum capacity.

- **Messages:** 100 AI conversations
- **Document Saves:** 100 Google Docs exports
- **Copy Actions:** 100 clipboard copies
- **Exclusive Features:** Priority support, early access to new assistants

**Want Unlimited?** Add your own API keys (free from Google Gemini) for extended usage beyond tier limits.

📄 **Full Comparison:** Visit [cbcaiug.github.io/billing.html](https://cbcaiug.github.io/billing.html)

---

## 🛠️ Assistants Available

| Assistant Name | Description | Best For |
|---|---|---|
| **Item Writer** | Generates scenario-based assessment items with structured scoring guides | Creating tests, quizzes, and exams |
| **UCE BIO Item Writer** | Specialized biology assessment items for Uganda Certificate of Education level | UCE Biology assessments |
| **Lesson Plans (NCDC)** | Creates detailed lesson plans following the official NCDC template | Daily lesson preparation |
| **Lesson Plans (with Biblical Integration)** | NCDC lesson plans with integrated biblical values and Christian worldview | Faith-based schools |
| **UACE SoW NCDC** | Comprehensive schemes of work for Uganda Advanced Certificate of Education level | A-Level planning |
| **Scheme of Work NCDC** | Develops structured schemes of work based on CBC syllabus requirements | Term/year planning |
| **Scheme of Work (with Biblical Integration)** | CBC schemes of work incorporating biblical principles and Christian values | Faith-based curriculum planning |
| **Lesson Notes Generator** | Produces comprehensive and well-structured notes for any topic | Student handouts, study materials |
| **UCE Project Assistant** | Guides students through UCE project planning and execution | Student project supervision |
| **AI in Education Coach** | Provides guidance on integrating AI tools into classroom teaching | Professional development |
| **Essay Grading Assistant** | Helps grade student essays based on specified rubrics and criteria | Marking and feedback |
| **Coteacher** | All-purpose teaching assistant for questions and brainstorming | General teaching support |
| **Data & Document Analyst** | Analyzes educational data, documents, and research materials with AI insights | Data analysis, research |
| **Prompt Assistant** | AI-powered prompt engineering and optimization for educational content | Advanced AI usage |

---

## 💻 Tech Stack

### Frontend
- **React:** Via CDN for component-based UI
- **Tailwind CSS:** Utility-first styling
- **Marked.js:** Markdown rendering for AI responses
- **Vanilla JavaScript:** Core application logic

### Backend
- **Google Apps Script:** Secure prompt storage and document creation
- **Firebase Authentication:** User account management
- **Cloud Firestore:** Real-time quota tracking and sync

### Deployment
- **GitHub Pages:** Static site hosting
- **Custom Domain:** cbcaiug.github.io

### APIs Integrated
- **Google Gemini API:** Primary AI provider
- **OpenAI API:** GPT-4, GPT-3.5 models
- **Anthropic API:** Claude models
- **Groq API:** Llama models
- **DeepSeek API:** DeepSeek models
- **Qwen API:** Alibaba Cloud Qwen models

---

## 🔧 How It Works

### User Authentication
1. Visit [cbcaiug.github.io](https://cbcaiug.github.io)
2. Sign up with email/password or Google Sign-In
3. Account created with Firebase Authentication
4. Initial quotas assigned automatically

### Quota System
- **Guest Users:** Limited trial quotas without account
- **Free Accounts:** Expanded quotas upon registration
- **Real-time Tracking:** Quotas sync across devices via Firestore
- **Quota Reset:** Based on tier-specific policies

### AI Interaction
1. Select a specialized assistant
2. Provide input (text, files, syllabus pages)
3. AI generates content using custom prompts
4. Review and refine the output
5. Export to Word, PDF, or Google Docs

### API Key Options
- **Shared Keys:** Use provided keys for free tier quotas
- **Bring Your Own Key (BYOK):** Add personal API keys for extended usage
- **Storage:** Keys stored locally in browser (never sent to servers)
- **Privacy:** Full control over API key security

### Data Storage
- **Local:** Chat history, API keys, settings (browser storage)
- **Cloud:** Email, quotas, last active timestamp (Firestore)
- **Exported Docs:** Google Drive (for quality improvement)

---

## 🚀 Getting Started

### Quick Start (3 Steps)

1. **Visit the App**
   ```
   https://cbcaiug.github.io
   ```

2. **Create Account**
   - Click "Sign Up"
   - Use email/password or Google Sign-In
   - Receive free quotas automatically

3. **Start Creating**
   - Select an assistant
   - Enter your requirements
   - Review and export content

### Optional: Add Your Own API Key

For extended usage beyond tier limits:

1. Get a free API key from [Google AI Studio](https://aistudio.google.com/apikey)
2. Go to Settings → API Keys
3. Add your key
4. Enjoy extended usage (subject to provider limits)

**Other Providers:**
- [OpenAI](https://platform.openai.com/api-keys) (Paid)
- [Anthropic](https://console.anthropic.com/settings/keys) (Paid)
- [Groq](https://console.groq.com/keys) (Free tier available)
- [DeepSeek](https://platform.deepseek.com/api_keys) (Paid)
- [Qwen](https://dashscope.console.aliyun.com/apiKey) (Paid)

---

## 📱 Installation as PWA

Install the app on your device for quick access and offline capabilities.

### Android (Chrome)
1. Open the app in Chrome
2. Tap the menu (⋮)
3. Select "Install app" or "Add to Home screen"
4. App icon appears on home screen

### iOS (Safari)
1. Open the app in Safari
2. Tap the Share button (↑)
3. Select "Add to Home Screen"
4. App icon appears on home screen

### Desktop (Chrome, Edge, Brave)
1. Open the app in browser
2. Click the install icon in address bar
3. Confirm installation
4. App appears in applications

**Benefits:**
- ⚡ Faster loading times
- 📴 Offline access to stored chats
- 🎯 Dedicated app icon
- 🔔 Notification support (future)

---

## 🔌 API Providers Supported

### Google Gemini
- **Models:** Gemini 1.5 Pro, Gemini 1.5 Flash
- **Free Tier:** Yes (via Google AI Studio)
- **Best For:** General use, Ugandan context understanding
- **Vision Support:** Yes

### OpenAI
- **Models:** GPT-4, GPT-4 Turbo, GPT-3.5 Turbo
- **Free Tier:** No
- **Best For:** Complex reasoning, creative tasks
- **Vision Support:** Yes (GPT-4 Vision)

### Anthropic Claude
- **Models:** Claude 3 Opus, Claude 3 Sonnet, Claude 3 Haiku
- **Free Tier:** No
- **Best For:** Long-form content, ethical considerations
- **Vision Support:** Yes (Claude 3 models)

### Groq
- **Models:** Llama 3, Mixtral
- **Free Tier:** Yes
- **Best For:** Fast responses, open-source preference
- **Vision Support:** No

### DeepSeek
- **Models:** DeepSeek Chat, DeepSeek Coder
- **Free Tier:** No
- **Best For:** Technical content, coding assistance
- **Vision Support:** No

### Qwen (Alibaba Cloud)
- **Models:** Qwen-Turbo, Qwen-Plus
- **Free Tier:** No
- **Best For:** Multilingual support, technical tasks
- **Vision Support:** Yes

---

## 🔒 Data Privacy & Security

### What's Stored Locally (Your Device)
- ✅ Chat history
- ✅ API keys (optional)
- ✅ Application settings
- ✅ User preferences

**You Control:** Clear at any time via browser settings

### What's Stored in Cloud (Firestore)
- ✅ Email address
- ✅ Quota usage (messages, saves, copies)
- ✅ Last active timestamp
- ✅ Tier status (Guest/Free/Pro)

**Security:** Firebase Security Rules restrict access

### What's NOT Stored
- ❌ Chat content (stays on your device)
- ❌ Personal student information
- ❌ Payment card details
- ❌ API keys (stored locally only)

### Data Usage
- **Exported Documents:** May be reviewed for quality improvement (no personal info attached)
- **Analytics:** Anonymous usage patterns via Google Analytics
- **Third-Party APIs:** Your prompts sent to selected AI provider only

📄 **Full Details:** [Privacy Policy](https://cbcaiug.github.io/privacy.html)

---

## ⚠️ Disclaimer

### AI-Generated Content Advisory

The content generated by AI is intended as a **draft or starting point**, not a final product. While the models are powerful, they can:

- ❌ Make factual errors
- ❌ Generate culturally inappropriate content
- ❌ Produce biased or incomplete information
- ❌ Misunderstand Ugandan educational context
- ❌ Create content that doesn't align with NCDC standards

### User Responsibilities

Teachers **must**:
- ✅ Review all AI-generated content thoroughly
- ✅ Verify accuracy and appropriateness
- ✅ Adapt content to their specific classroom needs
- ✅ Ensure alignment with NCDC curriculum
- ✅ Consider cultural and local context
- ✅ Use professional judgment before implementation

### Limitation of Liability

The Service accepts no liability for:
- Educational outcomes or student performance
- Inaccuracies in AI-generated content
- Third-party service interruptions (AI providers, Google)
- Data loss due to browser issues

📄 **Full Terms:** [Terms of Service](https://cbcaiug.github.io/terms.html)

---

## 👨💻 Project Creator

This project was conceptualized, designed, and developed by **Derrick Musamali**, a secondary school teacher of Biology and Chemistry in Uganda.

### Mission
To empower Ugandan educators with AI tools that reduce administrative burden and allow more time for meaningful student interaction.

### Background
As a practicing teacher, the challenges of adapting to CBC while managing heavy workloads were experienced firsthand. This platform was built to solve real problems faced by teachers every day.

### Contact
- **Email:** [cbcaitool@gmail.com](mailto:cbcaitool@gmail.com)
- **WhatsApp:** [+256 750 470234](https://wa.me/256750470234)
- **Location:** Kampala, Uganda
- **Updates Channel:** [WhatsApp Channel](https://whatsapp.com/channel/0029Vb6cj6J5vKAGEYH1Fk1d)

### Support the Project
This tool will always have a free tier available for teachers. For those who wish to support ongoing development:
- 💝 [Support the Creator](https://cbcaiug.github.io/gift.html)
- ⭐ Upgrade to Pro tier for expanded quotas
- 📣 Share with fellow educators

---

## 🤝 Contributing

### Feedback Welcome
- 🐛 **Bug Reports:** Found an issue? Report via [email](mailto:cbcaitool@gmail.com) or [WhatsApp](https://wa.me/256750470234)
- 💡 **Feature Requests:** Have an idea? Share it!
- 📝 **Content Suggestions:** Know how to improve prompts? Let us know!
- ⭐ **Reviews:** Share your experience with colleagues

### For Developers
This is currently a closed-source project, but feedback and suggestions are always welcome.

### For Educators
The best way to contribute is:
1. Use the tool and provide honest feedback
2. Share with fellow teachers
3. Report any issues or inaccuracies
4. Suggest new assistants or features

---

## 📜 License

This project is licensed under the MIT License.

### What This Means
- ✅ Free to use for educational purposes
- ✅ No warranty provided (use at your own risk)
- ✅ Content you generate is yours
- ❌ Service ownership and code remain with creator
- ❌ No commercial use without authorization

See the [LICENSE](LICENSE) file for full details.

---

## 📚 Additional Resources

### Documentation
- [About the Project](https://cbcaiug.github.io/about.html)
- [Frequently Asked Questions](https://cbcaiug.github.io/faq.html)
- [Access Tiers & Plans](https://cbcaiug.github.io/billing.html)
- [Privacy Policy](https://cbcaiug.github.io/privacy.html)
- [Terms of Service](https://cbcaiug.github.io/terms.html)

### Video Guides
- 🎥 [Full Tutorial](https://youtu.be/KGplNQfdf_w)
- 🎥 [Quick Demo](https://youtu.be/YXsOnmAD1Lg)

### Sample Outputs
- 📄 [Generated Lesson Plans](https://cbcaiug.github.io/samples.html)
- 📄 [Assessment Items](https://cbcaiug.github.io/samples.html)
- 📄 [Schemes of Work](https://cbcaiug.github.io/samples.html)

---

## 🌟 Acknowledgments

- **Ugandan Teachers:** For inspiring this project through their dedication
- **NCDC:** For the Competency-Based Curriculum framework
- **AI Providers:** Google, OpenAI, Anthropic, Groq, DeepSeek, Alibaba Cloud
- **Open Source Community:** For the tools and libraries that made this possible
- **Firebase Team:** For authentication and database infrastructure
- **Early Adopters:** For testing and feedback

---

## 📞 Get Help

### Need Assistance?
- 📧 Email: [cbcaitool@gmail.com](mailto:cbcaitool@gmail.com)
- 💬 WhatsApp: [+256 750 470234](https://wa.me/256750470234)
- 📱 Updates: [WhatsApp Channel](https://whatsapp.com/channel/0029Vb6cj6J5vKAGEYH1Fk1d)

### Response Time
- **General Inquiries:** Within 48 hours
- **Bug Reports:** Within 24 hours
- **Pro Tier Support:** Priority handling

---

**Built with ❤️ for Ugandan Educators**

*Empowering teachers to teach smarter, not harder.*