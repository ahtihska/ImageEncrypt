# ImageEncrypt

Java project that helps in encrypting and decrypting image using AES algorithm

# About the Project

The main use of computer is to store data and send it from one location to other. The information that is shared must be transferred in a secured manner. To ensure secured transmission of information, data is encrypted to unreadable formats by an unauthorized person. To implement this system, we have used encryption algorithm based on AES that encrypted the image into unexpected rough pixel format and generate the key for future decryption.

# Explanation of the Algorithm 

- First we choose an image to encrypt or decrypt
- After choosing an image we read the image in bytes
- This bytes are stored in an Array called Data
- We convert the bytes using XOR to encrypt
- We XOR the data with the key that the user inputs
- And then we store the values in place of the previous value
- Hence, Our Image gets encrypted 
- Now to decrypt we use the same key, since the XOR of the stored value with the key will give us back the initial data

# Steps

1. Run the code and you'll be presented with this dialog box, and enter the key value here. Once you enter the key just click on "Open Image"
2. Now navigate to the image which you wish to encrypt and click "Open"
3. As you can see the code will run and starts encrypting the image automatically.
4. Once it's done encrypting it will show a confirmation telling it's done.
5. And here you can that the image is encrypted and therefore there is no preview of the image and you can't open it.
6. To decrypt the image we have to run the code and type the same key value which we gave for the particular image for encrypting it.
7. And once it's decrypted it will show you a confirmation and the image is now available.

![gif](https://cdn.discordapp.com/attachments/637326316487704630/901811014998298705/gif.gif)
