# 🚀 AI-Powered Website Builder

> Build stunning websites with AI assistance — transform your ideas into fully functional websites using cutting-edge AI technology.

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Convex-FF6F61?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" />
</p>

---

## ✨ Features

- 🤖 **AI-Powered Code Generation** — Describe what you want and get working code instantly
- 💬 **Chat-Based Interface** — Conversational UI to iteratively build and refine your site
- 🔴 **Live Preview** — See your website update in real-time as you chat
- 📦 **Export & Download** — Download your generated project as a ZIP
- 🌙 **Dark / Light Mode** — Beautiful theming out of the box
- 🔐 **Google Auth** — Secure sign-in with Google
- 🗄️ **Convex Backend** — Real-time database for workspace persistence

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Next.js 15** | React framework with App Router |
| **Tailwind CSS** | Utility-first styling |
| **Convex** | Real-time serverless database |
| **Google Gemini AI** | AI code generation & chat |
| **Sandpack** | In-browser code editor & preview |
| **Lucide React** | Icons |

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- A [Google Gemini API key](https://aistudio.google.com/)
- A [Convex](https://convex.dev) account

### Installation

```bash
# Clone the repository
git clone <your-repo-url>
cd ai-website-builder

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
```

### Environment Variables

Create a `.env.local` file with:

```env
NEXT_PUBLIC_GOOGLE_AUTH_CLIENT_ID=your_google_client_id
NEXT_PUBLIC_CONVEX_URL=your_convex_url
GEMINI_API_KEY=your_gemini_api_key
```

### Running Locally

```bash
# Start the Convex dev server (in one terminal)
npx convex dev

# Start the Next.js dev server (in another terminal)
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
ai-website-builder/
├── app/                    # Next.js App Router pages & API routes
│   ├── api/                # AI chat, code gen, prompt enhancer endpoints
│   └── (main)/workspace/   # Workspace page
├── components/
│   └── custom/             # ChatView, CodeView, Header, Hero
├── configs/                # AI model configuration
├── context/                # React context (messages)
├── convex/                 # Convex schema & mutations
├── data/                   # Prompts & lookup data
└── public/                 # Static assets
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
