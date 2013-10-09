Omninote server app
===================
This Express app performs the OAuth flow needed by the Omninote Chrome browser extension.

Setup
-----------
My own production API key/secret is not commited in the repository for obsious security reasons. If you want to launch your own server instance, you will to:
- Create an [Evernote sandbox account](https://sandbox.evernote.com/Registration.action)
- Request an [Evernote API key](http://dev.evernote.com/)
- Rename server/config.sample.json to server/config.json and fill in your Consumer Key and Consumer Secret
- npm install

Start application
-----------------
You can start express server with `node app.js`.  Once the express server starts, you can access `http://localhost:3001` and see the application. It will list the notebooks in your sandbox account. Edit express/routes/index.js to try other parts of the Evernote API.
