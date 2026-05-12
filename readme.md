# 🧴 AI Skin Analyser

An intelligent skin analysis web application powered by AI. Upload a photo of your skin and receive instant, personalized analysis including skin type detection, concern identification, and tailored skincare recommendations.

---

## ✨ Features

- 📸 **Image Upload** — Upload a skin photo directly from your device
- 🤖 **AI-Powered Analysis** — Uses Claude AI to analyze skin type, tone, and visible concerns
- 📋 **Detailed Report** — Receive a breakdown of:
  - Skin type (oily, dry, combination, normal, sensitive)
  - Detected concerns (acne, pigmentation, dryness, redness, etc.)
  - Hydration and texture assessment
- 💡 **Personalized Recommendations** — Get product and routine suggestions tailored to your skin
- ⚡ **Fast & Private** — Analysis runs on-demand; no images are stored

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- npm (comes with Node.js)
- An [Anthropic API key](https://console.anthropic.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/skin-analyser.git
   cd skin-analyser
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory:
   ```env
   REACT_APP_ANTHROPIC_API_KEY=your_anthropic_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

---

## 🛠️ Available Scripts

| Script | Description |
|--------|-------------|
| `npm start` | Runs the app in development mode with hot reload |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production to the `build/` folder |
| `npm run eject` | Ejects from Create React App (one-way, irreversible) |

---

## 🏗️ Tech Stack

- **Frontend** — React 19, CSS3
- **AI Model** — Claude (Anthropic API) via `claude-sonnet-4-20250514`
- **Bootstrapped with** — [Create React App](https://github.com/facebook/create-react-app)

---

## 📁 Project Structure

```
skin-analyser/
├── public/
│   └── index.html
├── src/
│   ├── components/        # Reusable UI components
│   ├── App.js             # Root component
│   ├── App.css            # Global styles
│   └── index.js           # Entry point
├── .env                   # Environment variables (not committed)
├── .gitignore
├── package.json
└── README.md
```

---

## 🔐 Environment Variables

| Variable | Required | Description |
|----------|----------|-------------|
| `REACT_APP_ANTHROPIC_API_KEY` | ✅ Yes | Your Anthropic API key for Claude |

> ⚠️ **Never commit your `.env` file.** It is already listed in `.gitignore`.

---

## 📦 Building for Production

```bash
npm run build
```

This creates an optimized production build in the `build/` folder, ready to deploy to any static hosting service (Vercel, Netlify, GitHub Pages, etc.).

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## ⚠️ Disclaimer

This application is intended for **informational purposes only** and does not constitute medical advice. For any skin-related health concerns, please consult a qualified dermatologist.

---

## 📄 License

This project is private. All rights reserved.
