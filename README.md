# Password Generator

This is a simple and customizable password generator web application built using HTML, CSS, and JavaScript. The application allows users to generate secure passwords based on customizable settings such as password length, inclusion of uppercase and lowercase letters, numbers, and symbols.

## Features

- **Customizable Password Settings**: Users can specify the password length (between 4 and 20 characters) and choose whether to include uppercase letters, lowercase letters, numbers, and symbols.
- **Clipboard Functionality**: Generated passwords can be copied to the clipboard with a single click.
- **Responsive Design**: The layout is responsive, adjusting to different screen sizes.

## Demo

A live demo of the password generator can be accessed [here](https://harsh-password-generator.vercel.app/).

## How to Use

1. **Password Length**: Adjust the length of the password using the input box under "Password Length".
2. **Include Options**: Check or uncheck the boxes to include or exclude uppercase letters, lowercase letters, numbers, and symbols in the generated password.
3. **Generate Password**: Click the "Generate Password" button to generate a secure password based on the selected options.
4. **Copy to Clipboard**: After generating the password, click the clipboard icon to copy the password to your clipboard.

## Code Overview

### HTML

- The `index.html` file contains the structure of the web application, including the password display, customization options (length, uppercase, lowercase, numbers, symbols), and buttons for generating passwords and copying them to the clipboard.

### CSS

- The `style.css` file defines the styling of the web application, ensuring a clean and modern design that works well across different devices. It uses the `Muli` font and provides a visually appealing interface with good spacing and colors.

### JavaScript

- The `script.js` file contains the functionality of the application:
  - **Password Generation**: A random password is generated based on the selected settings (uppercase, lowercase, numbers, symbols, and length).
  - **Clipboard Support**: The generated password can be copied to the clipboard using the "Clipboard" button.
  - **Random Character Functions**: Helper functions (`getRandomLower`, `getRandomUpper`, `getRandomNumber`, `getRandomSymbol`) generate random characters.

## Installation and Setup

To run this project locally:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/password-generator.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd password-generator
    ```

3. **Open `index.html` in your web browser**:

    Simply open the `index.html` file in your browser, and the Password Generator will be ready to use.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **Font Awesome** (for icons)
- **Google Fonts** (for typography)

## Contributing

Contributions are welcome! If you have any ideas for improvements or new features, feel free to submit a pull request or open an issue.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push to the branch.
5. Open a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements

- [Font Awesome](https://fontawesome.com/) for icons.
- [Google Fonts](https://fonts.google.com/) for the Muli font.
- Inspiration from various online tutorials and password generators.
