# Random Joke Generator

A simple web application that fetches and displays random dad jokes at the click of a button. Built using HTML, CSS, and JavaScript, this app uses the [icanhazdadjoke API](https://icanhazdadjoke.com/api) to provide fresh, entertaining jokes every time the user requests one. It also includes a feature to share the joke on Twitter.

## Features

- Displays a random joke fetched from an API.
- Refresh button to get a new joke instantly without reloading the page.
- Share the current joke on Twitter with a single click.
- Clean, responsive design using CSS for an engaging user experience.

## Technologies Used

- **HTML**: Structure of the web page.
- **CSS**: Styling and layout design.
- **JavaScript**: Logic to fetch jokes from the API, update the UI dynamically, and handle events.
- **icanhazdadjoke API**: Source of random dad jokes.

## Usage

1. Open `index.html` in any modern web browser.
2. Click the **New Joke** button to fetch a new random joke.
3. If you like a joke, click on the **Tweet** button to share it on Twitter.

## Code Overview

- **index.html**: Contains the HTML markup including a container for the joke text, buttons for generating a new joke and tweeting it.
- **style.css**: Provides styling for the layout, buttons, and typography to create a user-friendly and visually appealing interface.
- **script.js**: Contains JavaScript code that fetches jokes from `https://icanhazdadjoke.com/` using `fetch()` with JSON response handling. It updates the joke display area and sets the tweet button URL dynamically. Includes error handling for API call failures.

## Screenshot

(Include a screenshot of the app here if available)

## How to Contribute

Feel free to fork the repository, make improvements or add features, and submit a pull request.

## License

This project is open source and available under the MIT License.

---

Made with ❤️ for learning and fun!
