# 🌍 Translator App

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/bhanukumardev/TranslatorApp)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Stars](https://img.shields.io/github/stars/bhanukumardev/TranslatorApp?style=social)](https://github.com/bhanukumardev/TranslatorApp/stargazers)
[![Forks](https://img.shields.io/github/forks/bhanukumardev/TranslatorApp?style=social)](https://github.com/bhanukumardev/TranslatorApp/forks)

> 🌐 AI-powered Translator App built with Python, Streamlit, and Deep Translator. Instantly translate text between multiple languages with a user-friendly web interface. 🚀

## 📹 Demo

**[📺 Watch Demo on LinkedIn →](https://www.linkedin.com/posts/bhanu-kumar-dev-97b820313_pinnaclelabs-ai-python-activity-7340036639034929152-Telc?utm_source=share&utm_medium=member_desktop)**

## 🚀 Overview

A real-time translation web application built as part of **Pinnacle Labs Internship** (Task 2). This project demonstrates:

- **Multi-language Support** - Translate between 100+ languages
- **Real-time Processing** - Instant translation results
- **Clean Interface** - Streamlit-powered UI
- **Deep Translator API** - Reliable translation engine

## ✨ Features

- 🌍 **100+ Languages** - Support for all major world languages
- ⚡ **Instant Translation** - Real-time text conversion
- 🎨 **Modern UI** - Clean, responsive Streamlit interface
- 📝 **Text Input** - Easy copy-paste functionality
- 📊 **Language Detection** - Auto-detect source language
- 🔄 **Bidirectional Translation** - Swap languages easily

## 🛠️ Tech Stack

- **Python 3.8+** - Core programming language
- **Streamlit** - Web application framework
- **Deep Translator** - Translation API wrapper
- **Google Translate API** - Backend translation service

## 📦 Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip package manager
- Git

### Clone Repository

```bash
git clone https://github.com/bhanukumardev/TranslatorApp.git
cd TranslatorApp
```

### Install Dependencies

```bash
# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt
```

### Run the Application

```bash
# Start Streamlit app
streamlit run app.py

# Open http://localhost:8501 in your browser
```

## 🎯 Usage Example

### Web Interface

1. Open the app in your browser
2. Select source language (or use auto-detect)
3. Select target language
4. Enter text to translate
5. View instant translation results

### Code Example

```python
from deep_translator import GoogleTranslator

# Translate from English to Spanish
translated = GoogleTranslator(source='en', target='es').translate('Hello, World!')
print(translated)  # Output: ¡Hola, Mundo!

# Auto-detect source language
translated = GoogleTranslator(source='auto', target='fr').translate('Hello')
print(translated)  # Output: Bonjour
```

## 🌏 Supported Languages

**Popular languages include:**
- English, Spanish, French, German
- Hindi, Chinese, Japanese, Korean
- Arabic, Russian, Portuguese, Italian
- And 90+ more languages!

[View full language list →](https://py-googletrans.readthedocs.io/en/latest/#googletrans-languages)

## 📁 Project Structure

```
TranslatorApp/
├── app.py                  # Main Streamlit application
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── .streamlit/             # Streamlit configuration (optional)
    └── config.toml
```

## 📚 Dependencies

```txt
streamlit>=1.20.0
deep-translator>=1.11.0
python-dotenv>=1.0.0
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewFeature`)
3. Commit your changes (`git commit -m 'Add NewFeature'`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Bhanu Kumar Dev**
- 🎓 3rd Year CSSE @ KIIT University
- 👨‍💻 Pinnacle Labs Intern | AI/ML Developer
- 📧 Email: kumarbhanu818@gmail.com
- 💼 LinkedIn: [bhanu-kumar-dev-97b820313](https://www.linkedin.com/in/bhanu-kumar-dev-97b820313)
- 🐙 GitHub: [@bhanukumardev](https://github.com/bhanukumardev)
- 🌐 Portfolio: [bhanukumardev.github.io/bhanu-portfolio](https://bhanukumardev.github.io/bhanu-portfolio/)

## 🌟 Acknowledgments

- **Pinnacle Labs** - For the internship opportunity (Task 2)
- **Streamlit Team** - For the excellent framework
- **Deep Translator** - For reliable translation API
- **Google Translate** - For the backend translation service

## 📈 Future Enhancements

- [ ] Voice input and output
- [ ] Document translation (PDF, DOCX)
- [ ] Translation history
- [ ] Custom translation models
- [ ] Offline translation support
- [ ] Browser extension

---

<div align="center">
  <b>⭐ Star this repo if you find it helpful!</b>
  <br>
  <i>Breaking language barriers with AI</i>
  <br>
  Made with ❤️ by Bhanu Kumar Dev | Pinnacle Labs Internship
</div>
