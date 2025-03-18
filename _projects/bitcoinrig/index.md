---
layout: post
title: AI-Powered Fact-Checking App in Swift
description: Designed and developed an AI-powered fact-checking app in Swift that processes image-based queries and cross-verifies responses using both ChatGPT and Google Gemini APIs running simultaneously.
skills:
- Swift
- API Integration
- Large Language Models (LLMs)
- Mobile App Development
- Software Engineering
- Machine Learning
main-image: /Fact.JPG
---

# Project Overview  
Developed a **fact-checking mobile application in Swift** that processes **image-based queries** and cross-verifies responses using **ChatGPT and Google Gemini APIs running simultaneously**. This AI-driven system **enhances response accuracy by comparing multiple language model outputs**, ensuring **reliable and verifiable information retrieval**.

## Core Features & Functionality  
1. **Image-Based Query Processing**  
   - Users can **upload an image** containing text or objects, which the app extracts and processes using **OCR (Optical Character Recognition)**.  
   - The extracted information is **interpreted and analyzed using AI models**.  

2. **Dual AI API Integration**  
   - The app simultaneously queries **ChatGPT and Google Gemini APIs**, retrieving responses from both models.  
   - Implemented a **real-time comparison algorithm** to detect inconsistencies between responses.  

3. **Fact-Verification System**  
   - Analyzes AI-generated responses and **highlights discrepancies**, allowing users to compare sources.  
   - Generates a **confidence score** based on model agreement and source credibility.  

{% include image-gallery.html images="unnamed.JPG" height="400" %}  
- **Screenshot of the AI-powered fact-checking app running in Swift, displaying real-time query processing and AI validation.**  

## Technical Implementation  
### **Swift & API Communication**  
- Designed the app’s **UI and backend using Swift** with a focus on **seamless API integration**.  
- Implemented **asynchronous API calls** to **ChatGPT and Google Gemini APIs**, optimizing response times.  

### **LLM Integration & Data Processing**  
- Developed **middleware logic** that **compares AI-generated responses**, identifying inconsistencies in fact-checking.  
- Optimized **natural language processing (NLP) functions** to **validate extracted information against trusted data sources**.  

## Key Learnings & Impact  
- **Advanced API Integration**: Strengthened expertise in **Swift’s URLSession, JSON parsing, and asynchronous API handling**.  
- **Machine Learning & LLMs**: Gained **hands-on experience integrating Large Language Models (LLMs) into a mobile application**.  
- **User-Centric Development**: Ensured a **fluid and intuitive UI/UX** for easy fact-checking and verification.  

## Future Enhancements  
- **Automated fact-ranking system** to score AI-generated responses based on credibility.  
- **Expanding API support** to include real-world news databases and knowledge graphs.  
- **Developing an offline verification mode** for users in low-connectivity environments.  

---

