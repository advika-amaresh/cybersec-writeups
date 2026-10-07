# Binary Digits

**Category:** Forensics

**Difficulty:** Easy


## Description

We are given a file - `digits.bin` filled with a bunch of 1's and 0's

## Solution

Upon downloading the file, I noticed that it was a  `.bin` file, that is commonly referred to as a binary file.

I displayed the contents of the file using command `cat digits.bin` in the terminal and got the below output. 

<img width="1321" height="276" alt="image" src="https://github.com/user-attachments/assets/c5b0f504-b945-42a3-be8f-c247aff92f18" />

Basically a huge series of binary digits

I then copy pasted this onto CyberChef to convert the binary input, and got the following.

<img width="1332" height="772" alt="image" src="https://github.com/user-attachments/assets/df582e09-9fe0-4ddb-805c-1f7c97c62507" />

There is "JFIF" in the output, which is a type of image file.

This leads us to the conclusion that an image is hidden or embedded inside that text

I then downloaded the output which gave me a `.dat` file, and I changed it to a `.jpg` file.

Opening the image file, I got the below photo.

<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/7f8d993d-bbae-4a5e-9838-a0b93c1e108c" />

This gives us the flag : `academy{h1dd3n_1n_th3_b1n4ry_75fdfb71}`
## Tools Used

* `terminal`
* `cyberchef`

