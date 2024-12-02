# PRODIGY_CS_01
Caesar Cipher Implementation for Task-01

This program implements the Caesar Cipher, a simple encryption technique where each letter in a message is shifted by a fixed number of positions in the alphabet. It allows users to both encrypt and decrypt messages using a shift value provided by the user.

Features:
Encrypt Messages: Converts plaintext into ciphertext by shifting each letter forward in the alphabet.
Decrypt Messages: Converts ciphertext back to plaintext using the same shift value used for encryption.
Customizable Shift: Users can specify the number of positions to shift.
Handles Non-Alphabet Characters: Numbers, punctuation, and spaces remain unchanged.
Interactive: Allows users to perform multiple encryptions or decryptions until they choose to exit.
How It Works:
Encryption: For each letter in the plaintext, its position in the alphabet is shifted forward by the shift value. If the shift goes beyond 'z', it wraps back to 'a'.
Decryption: For each letter in the ciphertext, its position is shifted backward by the shift value. If the shift goes before 'a', it wraps to 'z'.
Example:
Encrypting the message "hello" with a shift of 3 results in "khoor".
Decrypting the message "khoor" with the same shift restores the original message "hello".
This program is a practical implementation of a classic cryptographic method, demonstrating basic principles of encryption and decryption.
