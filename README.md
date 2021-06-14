# React Firebase Super Chat

A simple fullstack chat demo with React and Firebase. 
Watch on full [React Firebase Chat Tutorial](https://youtu.be/zQyrwxMPm88) on YouTube. 
[Live demo](https://fireship-demos.web.app/)


# running locally with google auth and db connection
![screencap](Capture.PNG)

# Usage

Clone
```bash
npm install
```
create auth.js
add auth info from firebase website to that file

used this in firebase config for test reasons 

```
// Allow read/write access to all users under any conditions
// Warning: **NEVER** use this rule set in production; it allows
// anyone to overwrite your entire database.
service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read, write: if true;
    }
  }
}
```
