# Rednit-Dating-App

This is a JAVA Programming Dating App for my course project

1) Explanation of the Assigned Task

Our group was assigned with a project called “Friend Zone”. Basically, this project implements the idea of a dating app but it is actually a fake one with features such as find users near me, find the same interests, troll message feature and substitution encryption. In this case, the users will find other users that are near to them and have the same interest. If they find one, they will begin chatting, however the text message will be converted to something that will turn off others. For example, “I love you” will convert to “I hate you”. This is done without the users realising it. Through a MySQL database we created, new users can register and create their account and also other users that already have a dating app account can sign up using that dating app account. In this project, we implemented the usage of “JFrame”, mainly in Netbeans and all the codes are in Java. Long story short, we hope that our fake dating app can destroy the market of couples.

2) Requirements of Task

- We need to implement an interface for users to sign up for this app and also a class to handle the data of users that sign up with other dating app accounts. The data from other dating app accounts will be extracted and inserted to our app’s database. We also need to implement a login interface for users that already have an account to use the app.
- For this module called Find Users Near Me, I am required to create a program to detect whether a user is inside a circle or not. Centre of the circle will be the coordinate of the user who is using the application. This user will be able to see a list of users that is inside the circle.
- In this module, we are required to sort the list of users that are in range according to current user preferences. The idea is to set weightage for each user before we sort them. After sorted, the app will display users that have the most relevance with current user’s interests to the least relevance. Therefore, we need to decide the appropriate sorting algorithm to sort the users efficiently.
- We are required to create a chat system which allows two parties to communicate where the messages will be encrypted and then sent to the database and will then be received by the receiver. We are also required to have rephrasing of certain words or adjectives.
- We are required to create an encryption system for the fake dating app. The messages from a user will be encrypted through the system when storing in our database. The stored messages will then be decrypted when retrieving them from the database to be sent to the other user.
