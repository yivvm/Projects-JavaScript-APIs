## Cat API Website

This project utilizes the Cat API to display information and images of different cat breeds. Users can select a breed from a dropdown menu, and the website dynamically loads images and information related to the selected breed.
![screenshot.png](./screenshot.png)

### Technologies Used
- JavaScript
- Axios for HTTP requests
- Bootstrap for styling (only grid system utilized)
- HTML and CSS

### Files
- **```index-axios.js``` and ```index.js```**: Contains the main JavaScript logic for fetching breed data, handling user interactions, and managing favorites.
- **```Carousel.js```**: Contains utility functions for creating and managing the carousel of images.
- **```index.html```**: HTML markup for the webpage layout.
- **```styles.css```**: CSS styles for the webpage.

### How to Run
1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser.

### Features
- **Initial Load**: When the webpage loads, it fetches a list of cat breeds from the Cat API and populates the dropdown menu.
- **Breed Selection**: Users can select a cat breed from a dropdown menu.
- **Carousel**: Images of the selected breed are displayed in a carousel, allowing users to navigate through them using previous and next buttons.
- **Breed Information**: Information about the selected breed, including description, temperament, origin, and lifespan, is displayed below the carousel.
- **Favorite Images**: Users can favorite images by clicking the "Favorite" button. Favorited images are stored locally using browser localStorage.
- **Get Favorites**: Users can view their favorited images by clicking the "Get Favorites" button. This button clears the carousel and displays only favorited images.

