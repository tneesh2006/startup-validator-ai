# Startup Validator AI

> *The co-founder that tells you what your friends won't.*

An AI-powered startup idea validator that gives brutally honest feedback from three perspectives — a Venture Capitalist, a Skeptical Customer, and a Competitor CEO.

Built for hackathons. Runs in minutes.

---

##  What It Does

Paste any startup idea and get instant analysis including:

- **Score out of 100** with a clear verdict
- **Killer Risk** — the single biggest threat to your idea
- **Market Analysis** — size, timing, and competition
- **Green Flags** — what's working in your favor
- **Red Flags** — what could sink you
- **Hard Questions** — what a real investor would ask
- **Comparable** — real startups that tried something similar

---

## Three Personas

| Persona | Perspective |
|---|---|
|  Brutal VC | 20-year investor who has seen 10,000 pitches |
|  Skeptical Customer | Real user who has been burned by overhyped products |
| Competitor CEO | Well-funded rival analyzing your threat level |

---

##  Tech Stack

- **Python** + **Streamlit** — UI framework
- **Google Gemini API** — AI brain (free tier)
- **No database** — fully stateless

---

##  Quick Start

**1. Clone the repo**
```bash
git clone https://github.com/YOUR_USERNAME/startup-validator-ai.git
cd startup-validator-ai
```

**2. Install dependencies**
```bash
pip3 install streamlit google-generativeai
```

**3. Get free Gemini API key**
```
https://aistudio.google.com/apikey
```

**4. Add your API key**
```bash
mkdir -p .streamlit
echo 'GEMINI_API_KEY = "your-key-here"' > .streamlit/secrets.toml
```

**5. Run**
```bash
streamlit run startup_validator.py
```

**6. Open in browser**
```
http://localhost:8501
```

---

## Project Structure

```
startup-validator-ai/
├── startup_validator.py    # Main app
├── .streamlit/
│   └── secrets.toml        # API keys (not committed)
└── README.md
```

---

## Environment Variables

| Variable | Description |
|---|---|
| `GEMINI_API_KEY` | Google Gemini API key (free at aistudio.google.com) |

---

## Features

- 3 AI personas with distinct perspectives
- Real-time scoring with color-coded results
- Validation history (last 5 ideas)
- Re-validate same idea with different persona
- Dark mode UI
- Fully free to run

---

## Built At

Built during an AI Hackathon in 2026.

---

## License

MIT — free to use, modify, and distribute.
# Startup Validator AI

> *The co-founder that tells you what your friends won't.*

An AI-powered startup idea validator that gives brutally honest feedback from three perspectives — a Venture Capitalist, a Skeptical Customer, and a Competitor CEO.

Built for hackathons. Runs in minutes.

---

##  What It Does

Paste any startup idea and get instant analysis including:

- **Score out of 100** with a clear verdict
- **Killer Risk** — the single biggest threat to your idea
- **Market Analysis** — size, timing, and competition
- **Green Flags** — what's working in your favor
- **Red Flags** — what could sink you
- **Hard Questions** — what a real investor would ask
- **Comparable** — real startups that tried something similar

---

## Three Personas

| Persona | Perspective |
|---|---|
|  Brutal VC | 20-year investor who has seen 10,000 pitches |
|  Skeptical Customer | Real user who has been burned by overhyped products |
| ⚔️ Competitor CEO | Well-funded rival analyzing your threat level |

---

##  Tech Stack

- **Python** + **Streamlit** — UI framework
- **Google Gemini API** — AI brain (free tier)
- **No database** — fully stateless

---

##  Quick Start

**1. Clone the repo**
```bash
git clone https://github.com/YOUR_USERNAME/startup-validator-ai.git
cd startup-validator-ai
```

**2. Install dependencies**
```bash
pip3 install streamlit google-generativeai
```

**3. Get free Gemini API key**
```
https://aistudio.google.com/apikey
```

**4. Add your API key**
```bash
mkdir -p .streamlit
echo 'GEMINI_API_KEY = "your-key-here"' > .streamlit/secrets.toml
```

**5. Run**
```bash
streamlit run startup_validator.py
```

**6. Open in browser**
```
http://localhost:8501
```

---

## 📁 Project Structure

```
startup-validator-ai/
├── startup_validator.py    # Main app
├── .streamlit/
│   └── secrets.toml        # API keys (not committed)
└── README.md
```

---

##  Environment Variables

| Variable | Description |
|---|---|
| `GEMINI_API_KEY` | Google Gemini API key (free at aistudio.google.com) |

---

## Features

- 3 AI personas with distinct perspectives
- Real-time scoring with color-coded results
- Validation history (last 5 ideas)
- Re-validate same idea with different persona
- Dark mode UI
- Fully free to run
---

## Built At

Built during an AI Hackathon in 2026.

---

##  License

MIT — free to use, modify, and distribute.
