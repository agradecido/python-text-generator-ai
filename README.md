<!--multilang v0 en:README.md es:LEEME.md -->
<!--multilang buttons-->

# 🦄 Building a Python Flask API for Generative Text AI

This project aims to develop a Python API that generates text based on keywords and/or short input phrases. One potential use case is to dynamically create web pages for affiliate market products.

The project will use Flask as the main framework for the API and ChatGPT as the text generation model.

## 🔍 State of the Art

We currently have a functional prototype in a Jupyter notebook, featuring a single endpoint API. This API receives a JSON payload with user input and returns text generated by the selected AI model.

### Example Request Payload

```json
{
    "prompt": "Let's create a page about a product to try and sell on an affiliate marketplace for profit. Generate 2 paragraphs (about 500 words each) for this product based on the following keywords, the first is the product:",
    "keywords": "'Led Zeppelin first album', 'rock', 'vinyl', 'classic', 'collector', 'guitar', 'bass', 'band', 'guitarist'",
    "system-role":  "Act as a helpful assistant for SEO purposes. You will only provide the content of the requested text, without intros or outros. You will speak only in English with an American accent."
}
```

## JWT Authentication

**JWT** is an open standard that allows information to be transmitted securely in JSON format between two parties.

We need the library **Flask JWT Extended**:

```bash
pip install Flask-JWT-Extended
```

## ⏭️ What next

The next step is to add rate limits to API connections.

## 🛠️ Tech stack

- 🎓 **Python 3.11**
- ⚡️ **Flask 3**
- 📓 **Jupyter Notebook** or **Google Colab**
- 🔮 **OpenAI API** | **ChatGPT**


## 🚀 Setup environment

Clone this repository, navigate to your local directory and start the Python virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

#### Environment Variables

Copy .env.example to .env in the root directory and set its values.

---

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)

---

Also available in:
[Spanish](LEEME.md)