## Meal Detection & Nutrient Analysis 🍽️⚖️
Meal Detection & Nutrient Analysis is an intelligent dietary tracking system that automates nutrition logging by combining computer vision with real-time weight sensing. By placing a food item on the digital scale, the system automatically identifies the food type, captures its exact weight, and calculates precise nutritional metrics—eliminating the need for manual data entry and portion guesswork.

## ✨ Features

* Automated Food Recognition: Employs computer vision to instantly identify individual food items (e.g., chicken breast, fruits, vegetables).
* Real-Time Weight Integration: Communicates with a digital scale to pull precise weight data dynamically.
* Dynamic Nutrient Calculation: Calculates macronutrients (protein, carbohydrates, fats) and calories tailored specifically to the exact weight of the portion.
* Seamless Logging: Reduces human error and friction in dietary tracking.

## 🚀 How It Works

   1. Place: The user places a food item on the smart scale.
   2. Scan: The camera captures the item, and the object detection model identifies the food type.
   3. Weigh: The system reads the weight data from the scale sensor.
   4. Analyze: The backend cross-references the food type and exact weight against a nutritional database to return real-time macros and calories.

