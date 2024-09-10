# Salsa20 Algorithm
The Salsa20 algorithm is a symmetric stream cipher designed to provide high security and performance. It operates on variable-length input data and produces ciphertext of the same length as the plaintext.

# Example usage
key = b"this_is_a_32_byte_key_for_salsa!"

nonce = b"nonce123"

plaintext = b"Hello, Salsa20!"

# Encrypt the plaintext
encrypted = encrypt(plaintext, key, nonce)

# Decrypt the ciphertext
decrypted = decrypt(encrypted, key, nonce)

# Result
Encrypted: 0109fc750bc2b016264d845aedb744

Decrypted: Hello, Salsa20!

# Compare Salsa20 to RC4

Salsa20 Generation Time: 5.387058973312378 seconds

RC4 Generation Time: 0.0003523826599121094 seconds

# DES Algorithm
DES, short for Data Encryption Standard, is a block cipher encryption algorithm developed by IBM in the 1970s and later recognized as an official encryption standard by the U.S. government in 1977. DES has been widely used in cryptographic applications for many years but has since been replaced by stronger encryption algorithms such as AES (Advanced Encryption Standard).

# Example
No.1

plaintext = 0x0123456789ABCDEF

key = 0x133457799BBCDFF1

No.2

key_des = b"mysecret"

plaintext = b"Hello, DES!"

# Result

No.1

Encrypted Text (DES): 85e813540f0ab405

Decrypted Text (DES) (hex): 0123456789abcdef

No.2

Encrypted Text (DES): b'\x90\xe3\x9d\x8de\xf1\xaa\xe6\xd5lo\xbb\xf7\xc68\xcf'

Encrypted Text (DES-hex): 90e39d8d65f1aae6d56c6fbbf7c638cf

Decrypted Text (DES): Hello, DES!


# Compare DES to RC4
Case 1:
Time taken for DES encryption: 0.001227 seconds

Time taken for RC4 encryption: 0.000046 seconds

Case 2:
Time taken for DES encryption: 0.000088 seconds

Time taken for RC4 encryption: 0.000043 seconds

Case 3:
Time taken for DES encryption: 0.000096 seconds

Time taken for RC4 encryption: 0.000045 seconds

Case 4:
Time taken for DES encryption: 0.000054 seconds

Time taken for RC4 encryption: 0.000035 seconds

Binary Data:
Time taken for DES encryption: 0.000157 seconds

Time taken for RC4 encryption: 0.000043 seconds

Numeric Data:
Time taken for DES encryption: 0.000127 seconds

Time taken for RC4 encryption: 0.000034 seconds

Repeated Character:
Time taken for DES encryption: 0.000120 seconds

Time taken for RC4 encryption: 0.000036 seconds

Mixed Data:
Time taken for DES encryption: 0.000134 seconds

Time taken for RC4 encryption: 0.000036 seconds

# Source Code
[Code](https://colab.research.google.com/drive/148CgeQQzID6h9XUVg9Igz2wtqXeK6Hin#scrollTo=wnQ-cZVr-4pb)
https://colab.research.google.com/drive/148CgeQQzID6h9XUVg9Igz2wtqXeK6Hin#scrollTo=wnQ-cZVr-4pb

# Github
https://github.com/DucBox/CyberSecurity
