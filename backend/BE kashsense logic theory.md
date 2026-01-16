the backend recieves expense detials from the frontend like category , amount , date and description 
BE validates for example it checks if the category exists in the app and others 
it saves the expense into the database returns response like successfull into the frontend 

- editing backend recieves expense id from the FE checks if it exists takes the updated then validate the updated data then save to the database 
- when deleting ackend recieves expense id from the FE checks if it exists removes the database where the id equals the id got from the FE
- when viewing backend should fetch all the list of expense from the database 

backend should authenticate the login and stores the tokens of JWT so user doesnt login  everytime 
