# Trivia Question App

This is a simple Trivia Question App built using HTML and JavaScript. The app allows users to fetch a random trivia question based on a specified category. Below is a guide on how to use the Trivia Question App.

## Getting Started

To use the Trivia Question App, follow these steps:

1. Open the HTML file (`index.html`) in a web browser.
2. You will see the title "Trivia Question App" and an input field with a label "Enter Trivia Category."
3. Enter the desired trivia category by providing either the category ID or name in the input field.

## Fetching Trivia Questions

After entering the trivia category, click the "Get Trivia Question" button. The app will make an API request to Open Trivia Database (https://opentdb.com) to fetch a random trivia question for the specified category.

## Displaying Trivia

The fetched trivia question and answer will be displayed below the input field. If the category is valid and questions are available, you will see the question along with the correct answer. In case there are no questions for the specified category, an error message will be displayed.

## Example

Here is an example of how to use the Trivia Question App:

1. Enter the trivia category ID or name (e.g., "science" or "17").
2. Click the "Get Trivia Question" button.
3. View the displayed trivia question and answer.

## Important Note

Make sure you have an internet connection as the app relies on an external API to fetch trivia questions.
