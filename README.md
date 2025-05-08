# 🔐 Password Generator

This is a simple Python-based **Password Generator** that creates a secure, randomized password based on user-defined criteria.

---

## ✨ Features

- Allows users to specify the number of:
  - ✅ Letters (uppercase and lowercase)
  - ✅ Symbols (e.g., `!`, `@`, `#`, etc.)
  - ✅ Numbers (0–9)
- Randomly shuffles characters to enhance password security
- Command-line based interface
- Uses Python's built-in `random` module

---

## 🛠️ How It Works

1. The user is prompted to enter:
   - Number of letters
   - Number of symbols
   - Number of numbers
2. Characters are randomly picked from predefined lists of:
   - Letters (A–Z, a–z)
   - Numbers (0–9)
   - Symbols (!, #, $, %, etc.)
3. The selected characters are shuffled for randomness.
4. The final password is displayed.

---

## 🧪 Example

```
Welcome to password Generator!
How much letters do you want? 4
How much symbols do you want? 2
How much numbers do you want? 3
Generated Password: g7&BaE0!1
```

---

## 🧰 Requirements

- Python 3.x

No external libraries are required. The script uses only Python's standard library.

---

## 📁 File Structure

```
password_generator.py   # Main script
```

---

## 🚀 Getting Started

1. Clone this repository or download the `password_generator.py` file.
2. Run the script using Python:

```bash
python password_generator.py
```

3. Follow the on-screen prompts.

---

## 🧠 Note

This tool is intended for learning and experimentation. For critical applications, consider using professional password managers and security tools.

---

## 📜 License

This project is open source and free to use under the [MIT License](LICENSE).
