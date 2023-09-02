# emoji_search_app
# Hosted Link:-https://tulasidurga1.github.io/emoji_search_app/
#### explanation:-
- HTML Structure:

<!DOCTYPE html>: This declaration defines the document type and version of HTML you are using, which is HTML5.

<html lang="en">: The opening tag for the HTML document, with the language attribute set to "en" for English.

<head>: This section contains metadata about the document, including character encoding, viewport settings, the page title, and links to external resources like CSS and JavaScript files.

<meta charset="UTF-8">: Specifies the character encoding as UTF-8, which is a widely used character encoding for handling various characters and symbols.

<meta name="viewport" content="width=device-width, initial-scale=1.0">: Defines the viewport settings for responsive design on different devices.

<title>Emoji Project</title>: Sets the title of the web page displayed in the browser tab.

<link rel="stylesheet" href="style.css">: Links an external CSS file named "style.css" to style the HTML content.

<body>: The main content of your web page is placed within this section.

<div class="container mt-3">: A container div with classes "container" and "mt-3" for styling and layout purposes.

<h1>Emojee - Emoji 🔍 Application</h1>: A heading displaying the title of your web application.

<form action="" id="search_form">: A form element with an empty action attribute and an ID "search_form."

<input type="text" id="search_field" autocomplete="off" placeholder="Emojee Search">: An input field for users to enter their emoji search queries. It has an ID "search_field," autocomplete turned off, and a placeholder text.

<input type="submit" value="Search">: A submit button for submitting the search form.

<table>: An empty table element.

<tbody id="search_result_container"></tbody>: An empty table body with an ID "search_result_container" where search results will be displayed.
JavaScript (emoji.js and script.js):
CSS (style.css):

My project  CSS stylesheet contains styles for various elements in your HTML document, such as fonts, colors, input fields, tables, and more.
It also includes some custom styling classes like "mt-3," "emoji," "aliases," and "desc" that are used in your HTML elements.
Explanation of JavaScript Functions:

searchEmoji: This function handles the form submission when the user clicks the "Search" button. It prevents the default form submission, extracts the search query from the input field, and calls displaySearchResults to display the search results.

autoSearch: This function is triggered when the user types in the search input field. It captures the input value and calls displaySearchResults to update the displayed results dynamically as the user types.

displaySearchResults: This function takes a search query as an argument (defaulting to an empty string) and filters the emojiList (which is not provided in your code) based on the search criteria. It then populates the "search_result_container" table body with the filtered results.

I have JavaScript code in two separate script tags included at the end of your HTML body.
The JavaScript code defines functions and event listeners for handling emoji search and display.
### Event Listeners:

There are two event listeners set up using addEventListener:
One listens for the form submission event on the "search_form" and calls searchEmoji.
The other listens for keyup events in the "search_field" input and calls autoSearch.
The window.onload function is set to displaySearchResults when the page loads initially, but it seems to lack an argument, so it may not work as expected without the emojiList.

Overall, my code seems to be the foundation for an emoji search application, but it relies on an undefined emojiList and certain HTML elements and classes that are not provided in the code snippet. You may need to further develop and integrate the missing parts to make the application fully functional.
