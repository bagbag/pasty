## Hello and welcome to pasty

### What's pasty?
1. you copy something to clipboard
2. you press **ctrl+shift+v** in skype, irc, in the web or wherever you want.
3. a link is inserted and your computer starts uploading your screenshot/file/whatever to our relay server
4. your (chat) partner opens the link, sees the upload progress, sees the result, and gets your stuff....

### Privacy:
1. it's open source, host it yourself or use our server (server not available for now)
2. your data gets AES-encrypted before upload.
3. the link you send to your partner contains the decryption key as a anchor like http://pasty.de/UPLOADID#PRIVATEKEY. anchors are never sent to the webserver, your browser decrypts it

### Viewer Features:
* Upload **Progressbar** and State
* **Image Viewer**
* **Syntaxhighting** for code uploads
* Auto Redirect for links
* Download for any other type of upload

### Supported Upload Types right now:
- Screenshots, text or code, links, files and folders in explorer.

###What about Linux and MacOSX?
We will support that with our next version (which is basically a complete rewrite of everything)