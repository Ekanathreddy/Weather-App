# Weather-App
A simple weather application that fetches and displays the current weather information for a specified city using the OpenWeatherMap API.

## Files:
- `index.html`: Contains the HTML structure for the application.
- `styles.css`:  Contains the CSS for the styling of the application.
- `weatherApp.js`: Contains the javascript code for fetching and displaying the weather information.

## Explanation:
- `API Key and URL`: The code starts with defining the API key and the base URL for the OpenWeatherMap API.
- `Element Selection`: HTML elements are selected using `document.querySelector` to manipulate them later.
- `Weather Checking Function`: The 'checkWeather` function fetches weather data for a given city. If the city is not found(status 404), it displays an error message. Otherwise it updates the weather information on the page and sets the appropriate icon.
- `Event Listener`: An event listener is added to the search button to call the `checkWeather` function with the value entered in the search box when clicked.
