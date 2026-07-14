🛡️ PhishGuard AI: Advanced Anti-Phishing Suite
PhishGuard AI is an ultra-futuristic, dual-engine cybersecurity dashboard designed to detect malicious digital threats. Built with Python, Streamlit, and state-of-the-art Machine Learning/Deep Learning models, the application unifies URL Phishing Analytics and AI-Powered Email Scans into a single cohesive ecosystem featuring a sleek hacker-themed UI.

🚀 Key Features
🌐 1. Website Phishing Scanner
Lexical Feature Extraction: Analyzes URL lengths, sub-domain distributions, specific character counts, and shortener usage patterns.
Algorithmic Evaluation: Backed by an optimized tree classifier framework (XGBoost/Random Forest) to output absolute structural threat probabilities.
📧 2. AI-Powered Email Analyzer
Semantic Analysis: Leverages Hugging Face Transformer models (BERT / RoBERTa) to parse intent, context, and psychological triggers (e.g., false urgency).
Reputation & Ecosystem Verification: Checks sender domain credibility and scans embedded body links against known target indicators.
Explainable AI (XAI): Generates clear structural reasons detailing exactly why a scanned layout was flagged as suspicious.
🎨 3. Cyberpunk Hacking Console GUI
High-performance custom glassmorphism components with soft breathing glow effects.
Responsive live interactive styling driven by an HTML5 canvas layer.
📂 Project Architecture
Phishing_Detection_Suite/
│
├── models/                       # Compressed binary files for trained models
│   ├── url_model.pkl             # Serialized XGBoost/Random Forest artifact
│   └── scaler.pkl                # Dynamic input feature normalizer
│
├── app.py                        # Streamlit visual frontend dashboard layout
├── url_detector.py               # Lexical feature extraction and routing logic
├── email_detector.py             # NLP pipeline and reputation ecosystem parser
├── style.css                     # Customized futuristic cyberpunk UI layout rules
└── requirements.txt              # Complete manifest of project dependencies
