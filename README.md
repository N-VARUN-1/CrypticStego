# CrypticStego

CrypticStego is a cryptographic steganography tool developed in C++ that allows users to securely encrypt and embed vital information in text form into the pixels of an image. It achieves this without visibly altering the image or the embedded information, ensuring confidentiality and integrity of hidden data.

## Features

- Encrypt sensitive text data using strong cryptographic methods.
- Embed encrypted data into image pixels with minimal or no visible changes.
- Extract and decrypt the hidden information securely.
- Command-line interface (CLI) based tool for easy integration and automation.
- Uses CMake for build management and argparse for command-line argument parsing.

## Technologies Used

- **Programming Language:** C++
- **Build System:** CMake
- **CLI Parsing:** Argparse (or similar alternative for argument parsing in C++)
- **Encryption Library:** Crypto++ (or your chosen cryptographic library)
- **Image Processing:** OpenCV (or your image processing library)

## Getting Started

### Prerequisites

- C++ compiler (supporting C++11 or higher)
- CMake version 3.10 or higher
- OpenCV installed on your system
- Crypto++ library installed

### Build Instructions

1. Clone the repository:
