
# Caesar Cipher Encryption & Decryption Tool

This is a simple command-line Python tool to encode and decode messages using the Caesar Cipher, one of the classic encryption techniques.

## Features:
- Encode your message by shifting each letter forward in the alphabet.
- Decode a message by shifting the letters backward.
- Supports custom shift values.
- Handles special characters and retains their positions.

## How to Use:

1. Clone the repository:
   ```bash
   git clone https://github.com/fazalsandhi/python-caesar-cipher.git
   cd caesar-cipher-tool
   ```

2. Run the script:
   ```bash
   python main.py
   ```

3. Follow the instructions in the terminal to either encode or decode a message.

## Example:
```text
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello world
Type the shift number:
5
Here is the encoded result: mjqqt btwqi
```

## Files:
- **main.py**: Contains the logic for encoding and decoding messages using Caesar Cipher.
- **art.py**: Contains the ASCII art logo displayed at the start of the program.

## Future Improvements:
- Add support for both upper and lowercase letters.
- Implement a user interface for easier usage.
- Add tests to ensure the correctness of encoding/decoding.
