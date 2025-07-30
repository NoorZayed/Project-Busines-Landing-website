# Business Landing Website Project - README

## Project Overview

This project involved building a responsive business landing website from scratch using HTML and CSS. The goal was to demonstrate proficiency in web development fundamentals, including:

* Creating a structured HTML layout.
* Applying custom CSS styling for visual design.
* Implementing responsive design principles.
* Organizing code for maintainability.

The website consists of a home page and a secondary page with a form, adhering to the project's requirements for functionality and design.
<img width="1440" height="900" alt="Screenshot 2025-07-30 at 11 10 58 PM" src="https://github.com/user-attachments/assets/6e2dab8a-17c4-4aaf-9adf-5b3a341bd68a" />
<img width="1440" height="900" alt="Scree<img width="1440" height="900" alt="Screenshot 2025-07-30 at 11 11 13 PM" src="https://github.com/user-attachments/assets/c2c469e9-ce68-414b-aee1-c2fae79fde68" />
nshot 2025-07-30 at 11 11 06 PM" src="https://github.com/user-attachments/assets/cca51bd9-2b9c-4e4c-9327-e6692a5db9b8" />
<img width="1440" height="900" alt="Screenshot 2025-07-30 at 11 11 25 PM" src="https://github.com/user-attachments/assets/c7f3a5ed-19d8-46a2-b735-7e0ffeef7309" />
<img width="1440" height="900" alt="Screenshot 2025-07-30 at 11 11 33 PM" src="https://github.com/user-attachments/assets/f08f1a58-6daa-48ac-b56a-987aba49e317" />

### Local Development
To run the demo locally for development:
1. Navigate to the project directory in your terminal
2. Run: `python3 -m http.server 8000`
3. Open your browser and go to `http://localhost:8000`

## Project Structure

The project is organized as follows:
* `index.html`: The main landing page of the website.
* `pages/contact.html`: The secondary page containing the form.
* `css/styles.css`: Contains global CSS styles applied across all pages.
* `css/index.css`: Contains CSS styles specific to the home page.
* `css/contact.css`: Contains CSS styles specific to the contact page.
* `images/`: Contains all image assets used in the website.

## Key Features

* **Responsive Design:** The website is designed to be responsive, adapting to different screen sizes using media queries.
* **Custom Layout and Styling:** The website features a custom layout and styling using HTML and CSS, including custom typography and color schemes.
* **Navigation:** A navigation bar is implemented to allow users to navigate between the home page and the contact page.
* **Semantic HTML:** HTML5 semantic elements are used to provide structure and meaning to the content.
* **Form Implementation:** The contact page includes a form with input fields and a submit button.
* **Flexbox and Grid:** CSS Flexbox and Grid are used for layout and component design.
* **Code Organization:** CSS styles are organized into separate files for global and page-specific styles.
* **Image handling:** All images include descriptive alt text.

## Technologies Used

* HTML5
* CSS3
* Flexbox
* CSS Grid
* Media Queries (for responsiveness)

## Implementation Details

* **HTML Structure:**
    * The `index.html` and `contact.html` files follow a clear and structured HTML5 document outline.
    * Semantic HTML5 elements (e.g., `<header>`, `<nav>`, `<section>`, `<footer>`, `<form>`) are used to enhance accessibility and SEO.
    * All images have descriptive alt attributes.
    * Forms have proper labels and input types.
* **CSS Styling:**
    * CSS styles are separated into global and page-specific files for maintainability.
    * Custom typography and color schemes are implemented using hex color values.
    * Flexbox and Grid are used for layout and component design.
    * Media queries are used to create responsive breakpoints for different screen sizes.
* **Responsiveness:**
    * The website is designed to be mobile-friendly and displays correctly on various devices.
    * Media queries are used to adjust the layout and styling for different screen sizes.
* **Navigation:**
    * A navigation bar is implemented using `<ul>` and `<li>` elements with `<a>` tags for links.
* **Form:**
    * A contact form is included on the contact page, using input fields, labels and a submit button.

## How to Run

### Method 1: Live Server (Recommended)
1. Navigate to the project directory in your terminal
2. Run: `python3 -m http.server 8000`
3. Open your browser and go to `http://localhost:8000`

### Method 2: Direct File Opening
1. Clone the repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Navigate to the `pages/contact.html` file to view the contact page.

**Note:** Using the live server method is recommended as it properly serves all assets and avoids potential CORS issues.

## Deployment

The website is deployed globally using GitHub Pages. To deploy your own version:

1. **Fork or clone this repository to your GitHub account**
2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"
3. **Your site will be available at:** `https://yourusername.github.io/repository-name/`

The deployment is automatic - any changes pushed to the main branch will update the live site within a few minutes.

### Alternative Deployment Options
- **Netlify:** Drag and drop the project folder to [netlify.com](https://netlify.com)
- **Vercel:** Connect your GitHub repository to [vercel.com](https://vercel.com)
- **Surge.sh:** Use `npm install -g surge` and run `surge` in the project directory

## Validation

* HTML code has been validated using the [W3C Markup Validation Service](https://validator.w3.org/).

## Best Practices

* Semantic HTML5 is used for proper structure and accessibility.
* CSS is organized into separate files for maintainability.
* Responsive design is implemented using media queries.
* Code is formatted for readability and consistency.
* No inline or embedded styles have been used.

## Future Improvements

* Add JavaScript for interactive elements.
* Implement form validation and error handling.
* Optimize images for better performance.
* Add more pages and content to the website.
* Add more complex responsive design features.
* Improve accessibility.

This README provides an overview of the project and its implementation.
