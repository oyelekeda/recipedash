RecipeDash is a fully responsive web application designed to help users discover, search, and save recipes from around the world. Its main goal is to make cooking easy, enjoyable, and accessible for both beginners and experienced users. The project is built using HTML, CSS, JavaScript, and Tailwind CSS, which provides a modern and responsive design.

The application is structured into four main pages:

Home Page (index.html)

This is the first page users see. It welcomes them with a friendly message and two main buttons: Get Started, which links to the About page, and View Recipes, which links to the Recipes page.

It highlights three primary meal categories: Breakfast, Lunch, and Dinner. Each category has an image, a title, and a short description to give users a quick overview.

The header navigation bar allows users to move seamlessly between Home, Recipes, About, and Contact pages.

Recipes Page (recipes.html)

This page is the core of the app. Users can search for recipes by typing a name into the search bar.

It integrates the TheMealDB API, which provides detailed recipe information such as meal name, category, area (cuisine), and image.

Search results are displayed dynamically using JavaScript, and each recipe includes a “❤️ Save” button. Users can click this button to store their favorite recipes in the browser’s local storage, allowing them to revisit saved recipes anytime.

The page also includes a dedicated Favorites section that automatically displays saved recipes.

About Page (about.html)

This page introduces RecipeDash, explaining its purpose and mission: to simplify cooking and inspire users to try new recipes.

It highlights the main features of the app: discovering recipes, saving favorites, and following step-by-step instructions to cook confidently.

The page also includes a Team section showcasing the people behind the project, such as the founder, recipe curator, and community manager.

Contact Page (contact.html)

Users can reach out to RecipeDash through a contact form with fields for name, email, and message.

It also displays the app’s contact information, including email, phone number, address, and links to social media platforms.

This ensures users can communicate feedback, suggestions, or inquiries easily.

API Integration

RecipeDash uses TheMealDB API to fetch recipes. When a user searches for a meal, the search term is sent to the API, which returns matching results in JSON format.

JavaScript processes these results and dynamically displays them on the page.

Users can then save recipes to local storage, which is non-volatile, meaning the data persists even after closing the browser.

Technologies Used

HTML5 & CSS: Provides the structure and styling of the website.

Tailwind CSS: Used for responsive design, modern layout, and styling.

JavaScript (ES6): Handles dynamic features like searching, API calls, and managing favorites.

Local Storage: Stores favorite recipes in the user’s browser.

TheMealDB API: Supplies recipes and meal information.

Key Features

Search Functionality: Users can quickly find recipes by name.

Favorites Management: Save, view, and remove favorite recipes.

Responsive Design: Works perfectly on desktops, tablets, and mobile devices.

Navigation: Easy-to-use header links for quick access to all pages.

Contact Form: Provides a way for users to communicate with the team.

Installation & Usage

The project is fully front-end and does not require a backend server.

To use the search feature, type a recipe name in the search bar on the Recipes page and click Search. Click the Save button on any recipe to add it to favorites.