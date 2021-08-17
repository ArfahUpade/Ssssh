# Ssssh.....

Project developed in FH2020 for an experiment that had to be performed for Security Lab.

**Experiment 2: Design & implementation of a product cipher using substitution and transposition Ciphers.**
<br>
<p align="center">
  
<!--   <video width="660" alt="1" src="https://user-images.githubusercontent.com/56472876/129677920-c799e690-bccf-4eb0-a34f-100ce1836319.mp4"> -->
  
https://user-images.githubusercontent.com/56472876/129677920-c799e690-bccf-4eb0-a34f-100ce1836319.mp4

</p>

</br>

## Introduction
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

## Project Images:

### Landing Page:

<p align="center">
<img width="660" alt="1" src="https://user-images.githubusercontent.com/56472876/129669828-cc7ee2b0-be5d-4178-86e5-182f50f87176.PNG">

<img width="660" alt="2" src="https://user-images.githubusercontent.com/56472876/129669847-2b4a773f-40a9-4172-9183-a787eda4f2a8.PNG">

<img width="660" alt="3" src="https://user-images.githubusercontent.com/56472876/129669860-392e8938-7cff-4536-a9bf-7fb19b90398b.PNG">

<img width="660" alt="4" src="https://user-images.githubusercontent.com/56472876/129669865-12fb0428-77b9-443b-9a1c-a586eb4e930e.PNG">
</p>

### Encryption:
<p align="center">
<img width="660" alt="5" src="https://user-images.githubusercontent.com/56472876/129669873-25c00d88-1ab1-4706-8f6c-0ce224a1a739.PNG">

<img width="660" alt="6" src="https://user-images.githubusercontent.com/56472876/129669885-2fb5083b-fbc0-4e4f-bf9c-43f59c7aa8f1.PNG">
</p>

### Decryption:
<p align="center">
<img width="660" alt="7" src="https://user-images.githubusercontent.com/56472876/129669892-933d7e9d-3711-43ec-a0d5-da6405b3cd88.PNG">

</p>

> QOUTES ABOVE (e.g by John Von Neumann) KEEP ON CHANGING FOR EACH MESSAGE.

<p align="center">
<img width="660" alt="8" src="https://user-images.githubusercontent.com/56472876/129669904-22739eac-2cb2-44a5-8184-7169ccdbd9a5.PNG">

<img width="660" alt="9" src="https://user-images.githubusercontent.com/56472876/129669911-6973f1ac-f0e9-4f2e-bdca-ff9e48d35a4d.PNG">
</p>

### If user tries to refresh:
<p align="center">
<img width="660" alt="10" src="https://user-images.githubusercontent.com/56472876/129669916-804c4821-73f3-4daa-ab10-78bacb85f2e2.PNG">
</p>

## TOOLS USED:

1. PYTHON – For Product Cipher (Encryption and Decryption)
2. FLASK – Sever-side
3. HTML, CSS, JS – For front-end
