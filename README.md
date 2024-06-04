# Password Generator Tool

This Python script generates a random password based on the user's specified choice of character sets and the desired password length.

## Table of Contents

- [How It Works](#how_it_works)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## How It Works

1. **User Input for Password Length**: 
   - The user is prompted to input the desired length of the password.

2. **Choosing Character Sets**:
   - The user is presented with four options to include in the password:
     1. Digits
     2. Letters
     3. Special characters
     4. Exit (to finish selecting character sets)
   - The user can select one or more of these options to build a custom character set for the password.

3. **Password Generation**:
   - A random password of the specified length is generated using the chosen character set.
   - The script ensures that the password is composed of characters randomly picked from the selected sets.

4. **Displaying the Password**:
   - The generated password is displayed as a string.

## Features

- **Secure Random Generation**: Utilizes Python's `random.choice` to ensure secure random selection of characters.
- **Customizable Character Sets**: Allows users to choose from digits, letters, and special characters.
- **User-Friendly Interface**: Easy-to-use command-line interface for input and selection.
- **Flexible Length**: Generates passwords of any specified length based on user input.

## Installation

To use this application, you'll need to have Python installed on your machine. Follow these steps to set up the application:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Sanders003/password_generator.git
    cd password_generator
    ```

2. **Install dependencies:**
    There are no external dependencies for this application. It uses Python's standard library.

## Usage

You can use the application through the command line. Simply run the Python script and follow the prompts:

```bash
python password_generator.py
```

## Example

```
Enter password length: 12
Choose character set for password from these : 
        1. Digits
        2. Letters
        3. Special characters
        4. Exit
Pick a number: 1
Pick a number: 2
Pick a number: 3
Pick a number: 4
The random password is A7!bC9#dE3$
```

In this example, the user chose all three character sets (digits, letters, and special characters), and a 12-character long password was generated using characters from the selected sets.

## Contributing

Contributions are welcome! If you have any ideas for improvements or new features, please open an issue or submit a pull request. Here's how you can contribute:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is an open source application.

## Contact

If you have any questions or suggestions, feel free to reach out to me at [22cs01004@iitbbs.com](mailto:22cs01004@iitbbs.com)
Or comment your suggestions in the code after the 45th line in the 'pass_gen.py' file.

---

Thank you for using the Password Generator Tool! We hope it meets your needs effectively.
