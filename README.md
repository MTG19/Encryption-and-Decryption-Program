# 🔐 **Encryption and Decryption Program** 🔐

## 🚀 Overview

This C++ program implements several classical encryption techniques:

1. **Vigenère Cipher** 🛡️
2. **Route Cipher** 🔄
3. **Baconian Cipher** 🅰️🅱️
4. **Morse Code Cipher** 📡

The program allows users to select an encryption technique, then encrypt or decrypt text accordingly. 

### 🔑 Features:
- **Vigenère Cipher**: Encrypts text using a keyword with a Caesar shift for each letter.
- **Route Cipher**: Uses a grid-based encryption system, reading text in a defined path (e.g., spiral, zigzag).
- **Baconian Cipher**: A binary cipher that represents letters using "A"s and "B"s.
- **Morse Code Cipher**: Encodes and decodes messages in Morse code (dots and dashes).

### 🔧 Technologies Used:
- **C++**: Programming language used to implement the algorithms.
- **Standard Input/Output**: User interface for interacting with the program.

---

## 💡 Cipher Techniques

### 1️⃣ **Vigenère Cipher** 🛡️

The **Vigenère cipher** is a method of encrypting alphabetic text by using a keyword. Each letter in the plaintext is shifted according to the corresponding letter in the keyword.

#### Example Code:

```cpp
// Vigenère Cipher Encryption Function
// Example Usage
std::string text = "HELLO WORLD";
std::string key = "KEY";
std::cout << vigenereEncrypt(text, key);  // Output: "RIJVS UYVJN"
```

#### Output:
```text
Encrypted Text: RIJVS UYVJN
```

---

### 2️⃣ **Route Cipher** 🔄

The **Route cipher** encrypts text by writing it in a grid, then reading the text in a defined pattern (such as a spiral).

#### Example Code:

```cpp
// Route Cipher Encryption Function (3x3 grid)
// Example Usage
std::string text = "HELLOISW";
std::cout << routeCipherEncrypt(text);  // Output: "HELOISW"
```

#### Output:
```text
Encrypted Text: HELLOISW
```

---

### 3️⃣ **Baconian Cipher** 🅰️🅱️

The **Baconian cipher** is a binary cipher where each letter of the alphabet is represented by a sequence of five "A"s and "B"s.

#### Example Code:

```cpp
// Baconian Cipher Encryption Function
// Example Usage
std::string text = "HELLO";
std::cout << baconianEncrypt(text);  // Output: "ABBAA ABBAA ABABA ABBAA AABAA"
```

#### Output:
```text
Encrypted Text: ABBAA ABBAA ABABA ABBAA AABAA
```

---

### 4️⃣ **Morse Code Cipher** 📡

The **Morse Code Cipher** encodes text using Morse code symbols (dots and dashes).

#### Example Code:

```cpp
// Morse Code Encryption Function
// Example Usage
std::string text = "HELLO";
std::cout << morseCodeEncrypt(text);  // Output: ".... . .-.. .-.. ---"
```

#### Output:
```text
Encrypted Text: .... . .-.. .-.. ---
```

---
