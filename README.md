# Cafeteria-Order-Menu-Recommendation-System-for-Elderly-Care-Facilities
A smart ordering assistant designed for care home cafeterias, allowing elderly users to order meals by voice while respecting dietary needs and personal preferences.


# Introduction
In aging societies like Japan, meal services in elderly care facilities face a critical dilemma known as the "Triple Constraint Problem" — balancing **food safety**, **menu diversity**, and **operational cost** is extremely difficult. 

- Prioritizing safety and cost leads to uniform meals, ignoring individual health conditions or preferences.
- Emphasizing safety and diversity increases labor costs and complexity.
- Focusing on cost and diversity risks mismatched meals that may harm patients' health.

To address this issue, we present an **AI-powered voice-based menu recommendation system** designed specifically for elderly care cafeterias. This system allows seniors to order meals simply by speaking, while the AI understands their preferences, dietary restrictions, and even emotional tone to recommend appropriate dishes. It ensures safety and personalization without increasing staff workload.

Key features include:
- LLM-based natural conversation and emotion-aware responses
- Health-aware filtering (diabetes, allergies, religious needs)
- Multilingual support (Japanese, English, Chinese)
- Tablet/smartphone compatibility for easy deployment
- Continuous learning from meal history and preferences

This system is designed not only to assist the elderly in making better meal choices, but also to reduce the burden on caregivers, enabling sustainable and inclusive food service in aged care environments.


****<img width="1742" height="995" alt="image" src="https://github.com/user-attachments/assets/f8df8a6c-6cbb-4e62-ae93-2a1a56be2fcc" />


# Agent Overview

At the heart of this system is an intelligent Agent that drives the voice-based menu recommendation and interaction process. Built on top of a large language model (LLM), the Agent integrates multiple components to enable seamless conversation and context-aware decision-making for elderly users.

### Key Functions:

- **Voice Interaction**: Listens to user speech (in Japanese, English, or Chinese) and converts it to text via ASR (Automatic Speech Recognition).
- **Prompt Engineering**: Injects structured system prompts to guide the LLM towards generating safe, context-aware, and polite responses.
- **Emotion & Preference Recognition**: Analyzes keywords and tone to infer the user's current mood and taste preferences (e.g., "I want something light", "Not too salty").
- **Health-Based Filtering**: References the user’s health profile (diabetes, hypertension, allergies, etc.) and automatically filters out unsuitable dishes.
- **Rejection & Substitution Logic**: Politely rejects harmful choices and suggests alternative meals.
- **Dialogue Memory**: Stores recent interaction history and meal records to improve future recommendations.
- **Robot Control Integration**: Sends feedback to a connected robotic interface for emotional gestures or confirmation motions (e.g., nodding, waving).
- **Multilingual Response**: Supports switching system replies across languages, including simplified Japanese speech for dementia users.

This modular Agent is designed for extensibility and can be customized to different care facilities or integrated into tablet/robotic environments.







