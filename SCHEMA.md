# Schema

## ingredient
- name: string
- id: integer
- nf_id: integer
- type: integer (1 = restaurant, 2 = cpg, 3 = USDA, 4 = custom)
- upc: integer
- description: string (e.g. finely chopped, etc..)
- calories: integer (kCal)
- total_fat: integer (g)
- carbohydrate: integer (g)
- protein: integer (g)
- serving_size: integer
- serving_unit: string


## recipe
- id: string
- name: string
- serving_size: integer
- serving_unit: string
- total_servings: integer
- cook_time: integer (seconds)
- instructions: text


## recipe_ingredient
- recipe_id: integer
- ingredient_id: integer
- serving_size: integer (for the recipe)
- serving_unit: string (for the recipe)

## Notes

1. There needs to be a way to convert between serving units of different kinds
