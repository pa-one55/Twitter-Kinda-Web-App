# Twitter Kinda Web App

## Register Page
![Register Page](https://github.com/pa-one55/Twitter-Kinda-Web-App/blob/master/screenshots/register.png?raw=true)

## Login Page
![Login Page](https://github.com/pa-one55/Twitter-Kinda-Web-App/blob/master/screenshots/login.png?raw=true)

## Profile Page
![Profile Page](https://github.com/pa-one55/Twitter-Kinda-Web-App/blob/master/screenshots/profile.png?raw=true)

## Edit Page
![Edit Page](https://github.com/pa-one55/Twitter-Kinda-Web-App/blob/master/screenshots/edit.png?raw=true)

## Deleted Page
![Deleted Page](https://github.com/pa-one55/Twitter-Kinda-Web-App/blob/master/screenshots/deleted.png?raw=true)

## Tutor
**App Description:**
- **We'll create users**
- **Users can write posts**

## Functions:
- **Login, Logout, Register**
- **Post Creation**
- **Post Like**
- **Post Delete** (only to the owner)

## Mine:
**Extra:**
- **Added error handling** - wrong entries in the form, empty fields, etc.
- **Handled the case when user directly tries to access the profile page:**
  - In this case, there is no cookie to begin with.
  - So, just added that case.
- **Added 'Register' button on login page**, in case a new user comes directly to the login page.
- **Added login on register page.**
- **Added delete a post feature.**

## Issues Faced:
- The **post was showing in my DB**, but the **post array in the userProfile was empty**.
- Wrong syntax: `<% user.username %>`
  - Correct syntax: `<%= user.username %>`
  - **Forgot to put that `=` sign.**

## Packages:
- **express**
- **mongoose**
- **bcrypt**
- **jsonwebtoken**
- **cookie-parser**
- **ejs**
