# Cocktail App

A simple and responsive cocktail search web application built with HTML, CSS, and JavaScript. The application uses TheCocktailDB API to search for cocktails and display their information, including the drink image, ingredients, measurements, and preparation instructions.

## About the Project

This project was created as a practice project for working with JavaScript, APIs, DOM manipulation, and responsive web design.

Users can enter the name of a cocktail into the search field and retrieve information about the drink. The application processes the API response and dynamically displays the available cocktail details on the page.

The default search is set to Margarita when the application is first opened.

## Features

* Search for cocktails by name
* Display the cocktail image
* Display the cocktail name
* Display ingredients and measurements
* Display preparation instructions
* Fetch cocktail data dynamically using an API
* Responsive layout for smaller screens
* Display an error message when the search input is empty or invalid

## Technologies Used

* **HTML5** — Structure of the application
* **CSS3** — Styling, layout, gradients, responsive design, and visual effects
* **JavaScript** — API requests, data processing, and dynamic DOM manipulation
* **TheCocktailDB API** — Source of cocktail information
* **Google Fonts (Poppins)** — Application typography

## API

This project uses TheCocktailDB API to retrieve cocktail information. The application sends the user's search term to the API and processes the returned JSON data.

The retrieved information includes:
* Cocktail name
* Cocktail thumbnail
* Ingredients
* Ingredient measurements
* Preparation instructions

## Project Structure

```text
Cocktail-App/
│
├── index.html
├── design.css
└── script.js
```

### `index.html`

Contains the main structure of the application, including the search input, search button, result container, and linked CSS/JavaScript files.

### `design.css`

Controls the application's visual design, including the background, centered content card, search interface, typography, cocktail results, and responsive behavior.

### `script.js`

Handles the application's functionality. It sends the search request to TheCocktailDB API, processes the returned cocktail data, extracts ingredients and measurements, and dynamically generates the result displayed to the user.

## How It Works

1. Enter the name of a cocktail in the search field.
2. Click the Search button.
3. JavaScript sends the cocktail name to TheCocktailDB API.
4. The API returns information about the requested drink.
5. The application extracts the cocktail's image, name, ingredients, measurements, and instructions.
6. The information is dynamically displayed on the page.

When the input field is empty, the application displays a message asking the user to enter an input. If the API request fails or the input does not return valid data, an error message is displayed.

## Design

The interface uses a warm brown and gold color palette with a blurred gradient background. The cocktail information is presented inside a centered white card with rounded corners and a subtle shadow.

The layout also includes responsive styling for smaller screens.

## Project Limitations

This is a small practice project and intentionally keeps the functionality simple. The application currently displays the first cocktail returned by the API rather than presenting multiple search results.

## Author
Developed as a college student project exploring web development 

A student project created while practicing front-end web development and JavaScript API integration.
