# encrypted-email-service
Encrypted Mailing Service:

A Web Based Application to send encrypted mail upto 50 counts to multiple users at a same time.

Note:

	———————————————————————————————————————————————————————————————————————

 ***!!!This application is build by me for basic understanding of HTML,CSS,JS!!!***

 ***!!!There may occur some bugs try mentioning in the Issues section!!!***

	———————————————————————————————————————————————————————————————————————
Technologies Used:

HTML - To build the web page (front end)

CSS - Styling the Web Pages

NodeJs - Backend

Steps to Run the Project:


Server Side

Clone the repository to your computer
Make use of a powerful editor (I used Visual Studio Code)
Install nodejs in your computer
Open the "Encrypted_Mailer" folder through visual studio code
Open terminal and type "npm install" wait for the packages from the "package.json" to install (The process takes place automatically)
Enter your own email id and password in .env file to access the email sending API -If you have trouble sending the mail from your account, go to https://myaccount.google.com/security and Turn On "Less Secure App Access"
Type npm start/npm server start to start the application.
Visit http://localhost:portno/email.html
Woalaaa..! Now you can send your encrypted mails to anyone on the internet.
Client Side

Open the "Client Side" folder in receiver's side computer.
Do the step 2,3,4(here open Client Side folder instead),5.
After Successful installation of the modules there are some steps to be done,
Go to "https://developers.google.com/gmail/api/quickstart/nodejs"
Enable Gmail API for the account to be used in Client side
Download 'credentials.json' file (Every account has different configuration file)
Your good to go with credentials.json file.
After installing required packages type 'node index' in terminal
When you run the program for the first time, a link will appear in the terminal! Open it and login to the account from which you want to read the Encrypted mail
After successful login you will be given a token to access the account via this program. Paste that in the terminal and your all set to go. Lets encrypt some Mails.
