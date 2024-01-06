# LaracApp: University of Lar android application
I have done this Android project for University of Lar

[Watch the introduction video](https://drive.google.com/file/d/1WIMk8_8hGDW3HAN317EBVUUv0yaZiL-7/view)

# Program Features:

1) Getting information from the university API.
2) Processing the received content.
3) Displaying processed content.
4) Storing content in SQLite database.
5) Online/offline functionality.
6) Dark Mode/Light mode available
7) Checking server connection every 10 seconds (if connected, data is retrieved from the API; if disconnected, data is read from SQLite).
8) Displaying the university location using Google Maps API.
9) Supporting both Persian and English languages.
10) When the program language is Persian, Persian data is obtained from the API, and when the language is English, English data is retrieved from the API.
11) Ability to submit comments (anonymously or with a user account), delete comments, and view comments from all users for each post.
12) Liking posts, unliking posts, viewing the list of users who liked a post, and seeing the number of likes for each post.
13) Sharing text and short links for each post.
14) Adding each post to the favorites list and removing posts from favorites.
15) Communicating with the university and the program admin through email and calls in various sections of the program.

# User Account Section:

16) Implemented using Firebase services and operates online.
17) Creating user accounts and receiving account recovery phrases.
18) Logging into user accounts.
19) Changing passwords (if the user knows the current password).
20) Password recovery (if the user forgets the password but has the account recovery phrase received during registration, they can change their password).

# After logging into the user account:

21) Users can view their previous chat lists with other users. Newer chats appear at the top rows.
22) Users can engage in a conversation with an AI based on chatGPT and receive responses (using the free openai API).
23) Users can generate and download images based on a description using AI (using the free openai API).

# In the chat page for each user:

24) Users can see sender and receiver messages.
25) Users can delete, copy, or save their sent messages in their saved messages.
26) Users can copy or save sender messages in their saved messages.

# In the user account settings page:

27) Users can view their personal information, including profile picture, name, username, and phone number. Users can change their profile picture and name on this page.
28) Users can set a new password by confirming their current password.
29) Users can view and copy the account recovery phrase by confirming their current password.

# In the user search page:

30) Users see two fixed rows, the first row is their own user account, where they can send themselves messages and save information in their chat. The second row is the program management account.
31) A search box and three filters are provided for searching. Users can search for other users based on phone number, name, or username. If such a user exists, the result will be displayed, and the user can start a new conversation.
33) For the comments and likes section, a dedicated API is developed, and a database is created. Other sections are completely online.

In the presentation clip, efforts have been made to show various parts of the application in both Persian and English languages. There are likely still bugs, and the application will be improved and developed in the future. 
The possibility of sharing the project source code is not available. all copyrights belong to University of Lar.
# Here are some pictures of the app

| Image 1                     | Image 2                     | Image 3                     |
|-----------------------------|-----------------------------|-----------------------------|
| ![Image 1](https://i.postimg.cc/N07VF91q/1.png) | ![Image 2](https://i.postimg.cc/MT39fyH4/2.png) | ![Image 3](https://i.postimg.cc/hPz5x390/3.png) |
| ![Image 4](https://i.postimg.cc/j293mzrN/4.png) | ![Image 5](https://i.postimg.cc/cC65FFP0/5.png) | ![Image 6](https://i.postimg.cc/sDk0J9mC/6.png) |

