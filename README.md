🔐 Diffie-Hellman Key Exchange (Java)

    This project demonstrates the Diffie-Hellman Key Exchange Algorithm implemented in Java. It allows two parties to securely generate a shared secret key over an insecure communication channel without directly transmitting the key.
📌 Features

    Accepts user-defined prime number (p) and primitive root (g)

    Generates private and public keys for two users (A and B)

    Computes shared secret keys for both parties

    Verifies that both computed shared keys are identical

🧠 Concepts Used

    Modular Exponentiation

    BigInteger operations for handling large values securely

    Public Key Cryptography principles

📥 Input Required

    A prime number p

    A primitive root g modulo p

    Private keys for users A and B (less than p)

✅ Output

    Public keys of A and B

    Shared secret keys computed by both parties

    Validation of the shared key agreement

🧪 Example Use Case

    Used as a foundational step in secure communication protocols such as TLS, SSH, and VPNs where symmetric keys are generated from public-private exchanges.
⚠️ Disclaimer

    This project is for educational purposes only. It does not implement any cryptographic security features such as protection against man-in-the-middle attacks, secure key storage, or encryption. Do not use this implementation in production systems.
📄 License

    This project is licensed under the MIT License. You are free to use, modify, and distribute it with appropriate attribution.
👩‍💻 Author

    Neha Biju(https://github.com/Neha-Biju)
   
