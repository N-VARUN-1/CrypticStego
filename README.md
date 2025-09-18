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
```
git clone https://github.com/yourusername/CrypticStego.git
cd CrypticStego
```
2. Create a build directory and navigate into it:
```
mkdir build
cd build
```
3. Generate build files using CMake:
```
cmake ..
```
4. Build the project:
```
cmake --build .
```

5. After successful build, the executable `CrypticStego` will be available in the build directory.

### Usage

Run the executable from the command line with required arguments. For example:
```
./CrypticStego --embed --input_image path/to/image.png --output_image path/to/output.png --message "Secret text"
```
or
```
./CrypticStego --extract --input_image path/to/output.png
```
Use `--help` to see all available command-line options:
```
./CrypticStego --help
```

## Contributing

Contributions are welcome! Feel free to submit issues, fork the repository, and send pull requests.

## License

Specify your license here (e.g., MIT License).

## Author

Your Name — [Github/NVarun](https://github.com/N-VARUN-1)


