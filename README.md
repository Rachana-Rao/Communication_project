# Communication_project

Communication Application using Javascript and local storage

1. Create below HTML pages 
Welcome.html
Login.html
LoginSuccess.html
Register.html
RegisterSuccess.html
Userlist.html
EditUser.html
DeleteUser.html or use Modal
Chatlist.html
Documentlist.html
Upload.html or use Modal
EditDocument.html or use Modal
DeleteUpload.html or use Modal
Logout.html

2. For login page

Do below login validation

- Email and Password field is mandatory
- Email should be valid
- During login, check email and password exist inside local storage or not, if exist redirect to login successful page else error message "Wrong Email or Password".
- Logged in user cannot access login page, redirect to manage users page.

3. For Login Successful page, Display welcome text along with loggedin user email from local storage.

4. For Register page
- Add register user inside users local storage if it is does not exist
- If user exist, display message "user already exist"

Do below validation

- Fullname, Email, Password and Confirm password field is mandatory.
- Email should be valid.
- Password and confirm password should same.

5. For Manage Users page

- Display users list from users local storage.

For example 

[
{
"id": 1,
"name": "Text User",
"email": "textuser@gmail.com"
},
{
"id": 2,
"name": "Anne Hunter",
"email": "annehunter@gmail.com"
}
]

6. For Edit User information page

- Display users information from users local storage based on id from url.
- When we click on save, update users local storage.

Do below validation

- Fullname and Email is mandatory field.
- Email validation

7. For Delete User Modal page

- When we click on Ok remove user from users local storage else not.
- Disabled delete link for loggedin user.

8. On Group Chat page

- Display chat information from chats local storage.
- When we write message and click on send, store message inside local storage.
- Add scroll when we have huge messages.
- When we click on refresh, refresh page.
- Display dynamic loggedin user name.
- Display dynamic date and time as per wireframe.

Do below validation

- Message input is mandatory field.

9. For Manage Documents page

- Display list of my uploads from uploads local storage, display all users uploads information

For example 

[
{
"id": 1,
"label": "Sales report",
"fileName": "salesreport.pdf"
},
{
"id": 2,
"label": "Summary report",
"fileName": "summary.pdf"
}
]

10. For Add upload Modal

- Add label and filename inside upload local storage, no need to upload file

Do below validation

- Description and label is mandatory field

11. For Edit upload modal

- Display edit upload information
- When we click on save, update uploads local storage

12. For delete upload Modal

- When we click on Ok remove upload from uploads local storage.

13. When we click on logout, remove user from loggedin local storage.
14. Only loggedin user can access internal pages for example Group Chat, Manage Users and Manage Documents and all modals.
15. When user is deleted,  delete uploads files, chat information from local storage.
16. When logged in user update, then update local storage information.
17. Display chat information in sorted order based on date and time.
