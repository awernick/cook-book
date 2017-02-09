# CookBook (Name Pending)

## Purpose
The main goal is to store 'recipes' or aggregations of ingredients. By storing the recipe, the system will calculate macro-nutrients and create an index of ingredients. A user will be able to search through the recipes by either ingredient or by macro-nutrient content.

## Technologies
- Frontend: Angular
- Backend: Flask
- Database: MongoDB
- APIs: Nutritionix
- Mobile: React Native

## Features

#### Ingredients
- Search for food through the Nutritionix database or by UPC
- View individual foods macronutrient content
- Create a food in case it is not in Nutritionix database

#### Recipes
- Create recipes (aggregate of food items)
- Calculate macro-nutrient content for a whole recipe
- Divide recipe into servings, which propagates into macro-nutrient content
- Store total prep / cook time
- Store recipe instructions and photos

#### Indexer
- Categorize recipes by ingredients
- Categorize recipes by macro-nutrient content