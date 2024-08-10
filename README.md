<!--multilang v0 en:README.md es:LEEME.md -->
<!--multilang buttons-->


# 🦄 Building a Python API a Python API for Generative Text AI

This project aims to develop a Python API that generates text based on keywords and/or short input phrases. One potential use case is to dynamically create web pages for affiliate market products.

The API usage for GPT-4 or the chosen model is expected to be minimal, as only a few pages will be generated each week.

## Tech stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)

- 🎓 Python
- ⚡️ Flask
- 🔮 GPT-4o mini

We use ![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white) as our development platform

## 🚀 Setup environment

Clone this repository, navigate to your local directory and start the Python virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 🔐 Environment Variables

Create a `.env` file in the root directory (or copy .env.example to .env) and add your OpenAI API key:

```
OPENAI_API_KEY=your_openai_api_key_here
```

---

Also available in:
[Spanish](LEEME.md)