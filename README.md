# 🍽️ Restaurant Product Recommendation Chatbot (Gen AI)

An AI-powered Restaurant Product Recommendation Chatbot built using Generative AI and OpenAI GPT model.  
The chatbot recommends food items based on user preferences such as vegetarian/non-vegetarian choice, spice level, and budget.

---

## 📌 Project Overview

This project demonstrates the real-world application of Generative AI in the food and hospitality industry.

The chatbot:
- Recommends menu items intelligently
- Filters based on Veg/Non-Veg preference
- Considers spice level
- Suggests combo meals
- Saves confirmed orders to CSV
- Maintains conversation memory

---

## 🚀 Technologies Used

- Python
- OpenAI GPT-4o-mini
- Google Colab
- CSV (for order storage)
- Prompt Engineering

---

## 🏗️ System Architecture

User Input  
↓  
Google Colab Interface  
↓  
System Prompt (Menu + Rules)  
↓  
OpenAI GPT Model  
↓  
Generated Intelligent Response  
↓  
(Optional) Save Order to CSV  

---

## 📋 Features

- Vegetarian / Non-Vegetarian filtering
- Budget-based recommendation
- Spice-level filtering
- Combo suggestions (Main + Drink + Dessert)
- Conversation memory
- Order saving system
- Friendly conversational interface

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/Ashok-0167/Chatbot_restaurent.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Add your OpenAI API key:

```python
import os
os.environ["OPENAI_API_KEY"] = "YOUR_API_KEY"
```

4. Run the notebook in Google Colab.

---

## 🧠 Example Interaction

User:
```
I want something spicy and non veg under 300
```

Bot:
```
I recommend Chicken 65 as a spicy starter.
For main course, Chicken Biryani is a great choice.
You can add Mango Lassi for a refreshing combo.
Would you like to confirm this order?
```

---

## 🎯 Future Enhancements

- Payment gateway integration
- GUI interface
- Real-time database integration
- Multilingual support
- Voice-based ordering
- Web app deployment

---

## 👨‍💻 Author

Ashok Kumar Periyasamy  
B.Tech Student  
Project: Generative AI Restaurant Chatbot  

---

## 📄 License

This project is licensed under the MIT License.
