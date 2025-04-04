Set the username and password in the startup of the mongoDB container
Need to pass the environment variable values in the container. 
    env: 
      name
      value

Adding the access of the application using the external URL or public IP 

-----------
Deploy the changes 

We need to create config the secret as the database will take the reference. 

create config
create secret 
create database
deploy app

kubect apply -f "FileName" 