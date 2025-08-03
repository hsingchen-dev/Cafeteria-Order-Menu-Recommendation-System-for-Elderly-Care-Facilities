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

# System Overview

This system provides a smart, voice-driven meal ordering experience for elderly users in care facilities. It integrates QR-based health data access, multilingual voice input, LLM-based natural language understanding, and menu filtering logic to recommend safe and personalized dishes.

# Team
This project is organized by an interdisciplinary team of doctoral and master's students, with each member contributing based on their respective areas of expertise.

- **Fuzuki Tasaka (Project Lead)** – Oversees overall project direction, system implementation, and agent behavior evaluation.  
  Acts as a bridge between development and real-world deployment by conducting usability testing and improving prototypes. Also contributes directly to coding and practical integration.  
  *Kobe University*

- **Hang Xingchen** – Responsible for system architecture design, including the integration of LLMs, robotic control, and multimodal coordination (vision, voice, behavior).  
  *Kobe University*

- **Haruki Maruyama** – In charge of prompt engineering and market research. Optimizes dialogue flow in Japanese and ensures the system aligns with user needs and social context.  
  *The University of Tokyo*


### 🧠 Step-by-Step Process

**Step 1: Scan QR Code**  
Users begin by scanning their personal QR code using a tablet or terminal. The QR contains their profile, including health conditions, allergies, and a 7-day meal history.

**Step 2: Speak Desired Meal**  
The user says what they would like to eat using natural spoken language. The system supports multiple languages and dialects.

**Step 3: Agent Reasoning (LLM + Rules)**  
The Agent analyzes the request using:
- Natural language understanding via LLM
- Health-based filtering logic
- Preference and emotion inference  
It then **accepts**, **modifies**, or **rejects** the request.

**Step 4: Menu Display with Tags**  
The system displays the filtered menu with allergy labels, nutritional info, and clear explanations, so users can understand what's safe and suitable.

**Step 5: Automatic Rejection (if needed)**  
If a user attempts to choose a dish that contradicts their current health status, the system automatically blocks it and recommends an alternative.

**Step 6: Update QR History**  
After ordering, the system updates the QR code with the selected meal and health impact. This history helps refine future recommendations and ensure balanced nutrition.

This six-step cycle enables personalized, safe, and efficient meal selection for seniors, while reducing the burden on care staff.

<img width="1744" height="989" alt="image" src="https://github.com/user-attachments/assets/0539065d-1f8f-4497-8d03-1ee0af676441" />
<img width="1741" height="993" alt="image" src="https://github.com/user-attachments/assets/473651a2-9789-4767-94d3-3a6d72f520aa" />
<img width="1741" height="993" alt="image" src="https://github.com/user-attachments/assets/e2a122a4-2511-4fff-8f8c-4fab994ba4f8" />
<img width="1739" height="991" alt="image" src="https://github.com/user-attachments/assets/02593728-12fe-475d-b815-a2571aa7636c" />
<img width="1742" height="992" alt="image" src="https://github.com/user-attachments/assets/03de1cf5-5167-4ba3-a8df-ca5a319b0c9f" />

## Demo Video
## Demo Video SKYNET-First-Generation Agent – Menu Recommendation System for General Restaurants
The following demo video showcases the **first-generation prototype** of our AI-powered meal ordering system. This version is designed for use in **general restaurants**, enabling users to interact with the menu via natural spoken language.
https://www.youtube.com/shorts/mqymFhW0tDY

The video showcases the lower-level control system linked with the ordering agent. By leveraging control technologies based on large language models, the agent can understand the user’s mood and respond with appropriate actions or expressions, enabling more natural and human-like interaction.
https://www.youtube.com/watch?v=IZ2gPEjCfZQ


## Demo Video SKYNET-Second-Generation Menu Recommendation Agent for Elderly Facilities





