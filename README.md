<p align="center">
  <a href="https://github.com/bniladridas/gemini_cli"><img src="https://avatars.githubusercontent.com/u/203538727?s=200&v=4" height="128"></a>
  <h2 align="center"><a href="https://github.com/bniladridas/gemini_cli">Synthara | The Education Times CLI</a></h2>
  <p align="center">An AI-powered command-line tool that generates beautifully formatted, article-style answers using Google's Gemini Model.<p>
  <p align="center">
    <a href="https://aistudio.google.com/app/apikey">
    	<img src="https://img.shields.io/badge/%E2%9C%A8-Gemini%20API-0a0a0a.svg?style=flat&colorA=0a0a0a" alt="Gemini API" />
    </a>
    <a href="https://github.com/bniladridas/gemini_cli">
    	<img src="https://img.shields.io/badge/%E2%9C%A8-Open%20Source-0a0a0a.svg?style=flat&colorA=0a0a0a" alt="Open Source" />
    </a>
    <a href="https://github.com/bniladridas">
    	<img src="https://img.shields.io/badge/%E2%9C%A8-Created%20by%20Niladri-0a0a0a.svg?style=flat&colorA=0a0a0a" alt="Niladri Das" />
    </a>
  </p>
</p>

<br>

![](https://i.imgur.com/waxVImv.png)

## 🧠 Overview

Synthara is a sophisticated newspaper-style AI CLI powered by Google's Gemini models. It transforms your queries into elegantly formatted articles directly in your terminal. The responses are presented with professional formatting, including headers, sections, and proper markdown styling.

### Why Synthara?

- **For Students**: Get well-structured, educational content for research and learning
- **For Writers**: Generate article drafts and creative content with proper formatting
- **For Developers**: Access AI capabilities with minimal setup in a familiar terminal environment
- **For Educators**: Create teaching materials and explanations in a readable format

## ✨ Features

- 📰 **Rich Article Formatting**: Responses are structured like professional articles with headers, sections, and proper markdown
- 🧠 **Multiple AI Models**: Choose between Gemini models (`flash`, `pro`, `preview`) for different capabilities and speeds
- 🖼️ **Elegant Presentation**: Newspaper-style interface with beautiful headers, footers, and typography
- ⚡ **Fast & Efficient**: Lightweight design with minimal dependencies for quick responses
- 🔐 **API Key Management**: Securely save your API key for future sessions
- 💻 **Terminal Native**: Works entirely in your terminal with no browser or GUI required
- 🧪 **Developer Friendly**: Easy to customize, extend, or integrate into your workflows

---

## 🚀 Installation

### One-Command Setup (Recommended)

Install everything with a single command:

```bash
curl -s https://raw.githubusercontent.com/bniladridas/gemini_cli/main/setup-cli.sh | bash
```

This will:
- Create a dedicated installation directory
- Set up a Python virtual environment
- Install all dependencies
- Create a launcher script

After installation, start the application with:

```bash
cd ~/synthara-cli && ./gemini-chat
```

### Manual Installation

If you prefer more control over the installation process:

```bash
# Clone the repository
git clone https://github.com/bniladridas/gemini_cli.git
cd gemini_cli

# Create a virtual environment (recommended)
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install google-generativeai rich

# Run the application
python simple_gemini_cli/gemini_chat.py
```

### API Key

You'll need a Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey). The application will prompt you for this key on first run and securely save it for future sessions.

---

## 🧭 Usage

### Getting Started

After installation and launching the application:

1. Enter your Gemini API key when prompted (only needed once)
2. Type your question or topic after the "READER INQUIRY" prompt
3. Receive a beautifully formatted article-style response
4. Continue with more questions or exit when done

### Example Queries

```
What are the ethical implications of artificial intelligence?
```

```
Explain quantum computing in simple terms
```

```
What are the top 5 advancements in renewable energy?
```

### Commands

- `exit` or `quit`: End the session
- `key`: Update your API key
- `model`: Switch between different Gemini models:
  - `flash`: Gemini-1.5-flash (fastest, recommended)
  - `pro`: Gemini-1.5-pro (more capable)
  - `preview`: Gemini-2.5-pro-preview (experimental)

### Tips for Best Results

- Be specific in your queries for more focused articles
- For complex topics, consider breaking them into multiple questions
- Try different models if you're not satisfied with the response quality
- The `flash` model is fastest, while `pro` and `preview` may provide more detailed responses

---

## 📦 File Structure

```plaintext
gemini_cli/
├── simple_gemini_cli/
│   ├── gemini_chat.py         # Main CLI entry point
│   └── utils.py               # Utility functions
├── setup-cli.sh               # One-command installer
└── README.md
```

---

## 🤝 Contributing

Pull requests are welcome! Ideas, fixes, or feature suggestions—go ahead and contribute.

- Fork the repo
- Create a feature branch
- Submit your PR

Check out [contributing guidelines](./CONTRIBUTING.md) (coming soon).

---

## 💖 Credits

Made with 💡 and 🚀 by [Niladri Das](https://github.com/bniladridas)

<a href="https://github.com/bniladridas/gemini_cli/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=bniladridas/gemini_cli" />
</a>

---

## 📜 License

MIT — See [license file](./LICENSE) for more information.

---

## 📣 Spread the Word

If you liked the project, please consider sharing it! It helps a ton 💙

[![Share on Reddit](https://img.shields.io/badge/share%20on-reddit-red?logo=reddit)](https://reddit.com/submit?url=https://github.com/bniladridas/gemini_cli&title=AI%20Newspaper-Style%20CLI)
[![Share on Hacker News](https://img.shields.io/badge/share%20on-hacker%20news-orange?logo=ycombinator)](https://news.ycombinator.com/submitlink?u=https://github.com/bniladridas/gemini_cli)
[![Share on Twitter](https://img.shields.io/badge/share%20on-twitter-03A9F4?logo=twitter)](https://twitter.com/share?url=https://github.com/bniladridas/gemini_cli)
[![Share on LinkedIn](https://img.shields.io/badge/share%20on-linkedin-3949AB?logo=linkedin)](https://www.linkedin.com/shareArticle?url=https://github.com/bniladridas/gemini_cli)

![](https://i.imgur.com/waxVImv.png)
