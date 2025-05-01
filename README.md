# WiseChoice
Your Intelligent Shopping Companion

## 📋 Overview
WiseChoice is an intelligent shopping assistant that helps e-commerce shoppers make informed purchasing decisions through advanced AI-powered analysis. The platform combines natural language processing, machine learning, and web scraping to provide comprehensive product insights.

## ✨ Key Features

### 1. Review Analysis System
- **Review Extraction**: Automated scraping of product reviews from e-commerce platforms
- **Fake Review Detection**: Machine learning-based identification of suspicious reviews
- **Sentiment Analysis**: Deep learning-powered sentiment evaluation of genuine reviews
- **Review Summarization**: AI-generated concise summaries highlighting key pros and cons

### 2. Price Analysis
- **Market Price Comparison**: Cross-platform price analysis
- **Price Fairness Evaluation**: Machine learning-based assessment of price reasonableness

### 3. Interactive Features
- **AI Chatbot**: Powered by Google's Generative AI for intelligent product queries
- **Product Grading System**: Comprehensive grading (S, A, B, C, D) based on quality and price metrics

## 🛠️ Technical Architecture

### Backend (Python)
- **Web Framework**: Flask with CORS support
- **NLP & ML Stack**:
  - Transformers (Hugging Face)
  - PyTorch
  - NLTK
  - Scikit-learn
- **Web Scraping**: Selenium with Chrome WebDriver
- **Data Processing**: Pandas, SciPy
- **Visualization**: Plotly, Matplotlib
- **AI Integration**: Google Generative AI

### Frontend (Next.js)
- **Framework**: Next.js 13+ with React
- **Styling**: Tailwind CSS
- **Component Library**: Shadcn UI
- **State Management**: React Context API

## 🚀 Setup Instructions

### Prerequisites
- Python 3.10+
- Node.js 16+
- Chrome browser
- 8GB+ RAM recommended

### Installation

1. **Clone and Setup**
   ```bash
   git clone https://github.com/lokeshpanthangi/WiseChoice.git
   cd WiseChoice
   ```

2. **Backend Setup**
   ```bash
   # Install Python dependencies
   pip install -r requirements.txt
   
   # The project may already include the joblib file. If not, use the link below to download it.
   # Download required ML model from : https://drive.google.com/file/d/1HISyKqoWQk0-Xcztx317f6uCWIYsd8lN/view?usp=sharing
   # Place the model file in backend-server directory
   ```

3. **Frontend Setup**
   ```bash
   cd frontend-UI
   npm install
   ```

### Running the Application

1. **Start Backend Server**
   ```bash
   cd backend-server
   python app.py
   ```

2. **Start Frontend Development Server**
   ```bash
   cd frontend-UI
   npm run dev
   ```

3. **Access**
   - Open browser and navigate to: http://localhost:3000

## 📖 Usage Guide

1. **Product Analysis**
   - Enter product URL from supported e-commerce platforms
   - System automatically:
     - Extracts and processes reviews
     - Filters fake reviews
     - Performs sentiment analysis
     - Evaluates price fairness
     - Generates comprehensive report

2. **Interactive Features**
   - Use the AI chatbot for specific product queries
   - View product grade and detailed analysis
   - Access price comparison data

## Support & Contact

For questions or issues:
- Email: lokeshpantangi@gmail.com
