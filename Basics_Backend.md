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