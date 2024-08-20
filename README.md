# Text Encryption Program using Unimodular Hill Cipher and AES

This Python program provides a secure method for text encryption by combining the Unimodular Hill Cipher (UHC) and Advanced Encryption Standard (AES) algorithms. It is designed to offer robust encryption by leveraging the strengths of both these algorithms.

## Features

- **Unimodular Hill Cipher (UHC)**: This algorithm uses a unimodular matrix for encryption, ensuring complex transformations of text data, making it difficult to reverse without the correct key.

- **AES Encryption**: AES is a widely recognized encryption standard that provides strong security. When combined with UHC, it adds an additional layer of protection to the encrypted text.

- **Hybrid Encryption Process**: The program first encrypts the text using UHC, and the resulting data is then further encrypted using AES. This dual-layer encryption approach ensures high security.

- **Customizable Input**: The program generates an initial plaintext file called `original.txt`. You can modify the content of this file through the `create_original_text` function if needed.

- **Final Encrypted Output**: The encrypted text is saved in a file named `uhcAES_encrypted.txt`.

## Installation

To install the required dependencies, run the following command:

```bash
pip install pycryptodome matplotlib
```

## Usage

1. **Run the Program**:
    ```bash
    python main.py
    ```

2. The program will generate an `original.txt` file with the text to be encrypted. You can modify the text in this file or adjust the `create_original_text` function if necessary.

3. After running the program, the final encrypted output will be saved in `uhcAES_encrypted.txt`.

## File Structure

- **original.txt**: The initial plaintext file generated by the program.
- **uhcAES_encrypted.txt**: The file containing the final encrypted text.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an Issue or submit a Pull Request.
