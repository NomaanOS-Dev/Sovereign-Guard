# Sovereign-Guard

LLM Security Firewall & Prompt Injection Scanner (SAS Initiative).

Sovereign-Guard is an AI-assisted security tool for reviewing untrusted prompts and model inputs for prompt injection, jailbreak attempts, instruction overrides, data-exfiltration requests, and unsafe tool-use behavior.

Developed by NomaanOS-Dev.

## Key Features

- Prompt injection detection and instruction override analysis
- Jailbreak and safeguard bypass assessment
- Data-exfiltration risk identification
- Severity scoring and evidence-based findings
- Defensive recommendations for mitigation and monitoring
- Interactive Streamlit dashboard for prompt scanning and report download

## Tech Stack

- Python 3.x
- Streamlit
- OpenAI Python SDK

## Installation

```bash
git clone https://github.com/NomaanOS-Dev/Sovereign-Guard.git
cd Sovereign-Guard
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
```

Then configure your OpenAI API key in the sidebar of the running app.

## How It Works

1. Paste an untrusted prompt or model input into the app.
2. Sovereign-Guard sends the content to an LLM security auditor.
3. The system evaluates suspicious patterns such as:
   - instruction overrides
   - jailbreak attempts
   - exfiltration requests
   - unsafe tool-use or hidden directives
4. The app returns a structured security assessment with recommendations.

## Security Notice

This application provides AI-assisted security triage and is not a guarantee that all attacks will be detected. Avoid submitting real secrets or confidential data. Verify all findings before taking action or escalating them in a production environment.

## License

This project is provided as-is for research, evaluation, and security testing workflows.
