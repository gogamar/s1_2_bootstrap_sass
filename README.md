# Bookmark Manager Landing Page

This project features a responsive web layout based on wireframes, utilizing HTML, Bootstrap, and SASS. It includes a fixed navigation bar, a grid-based responsive layout, customized Bootstrap components, and unique SASS styling.

## Project Structure / Description

### Exercise 1: Navbar & Header

- **Desktop Layout**:
  - Create a desktop layout with a fixed top navigation bar using Bootstrap.
  - Use the responsive grid to organize main content into two columns (slogan and image).
- **Tablet and Mobile Layout**:
  - Make the design responsive with media queries.
  - Adjust the grid layout and element colors based on screen size.

### Exercise 2: Features Section

- Add a "Features" section using Bootstrap’s grid and customize the "tabs" component.

### Exercise 3: Download Section

- Implement download cards using Bootstrap cards or custom CSS, ensuring responsiveness.

### Exercise 4: FAQs Section

- Create a FAQs section using the "Accordion" component, ensuring responsiveness and including Bootstrap buttons.

### Exercise 5: Footer Section

- Add a responsive footer with a newsletter submission form that validates email input.

### Exercise 6: Button and Link States

- Update hover and active states for buttons, links, and tabs with custom effects.

## Technologies Used

- **HTML**: Structure and content of the web page.
- **Bootstrap**: Responsive design and pre-built components.
- **SASS**: Custom styling and variables for CSS management.
- **JavaScript**: Include Bootstrap Bundle JS. Form validation.

## Requirements

To successfully run this project, we recommend using Visual Studio Code.

### Recommended Tools

- **Node.js**: Required to manage packages and run build tasks.

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/gogamar/s1_2_bootstrap_sass.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd s1_2_bootstrap_sass
   ```

3. **Install Dependencies**:
   Use npm to install Bootstrap and SASS by running the following command:

   ```bash
   npm install
   ```

   This command installs the necessary packages defined in the `package.json` file:

   - **Bootstrap**: A popular CSS framework for responsive design.
   - **SASS**: A CSS preprocessor for writing modular and maintainable CSS.

4. **Run the Build Script**:
   To compile your SASS files into CSS, use the following npm script:
   ```bash
   npm run build-css
   ```
   This command executes the SASS compiler to convert your `scss/main.scss` file into a CSS file located at `css/style.css`, and it will watch for changes so that it recompiles automatically as you edit your SASS files.

## Execution

To run the project locally use **Live Server** extension for Visual Studio Code.
