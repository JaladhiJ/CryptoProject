# CryptoProject
# Learnerspace project
Problem statement: Script to input a Vigenère-encrypted ciphertext and print the plaintext and key
For part 1 of the project just type python3 project1.py in the terminal and then input the encrypted text.
# 
Problem statement: Write a script called sign.py that takes in a the name of a text file as input and prints out the digital signature of that file as follows:
It must first get the SHA-256 hash of the file (as bytes).
Then it must create a random semiprime N to be used in the RSA digital signature.
Then it signs the hash using RSA digital signature with N above and e = 65537.
Finally, it returns (N, e) as a tuple and the the signature (in hex)
Create a separate script called verifier.py that takes in tha name of a text file, N, e, and a signature in hex and verifies the digital signature of the contents of the text file and returns accept or reject depending on whether the signature is valid or not.

For part 2 of the project type python3 sign.py <file_name> and then python3 verifier.py <file_name> < N > < e > <signature_hex> where N,e and signature_hex u will get from the output of the first command
