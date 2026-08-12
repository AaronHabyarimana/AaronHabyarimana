# Aaron Habyarimana

CS student at JGU Mainz, graduating September 2026. Currently a working student at Aareon, building internal AI agents with n8n and Copilot Studio.

## Projects

**[recall](https://github.com/AaronHabyarimana/recall)** — Turns lecture slides into
spaced-repetition flashcards. Generating them is the easy half; the other half is a critic that
reads the cards back and drops the ones that can't be learned from, with a reason for each.
Python · PyMuPDF · Gemini · SQLite · FSRS · Streamlit.

**[structuring-llm-arguments](https://github.com/AaronHabyarimana/structuring-llm-arguments)** —
Bachelor's thesis. An LLM extracts arguments from debate texts and classifies which ones attack
which; SWI-Prolog solves the resulting Dung-style argumentation framework. Every stage writes its
artifacts to disk, so a result can be traced back to the sentence it came from.
Python · SWI-Prolog.

**[social-engineering-resilience-trainer](https://github.com/AaronHabyarimana/phish-drill)** —
An interactive CLI that hardens employees against social engineering. An LLM attacker agent runs a
role-play (fake IT support, CEO fraud, a smishing link, a bank OTP request) while the trainee answers
in the console; a second LLM agent judges the transcript and returns a structured debrief — techniques
used, whether anything sensitive was disclosed, a resistance score out of 100. The human is the
trainee, not the target, and misuse attempts are caught by a rule-based guard before they reach the
model. Python · OpenAI-compatible LLMs · pytest.

## Stack

| | |
|---|---|
| **Languages** | Python, SQL, Prolog, JavaScript |
| **LLM work** | Gemini API, multi-stage pipelines, a judging stage over generated output |
| **Data** | SQLite, Pydantic, PyMuPDF |
| **Interfaces** | Streamlit, Flask, CLIs |
| **Tooling** | uv, pytest, ruff, GitHub Actions, LaTeX |
