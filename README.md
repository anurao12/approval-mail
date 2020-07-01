
## Getting Started

```
cd react-confirm-email/client
npm i && npm start
// open another terminal tab
cd react-confirm-email/server
npm i && npm run dev
// open another terminal tab (if running mongo locally)
mongod

```
Create a new gmail account.

You can sign up for a new gmail account here. Afterwards you will need to plug the credentials for your new account into a .env file on the server.

// server/.env
MAIL_USER=your_new_email_address@gmail.com
MAIL_PASS=your_password
