# 🤖 Wichi AI

Wichi AI is a Python-based intelligent AI assistant designed to provide natural conversations in both text and voice modes. It is powered by Google's Gemini API while maintaining its own custom identity, personality, and configurable behavior.

## ✨ Features

- 💬 Interactive text chat
- 🎙️ Voice mode support
- 🧠 Powered by Google Gemini API
- ⚙️ Configurable through YAML
- 🎭 Custom AI personality (Wichi)
- 🔒 Environment variable support for API keys
- 📂 Modular project structure
- 🖥️ Runs on Linux and Termux

---

## 📁 Project Structure

```
wichi/
├── src/
│   ├── Manager/
│   ├── lib/
│   ├── config.yml
│   └── wichi.py
├── .env
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/wichi-ai.git
cd wichi-ai
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Create a `.env` file

```env
GEMINIAI_KEY=YOUR_GEMINI_API_KEY
```

### Run the assistant

```bash
cd src
python wichi.py
```

---

## ⚙️ Configuration

Modify `src/config.yml` to customize:

- AI model
- Temperature
- Safety settings
- Fine-tuned personality
- Output configuration

---

## 🛠 Technologies

- Python 3
- Google Gemini API
- PyYAML
- dotenv

---

## 📌 Requirements

- Python 3.10+
- Gemini API Key
- Internet connection

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Isha Saifi**

GitHub:
https://github.com/ishasaifi200628-alt

---

## ⭐ Support

If you like this project, please consider giving it a ⭐ on GitHub.
