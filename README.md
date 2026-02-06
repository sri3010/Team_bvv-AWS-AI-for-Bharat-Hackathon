# 🌾 AI-Powered Agricultural Assistant System

[![AWS](https://img.shields.io/badge/AWS-Bedrock-FF9900?style=flat&logo=amazon-aws)](https://aws.amazon.com/bedrock/)
[![Hackathon](https://img.shields.io/badge/Hackathon-AWS%20AI%20for%20Bharat-blue)](https://aws.amazon.com/)
[![Team](https://img.shields.io/badge/Team-BVV-green)](https://github.com)

> Empowering Indian farmers with AI-driven crop disease detection, market insights, weather forecasting, and financial planning through voice and mobile interfaces.

**Team BVV** | AWS AI for Bharat Hackathon 2026

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Documentation](#documentation)
- [Demo](#demo)
- [Team](#team)
- [License](#license)

---

## 🎯 Overview

The AI-Powered Agricultural Assistant System is a comprehensive solution designed to address the challenges faced by Indian farmers. By leveraging AWS AI services, particularly Amazon Bedrock, we provide farmers with:

- 🗣️ **Voice-first interface** for low-literacy users
- 📸 **AI-powered crop disease detection** through image analysis
- 📊 **Market price predictions** and trend analysis
- 💰 **Financial planning tools** for profit optimization
- 🌤️ **Weather forecasting** with farming recommendations

### Problem Statement

Indian farmers face multiple challenges:
- Limited access to agricultural experts
- Difficulty identifying crop diseases early
- Lack of real-time market information
- Poor financial planning tools
- Language and literacy barriers

### Our Solution

A multi-modal AI assistant accessible via phone calls, mobile apps, and web interfaces, supporting regional Indian languages and providing actionable insights to improve farming outcomes.

---

## ✨ Features

### 🎙️ Voice Buddy Conversation
- Natural language voice interactions in regional languages
- Phone call support via Twilio integration
- Speech-to-Text and Text-to-Speech capabilities
- AI-powered query understanding and response generation

### 🌱 Crop Guardian (Disease Detection)
- Upload or capture crop photos
- Real-time AI-powered disease identification
- Treatment recommendations with confidence scores
- Alert system for crop health issues
- Support for multiple crop types

### 📈 Market Insight
- Real-time crop price information
- AI-driven price predictions
- Market trend analysis
- Regional price comparisons
- Historical data visualization

### 💵 Profit Planner
- Financial planning and tracking
- Automated profit/loss calculations
- Revenue monitoring
- Financial report generation
- Profit alerts and notifications

### 🤖 AI Agents
- **Crop Analyzer**: Intelligent disease detection and prediction
- **Weather Forecaster**: Weather-based farming recommendations
- **Market Analyzer**: Price prediction and trend analysis

---

## 🏗️ Architecture

### High-Level Architecture

```
┌─────────────────┐     ┌──────────────────┐     ┌─────────────────┐
│  User Interface │────▶│ Communication    │────▶│  Core Platform  │
│  - Phone Call   │     │  - Twilio        │     │  - Bedrock      │
│  - Web App      │     │  - TTS/STT       │     │  - Lambda       │
│  - Mobile App   │     │  - Voice I/O     │     │  - API Gateway  │
└─────────────────┘     └──────────────────┘     └─────────────────┘
                                                           │
                        ┌──────────────────────────────────┼──────────────────┐
                        ▼                                  ▼                  ▼
                ┌───────────────┐              ┌──────────────────┐  ┌──────────────┐
                │  AI Agents    │              │ Support Services │  │ Data Storage │
                │  - Crop       │              │  - Monitoring    │  │  - S3        │
                │  - Weather    │              │  - Notifications │  │  - DynamoDB  │
                │  - Market     │              │  - Auth          │  │  - RDS       │
                └───────────────┘              └──────────────────┘  └──────────────┘
```

### AWS Services Used

- **Amazon Bedrock**: AI agents and knowledge bases
- **AWS Lambda**: Serverless compute
- **Amazon S3**: Object storage for images and reports
- **Amazon Rekognition**: Image analysis for disease detection
- **Amazon Polly**: Text-to-Speech conversion
- **Amazon Transcribe**: Speech-to-Text conversion
- **Amazon DynamoDB**: NoSQL database
- **Amazon API Gateway**: RESTful API management
- **Amazon CloudWatch**: Monitoring and logging
- **Amazon SNS/SES**: Notifications
- **AWS IAM**: Security and access control

---

## 🛠️ Technology Stack

### Frontend
- **Mobile**: React Native, Expo
- **Web**: React.js, Material-UI
- **State Management**: Redux

### Backend
- **Language**: Python 3.11+
- **Framework**: AWS Lambda (Serverless)
- **API**: Amazon API Gateway

### AI/ML
- **Platform**: Amazon Bedrock
- **Computer Vision**: Amazon Rekognition, SageMaker
- **NLP**: Amazon Comprehend
- **Voice**: Amazon Polly, Amazon Transcribe

### Communication
- **Voice**: Twilio Voice API
- **SMS**: Twilio SMS / Amazon SNS

### DevOps
- **Version Control**: Git
- **CI/CD**: AWS CodePipeline, CodeBuild
- **IaC**: AWS SAM, CloudFormation

---

## 📚 Documentation

- **[Requirements Document](./requirements.md)**: Detailed functional and non-functional requirements
- **[Design Document](./design.md)**: Complete system architecture and technical design
- **[API Documentation](./docs/api.md)**: API endpoints and usage (coming soon)
- **[User Guide](./docs/user-guide.md)**: End-user documentation (coming soon)

---

## 🎬 Demo

### Screenshots

#### Core Features
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/311aa0a1-6068-4272-be18-0900ab2551be" />


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/86ba2905-782f-4317-9609-75d2acae8996" />


### Key Features Demonstrated

**Voice Assistant**
- Tap-to-speak interface for voice queries
- Real-time voice processing
- Natural language understanding

**Transportation Services**
- Nearby transport providers with distance
- Vehicle capacity information
- Estimated arrival times
- Direct contact options

**Fertilizer Procurement**
- Search and browse fertilizer suppliers
- Price comparison (₹980 - ₹1450 per bag)
- Distance-based supplier listing
- Direct supplier contact

**Weather Updates**
- Current weather conditions (Krishnagar, India)
- 5-day forecast with temperature ranges
- Weather-based farming recommendations

**Storage Facilities**
- Nearby warehouse and cold storage options
- Distance information
- Direct call functionality

**Market Intelligence**
- Latest farming podcasts
- Market trends for cash crops
- FAQ section for common queries
- Daily agricultural news and updates

**Daily News Feed**
- Government subsidy announcements
- Innovative farming techniques
- Market price trends
- Pest control updates

### Live Demo

*Coming soon - Link to live application*

---

## 👥 Team BVV

- **Team Member 1**: [Role] - [GitHub](https://github.com/username)
- **Team Member 2**: [Role] - [GitHub](https://github.com/username)
- **Team Member 3**: [Role] - [GitHub](https://github.com/username)

---

## 🎯 Hackathon Goals

- ✅ Implement voice-first interface for farmers
- ✅ AI-powered crop disease detection
- ✅ Market price prediction system
- ✅ Financial planning tools
- ✅ Multi-language support
- ✅ Serverless architecture on AWS
- ✅ Integration with Amazon Bedrock

---

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](./CONTRIBUTING.md) for details.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

## 🙏 Acknowledgments

- AWS for providing the cloud infrastructure and AI services
- Amazon Bedrock team for the powerful AI capabilities
- The farming community for inspiring this solution
- AWS AI for Bharat Hackathon organizers

---

## 📞 Contact

For questions or feedback, please reach out to:
- **Email**: team.bvv@example.com
- **GitHub Issues**: [Create an issue](https://github.com/yourusername/Team_bvv-AWS-AI-for-Bharat-Hackathon/issues)

---

<div align="center">
  <strong>Built with ❤️ for Indian Farmers</strong>
  <br>
  <sub>Team BVV | AWS AI for Bharat Hackathon 2026</sub>
</div>
