# Data Integrity Using SHA-256 and Secure Key Exchange Using Diffie-Hellman Protocol
# AIM
To create a Python program that utilizes the SHA-256 hashing algorithm for ensuring data integrity in network communications and implements the Diffie-Hellman key exchange protocol to securely establish and evaluate exchanged keys.
# EQUIPMENTS REQUIRED
●	Computer/Laptop
●	Python 3.x
●	Python IDE (IDLE, VS Code, PyCharm, or Jupyter Notebook)
●	Internet connection (optional)
# PROCEDURE
# Part A: SHA-256 Hashing for Data Integrity
1.	Open the Python IDE.
2.	Import the hashlib module.
3.	Enter a message to represent the data being transmitted through a network.
4.	Generate the SHA-256 hash value of the original message.
5.	Modify the message to simulate data alteration during transmission.
6.	Generate the SHA-256 hash value of the modified message.
7.	Compare both hash values.
8.	If the hash values are the same, the data integrity is preserved.
9.	If the hash values are different, the data has been modified.

# Part B: Diffie-Hellman Key Exchange
1.	Select a public prime number p and a generator g.
2.	Generate private keys for two communicating users, Alice and Bob.
3.	Calculate the public key of Alice using:
A = gᵃ mod p
4.	Calculate the public key of Bob using:
B = gᵇ mod p
5.	Exchange the public keys between Alice and Bob.
6.	Alice calculates the shared secret using:
K₁ = Bᵃ mod p
7.	Bob calculates the shared secret using:
K₂ = Aᵇ mod p
8.	Compare the two generated shared secret keys.
9.	If both keys are equal, the Diffie-Hellman key exchange is successful.
# PYTHON PROGRAM


# OUTPUT : 
 
# RESULT
Thus, a Python program was successfully created and executed to verify data integrity using the SHA-256 hashing algorithm and to establish a shared secret key using the Diffie-Hellman key exchange protocol. 

