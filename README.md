# Dragon Ball Z Universe Website

Welcome to the Dragon Ball Z Universe Website! This project is a demonstration of an HTML website that showcases information about the popular Dragon Ball Z characters and uses SASS features for styling. This README will guide you through the project, its structure, and how to set it up.

## Table of Contents
- [Project Structure](#project-structure)
- [Running the Project](#running-the-project)
- [SASS Features](#sass-features)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

The project is organized with the following file and folder structure:
project-folder/
```
├── css/
│   └── styles.css          (Compiled CSS file)
├── images/
│   ├── ...                (Image files)
├── js/
│   ├── ...                (JavaScript files)
├── audio/
│   ├── ...                (Audio files)
├── _variables.scss         (SASS variables file)
├── _mixins.scss            (SASS mixins file)
├── _grid.scss              (SASS grid layout file)
├── _flexbox.scss           (SASS flexbox layout file)
├── your_choices.scss       (Custom SASS file)
├── styles.scss             (Main SASS file that imports others)
├── index.html
└── profiles.html
```
## Running the Project

To run the project and see the HTML website with SASS styles, follow these steps:

1. **Node.js and npm**:
   - Make sure you have Node.js and npm (Node Package Manager) installed. You can download them from [the official website](https://nodejs.org/).

2. **Install SASS**:
   - Open your command line or terminal.
   - Install SASS by running this command:
     ```
     npm install -g sass
     ```

3. **Compile SCSS**:
   - In your project directory, use SASS to compile your SCSS files into CSS. Run this command to watch for changes and compile automatically:
     ```
     sass --watch styles.scss:css/styles.css
     ```

4. **Link Compiled CSS in HTML**:
   - In your HTML files (`index.html` and `profiles.html`), link the compiled CSS file in the `<head>` section:
     ```html
     <link rel="stylesheet" href="css/styles.css">
     ```

5. **Open in the Browser**:
   - Open your web browser and navigate to the following:
     - For the index page: `file:///path-to-your-project/index.html`
     - For the profiles page: `file:///path-to-your-project/profiles.html`

6. **View in the Browser**:
   - You should now see your HTML website with SASS styles applied. Any changes made to the SCSS files will be automatically compiled into CSS.

## SASS Features

The project's SASS (`styles.scss`) includes the following features:

- **Variables**: Defined variables for primary colors and background colors.
- **Custom Properties**: Custom properties are used for the same colors.
- **Nesting**: Styles are organized using nesting for improved readability.
- **Interpolation**: Interpolation is used for dynamic CSS properties.
- **Placeholder Selectors**: Placeholder selectors are employed for hover effects.
- **Mixins**: A `form-input-style` mixin is used for consistent form input styling.
- **Functions**: A custom function `darken-color` darkens a color and is used in the footer styling.

## Contributing

Contributions to this project are welcome! If you'd like to improve or expand the project, feel free to submit pull requests or open issues.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.