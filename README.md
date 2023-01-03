# CS-454-Reliability-and-Security-of-Computing-Systems

Prepare a message that could be any content as plain text.
1. With AES as the encryption / decryption algorithm, generate your own key.

  a) using ECB, CBC, CFB, OFB, and CTR modes to encrypt and decrypt your message.
  b) implement one mode by yourself (do not use related packages)
  c) introduce errors in you ciphertext. Perform the encryption and decryption with the 5 
      operation modes again. Check how many blocks the errors propagated in each mode. Discuss if 
      the propagations are as expected. 
      
  AES in Python: https://pycryptodome.readthedocs.io/en/latest/src/cipher/aes.html 
  
2. Use RSA to encrypt and decrypt the same message. Compare the time consumption with AES. (You may need to make the 
    message long enough to see the significant difference in time.)
