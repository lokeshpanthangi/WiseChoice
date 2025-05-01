# WiseChoice
Your Intelligent Shopping Companion

## Overview
WiseChoice is an intelligent shopping assistant designed to help e-commerce shoppers make informed purchasing decisions by addressing two major challenges:

1. **Product Quality Assessment**: Analyzing and summarizing product reviews while filtering out fake reviews
2. **Price Fairness Evaluation**: Determining if a product's price is reasonable based on market analysis

## Key Features

### 1. Review Analysis
- **Fake Review Detection**: Identifies and filters out computer-generated and paid reviews
- **Sentiment Analysis**: Evaluates the overall sentiment of genuine reviews
- **Review Summarization**: Provides concise pros and cons from verified reviews

### 2. Price Analysis
- **Price Fairness Evaluation**: Analyzes if the current price is reasonable
- **Market Comparison**: Compares prices across different platforms

### 3. Interactive Features
- **AI Chatbot**: Interactive assistant to answer product-related queries
- **Product Grading**: Assigns a grade (S, A, B, C, D) based on overall product quality and price fairness

## Technical Stack

### Backend
- Python 3.10+
- Flask (Web Framework)
- Selenium (Web Scraping)
- Transformers (NLP)
- NLTK (Natural Language Processing)
- Scipy (Scientific Computing)

### Frontend
- Next.js
- React
- Tailwind CSS

## Setup Instructions

### Prerequisites
- Python 3.10 or higher
- Node.js and npm
- Minimum 8GB RAM
- Chrome browser (for web scraping)

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone [repository-url]
   cd WiseChoice
   ```

2. **Install Python Dependencies**
   ```bash
   python setup.py
   ```

3. **Download Required Model**
   - Download the joblib file from:
     https://drive.google.com/drive/u/1/folders/1z2MCfuIaRLS6kblz7E4uj6P-4IXmdHqv
   - Place it in the `backend-server` directory

4. **Install Frontend Dependencies**
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

3. **Access the Application**
   - Open your browser and navigate to: http://localhost:3000

## Usage

1. Enter a product URL from a supported e-commerce platform
2. The system will:
   - Extract and analyze reviews
   - Filter out fake reviews
   - Perform sentiment analysis
   - Evaluate price fairness
   - Generate a comprehensive product report

3. Use the chatbot to ask specific questions about the product

## Support

For more information about the project, mail :
lokeshpantangi@gmail.com

