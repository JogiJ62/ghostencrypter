# ghostencrypter
This is a simple Python script that encrypts passwords using various hashing algorithms.

## Features

- Encrypts passwords using specified hashing algorithms.
- Supports a range of hashing algorithms available in the Python hashlib library.
- Provides a help option to list available hashing algorithms.

## Usage

To use this tool, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/ghostvirus62/ghostencrypter.git
    ```

2. Navigate to the directory:

    ```bash
    cd ghostencrypter
    ```

3. Run the script with the password and optional algorithm:

    ```bash
    python ghostencrypter.py <password> [algorithm]
    ```

    If the algorithm is not provided, SHA-256 will be used by default.

    Example:

    ```bash
    python ghostencrypter.py mypassword sha256
    ```

4. Optionally, use the `-h` or `--help` option to list available hashing algorithms:

    ```bash
    python ghostencrypter.py --help
    ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
