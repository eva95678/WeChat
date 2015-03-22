# WeChat
Steps to run the application:

1. Start the server: node server.js

2. Go to "http://localhost:3000/index.html"

The backend server has a list of user information. (These users have the following ChatIDs -- "1" or "2" or "3" or "4". The passwords for these ChatIDs are the same -- "123”;)



To test the one-to-one chat function:
  Firstly, login with ChatID “1” (Kyle). By default, Kyle has four contacts in his contact list: Kenny (ChatID “2”), Stan (ChatID “3”),Cartman (ChatID “4”) and S-P Group(ChatID “0”). And then, open a new tab and login with ChatID “2” (Kenny). By default, Kenny(ChatID “2”) has four contacts in his contact list: Kyle (ChatID “1”), Stan (ChatID “3”), Cartman (ChatID “4”) and S-P Group(ChatID “0”). Right now, the first user Kyle can chat with the second user Kenny.

To test the group chat function:
  Users click “S-P Group” to join the group chat. You can open another tab and login as user Stan (ChatID “3”). By default, user “Stan”’s contact list does not have the “S-P group” friend. Therefore, you need to go to the “Contacts” tab and add the “S-P group” by “S-P group”’s ChatID “0”. Now you can test the group chat function.  

To sign up as a new user, please click the "Sign Up" button. You can set your username and password for your account. Your ChatID is assigned to you by the server, after you submit your information. You will need this ChatID for login. You can add friends (the four users stored in the “server”) by their ChatIDs in the “Contacts” tab.


To test moment sharing:
  People who are friends can see each other's moments updates when:
  1.One login and clicks the "Moments" icon in the footer.Then he can see his friends' updated moments.
  2.On the moments page, one can post new moment by clicking the right side icon in the header.After one updates his     moment by clicking the "Send" button, he can see his new moment and his friends' updated moments by clicking the left     side ">Moments" in the header.

About settings:
  On the setting main page, one can see his account info by clicking "My Account".On the my account page, one can see his wechat Id and user name by clicking "WeChat ID" and "User Name".
  To leave a feedback,first click "About" on the setting page and then click "Leave a feedback".
  To log out, click "Log Out" on the setting page.


