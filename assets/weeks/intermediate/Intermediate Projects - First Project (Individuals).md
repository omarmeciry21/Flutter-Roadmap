# First Project (Individuals)

### First Project (Individuals):

In this project, each member will do the required app individually. The app we will work on is a Food Recipe App. We will use the **[Spoonacular API](https://spoonacular.com/food-api).** The app should have the following screens with the following features:

- **First Screen:** Recipes List: this screen should show a list of different recipes. You can achieve this using the Search Recipe section in the API Docs. When the user clicks on any recipe, the app should navigate to the second screen to show the recipe details.
- **Second Screen:** Recipe Details: when the user clicks a specific recipe, it should navigate the user to another screen with the recipe details. You can achieve this using the Get Recipe Information section in the API Docs. Also, a very mandatory feature in this screen, the user should have a button to choose the Recipe as a favorite recipe. For the favorite recipe part, we will use SQLite to save favorite recipes id, name and some more data to use in the third screen, to be able to retrieve the recipe information later.
- **Third Screen:** Favorite Recipes List:  this screen should show a list of favorite recipes using the favorite recipes added to the SQLite database using the favorite button in the Recipe Details Screen. When the user clicks on any recipe, the app should navigate to the second screen to show the recipe details.

For this app, we will use the following design. The components marked with yellow are excluded, this design is from [this page](https://uxplanet.org/case-study-freshly-dropped-app-ux-design-for-cooking-and-shopping-a19c7a00c322) but we only need the general main details. For the first and third screen, they will be similar but the screen title will change. The user can navigate between Recipes List and Favorite Recipes List using a BottomNavigationBar, please search for it and how to use it well, that have only two icons, Home and Favorites. The design shouldn’t be exactly the same, so feel free to add or edit any part to make it better.

![Inked1_bbxRRAQBVGRXQMurjuXixA_LI.jpg](../../images/intermediate/Intermediate%20Projects%20-%20Individual.jpg)