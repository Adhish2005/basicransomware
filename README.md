# basicransomware

README 

Ransomware (Encryption and Decryption)

Motive? 
The motive was really to better understand python better (Since I was learning it in school), to get a little more hands on with ransomewares and how they work 
(This project was made after a lot of googling and rage.)

How does it work? 
Encryption:
When file encrypt.py is run, the program goes through all the files and directories within the directory in which the program was run. Using fernet module, all the file contents and directories get replaced with gibbrish alphabets and numbers. After this step, files can be concatenated but the contents will be encrypted. (When the program is run it displays all the files which have been encrypted)    

Decryption: 
To run the decryption you need to first have access to the password ("ittalenthunt"). After the password is correctly entered, the program decrypts all the gibbrish to the original format (i.e it is accesible and readable depending on the file type) 

Awards Won 
This project was presented in IT TALENT HUNT (2022-2023), a inter-house competition, and was awarded 1st Place.  

WARNING 
THE FOLLOWING CODE HASN'T BEEN TESTED IN A WINDOWS ENVIRONMENT. PLEASE TEST CODE IN A VIRTUAL ENVIRONMENT 

  
