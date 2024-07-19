# PGP-KEYS

Repository for storing my PGP public key for secure communication through time and space.

## How to Use

1. **Download the Public Key**: You can download my public key from this repository (`public_key.asc`).
2. **Import the Public Key**: `gpg --import public_key.asc`
3. **Verify the Key**: Ensure that the key is correctly imported by listing your keys: `gpg --list-keys info@tech-architecti.com`
4. **Encrypt a Message**: Use my public key to encrypt messages: `gpg --encrypt --recipient info@tech-architecti.com file.txt`

## Contact

If you have any questions or need further assistance, please contact me at [info@tech-architecti.com](mailto:info@tech-architecti.com).
