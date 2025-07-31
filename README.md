# Stock Prediction AI App

A project that demonstrates how to integrate AI APIs with stock market data using Cloudflare Workers. This application showcases secure API handling, serverless architecture, and AI-powered stock market analysis.

## 🛠️ Tech Stack

- **Frontend**: Vanilla JavaScript, HTML, CSS
- **Backend**: Cloudflare Workers (Serverless)
- **APIs**: OpenAI API, Polygon.io Stock API
- **Deployment**: Cloudflare Pages
- **Tools**: Wrangler CLI

## 🚀 Features

- **Stock Ticker Input**: Add up to 3 stock tickers for analysis
- **Real-time Data Fetching**: Retrieves recent stock market data
- **AI-Powered Analysis**: Uses OpenAI to generate stock performance reports
- **Secure API Handling**: All API keys are protected through Cloudflare Workers
- **Responsive Design**: Clean, mobile-friendly interface

## 🔒 Security Implementation

- **API Key Protection**: All sensitive API calls are routed through Cloudflare Workers
- **No Client-Side Exposure**: API keys never exposed in frontend code
- **Environment Variables**: Secure configuration management
- **CORS Handling**: Proper cross-origin request handling

## 🌐 How It Works

1. **User Input**: User enters stock tickers through the web interface
2. **Data Fetching**: Frontend requests stock data from Polygon.io API
3. **AI Processing**: Stock data is sent to Cloudflare Worker
4. **OpenAI Integration**: Worker securely calls OpenAI API for analysis
5. **Response**: AI-generated stock report is returned to the user

## 🏗️ Architecture & Implementation

- **Serverless Architecture**: Cloudflare Workers for edge computing
- **API Security**: Protected API keys through serverless functions
- **Async JavaScript**: Promise-based data fetching and processing
- **Error Handling**: Comprehensive error management system
- **Environment Management**: Secure configuration handling
