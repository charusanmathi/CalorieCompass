# CalorieCompass

Calorie Compass: Nutritional Monitor App

Calorie Compass is a Streamlit-powered web application that utilizes Google's Gemini AI to analyze meal images, identify food items, estimate nutritional values, and provide dietary insights. This project combines image processing with generative AI to deliver a user-friendly tool for understanding meal composition.

Features

Upload Meal Images: Users can upload photos of meals in JPG, JPEG, or PNG formats.
AI-Powered Analysis: Google Gemini AI identifies ingredients, estimates calories, and provides a breakdown of macronutrients (protein, carbs, fats).
Health Insights: Includes information on whether the meal is healthy, along with fiber content and other nutritional highlights.
Interactive Interface: Modern, responsive, and user-friendly UI with custom styling.
Error Handling: Ensures seamless user experience with robust exception handling.
How It Works

Image Upload:
Upload a meal photo through the app's sidebar.
The image is processed and displayed in the main content area.
AI Analysis:
Click on the "Analyze this Food" button.
The app sends the uploaded image and a predefined nutritionist prompt to the Google Gemini AI model.
The model processes the image and returns:
Meal name.
Ingredients and estimated calories for each.
Total calories and macronutrient breakdown.
Health assessment and additional nutritional details.
Results Display:
Results are formatted and displayed dynamically for easy reading.
Requirements

Python 3.7 or higher
Libraries: streamlit, dotenv, google-generativeai, Pillow, base64
