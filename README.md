# Ceaser-Cipher
![caesarpicture](https://user-images.githubusercontent.com/41043701/131649886-81bc3de6-e454-4209-81b4-5ad0c2f0c0f5.png)

### Problem Statement:

An encrypter based on the ceaser cipher  in python. It is a substitution cipher where each character of the original text is shifted a certain number characters in the alphabet. This is a function that would require 2 arguments – the input text to be encrypted and a key. For eg: Given the input text ‘hello’ and the key 3, the resulting encryted text would be ‘khoor’. Here you can see that every character in the string hello is shifted by 3 characters. ‘h’ has shifted to ‘k’, ‘e’ has shifted to ‘h’ and so on. If a key of 5 were used, the resulting string would be ‘mjqqt’. This function should be capable of ignoring any characters which are not alphabets. The character ‘z’ entered by the user for a key of 3 would result in ‘c’.

Usage:<br>
**encrypt(‘python!’, 4)**<br>
**‘tcxlsr!’**

Similarly create decrypter which can decode the encryted text when provided the input text and key

Usage:<br>
**decrypt(‘khoor zruog!’, 3)**<br>
**‘hello world!’**
