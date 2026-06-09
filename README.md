# Caesar Cipher Tools

[![Python Version](https://img.shields.io/badge/python-3.6+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A lightweight and efficient command-line utility written in Python for encrypting and decrypting text using the classic Caesar Cipher algorithm. This tool provides a straightforward interface for basic cryptographic demonstrations, text obfuscation, and educational purposes.

## Features

- **Dual Modes:** Easily toggle between Encryption and Decryption modes.
- **Customizable Shift Key:** Supports user-defined shifting values to alter the cipher strength.
- **Case & Structure Preservation:** Maintains the original capitalization of characters while keeping spaces and special punctuation symbols intact during execution.
- **Clean CLI Interface:** Simple and interactive command-line prompts for a seamless user experience.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

To run this tool, you only need to have Python installed on your system:
- Python 3.6 or higher

### Installation

1. Clone the repository to your local machine:
```bash git clone [https://github.com/BenTimothyM/CaesarChiper-Tools.git](https://github.com/BenTimothyM/CaesarChiper-Tools.git)```

2. Navigate into the project directory:
```bash cd CaesarChiper-Tools```

## Usage

Run the main script using Python:
```bash python main.py```

### Example

**Encryption Mode:**

* **Input Text:** `Hello, World!`
* **Shift Key:** `3`
* **Output Ciphertext:** `Khoor, Zruog!`

**Decryption Mode:**

* **Input Text:** `Khoor, Zruog!`
* **Shift Key:** `3`
* **Output Plaintext:** `Hello, World!`

## Roadmap / Future Enhancements

* [ ] Add support for brute-force decryption (cracking without a key).
* [ ] Implement a graphical user interface (GUI).
* [ ] Support file input/output for bulk file encryption.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

```
