## Hello and welcome to pasty

### What's pasty?
A easy to use filesharing service, made to share all kind of files faster than before.
![Pasty](http://i.imgur.com/56uab30.png)

### How does it work?
#### 1. you copy something to clipboard
![Copy](http://i.imgur.com/p36dipz.png)

#### 2. you press **ctrl+shift+v** in skype, irc, in the web or wherever you want.
   A link is inserted and your computer starts uploading your screenshot/file/whatever to our relay server.
![Paste](http://i.imgur.com/2esU2ST.png)

#### 3. your (chat) partner opens the link, sees the upload progress, sees the result, and gets your stuff....
![Progress](http://i.imgur.com/Qo2w0EY.jpg)
![Download](http://i.imgur.com/4ACuYXn.jpg)

### This also works with different types of data:
#### Images
![Image](http://i.imgur.com/QDI6lbp.jpg)

#### Text
![Text](http://i.imgur.com/DVxm9t2.jpg)

#### And everything else (although it won't handle it in a special way, just a simple download, but we will soon support more like audio.)

### Privacy:
1. it's open source, host it yourself or use our server (server not available for now)
2. your data gets AES-encrypted before upload.
3. the link you send to your partner contains the decryption key as a anchor like http://psty.de/?UPLOADID#PRIVATEKEY -> anchors are never sent to the webserver, your browser decrypts it

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