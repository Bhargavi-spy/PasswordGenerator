# 🔐 Random Password Generator

This is a simple and interactive **Random Password Generator** built using Python. The user can choose which character sets to include in the password (letters, digits, special characters), specify the length of the password, and generate a secure, randomized password.

## 🧠 Features

- Input validation for password length and character choices
- Supports:
  - Uppercase and lowercase letters
  - Numbers
  - Special characters
- Ensures at least one character set is selected before generating a password
- Easy to use and beginner-friendly

## 🖥️ How It Works

1. The user is asked to enter the desired length of the password.
2. The user then selects which character sets to include in the password:
   - Letters (A-Z, a-z)
   - Digits (0-9)
   - Special Characters (!@#$%^&*, etc.)
3. Once selections are made, the password is generated and displayed.

## 📌 Example

Enter password length: 12
Choose character set for password from these:
1. Letters
2. Digits
3. Special characters
4. Exit
Pick a number: 1
Letters added.
Pick a number: 2
Digits added.
Pick a number: 4
The random password is: hD3kGq9JmT8v

shell
Copy
Edit

## ▶️ Getting Started

### Prerequisites

Make sure you have **Python 3** installed on your system.

### Run the Script

```bash
python password_generator.py
🛠️ Code Highlights
Uses Python’s built-in string and random modules.

Input is validated to prevent crashes due to invalid entries.

Prevents duplicate character set selections.

📁 File Structure
pgsql
Copy
Edit
📦 password-generator
 ┣ 📄 password_generator.py
 ┗ 📄 README.md
🧑‍💻 Author
Bhargavi Mandalapu
Feel free to connect or contribute!
