# EChat

### A Public Repo of the EncryptedChat Repository contains the executables of the different versions of the program as well as documentation.

### This is a closed source project at this moment, only executables and documentation will be published in this repository.


### Its a SECURE messaging service:
  - allows people to text over the internet without identifying themselves by phone numbers or email or anything.
  - the person to who the message is sent is the ONLY one who can decrypt the message, so the only one who can read the text.
  - no data is stored on the server.


### Username Criteria:
- Only contains characters, underscore, and dot.
- Underscore and dot can't be at the end or start of a username (e.g _username / username_ / .username / username.).
- Underscore and dot can't be next to each other (e.g user_.name).
- Underscore or dot can't be used multiple times in a row (e.g user__name / user..name).

## The project is still under development, the server is being rebuilt for better scalability.

```
Versions Older Than 1.2.9.0 are now rejected by the official server.
```


![Channels-end-to-end-encryption (2)](https://user-images.githubusercontent.com/81851926/164936524-b3ee5827-7ee2-49a3-bf5d-cebae88d670d.jpg)



## VERSION 1.2.9.1

- Introducing New Lines in messages:
  
  + The user can SHIFT + ENTER to add a line in their message
  
    ![image](https://user-images.githubusercontent.com/81851926/162732581-2292ca78-f953-4ce5-9a97-f109207c3446.png)
    
    
    ![image](https://user-images.githubusercontent.com/81851926/162732904-6e65e4b5-419d-436d-b51e-678cf0a23242.png)





## VERSION 1.2.9.0

- Introducing Banning Users:
  
  + The server can ban users in case of misbehavior

   ![image](https://user-images.githubusercontent.com/81851926/162729580-f64a00e9-7bd2-4587-84b5-63a7a28a282e.png)
  
  
  
  + the banned user cannot send or receive any more messages

   ![image](https://user-images.githubusercontent.com/81851926/162729864-aa19135a-cdf2-4c62-82e3-67915799628d.png)


   ![image](https://user-images.githubusercontent.com/81851926/162730171-2dd868ea-a657-4072-8dde-dd4ce8d759c6.png)



- the change user button is disabled as it crashes the app
  
  ![image](https://user-images.githubusercontent.com/81851926/162730610-548de8a5-4e73-4826-a35c-aee8f0fdf6c0.png)





## VERSION 1.2.8

 - login and register:
  	+ now they are two separate frames
  	+ press "I want to register/ I want to login" to switch between the frames
  	
  + Login:

    ![image](https://user-images.githubusercontent.com/81851926/157271247-6acc44d7-91dc-4f82-a4a4-4696c4d9fc41.png)



  + Register (Disabled in this version) :

    ![image](https://user-images.githubusercontent.com/81851926/157271118-3a11326c-019b-4ac2-92ea-cb7326fb8ff8.png)



  	+ tab works to switch between the options  
    
    ![image](https://user-images.githubusercontent.com/81851926/157271643-01119b5e-7fe0-4d47-8efe-b5a500ed707e.png)



  	+ pressing enter when in the textField now will try to login
    
    ![image](https://user-images.githubusercontent.com/81851926/157272032-f49ad272-c5d9-4e96-b77e-f62a20cf4348.png)

    
    
  	+ "localhost:34000" is the default when the link textField is left empty

    ![image](https://user-images.githubusercontent.com/81851926/157272660-fdd87d55-79a4-4d26-895f-afa7da2a5121.png)



  	+ in case of the server is not found or offline a JOptionPane will pop up saying "Server Offline" and  asking if you wanna close the app or try another link or maybe wait a bit
    
    ![image](https://user-images.githubusercontent.com/81851926/157272975-7fa4074d-6c54-44ee-b709-6858cf6dfa1a.png)


    
  	+ pressing x on the login now will close the program

    ![image](https://user-images.githubusercontent.com/81851926/157273409-c9b985bc-ce80-45a5-9899-d9ff24b2d78e.png)



 - Added a button in the setting to reRandomize the colors.
 - improved Color generation.

  before randomizing:
  
  ![image](https://user-images.githubusercontent.com/81851926/157273905-352c57c1-9628-43cb-bdfe-214498a214a0.png)



  randomizing:
  
  ![image](https://user-images.githubusercontent.com/81851926/157274460-fe467205-b956-4a56-8ee0-88e0504211c2.png)


  ![image](https://user-images.githubusercontent.com/81851926/157274538-2a8e560d-616e-4d82-ab4a-ebb11108458f.png)



  after randomizing:
  
  ![image](https://user-images.githubusercontent.com/81851926/157275296-90353440-643d-45cd-a5c8-b88645464183.png)



 - when a user gets kicked the message "USER Was Kicked From The Chat" is displayed

  ![image](https://user-images.githubusercontent.com/81851926/157275788-3c43785a-bed7-4c7b-97f1-4810e42c237a.png)



 - Fixed AutoReconnect.

 - The "change user" feature is in working progress, does not work, and crashes the app.

 - improved security



## VERSION 1.2.7

- Fixed some visuals, like Icons, and some resizing and alignments.

![image](https://user-images.githubusercontent.com/81851926/155596402-7313006f-b1d9-4c4e-a5f2-c9be88db4986.png)



- Added Settings Frame, right now it only contains (ABOUT) like version author name and my email.

![image](https://user-images.githubusercontent.com/81851926/155596849-0b259cb2-adbc-4c51-832c-c9951ff376ff.png)





## VERSION 1.2.6

- A "$ Private message From " text will be displayed before any private message

![image](https://user-images.githubusercontent.com/81851926/153710010-9723d390-4c36-4bcc-9dc3-82053c298fee.png)



- A "MESSAGE NOT SENT =>" text will be displayed if the message wasn't sent.

![image](https://user-images.githubusercontent.com/81851926/153710118-1b91a456-b42a-4606-9c30-85358d1ce8fb.png)





## VERSION 1.2.5

- Introducing Private Messaging:
  we can send private messages to the user we want as long as we see their name on the left (Online), so we just have to click on the person's name and type a message.

![image](https://user-images.githubusercontent.com/81851926/153709793-82daea5e-9369-4d20-97c1-eb863b4c05ed.png)


![image](https://user-images.githubusercontent.com/81851926/153709872-b369c834-ad30-431f-9b6c-fee55db44ecc.png)


![image](https://user-images.githubusercontent.com/81851926/153709885-a36ec0fa-520d-4367-adbb-fb726be90ff0.png)



- fixed reconnecting problems

- client tries to reconnect automatically after disconnection or when sending messages when offline.

- other minor bugs.


- reconnecting color is blue.

![image](https://user-images.githubusercontent.com/81851926/153709650-e79b2281-c2ab-43d4-afa4-b628c73d92f7.png)





## VERSION 1.2.4

- Added Reconnect Button in the top right so the user can simply reconnect instead of closing and reopening the application

![image](https://user-images.githubusercontent.com/81851926/153709540-1a0fca9f-cdb4-40ac-8749-635435762ec4.png)





## VERSION 1.2.3

- The setup frame has disabled objects to make it easier to use the working slots only

![image](https://user-images.githubusercontent.com/81851926/153709453-df87d6ea-6b7f-4792-adad-13ccc72b0f16.png)





## VERSION 1.2.2

- we have a setup frame where we can enter our details like Username password..., so we can log in or register (Registration is disabled at this point).

- You only need a username and a hotlink to connect.

![image](https://user-images.githubusercontent.com/81851926/153709294-e1330728-f50b-4f14-aff7-949aa0f2b74d.png)



- after clicking connect the setup frame closes and the mainframe is active and we gave a green light on the top right indicating the server is online

![image](https://user-images.githubusercontent.com/81851926/153709341-27c53b31-b7f6-4a57-aae8-f6620b144f7b.png)



- the scroll panel is now fixed it automatically goes to the bottom to display new messages

- some other fixes...


## VERSION 1.2.1

- Minor Bug Fixes



## VERSION 1.2.0

- no private chats YET

- messages are color-coded

![image](https://user-images.githubusercontent.com/81851926/153709928-59448d65-b3a5-49bb-be40-40f5ac7bdfd9.png)



GUI:

![image](https://user-images.githubusercontent.com/81851926/153705282-adf37fe0-d233-4c8d-a901-f2ac11e4be22.png)



If the user disconnects from the server or the server Goes Offline:

![image](https://user-images.githubusercontent.com/81851926/153705334-aeb34275-cad4-41d7-b01c-16f90c1689ce.png)





## VERSION 1.1.2
- unstable version.

GUI:

![image](https://user-images.githubusercontent.com/81851926/153704783-18637ad9-f43b-40a6-aa1a-69f2df9a3a0c.png)


![image](https://user-images.githubusercontent.com/81851926/153705056-f8764c76-a584-4c94-8547-fb309fa06a40.png)



If the user disconnects from the server or the server Goes Offline:

![image](https://user-images.githubusercontent.com/81851926/153705091-78518ca8-5fef-45ce-9e96-db362da0df78.png)
