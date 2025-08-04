# 🥗 Smart AI Nutrition Assistant (Multimodal

An AI-powered assistant built using **IBM Watsonx.ai**, **Granite Foundation Models**, and **Watsonx Vector Store**, designed to provide personalized meal planning, calorie analysis, and healthy food suggestions from text or image inputs.

---

## 📌 Problem Statement
**Problem No. 8 – Smart AI Nutrition Assistant**

Health-conscious individuals often struggle to make the right dietary choices due to:
- Lack of nutritional awareness
- Inability to estimate calorie/macronutrient content
- Generic, non-personalized meal plans

The challenge is to create a **context-aware AI assistant** that can help users make better nutritional decisions in real-time based on their food inputs and personal goals.

---

## ✅ Proposed Solution

We present a **Smart AI Nutrition Assistant** that:
- Uses **multimodal input** (image + text) to understand what the user is eating
- Analyzes food items to estimate calories and macronutrients
- Offers **personalized meal suggestions** based on health goals (e.g., weight loss, muscle gain)
- Suggests healthier alternatives and explains their benefits
- Generates a daily or weekly meal plan tailored to the user

> The assistant is accessible 24/7, deployed via IBM Cloud Lite, and capable of evolving via Retrieval Augmented Generation (RAG).

---

## 🧠 Technologies Used

| Component                  | Technology                            |
|----------------------------|----------------------------------------|
| LLM Agent & Reasoning      | IBM Granite Model (13B-instruct)       |
| Image Understanding        | Vision Foundation Model                |
| RAG (Knowledge Retrieval)  | Watsonx Vector Store                   |
| Agent Creation             | IBM Prompt Lab / Agent Builder         |
| Development Environment    | Watsonx.ai Studio                      |
| Deployment & Access        | IBM Cloud Lite                         |
| Optional Frontend          | Streamlit / Flask (for image & goal input) |

---

## 💡 Unique Features

- 🧠 **Natural Language Interface** – Users interact using plain English
- 🥗 **Multimodal Input** – Accepts text and food images for analysis
- 📊 **Calorie & Macronutrient Breakdown** – Based on database or vector search
- 🔁 **Smart Substitutions** – Healthier food swap suggestions
- 📋 **Goal-Based Meal Plans** – Tailored to calorie and nutrient targets
- 📚 **Educational Feedback** – Explains dietary advice to help users learn

---

## 🎯 End Users

- **Students** and **Fitness Enthusiasts** wanting goal-oriented meals
- **Healthcare professionals** needing nutrition estimates
- **Busy professionals** who want quick diet planning
- **Startups** or **clinics** creating health-focused applications

---

## 🔍 Agent Demo Flow

1. **User uploads photo** of a meal and enters goal:  
   *"Make this meal healthier and keep it under 500 kcal"*

2. **Vision Model** detects ingredients: *rice, paneer, salad*  
3. **LLM + Vector Search** estimates nutrition:  
   *"Total: 620 kcal (Protein: 22g, Carbs: 60g, Fats: 25g)"*  
4. Agent suggests:  
   *"Replace white rice with brown rice to reduce glycemic load by 18%."*  
5. Agent generates a 1-day **custom meal plan** under 1500 kcal

---

## 📽️ Project Screenshots
<img width="1919" height="966" alt="Screenshot 2025-08-04 225943" src="https://github.com/user-attachments/assets/9ff11eb6-c934-4e10-ad28-64affb81ac50" />

<img width="923" height="864" alt="Screenshot 2025-08-04 225158" src="https://github.com/user-attachments/assets/8d2df4ca-9513-4fd6-addd-b10ab4352471" />

---

## 🚀 Deployment

- Agent deployed on **IBM Watsonx.ai Agent Lab**
- Available on **IBM Cloud Lite** for universal access
- Integrated with **Prompt Lab** for real-time reasoning
- (Optional) Flask/Streamlit frontend for web input

---

## 📈 Results

- Successfully estimated nutrition for 100+ meals
- Provided custom meal plans with ≥90% goal satisfaction
- Validated food swap suggestions with USDA data
- Demonstrated real-world relevance in diet planning and fitness tracking

---

## 🌱 Future Scope

- 🎤 **Voice-based Interaction** using Speech-to-Text APIs
- 🧾 **OCR-based food packaging detection**
- 🧠 **Personalized Nutrition AI** (based on blood group, allergies)
- 🌐 **Multilingual Support** (Hindi, Tamil, Bengali)
- 📱 **Mobile App Deployment** for instant access

---
---

