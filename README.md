# DES
This repository has an implementation of DES encryption.

Below is the description of the assignment.

DES program consists of several classes: 

1. DES_Simultion
   - Main simulation engine
   
2. Conversion
   - Provides utility functions for conversion between a string 
     of characters and a binary string
   - Not part of DES

3. DES
   - Includes encryption and decryption algorithms

3. IP
   - Initial permutation

4. FeisteNetwork
   - Consists of 16 rounds. 
   - This class includes the f-function with four steps: Expansion, Xor, S-box substitution, Permutation 


5. IPinverse
   - Final permutation, inverse of the initial permutation

6. KeySchedule
  - Includes key scheduling algorithms for both encryption and decryption

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

