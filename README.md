# Password Generator Tool

This Python script generates a random password based on the user's specified choice of character sets and the desired password length.

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

## Example Usage

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
