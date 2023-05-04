Download Link: https://assignmentchef.com/product/solved-csci-4380-lab-2
<br>
Database Systems

This lab will focus on the use of relational algebra to query a relational schema, as well as concepts related to functional dependencies.

1. Assume the existence of a database with the following relations: Ingredient(name, calories, cost, containsNuts)Recipe(name, ingredientName, amount)Menu(recipeName, season)which is used by a restaurant to manage its menu items. Assume that all amounts are in the same unit (e.g., grams) and that:πingredientNameRecipe ⊆ πnameIngredient πrecipeNameMenu ⊆ πnameRecipeTwo facts that may be helpful to remember:• the natural join (N with no condition) will pair tuples that agree on attributes with the same name.• recipes that contain nuts may also contain some ingredients without nutsWrite relational algebra expressions for the following:(a) (3 points) List the names of all recipes on the menu for the Spring and Summer seasons(b) (3 points) List the names of the recipes on the Winter menu that contain nuts

(c) (4 points) List the names of the recipes on the Fall menu that do not contain nuts

2. Assume the relation R(a, b, c, d, e, f) with the following FDs:b → cab → dec → f(a) (2 points) Find the key(s) of R(b) (3 points) Compute {ac}+. Show your work.