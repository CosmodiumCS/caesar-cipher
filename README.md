# Caesar-Cipher
> Blue Cosmo

## Overview:
```
A python based caesar cipher program
can encrypt, decrypt, and bruteforce text files
```

## Requirements:
- python 3.8+

## Instructions:
> Run CaesarCipher Program
- Open directory in terminal or commandline
```bash
python3 caesar-cipher.py 
Enter File Name :
```
- Enter the file name or path of your file
```bash
Enter File Name : helloworld.txt
Choose an Option :                                                                                                      
1) Encrypt                                                                                                              
2) Decrypt                                                                                                              
3) Bruteforce                                                                                                           
4) Exit 
```
### Options
1. Encrypt
```
Enter File Name : helloworld.txt
Choose an Option :                                                                                                      
1) Encrypt                                                                                                              
2) Decrypt                                                                                                              
3) Bruteforce                                                                                                           
4) Exit 
1

Shift of :
```
- input shift key
- encrypts text file
```
Shift of : 5
Translating...
Success! Output Written to encrypted-caesar.txt
```

2. Decrypt
```
Enter File Name : helloworld.txt
Choose an Option :                                                                                                      
1) Encrypt                                                                                                              
2) Decrypt                                                                                                              
3) Bruteforce                                                                                                           
4) Exit 
2

Shift of :
```
- input shift key
- decrypts text file
```
Shift of : 5
Translating...
Success! Output Written to encrypted-caesar.txt
```

3. Bruteforce
```
Enter File Name : helloworld.txt
Choose an Option :                                                                                                      
1) Encrypt                                                                                                              
2) Decrypt                                                                                                              
3) Bruteforce                                                                                                           
4) Exit 
3

Choose an Option :
1) Bruteforce All shift Keys
2) Choose Range
```
- Option 1 - Bruteforce using all 26 keys
```
Choose an Option :
1) Bruteforce All shift Keys
2) Choose Range
1
Bruteforcing...
Success! Output Written to bruteforce-all-keys.txt
```
- Option 2 - Choose a custom range of keys (Example: 10 - 20)
```
Choose an Option :
1) Bruteforce All shift Keys
2) Choose Range
2

Start Range : 10
End Range : 20
Bruteforcing...
Success! Output Written to bruteforce-range.txt
```
4. Exit
- exits program


## Output:
- "encrypted-caesar.txt"
	- output file for encrypted caesar text
- "decrypted-caesar.txt"
	- output file for decrypted caesar text
- "bruteforce-all-keys.txt"
	- output file for bruteforced caesar text
- "bruteforce-range.txt"
	- output file for bruteforced ceasar text [with a custom range]
