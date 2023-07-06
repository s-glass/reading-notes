# 401 class 18 notes

**Why this matters**: This information matters because encryption protects important, private, or sensitive data, and makes communication on the internet or through computers more sercure.

------------------------------------

**1. What is the basic principle behind the Caesar Cipher, and how was it used historically?**

It was historically used by Julius Caesar more than 2,000 years ago to communicate messages to his allies.

The basic principle is that the Caesar Cipher is a simple substitution cipher which replaces each original letter with a different letter in the alphabet by shifting the alphabet by a certain amount.

[Source](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security/xcae6f4a7ff015e7d:data-encryption-techniques/a/encryption-decryption-and-code-cracking)

**2. What are the key differences between symmetric and asymmetric encryption? How is asymmetric used in secure communication today?**

Symmetric encryption uses a single key to encrypt a message and then decrypt that message upon delivery. Asymmetric enncryption uses two different keys for encryption and decryption. 

Asymmetric encryption is used in sending email files, connecting to servers, electronically signing PDF documents, and with secure URLs - https://

[Source](https://thebestvpn.com/cryptography/)

**3. How do computers generate random numbers, and what are the differences between true random number generation (TRNG) and pseudo-random number generation (PRNG)? Discuss their use cases in cryptography.**

Computers can generate random numbers through two methods: TRNG and PRNG. 

To generate a true random number, the computer measures some type of physical phenomenon that takes place outside of the computer, for example atmospheric noise or radioactive decay. TRNGs are suitable for applications where high-quality randomness is critical to security, such as generating encryption keys, initialization vectors, or nonce values.

To create pseudorandom numbers, a computer could use a seed value and an algorithm to generate numbers that appear to be random, but that are in fact predictable. In this case, the computer doesn’t gather any random data from the environment. PRNGs are used when true randomness is not strictly required, such as in simulations, gaming, or statistical analysis.

[Source](https://www.cryptomathic.com/news-events/blog/the-role-of-random-number-generators-in-cryptography)

[Source](https://www.howtogeek.com/183051/htg-explains-how-computers-generate-random-numbers/)

**4. What’s the difference between encryption and decryption? Explain with an analogy.**

Encryption is the process of converting normal message (plaintext) into meaningless message (Ciphertext). Whereas Decryption is the process of converting meaningless message (Ciphertext) into its original form (Plaintext).

An analagy of this could be that encryption is taking a stack of folded laundry and unfolding each piece and placing the unfolded pieces in a set, but secret order. Whereas decryption is the process of converting a the set of unfolded clothes into a re-ordered stack of folded laundry.

[Source](https://www.geeksforgeeks.org/difference-between-encryption-and-decryption/)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!