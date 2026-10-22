# Sovereign-Guard

An AI-assisted Large Language Model (LLM) security firewall designed to identify prompt injection, jailbreak attempts, data-exfiltration requests, and unsafe instructions.

Developed by NomaanOS-Dev.

## 🚀 Key Features

- **Prompt Injection Detection:** Identify attempts to override trusted instructions.
- **Jailbreak Analysis:** Flag suspicious requests targeting model safeguards.
- **Data Exfiltration Detection:** Highlight prompts requesting confidential information.
- **Risk Assessment:** Generate severity estimates and supporting evidence.
- **Defensive Recommendations:** Suggest input validation, monitoring, and security controls.
- **Interactive Security Dashboard:** Scan prompts and download assessment reports through Streamlit.

## 🛠️ Tech Stack

Python 3.x | Streamlit | OpenAI API

## 📦 Installation

```bash
git clone https://github.com/NomaanOS-Dev/Sovereign-Guard.git
cd Sovereign-Guard
pip install -r requirements.txt
streamlit run app.py
Configure your OpenAI API key in the application sidebar.
🛡️ Security Notice
This application provides AI-assisted security triage, not a guarantee that all attacks will be detected. Avoid submitting real secrets or confidential data. Verify findings before making security decisions.
