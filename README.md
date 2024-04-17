# Raspberry Pi LCD Book Reader with HD44780 and AI 📚🖥️

The Raspberry Pi LCD Book Reader is a minimalist e-book reader implemented on the hardware of a Raspberry Pi, leveraging the capabilities of the Hitachi HD44780 LCD controller. This project also integrates an embedded artificial intelligence (AI) model to generate books, providing a unique reading experience.

## Hardware 🛠️

The hardware foundation for this project is the Raspberry Pi, a credit-card sized computer with GPIO (General Purpose Input Output) capabilities, including I²C, SPI, and UART. The project interfaces with a display based on the Hitachi HD44780 LCD controller, a popular choice for character LCD displays in various consumer electronics devices.

## Software 💻

This e-book reader is developed in Python and offers a high-level interface to the LCD, facilitating easy application development. The software library supports both GPIO (parallel) and I²C modes, offering flexibility in connection setups.

## Features 🌟

- E-book reading on a minimalist LCD interface
- Embedded AI for generating books
- Support for both GPIO and I²C modes
- Easy-to-use Python interface

## Setup & Installation 🛠️

```bash
# Clone the repository
git clone https://github.com/cadavidf/BeeperBooks.git

# Navigate to the downloaded folder
cd BeeperBooks

# Install the required Python packages
pip install -r requirements.txt

# Run the application
python main.py

 ```

Usage 📘

Utilize this library to read from your collection of books by placing textual ebooks in the predefined folder, running the application, and using the dedicated controls to navigate through the pages. Additionally, you can use the built-in AI to generate new books based on the trained model and enjoy the creative outputs.

Contributing 🤝

Contributions to the Raspberry Pi LCD Book Reader library are welcome. Please refer to the CONTRIBUTING.md file for details.

License 📝

This project is licensed under the MIT License. See the LICENSE file for details.


