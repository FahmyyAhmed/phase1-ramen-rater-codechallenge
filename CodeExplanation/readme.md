# Ramen Rater

Ramen Rater is an interactive web application where users can browse a list of ramen dishes, see detailed information about each dish, and add new ramen reviews with their own comments, ratings, and images. It's a fun and easy way to keep track of your favorite ramen!

## Features

- **Ramen Menu**: A collection of ramen dishes is displayed, each with an image. Clicking on any ramen dish displays detailed information such as the restaurant name, rating, and comment.
- **Add New Ramen**: Users can add new ramen dishes to the menu by filling out a form with the name, restaurant, image URL, rating, and comment. The new ramen is then added to the menu dynamically.
- **Responsive Design**: The layout adjusts for different screen sizes to ensure a good user experience.

## Technologies Used

- **HTML**: For the structure and content of the webpage.
- **CSS**: For styling and responsive design.
- **JavaScript**: To make the page interactive, handling the display of ramen dishes, form submission, and dynamic updates to the page.
- **Font Awesome**: For icons used in the header and footer.

## Setup Instructions

1. **Clone the repository**:
   ```
   git clone https://github.com/FahmyyAhmed/ramen-rater.git
   ```

2. **Navigate to the project directory**:
   ```
   cd ramen-rater
   ```

3. **Open the `index.html` file** in your browser to see the app in action.

## How It Works

### Displaying Ramens
The app starts by displaying a set of ramen dishes. Each ramen is shown with an image, and when clicked, the app shows more details including the ramen name, the restaurant where it's from, its rating, and a short comment.

### Adding New Ramens
Users can add new ramen dishes using the form at the bottom of the page. Once the form is filled out and submitted, the new ramen dish is added to the display dynamically. It includes the ramen name, restaurant, image, rating, and comment.

### Updating the Display
When a ramen image is clicked, the app updates the ramen details section with the corresponding ramen's information.

## Project Structure

```
/ramen-rater
  /assets
    /images
      - ramen images
  /css
    - style.css
  /js
    - script.js
  index.html
```

- **assets/images**: Contains images of the ramen dishes.
- **css/style.css**: Contains styles for the webpage.
- **js/script.js**: Contains the JavaScript logic for displaying and adding ramen dishes.
