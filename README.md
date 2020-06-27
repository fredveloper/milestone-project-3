# [Mix and Cheers](https://cocktails-recipes.herokuapp.com/)

Milestone Project 3: Data-Centric Development - Code Institute

[Mix and Cheers](https://cocktails-recipes.herokuapp.com/) is a website that allows the users to easily access, store and manage cocktails recipes.

The main functionalities of the website include: 

- Searching, adding, editing and deleting cocktail recipes.
- Adding, editing and deleting cocktail categories.
- Find information related to bartending field and also purchase products/services.

## UX

My goal in the design was to create a fresh, dynamic, responsive and user-friendly website, where all cocktail lovers could come together to share their recipes.

The website consists of five main sections: Recipes, Add Recipe, Categories, Search and Start Mixing; where the users can easily navigate and try the website's functionalities.

As the site's owner, another goal was to promote bartending products/services and earn money by including affiliate links where potential customers could buy from. All these links are located in the 'Start Mixing' area of the navigation bar.

### User Stories

User Stories

- As a user, I want to find cocktails recipes already stored.
> This can be achieved by accessing the homepage where all the recipes are presented as flipping cards and clicking the 'View Recipe' button of the selected recipe.

- As a user, I want to search for a particular cocktail recipe.
> This can be achieved by typing the recipe's name into the search bar located above the flipping cards area in the homepage. If browsing on a different page, the 'Search' link located in the navigation bar will also redirect to the homepage where the main search functionality is available.

- As a user, I want to add a new cocktail recipe.
> This can be achieved by clicking on the 'Add Recipe' link located in the navigation bar. After filling in a form, the recipe can be saved by clicking on the 'Save' button.

- As a user, I want to edit a cocktail recipe.
> This can be achieved by clicking on the 'View Recipe' button of the card's front area, and then clicking on the 'edit' button of the card's back area. The recipe's details will be displayed in an editable form, and the changes can be saved by clicking on the 'Save' button.

- As a user, I want to delete a cocktail recipe.
> This can be achieved by clicking on the 'View Recipe' button of the card's front area and then clicking on the 'Delete' button of the card's back area.

- As a user, I want to add a cocktail category.
> This can be achieved by clicking on the 'Categories' link located in the navigation bar and then clicking on the 'Add Category' button available on the displayed page. After filling in a form, the category can be saved by clicking on the 'Save' button.

- As a user, I want to edit a cocktail category.
> This can be achieved by clicking on the 'Categories' link located in the navigation bar, and then clicking on the 'Edit' button placed next to the relevant category. The category details will be displayed in an editable form, and the changes can be saved by clicking on the 'Save' button.

- As a user, I want to delete a cocktail category.
> This can be achieved by clicking on the 'Categories' link located in the navigation bar, and then clicking on the 'Delete' button placed next to the relevant category.

- As a user, I want to have access to bartending products/services information. 
> This can be achieved by clicking on the 'Start Mixing' dropdown menu located in the navigation bar, and then clicking on any of the available options: 'Bartender Books', 'Bartender Tools' or 'Bartender School'.

### Design (Mockups)

The original design of the application was represented with Mockups. Click [here](https://github.com/fredveloper/milestone-project-3/tree/master/doc) to see the mockups.

## Features

### Existing Features
- Add Recipe - allows users to add their own cocktail recipes. The details include the ingredients, preparation method, difficulty,  an image, etc.
- Edit Recipe - allows users to edit an existing cocktail recipe.
- Delete Recipe - allows users to remove a cocktail recipe.
- Search Recipe (by name) - allows users to search cocktail recipes by name.
- Links to access/purchase bartending related material: books, tools and training.

### Features Left to Implement

Another feature ideas:

- Expand the search functionality: search by ingredient, by category, etc.

- Add user login authentication: only the recipe's author will have permissions to edit/delete them.

- Add star-rating component: users will be able to rate the recipes and see which are the more recommended or popular.

## Technologies Used

The project uses:

- HTML5
- CSS3
- [Bootstrap4](https://getbootstrap.com/)
    - As a framework to create a responsive design, to style and structure all the pages of the website.
- [GoogleFonts](https://fonts.google.com/)
    - As the library for the font families selected.
- [FontAwesome](https://fontawesome.com/)
    - As icon library to style different components of the website.
- [JQuery](https://jquery.com)
    - To simplify DOM manipulation.
- [JavaScript](https://www.javascript.com/)
    - For interactive elements on pages.
- [Python3](https://www.python.org/)
    - As main programming language.
- [Flask](https://palletsprojects.com/p/flask/)
    - As a microframework for routing, request handling and other backend functionalities.
- [MongoDB](https://www.mongodb.com/)
    - As a non-relational database to store the recipe's data.
- [GitHub](https://github.com/)
    - For version control and backup of the code.
- [Heroku](https://www.heroku.com/)
    - As a platform for app deployment.

## Testing

### Manual Test

The website has a fully responsive design. This was tested through different web browsers: Google Chrome, Firefox, Microsoft Edge and Internet Explorer. 

The website pages are displaying and working correctly on different screen sizes for Google Chrome, Firefox and Microsoft Edge. 

Even though the website is also displaying correctly in Internet Explorer, the flipping cards are not fully functional, since their back areas are not showing up when clicking the 'View Recipe' button. Therefore, it is not recommended to use Internet Explorer to access this project.

A manual test was done for every single page to evaluate the website's functionality. All the forms, buttons, links and functions were checked.

- **All Pages**

    The navigation bar and footer elements (fonts, icons, links, dropdown menu) are displaying correctly and all the links are redirecting to the correct locations.

- **Recipes.html**

    - Search Area:
    
        The search input field and the search button are working correctly and the result is displayed according to the user's search.

    - Flipping Cards:

        The flipping cards elements (image, text, buttons) are displaying correctly. All the buttons are responding according to the action executed (view recipe, go back, edit, delete) and are redirecting to the correct locations.

- **AddRecipe.html and AddCategory.html**

    - Forms:
        - All elements are displaying correctly.
        - The form is successfully processed when all the required fields are filled in. 
        - The form is not being processed when a required field is left blank. In this case, an alert message is displayed to the user to indicate the required fields.
        - The buttons are responding according to the action executed (save, delete)

- **EditRecipe.html and EditCategory.html**

    - Forms:
        - All elements are displaying correctly.
        - All the fields are populated according to the recipe/category selected for edition.
        - The form is successfully processed when all the required fields are filled in. 
        - The form is not being processed when a required field is left blank. In this case, an alert message is displayed to the user to indicate the required fields.
        - The buttons are responding according to the action executed (save, delete)

- **Categories.html**

    - Table:

        - The stored categories are presented in a table and all its elements are displaying correctly.
        - The buttons are responding according to the action executed (save, delete)

### Code Validation

All the files were inspected using the below validators:

- [W3C HTML Validator](https://validator.w3.org/) for the HTML files.
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) for the CSS files.

## Deployment

- Live Demo: [Mix and Cheers](https://cocktails-recipes.herokuapp.com/)

- GitHub Repository: [Milestone Project 3](https://github.com/fredveloper/milestone-project-3)

### Remote Deployment

This application was fully deployed to Heroku, by following the below steps:

1. Run the command `pip3 freeze —local > requirements.txt` to create a requirements.txt file that contains all the packages required for this project.

2. Create a Procfile by running the command `echo web: python app.py > Procfile`.

3. Run `git add .` to stage all the files, run the command `git commit -m "<message>"` to commit the changes and finally push the files to the GitHub repository by using the command `git push origin master`.

4. Access Heroku and create a new app from the dashboard.

5. Go to new app 'Settings' section, and click on 'Reveal Config Vars' to set the following key-values:

| KEY | VALUE |
|:-:|:-:|
| IP | 0.0.0.0 |
| PORT | 5000 |
| MONG0_URI | mongodb+srv://<'username'>:<'password'>@<'cluster_name'>-tfc39.mongodb.net/database_name?retryWrites=true&w=majority |

6. Go to the 'Deploy' section to see the required steps to deploy the project to Heroku.

7. Push the code to GitHub and Heroku

8. The app will be finally hosted at: `http://<your_app_name>.herokuapp.com/`

### Local Deployment

The application can be deployed locally, by following the below steps:

Requirements:
- IDE (Visual Studio, PyCharm, etc).
- PIP, Git, Python and MongoDB installed.

1. Download the application repository by clicking on 'Clone or Download' button located at the top of this page. Click on ‘Download ZIP’ and extract the files in a folder.

2. Within the IDE, open the folder that contains the repository.

3. Create a .env file containing the MongoDB credentials MONGO_URI='mongodb+srv://<username>:<password>@<cluster_name>-qtxun.mongodb.net/<database_name>?retryWrites=true&w=majority'
Install the required packages by running the command `pip -r requirements.txt`

4. Create a new MongoDB database and name it as 'cocktails-recipes', then create the following collections:

    Categories:

        category_name: "Short Cocktail"
        category_name: "Highball Cocktail"
        category_name: "Blended Cocktail"
        category_name: "Hot Cocktail"
        category_name: "Tiki and Specialty Cocktail"
        category_name: "Shooter Cocktail"
        category_name: "Smoothie Cocktail"
        category_name: "Non-Alcoholic Cocktail"

    Recipes:

        category_name: <string>
        recipe_name: <string>
        recipe_description: <string>
        ingredients: <string>
        preparation_method: <string>
        difficulty: <string>
        recipe_image: <string>

5. Use the command `python app.py` to run the application and it will run at 'http://127.0.0.1:8080'.

## Credits

### Content
- The recipes texts were copied from [Wikipedia](https://www.wikipedia.org/).

### Media
- The images were collected from [Unsplash](https://unsplash.com/) and [Wikipedia](https://www.wikipedia.org/).