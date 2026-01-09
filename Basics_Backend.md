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
that means its simple but not secure 

and Asymmetric uses different key for encryptiom and decryption 
more complex means more secure 

there is another types of standard encryption like hashing algorithm

since our backend needs to control how many request you can sent to the server 

# Rate Limiting 
Rate limiting is a technique to control the frequency 
of requests to a network server or API  to protect DDos attack 

# what is DDos attack

is cyper attack while the hackers sends massive amount of 
fake internet request that traffic may couse server to shutdown or goes slow 
using sometimes bots 

since caching is more important for JWT and other uses for your websites

# what is caching strategy 

that means caching strategy is set of rules for managing temporary 
high speed storage called cache 
why?
to quickly serve frequency of requested data taking out the load you are giving the database 
so you should improve the applications speed and scability 


# cookies vs JWT vs sessions vs httpscookies

cookies are generally client side storage machanism means 
it concerns frontend while sessions and JWT are authenticated methods that
can use cookies as transport 

### cookies and httpscookies 

are browser concern so its client side 
cookies are for small data like 4kb server doesnot look up and 
dont tracks every cookies data and its also accessed by client side javascript 

while httpscookies special for session ID 
so server most look up always for session ID and cannot accessed by javascript clientside 


### session and JWT 

server side for database memory while JWT is client side often in cookies and local storage 
user uses jwt for claiming data self contained signed 
while session is for extensive user data 

server verifies jwt tokens so sessions needs server management system

sessions is server side authenticated method when user login server created sessions and 
gives the browser a unique session ID typically stored im cookies 

so when browser needs data from server the server validates the session ID
server needs to store active users according to thier session ID 

