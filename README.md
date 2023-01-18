# PGP-Login-System
Replace a password with PGP encryption.

Concept: The web server sends a login page with just your username required. It then sends a page with your PGP Public Key encrypted (20 random characters) code, asking for you to decrypt and enter code. The server compares what you entered with the original code.

Pros: Can't be phished. Don't have to remember a password. Simple and easy, without being so easy it becomes mindless.
Cons: Get used to using PGP for decryption. More complex then a password.

Todo: Write PHP class.
