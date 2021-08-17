# Ssssh.....

### Substitution Cipher:
>In cryptography, a substitution cipher is a method of encrypting in which units of plaintext are replaced with ciphertext, according to a fixed system; the "units" may be single letters (the most common), pairs of letters, triplets of letters, mixtures of the above, and so forth.

#### ONE-TIME PAD SUBSTITUTION CIPHER:
One-time pad cipher is a type of Vignere cipher which includes the following features −

• It is an unbreakable cipher.

• The key is exactly same as the length of message which is encrypted.

• The key is made up of random symbols.

• As the name suggests, key is used one time only and never used again for any other message to be encrypted.

Due to this, encrypted message will be vulnerable to attack for a cryptanalyst. The key used for a one-time pad cipher is called pad, as it is printed on pads of paper.

#### Encryption
To encrypt a letter, a user needs to write a key underneath the plaintext. The plaintext letter is placed on the top and the key letter on the left. The cross section achieved between two letters is the plain text.
#### Decryption
To decrypt a letter, user takes the key letter on the left and finds cipher text letter in that row. The plain text letter is placed at the top of the column where the user can find the cipher text letter.

### Transposition Cipher: 
>In cryptography, a transposition cipher is a method of encryption by which the positions held by units of plaintext (which are commonly characters or groups of characters) are shifted according to a regular system, so that the ciphertext constitutes a permutation of the plaintext. 

#### RAIL – FENCE CIPHER: 
Given a plain-text message and a numeric key, cipher/de-cipher the given text using Rail Fence algorithm. The rail fence cipher (also called a zigzag cipher) is a form of transposition cipher. It derives its name from the way in which it is encoded.

#### Encryption 
In a transposition cipher, the order of the alphabets is re-arranged to obtain the cipher-text. 

• In the rail fence cipher, the plain-text is written downwards and diagonally on successive rails of an imaginary fence. 

• When we reach the bottom rail, we traverse upwards moving diagonally, after reaching the top rail, the direction is changed again. Thus the alphabets of the message are written in a zig-zag manner. 

• After each alphabet has been written, the individual rows are combined to obtain the cipher-text.
