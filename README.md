# DES
This repository has an implementation of DES encryption. It was created as part of a homework assignment in CSEC.362.01 - Crypto & Authentication.
Below is the description of the assignment.

DES program consists of several classes: 

1. DES_Simultion
   - Main simulation engine
   - Completed (do not modify)
   
2. Conversion
   - Provides utility functions for conversion between a string 
     of characters and a binary string
   - Not part of DES
   - Completed (do not modify)

3. DES
   - Includes encryption and decryption algorithms
   - Completed (do not modify)


3. IP
   - Initial permutation
   - Completed (do not modify)

4. FeisteNetwork
   - Consists of 16 rounds. 
   - This class includes the f-function with four steps: Expansion, Xor, S-box substitution, Permutation 
   - To be completed


5. IPinverse
   - Final permutation, inverse of the initial permutation
   - To be completed  

6. KeySchedule
  - Includes key scheduling algorithms for both encryption and decryption
  - To be completed

7. To run the DES_Simulation class, provide two command line arguments 
   for a file name for plaintext and another file name for the key
   To run, type “java DES_Simulation input.txt key.txt”
   
   With the given txt files, your program output must be:

ciphertext: 0011011101110111100110111110011011101010000011011001110011111000
Success
recoverted Text: 
Hi World


8. .txt files are included:
   - The plaintext.txt file contains exactly 8 characters which fit in a block of 64 bits. 
   - The key.txt file contains a key of 64 bits.
   - You may choose different plaintext and keys.

