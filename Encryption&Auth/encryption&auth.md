# Cryptography and Encryption:

Encryption is the process of converting a message or information into a cryptogram.

Encryption Algorithm: A program that enables coding and decoding of data. Key notion appears as the solution to overcome the fixed coding method which is easy to discover and difficult to change for every exchange. The key along with the algorithm generates a unique coding for the key owner.

Keys: Computer keys are simply numbers with a variable length in bits. Used by encryption algorithms to code and decode information. All key-based encryption methods can be circumvented. The most tedious method is trying all combinations to find the right one (brute force). Longer the key used, higher the computing means and time needed to find it.

Public Keys: Public key mechanisms use two keys to code data and two keys to decode data. Both ends of the communication channel have two keys: a private key known only to its owner, and a public key that can be disclosed. Only the public key needs to be exchanged between the two communication partners to encrypt and decrypt the information.

Symmetric Keys: Private key or symmetric encryption method uses one key to encrypt and decrypt information.

Symmetric Key Advantages: fast encryption and decryption.

Symmetric Key Inconveniences: different key for each communication pair, multiple users = multiple keys to manage. If the secret key is captured, access to all exchanged data. The more the key is used to encrypt large blocks of data, the more exposed the key becomes.

Asymmetric encryption, also known as public key cryptography, uses two different keys for encryption and decryption. One key, the public key, is used for encryption, and the other key, the private key, is used for decryption. This provides better security as the private key never needs to be shared and can be kept confidential.

Examples of asymmetric encryption algorithms include RSA, Elliptic Curve Cryptography (ECC), and Diffie-Hellman. These algorithms use mathematical functions to encrypt and decrypt data, making it more secure.

Encryption Algorithm Name and Comments: DES, IDEA, RC2, RC4, RC5, SKIPJACK, Blowfish, AES, etc.


## Authentication:

The process of verifying the identity of a person or device.
Methods: Password, smart card, biometrics, certificate-based, etc.




## Standards:

SKIP (Simple Key Management draft - IETF)
IPSec (Internet Protocol Security) - Uses a single public key
ISAKMP (IKE) - Uses Diffie-Hellman for key exchange

## Hashing Functions:

Used for creating and verifying digital signatures
Result of a calculation on the content of digital information
It's impossible to reconstruct the original information 
from the hash result

Unlike encryption, hash function is a one-way operation and information is lost during the process
It's unlikely to produce two different messages that have the same message digest (collisions)

Examples:
MD4 (Message Digest 4)
MD5 (Message Digest 5)
SHA (Secure Hash Algorithm)
Whirlpool


