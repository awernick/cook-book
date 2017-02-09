# CookBook (Name Pending)

## Purpose
The main goal is to store 'recipes' or aggregation of food items. By storing the recipe, the system will calculate the macro-nutrients and create a database of ingredients. A user will be able to search through the database by either ingredient or by macro-nutrient content.

## Technologies
- Frontend: Angular
- Backend: Flask
- Database: PostgreSQL
- APIs: Nutritionix
- Mobile: React Native

## Features

#### Food
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