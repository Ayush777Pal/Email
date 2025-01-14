# Email
This project uses JavaScript, HTML, and CSS, Django, bootstrap, font awesome to create a single-page-app email client-server web app. This project consist of single inbox.html file that loads different pages on client side with help of javascript, the pages consist of different sections such as compose,inbox,sent,archived,logout other files such as logout.html, register.html that is used for logout and register of client on django development.
Note:-This app will not send mail until you register on our web app
## Main Page
This page shows the inbox of your that shows other receipient who has send you mail on click on mail it will take you to content of mail that consist information about who has send you mail, subject, timestamp, body of mail
## Compose
On clicking compose button a page will load that consist of compose form that will send mail to other recepient this form consist of from, to , subject, body, submit button that will send mail to other recepient 
## Sent
On clicking sent button the user will directed to a page that shows detail of the mail that is being sended by the current user to other user of mail app
## Archived 
On clicking archived button the user will be able to see all the archieved mail that is being archived by current user.
## Log out 
On clicking of log out button user will be logout from current account and will be redirected to login page 
### Important Features 
1)On clicking on any mail user will be able to see detail of mail and can even see a archive and reply button
2)Archive button can toggle to both archive and unarchive mail when clicking on Archieve button the mail will be archived and on clicking on Unarchieve the mail will return back to inbox
3)Reply button takes user to reply form that will automatically fill the other sender email and its mail content
4)login and register page works same as login to make user login to web app and register page makes user register to django development server
## Django Database
Shows the database for user and email data
