# CSC-545-Team-Project

The main menu has five options, you can: view your weekly meal plan, view your shopping list based on the weekly meal plan, add or edit items, add or edit recipes, or exit the system. The system runs on a seven day cycle, resetting every Sunday at 12:00AM.  

The first option, to view your weekly meal plan, is where you will assign the recipe to a certain day and category (breakfast, lunch or dinner). From here, you can view all 21 meals of the week, as well as edit them or view the recipe. [You can also select which meal plan you want to follow for that week.]  
  
*Note – At 12:00AM of the next day, the quantities will update automatically.  

The shopping list is where you see what items you are missing and need to pick up for the selected week. After getting the item, you can check the item off the list by selecting it and adding it to your cart. You can also choose to add the entire cart, instead of selecting them one by one. The quantity of the items will be automatically updated. 
  
*Note – If you purchase more than what is required, you will need to manually insert the amount you purchased OVER the required amount. 
The add or edit item button will allow you to either edit or delete an existing item, including its name, nutritional values, and quantity, or create a new item. When creating an item, the item must have a name, and any other unfilled information will be automatically assigned the value of 0. [default value of food group or set to null?]
*Note – Each item must have its own unique name, no duplicates are allowed. 

The add or edit recipe button will allow you to either edit or delete an existing recipe, including its name, instructions, category, and ingredients, or to create a new recipe. To create a recipe, the ingredients required must already be stored in the CookPal database, otherwise the creation of the recipe will fail. 
*Note - You can create a new item while in the process of creating a recipe.
