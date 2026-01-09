# Hashing and Salting 
hashing uses one way function to convert data 
into a unique fixed length 
while saltings adds unique string before hashing 
ensures same passwords produce different hashing 

let we say for example my password is 
- my123password 
then salt is being added for example "c6Fx67fht"

then combine it like this "my123passwordc6Fx67fht"

so now hashing comes and it becomes random strings 
like "h6gg75x.........."

so now both salt and hashing strings are stored 
so since the user needs to login for the same password 
System retrieves the user's salt, combines them ("my123passwordc6Fx67fht"), hashes it, and compares the new hash to the stored one. 
If they match, login succeeds. 


# Encryption Standards 

protocol used when protecting data from unauthorized access is what we call Encryption standard 
its used to encrypt data at rest and when its transit 
so with our its key for authentication data will be 
unreadable to anyone 

since worlds data is different from finance to health 
it needs different encryption standard and it uses set of algorithm named cipher 

### what is cipher ?
its mathmatical formula that converts data from plain text to unreadable text 

so to decipher the cipher you need the correct key and authorization 

depend on algorithm sometimes the cipher can get different security levels 

### symmetric and asymmetric 
this ciphers is the two main types of encryption standard

so symmetric uses same key for  encryption and dencryption 
so the keys that you wanna encrpt is same ley that you wanna dencrypt