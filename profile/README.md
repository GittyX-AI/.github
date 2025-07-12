# GittyX

**🔍 Understand your codebase history with AI-powered Git analysis**  
GittyX is an open-source CLI tool that uses AI to analyze your Git repository’s evolution and launches a local web dashboard for exploring your codebase's journey.

![npm version](https://img.shields.io/npm/v/gittyx-ai) ![license](https://img.shields.io/github/license/GittyX-AI/gittyx-ai) ![stars](https://img.shields.io/github/stars/GittyX-AI/gittyx-ai?style=social)  

---

## 🚀 Key Features

### 🧠 AI-Powered Code Analysis
Analyze commits, generate semantic summaries, and ask natural language questions about your repo:
- “When did we switch to GraphQL?”
- “Why was Redis removed?”

### 🧰 CLI Tool + 🌐 Web Dashboard
- Analyze Git repositories using the CLI
- Launch an interactive dashboard at `http://localhost:3000`
- Commit timeline, semantic summaries, Q&A interface

### 🔒 Local-First & Private
All processing happens locally by default. Your code never leaves your machine.

### 📈 Smart Timeline Analysis
Understand the evolution of major features, architectural decisions, and code components over time.

---

## 🧑‍💻 Quick Start

```bash
# Install GittyX globally
npm install -g gittyx-ai

# Navigate to your Git project
cd your-project

# Analyze your repository
gittyx analyze
```

> 💡 Requires Node.js 18+ and a Git repository  
> 🔑 For online AI mode, set your `GEMINI_API_KEY` in `.env`  

---

## 📦 Install & Configure

1. Install GittyX globally:  
   ```bash
   npm install -g gittyx-ai
   ```

2. Verify installation:  
   ```bash
   gittyx --version
   ```

3. Set up `.env` with your Gemini API key (for online mode):  
   ```bash
   GEMINI_API_KEY=your_key_here
   ```

4. Analyze your repo and launch dashboard:  
   ```bash
   gittyx analyze
   ```

---

## 🗂️ CLI Options
```bash
gittyx analyze
```
```bash
Usage: gittyx analyze [options] 

Analyze repository and start dashboard 

Options: 
-l, --limit <number>  The number of the most recent commits to analyze (default: 200) 
-d, --date <date>     The date to start analyzing commits from (YYYY-MM-DD) 
-m, --mode <string>   GittyX mode: online (gemini or openai) or local (huggingface) (default: "online") 
-h, --help            display help for command
```

---

## 🧪 Coming Soon

- ✅ VSCode Extension
- ✅ GitHub Integration
- ✅ Timeline Diff Comparison
- ✅ Team Dashboards *(online only)*

---

Join thousands of developers using GittyX to explore and understand their codebase history.

---

## 🤝 Contributing

We welcome contributions! Check out our [Contribution Guide](https://github.com/GittyX-AI/gittyx-ai/blob/main/CONTRIBUTING.md) and help improve GittyX.

---

## 👨‍💻 About the Developer

Developed with ❤️ by [Mohammed TATI](https://github.com/tatimohammed)

---

## 📜 License

Licensed under the [Apache-2.0 License](https://github.com/GittyX-AI/gittyx-ai/blob/main/LICENSE)

---

> Made for developers, by a developer
