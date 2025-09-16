# 🍳 Smart Recipe Generator

> **Transform everyday ingredients into extraordinary meals with the power of AI**

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.0+-red.svg)](https://streamlit.io/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--3.5-green.svg)](https://openai.com/)
[![Tesseract](https://img.shields.io/badge/Tesseract-OCR-orange.svg)](https://github.com/tesseract-ocr/tesseract)
[![Pillow](https://img.shields.io/badge/Pillow-PIL-lightblue.svg)](https://pillow.readthedocs.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13+-blue.svg)](https://www.postgresql.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 🌟 Overview

Smart Recipe Generator is an AI-powered application that instantly transforms your available ingredients into delicious, personalized recipes. Whether you're dealing with leftovers, planning meals, or exploring new cuisines, our intelligent system provides tailored culinary solutions that save time, reduce food waste, and make cooking enjoyable.

## ✨ Key Features

- **🔍 AI-Driven Ingredient Recognition**: Upload images of ingredients and let our pre-trained models identify them automatically
- **📝 OCR Text Detection**: Scan ingredient labels and text for accurate identification
- **🎯 Personalized Recipe Generation**: Get customized recipes based on your ingredients and preferences
- **🍽️ Food Category Selection**: Choose from various cuisine types and dietary preferences
- **🔄 Multiple Recipe Options**: Generate alternative recipes with the same ingredients
- **💾 Recipe Storage**: Save your favorite recipes for future reference
- **📱 User-Friendly Interface**: Clean, intuitive Streamlit-based web application

## 🚀 Problem Solved

- **Meal Decision Fatigue**: Eliminates the daily "What should I cook?" dilemma
- **Food Waste Reduction**: Utilizes leftover and available ingredients effectively
- **Nutritional Goals**: Helps meet dietary requirements with tailored suggestions
- **Time Management**: Provides instant recipe solutions for busy individuals

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Programming** | Python 3.8+ |
| **Web Framework** | Streamlit |
| **Database** | PostgreSQL with SQLAlchemy |
| **ML/AI** | PyTorch, TensorFlow, OpenAI GPT-3.5 Turbo |
| **Image Processing** | OpenCV, Tesseract OCR, Pillow (PIL) |
| **Cloud/Deployment** | Docker (optional) |

## 📋 Installation & Setup

### Prerequisites
- Python 3.8 or higher
- PostgreSQL database
- OpenAI API key

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/AmruthReddy18/SmartRecipeGenerator
   cd SmartRecipeGenerator
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Environment Setup**
   ```bash
   cp .env.example .env
   # Edit .env with your API keys and database credentials
   ```

5. **Database Setup**
   ```bash
   python setup_db.py
   ```

6. **Run the application**
   ```bash
   streamlit run app.py
   ```

## 🔄 Workflow

1. **Image Upload**: Users upload images of available ingredients
2. **AI Recognition**: Pre-trained models identify and classify ingredients
3. **OCR Processing**: Text extraction from ingredient labels for accuracy
4. **Recipe Matching**: Database-driven matching with personalization via GPT-3.5
5. **Recipe Generation**: Customized recipes with step-by-step instructions
6. **Storage**: Option to save favorite recipes for future use

## 📸 Screenshots

//*Add screenshots of your application interface here*(Updating soon)

## 🎯 Results & Impact

- **Reduced Food Waste**: Efficiently utilizes leftover ingredients
- **Time Savings**: Instant meal planning and recipe generation
- **Enhanced Cooking Experience**: Step-by-step guidance for all skill levels
- **Personalized Nutrition**: Tailored recipes for healthier eating habits
- **Stress Reduction**: Eliminates meal planning anxiety

## 🚀 Future Enhancements

- [ ] **Enhanced Ingredient Recognition**: Improved accuracy with advanced computer vision models
- [ ] **Health & Allergy Integration**: Personalized recipes based on dietary restrictions and allergies
- [ ] **Smart Device Integration**: IoT connectivity for smart kitchen appliances
- [ ] **Seasonal Recommendations**: Context-aware seasonal ingredient suggestions
- [ ] **Voice Assistant Integration**: Hands-free recipe generation and cooking guidance
- [ ] **Mobile App**: Native iOS and Android applications
- [ ] **Community Features**: Recipe sharing and rating system

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## 🙏 Acknowledgments

- OpenAI for GPT-3.5 Turbo API
- Streamlit team for the amazing framework
- Open source computer vision and OCR communities
- All beta testers and contributors

---

<div align="center">
  <strong>⭐ Star this repo if you find it helpful! ⭐</strong>
</div>
